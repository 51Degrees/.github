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

## The full guide

Raising issues, commit messages, comments, tests and the release steps are
covered in the
[common-ci contributing guide](https://github.com/51Degrees/common-ci/blob/main/CONTRIBUTING.md).
