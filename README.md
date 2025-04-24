# Eclipse FA³ST Parent

![FA³ST Logo Light](./docs/images/fa3st-positive.svg/#gh-light-mode-only "FA³ST Service Logo")
![FA³ST Logo Dark](./docs/images/fa3st-negative.svg/#gh-dark-mode-only "FA³ST Service Logo")

This is the parent POM of the Eclipse FA³ST Ecosystem.
If you are developing an extension to FA³ST or an implementation of one of the interfaces it is recommended to use this project as your parent POM

```xml
<parent>
	<groupId>org.eclipse.digitaltwin.fa3st</groupId>
	<artifactId>fa3st-parent</artifactId>
	<version>1.0.0-SNAPSHOT</version>
</parent>
```

This project provides the following functionality
- defines all dependencies of FA³ST using `properties` and `dependencyManagement`
- include all relevant dependency and plugin repositories
- configures plugins
- defines profiles `release` and `owasp`

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions are **greatly appreciated**.
You can find our contribution guidelines [here](.github/CONTRIBUTING.md)

## License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

Copyright (C) 2025 the Eclipse FA³ST Authors.

You should have received a copy of the Apache 2.0 License along with this program. If not, see https://www.apache.org/licenses/LICENSE-2.0.html.
