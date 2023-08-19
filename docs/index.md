---
title: Result Library BOM
description: Bill of Materials for Result libraries
image: https://dev.leakyabstractions.com/result/result-magic-ball.png
---

# Result Library BOM

This project contains [Bill of Materials (BOM) POM][BILL_OF_MATERIALS] for [Result libraries][RESULT_LIBRARY], which is
a special POM file that groups dependency versions that are known to be valid and tested to work together, reducing the
chances to have version mismatches.

The basic idea is that, instead of specifying a version number for every Result library that you want to use in your
project, you can use this BOM POM to get a full set of consistent versions to use.


## Adding Result BOM to Your Build

Artifact coordinates:

- Group ID: `com.leakyabstractions`
- Artifact ID: `result-bom`
- Version: `{{ site.current_version }}`

To [import the BOM using Maven][MAVEN_IMPORT_BOM], use the following:

```xml
<dependencyManagement>
  <dependencies>
    <dependency>
      <groupId>com.leakyabstractions</groupId>
      <artifactId>result-bom</artifactId>
      <version>{{ site.current_version }}</version>
      <scope>import</scope>
      <type>pom</type>
    </dependency>   
  </dependencies>
</dependencyManagement>
```

To [import the BOM using Gradle][GRADLE_IMPORT_BOM], use the following:

```gradle
dependencies {
    // Import the BOM
    implementation platform('com.leakyabstractions:result-bom:{{ site.current_version }}')

    // Define dependencies without version numbers
    implementation 'com.leakyabstractions:result'
    implementation 'com.leakyabstractions:result-jackson'
    implementation 'com.leakyabstractions:result-lazy'
    testImplementation 'com.leakyabstractions:result-assertj'
}
```


## Releases

This library adheres to [Pragmatic Versioning][PRAGVER].

Artifacts are available in [Maven Central][ARTIFACTS].


## Javadoc

Here you can find the full [Javadoc documentation][JAVADOC].


## Looking for Support?

We'd love to help. Check out the [support guidelines][SUPPORT].


## Contributions Welcome

If you'd like to contribute to this project, please [start here][CONTRIBUTING].


## Code of Conduct

This project is governed by the [Contributor Covenant Code of Conduct][CODE_OF_CONDUCT].
By participating, you are expected to uphold this code.


## Author

Copyright 2023 [Guillermo Calvo][AUTHOR].

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
[BILL_OF_MATERIALS]:            https://reflectoring.io/maven-bom/
[CODE_OF_CONDUCT]:              https://dev.leakyabstractions.com/result/CODE_OF_CONDUCT.html
[CONTRIBUTING]:                 https://dev.leakyabstractions.com/result/CONTRIBUTING.html
[GRADLE_IMPORT_BOM]:            https://docs.gradle.org/current/userguide/platforms.html#sub:bom_import
[GUILLERMO]:                    https://guillermo.dev/
[GUILLERMO_IMAGE]:              https://guillermo.dev/assets/images/thumb.png
[JAVADOC]:                      https://dev.leakyabstractions.com/result/javadoc/
[MAVEN_IMPORT_BOM]:             https://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html#bill-of-materials-bom-poms
[PRAGVER]:                      https://pragver.github.io/
[RESULT_LIBRARY]:               https://dev.leakyabstractions.com/result/
[SUPPORT]:                      https://dev.leakyabstractions.com/result/SUPPORT.html
