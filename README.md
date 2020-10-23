Ballerina Config Library
=========================

[![Build](https://github.com/ballerina-platform/module-ballerina-config/workflows/Build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-config/actions?query=workflow%3ABuild)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-config.svg)](https://github.com/ballerina-platform/module-ballerina-config/commits/master)
[![Github issues](https://img.shields.io/github/issues/ballerina-platform/ballerina-standard-library/module/config.svg?label=Open%20Issues)](https://github.com/ballerina-platform/ballerina-standard-library/labels/module%2Fconfig)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The config library is one of the standard library modules of the<a target="_blank" href="https://ballerina.io/"> 
Ballerina</a> language.

This module provides the interface and functionality to read configurations from environment variables, TOML files, 
and command-line parameters and build a consolidated set of configurations.

For more information go to [The Config Module](https://ballerina.io/swan-lake/learn/api-docs/ballerina/config/).

For example demonstrations of the usage, go to [Ballerina By Examples](https://ballerina.io/swan-lake/learn/by-example/config-api.html).

## `Issues` and `Projects` 

`Issues` and `Project` tabs are disabled for this repository as this is one of the Ballerina Standard Libraries. To report bugs, request new features, start new discussions, view project boards, etc. please visit Ballerina Standard Library [parent repository](https://github.com/ballerina-platform/ballerina-standard-library). 

This repository only contains the source code for the module.

## Building from the Source

### Setting Up the Prerequisites

Download and install Java SE Development Kit (JDK) version 11 (from one of the following locations).

   * [Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
   
   * [OpenJDK](https://adoptopenjdk.net/)
   
        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.
     
### Building the Source

Execute the commands below to build from source.

1. To build the library:
        
        ./gradlew clean build

2. To debug the tests:

        ./gradlew clean build -PdebugBallerina=<port>
        
3. To build the module without the tests:
        
        ./gradlew clean build -PskipBallerinaTests

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

You can also check for [open issues](https://github.com/ballerina-platform/ballerina-standard-library/labels/module%2Fconfig) that interest you. We look forward to receiving your contributions.

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss about code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
