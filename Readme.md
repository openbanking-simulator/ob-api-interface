# Open Banking Interface

This project is based on ACCC Data61 Open Banking Specification __v.1.5.0__

API Interfaces are generated using __Open API Tools__ maven plugin for the specification published @ https://consumerdatastandardsaustralia.github.io

Minor changes are done to swagger to support breaking the spec to multiple interfaces

* Commented `- Banking` tag for all `Banking APIs`.
* Commented `- Accounts` tag for endpoints which are specific for `Balances`, `Transactions`.
* Commented `- Common` tag for all `Common APIs`

## Generating Interface jar

Run `mvn clean build` to generate the interfaces in `Java` Language using `Spring WebFlux` as implementation.