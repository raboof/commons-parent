<!---
 Licensed to the Apache Software Foundation (ASF) under one or more
 contributor license agreements.  See the NOTICE file distributed with
 this work for additional information regarding copyright ownership.
 The ASF licenses this file to You under the Apache License, Version 2.0
 (the "License"); you may not use this file except in compliance with
 the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->
<!---
 +======================================================================+
 |****                                                              ****|
 |****      THIS FILE IS GENERATED BY THE COMMONS BUILD PLUGIN      ****|
 |****                    DO NOT EDIT DIRECTLY                      ****|
 |****                                                              ****|
 +======================================================================+
 | TEMPLATE FILE: readme-md-template.md                                 |
 | commons-build-plugin/trunk/src/main/resources/commons-xdoc-templates |
 +======================================================================+
 |                                                                      |
 | 1) Re-generate using: mvn commons-build:readme-md                    |
 |                                                                      |
 | 2) Set the following properties in the component's pom:              |
 |    - commons.componentid (required, alphabetic, lower case)          |
 |    - commons.release.version (required)                              |
 |                                                                      |
 | 3) Example Properties                                                |
 |                                                                      |
 |  <properties>                                                        |
 |    <commons.componentid>math</commons.componentid>                   |
 |    <commons.release.version>1.2</commons.release.version>            |
 |  </properties>                                                       |
 |                                                                      |
 +======================================================================+
--->
Apache Commons Parent
===================

[![Java CI](https://github.com/apache/commons-parent/actions/workflows/maven.yml/badge.svg)](https://github.com/apache/commons-parent/actions/workflows/maven.yml)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.commons/commons-parent/badge.svg?gav=true)](https://maven-badges.herokuapp.com/maven-central/org.apache.commons/commons-parent/?gav=true)
[![Javadocs](https://javadoc.io/badge/org.apache.commons/commons-parent/71.svg)](https://javadoc.io/doc/org.apache.commons/commons-parent/71)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/apache/commons-parent/badge)](https://api.securityscorecards.dev/projects/github.com/apache/commons-parent)

The Apache Commons Parent POM provides common settings for all Apache Commons components.

Documentation
-------------

More information can be found on the [Apache Commons Parent homepage](https://commons.apache.org/proper/commons-parent).
The [Javadoc](https://commons.apache.org/proper/commons-parent/apidocs) can be browsed.
Questions related to the usage of Apache Commons Parent should be posted to the [user mailing list](https://commons.apache.org/mail-lists.html).

Getting the latest release
--------------------------
You can download source and binaries from our [download page](https://commons.apache.org/proper/commons-parent/download_parent.cgi).

Alternatively, you can pull it from  the central Maven repositories:

```xml
<dependency>
  <groupId>org.apache.commons</groupId>
  <artifactId>commons-parent</artifactId>
  <version>71</version>
</dependency>
```

Building
--------

Building requires a Java JDK and [Apache Maven](https://maven.apache.org/). 
The required Java version is found in the `pom.xml` as the `maven.compiler.source` property.

From a command shell, run `mvn` without arguments to invoke the default Maven goal to run all tests and checks.

Contributing
------------

We accept Pull Requests via GitHub. The [developer mailing list](https://commons.apache.org/mail-lists.html) is the main channel of communication for contributors.
There are some guidelines which will make applying PRs easier for us:
+ No tabs! Please use spaces for indentation.
+ Respect the existing code style for each file.
+ Create minimal diffs - disable on save actions like reformat source code or organize imports. If you feel the source code should be reformatted create a separate PR for this change.
+ Provide JUnit tests for your changes and make sure your changes don't break any existing tests by running `mvn`.
+ Before you pushing a PR, run `mvn` (by itself), this runs the default goal, which contains all build checks.
+ To see the code coverage report, regardless of coverage failures, run `mvn clean site -Dcommons.jacoco.haltOnFailure=false`

If you plan to contribute on a regular basis, please consider filing a [contributor license agreement](https://www.apache.org/licenses/#clas).
You can learn more about contributing via GitHub in our [contribution guidelines](CONTRIBUTING.md).

License
-------
This code is licensed under the [Apache License v2](https://www.apache.org/licenses/LICENSE-2.0).

See the `NOTICE.txt` file for required notices and attributions.

Donating
--------
You like Apache Commons Parent? Then [donate back to the ASF](https://www.apache.org/foundation/contributing.html) to support development.

Additional Resources
--------------------

+ [Apache Commons Homepage](https://commons.apache.org/)
+ [Apache Issue Tracker (JIRA)](https://issues.apache.org/jira/browse/COMMONSSITE)
+ [Apache Commons Slack Channel](https://the-asf.slack.com/archives/C60NVB8AD)
+ [Apache Commons Twitter Account](https://twitter.com/ApacheCommons)

Apache Commons Components
-------------------------

Please see the [list of components](https://commons.apache.org/components.html)
