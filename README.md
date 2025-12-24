
[![Build Status][BADGE_BUILD_STATUS]][BUILD_STATUS]
[![OpenSSF Best Practices][BADGE_BEST_PRACTICES]][BEST_PRACTICES]
[![Maven Central][BADGE_ARTIFACTS]][ARTIFACTS]
[![Benchmark Report][BADGE_BENCHMARK]][BENCHMARK]

# Result Library BOM

This project contains [Bill of Materials (BOM) POM][BILL_OF_MATERIALS] for [Result libraries][RESULT], which is a
special POM file that groups dependency versions that are known to be valid and tested to work together, reducing the
chances to have version mismatches.

The basic idea is that, instead of specifying a version number for every Result library that you want to use in your
project, you can use this BOM POM to get a full set of consistent versions to use.

- [![result][BADGE_RESULT_CORE]][RESULT_CORE]
- [![result-api][BADGE_RESULT_API]][RESULT_API]
- [![result-assertj][BADGE_RESULT_ASSERTJ]][RESULT_ASSERTJ]
- [![result-jackson][BADGE_RESULT_JACKSON]][RESULT_JACKSON]
- [![result-jackson3][BADGE_RESULT_JACKSON3]][RESULT_JACKSON3]
- [![result-lazy][BADGE_RESULT_LAZY]][RESULT_LAZY]
- [![result-mnserde][BADGE_RESULT_MNSERDE]][RESULT_MNSERDE]


## Getting Started

Please read the [Quick Guide][QUICK_GUIDE] to know how to add this POM to your build.

Also available as an ebook in multiple formats. [Download your free copy now!][GUIDE_BOOK]


## Releases

This library adheres to [Pragmatic Versioning][PRAGVER].

Artifacts are available in [Maven Central][ARTIFACTS].


## Javadoc

Here you can find the full [Javadoc documentation][JAVADOC].


## Benchmarks

You may want to visualize the latest [benchmark report][BENCHMARK].


## Looking for Support?

We'd love to help. Check out the [support guidelines][SUPPORT].


## Contributions Welcome

If you'd like to contribute to this project, please [start here][CONTRIBUTING].


## Code of Conduct

This project is governed by the [Contributor Covenant Code of Conduct][CODE_OF_CONDUCT].
By participating, you are expected to uphold this code.


## Author

Copyright 2025 [Guillermo Calvo][AUTHOR].

[![][GUILLERMO_IMAGE]][GUILLERMO]


## License

This library is licensed under the *Apache License, Version 2.0* (the "License");
you may not use it except in compliance with the License.

You may obtain a copy of the License at <http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software distributed under the License
is distributed on an "AS IS" BASIS, **WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND**, either express or implied.

See the License for the specific language governing permissions and limitations under the License.


**Permitted:**

- **Commercial Use**: You may use this library and derivatives for commercial purposes.
- **Modification**: You may modify this library.
- **Distribution**: You may distribute this library.
- **Patent Use**: This license provides an express grant of patent rights from contributors.
- **Private Use**: You may use and modify this library without distributing it.

**Required:**

- **License and Copyright Notice**: If you distribute this library you must include a copy of the license and copyright
  notice.
- **State Changes**: If you modify and distribute this library you must document changes made to this library.

**Forbidden:**

- **Trademark use**: This license does not grant any trademark rights.
- **Liability**: The library author cannot be held liable for damages.
- **Warranty**: This library is provided without any warranty.


[ARTIFACTS]:                    https://search.maven.org/artifact/com.leakyabstractions/result-bom/
[AUTHOR]:                       https://github.com/guillermocalvo/
[BADGE_ARTIFACTS]:              https://img.shields.io/maven-central/v/com.leakyabstractions/result-bom
[BADGE_BENCHMARK]:              https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-benchmark/badge.json&style=flat
[BADGE_BEST_PRACTICES]:         https://www.bestpractices.dev/projects/8122/badge
[BADGE_BUILD_STATUS]:           https://github.com/leakyabstractions/result-bom/workflows/Build/badge.svg
[BADGE_GUIDE_BOOK]:             https://img.shields.io/badge/Free_book-444?logo=leanpub
[BADGE_RESULT_API]:             https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-api/badge.json&logo=0
[BADGE_RESULT_ASSERTJ]:         https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-assertj/badge.json&logo=0
[BADGE_RESULT_CORE]:            https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result/badge.json&logo=0
[BADGE_RESULT_JACKSON]:         https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-jackson/badge.json&logo=0
[BADGE_RESULT_JACKSON3]:        https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-jackson3/badge.json&logo=0
[BADGE_RESULT_LAZY]:            https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-lazy/badge.json&logo=0
[BADGE_RESULT_MNSERDE]:         https://img.shields.io/endpoint?url=https://dev.leakyabstractions.com/result-micronaut-serde/badge.json&logo=0
[BENCHMARK]:                    https://dev.leakyabstractions.com/result-benchmark/
[BEST_PRACTICES]:               https://www.bestpractices.dev/projects/8122
[BILL_OF_MATERIALS]:            https://reflectoring.io/maven-bom/
[BUILD_STATUS]:                 https://github.com/LeakyAbstractions/result-bom/actions?query=workflow%3ABuild
[CODE_OF_CONDUCT]:              https://github.com/LeakyAbstractions/.github/blob/main/CODE_OF_CONDUCT.md
[CONTRIBUTING]:                 https://github.com/LeakyAbstractions/.github/blob/main/CONTRIBUTING.md
[GRADLE_IMPORT_BOM]:            https://docs.gradle.org/current/userguide/platforms.html#sub:bom_import
[GUIDE_BOOK]:                   https://leanpub.com/result/
[GUILLERMO]:                    https://guillermo.dev/
[GUILLERMO_IMAGE]:              https://guillermo.dev/assets/images/thumb.png
[JAVADOC]:                      https://dev.leakyabstractions.com/result/javadoc/
[MAVEN_IMPORT_BOM]:             https://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html#bill-of-materials-bom-poms
[PRAGVER]:                      https://pragver.github.io/
[QUICK_GUIDE]:                  https://result.leakyabstractions.com/docs/start/adding-dependency
[RESULT]:                       https://dev.leakyabstractions.com/result/
[RESULT_API]:                   https://github.com/LeakyAbstractions/result-api/
[RESULT_ASSERTJ]:               https://github.com/LeakyAbstractions/result-assertj/
[RESULT_CORE]:                  https://github.com/LeakyAbstractions/result/
[RESULT_JACKSON]:               https://github.com/LeakyAbstractions/result-jackson/
[RESULT_JACKSON3]:              https://github.com/LeakyAbstractions/result-jackson3/
[RESULT_LAZY]:                  https://github.com/LeakyAbstractions/result-lazy/
[RESULT_MNSERDE]:               https://github.com/LeakyAbstractions/result-micronaut-serde/
[SUPPORT]:                      https://github.com/LeakyAbstractions/.github/blob/main/SUPPORT.md
