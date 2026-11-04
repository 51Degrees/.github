# Contributing to 51Degrees

This guide applies to every 51Degrees repository that has no contributing guide
of its own.

## Where a change goes

Take a branch from `rc` and open the pull request against `rc`. `rc`, short for
release candidate, collects the changes for the next release. When a release is
wanted, 51Degrees opens one pull request that merges `rc` into `main`, so
everything in it goes live together.

Do not open a pull request against `main`. In most repositories a commit on
`main` starts a release, and where the "Only rc into main" check runs, it fails
any pull request into `main` that does not come from `rc`. A repository with no
`rc` branch takes pull requests against its default branch.

For a fork of another project, contribute to the project it was forked from.

## How often a release goes out

A repository that publishes packages releases `rc` into `main` at most once a
week, so each package gets at most one new version a week. Fewer versions are
easier for the people who use the packages to keep up with, and they keep the
packages in search. nuget.org asks search engines not to index a package's page
while the oldest of its 20 newest versions is less than 90 days old, so a
package that releases more often than once every four and a half days drops out
of search. Weekly leaves room for an urgent fix.

The "Only rc into main" check fails a release pull request that comes less
than seven days after the last one merged, and the publish refuses a release
less than seven days after the last. An early release needs James Rosewell's
permission. With it, add the label `early-release` to the release pull request
and re-run the check, because adding a label does not run it again. The
[common-ci contributing guide](https://github.com/51Degrees/common-ci/blob/main/CONTRIBUTING.md#releasing-at-most-once-a-week)
gives the details.

## The full guide

Raising issues, commit messages, comments, tests and the release steps are
covered in the
[common-ci contributing guide](https://github.com/51Degrees/common-ci/blob/main/CONTRIBUTING.md).
