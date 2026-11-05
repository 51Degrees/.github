# 51Degrees Device Detection, IP Intelligence, and bot detection

We provide Device Detection, User-Agent and User-Agent Client Hints parsing, IP Intelligence and IP geolocation, and bot and crawler detection. Run Device Detection and IP Intelligence on-premise or in the cloud. Human Confidence is a cloud property for bot detection.

Device Detection identifies devices, operating systems, browsers, and crawlers from HTTP request headers, which carry information from a browser to a server. IP Intelligence returns an IP address's likely location, connection type, and network. Human Confidence says how confident we are that a person is viewing a page.

## Choose your language or platform

| Language or platform | Repository | Examples |
| --- | --- | --- |
| C and C++ | [51degrees-cxx](https://github.com/51Degrees/51degrees-cxx) | [Device Detection](https://github.com/51Degrees/51degrees-cxx/tree/main/examples/dd), [IP Intelligence](https://github.com/51Degrees/51degrees-cxx/tree/main/examples/ipi) |
| .NET and C# | [51degrees-dotnet](https://github.com/51Degrees/51degrees-dotnet) | [Device Detection](https://github.com/51Degrees/51degrees-dotnet/tree/main/examples/device-detection), [IP Intelligence](https://github.com/51Degrees/51degrees-dotnet/tree/main/examples/ip-intelligence) |
| Go | [51degrees-go](https://github.com/51Degrees/51degrees-go) | [Device Detection](https://github.com/51Degrees/51degrees-go/tree/main/examples/device-detection), [IP Intelligence](https://github.com/51Degrees/51degrees-go/tree/main/examples/ip-intelligence) |
| Java | [51degrees-java](https://github.com/51Degrees/51degrees-java) | [Device Detection](https://github.com/51Degrees/51degrees-java/tree/main/examples/device-detection), [IP Intelligence](https://github.com/51Degrees/51degrees-java/tree/main/examples/ip-intelligence) |
| NGINX | [51degrees-nginx](https://github.com/51Degrees/51degrees-nginx) | [Device Detection](https://github.com/51Degrees/51degrees-nginx/tree/main/examples/hash), [IP Intelligence](https://github.com/51Degrees/51degrees-nginx/tree/main/examples/ipi) |
| Node.js | [51degrees-node](https://github.com/51Degrees/51degrees-node) | Device Detection [cloud](https://github.com/51Degrees/51degrees-node/tree/main/device-detection/fiftyone.devicedetection.cloud/examples/cloud) and [on-premise](https://github.com/51Degrees/51degrees-node/tree/main/device-detection/fiftyone.devicedetection.onpremise/examples/onpremise), IP Intelligence [cloud](https://github.com/51Degrees/51degrees-node/tree/main/ip-intelligence/fiftyone.ipintelligence.cloud/examples/cloud) and [on-premise](https://github.com/51Degrees/51degrees-node/tree/main/ip-intelligence/fiftyone.ipintelligence.onpremise/examples/onpremise) |
| PHP | [51degrees-php](https://github.com/51Degrees/51degrees-php) | Device Detection [cloud](https://github.com/51Degrees/51degrees-php/tree/main/device-detection/cloud/examples/cloud) and [on-premise](https://github.com/51Degrees/51degrees-php/tree/main/device-detection/onpremise/examples/onpremise), IP Intelligence [cloud](https://github.com/51Degrees/51degrees-php/tree/main/ip-intelligence/examples/cloud) and [on-premise](https://github.com/51Degrees/51degrees-php/tree/main/ip-intelligence/examples/onpremise) |
| Python | [51degrees-python](https://github.com/51Degrees/51degrees-python) | [Device Detection](https://github.com/51Degrees/51degrees-python/tree/main/device-detection/fiftyone_devicedetection_examples), [IP Intelligence](https://github.com/51Degrees/51degrees-python/tree/main/ip-intelligence/fiftyone_ipintelligence_examples) |
| Rust | [51degrees-rust](https://github.com/51Degrees/51degrees-rust) | [Device Detection](https://github.com/51Degrees/51degrees-rust/tree/main/examples/device-detection-examples), [IP Intelligence](https://github.com/51Degrees/51degrees-rust/tree/main/examples/ip-intelligence-examples) |
| Varnish | [51degrees-varnish](https://github.com/51Degrees/51degrees-varnish) | [Device Detection](https://github.com/51Degrees/51degrees-varnish/tree/main/examples/hash), [IP Intelligence](https://github.com/51Degrees/51degrees-varnish/tree/main/examples/ipi) |
| WordPress | [pipeline-wordpress](https://github.com/51Degrees/pipeline-wordpress) | See the repository README |
| JavaScript and TypeScript | [ua-parser-js](https://github.com/51Degrees/ua-parser-js) | See the repository README |

## Try it

Try the [User-Agent tester](https://51degrees.com/developers/user-agent-tester?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=try-it) and [IP tester](https://51degrees.com/developers/ip-tester?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=try-it). For cloud use, [create a Resource Key](https://configure.51degrees.com/?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=try-it).

Some cloud properties are free. Others need a paid plan. On-premise engines read a data file on your server. The free Lite files in the [data repository](https://github.com/51Degrees/data) carry a small set of properties. [Contact us](https://51degrees.com/contact-us?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=enterprise-data-file) about the Enterprise data files, which carry every property.

## Documentation and testing

- [Documentation](https://51degrees.com/documentation/index.html?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=documentation-and-testing)
- [Tested versions](https://51degrees.com/documentation/4.5/_product_summaries__tested_versions.html?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=documentation-and-testing)
- [Performance benchmarks](https://51degrees.com/documentation/4.5/_product_summaries__benchmarks.html?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=documentation-and-testing)
- [Automated test dashboard](https://github.com/51Degrees/common-ci/blob/main/DASHBOARD.md)
- [Contributing guidelines](https://github.com/51Degrees/common-ci/blob/main/CONTRIBUTING.md)

Our automated tests run nightly across C/C++, .NET, Java, NGINX, Varnish, Python, PHP, Node.js, Go, and Rust. We test Windows, Mac, and Linux across recent operating system and language runtime versions. Our engineers work across these languages and platforms to improve the code and development practices.

## Find out more

- [Device Detection](https://51degrees.com/device-detection?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=find-out-more)
- [IP Intelligence](https://51degrees.com/ip-intelligence?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=find-out-more)
- [Bots and humans](https://51degrees.com/bots-and-humans?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=find-out-more)
- [robots.txt service](https://51degrees.com/robots-txt?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=find-out-more)
- [Contact us about other languages](https://51degrees.com/contact-us?utm_source=github&utm_medium=readme&utm_campaign=.github&utm_content=profile-readme&utm_term=find-out-more)
