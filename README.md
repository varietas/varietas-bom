[![OSI](https://res-5.cloudinary.com/crunchbase-production/image/upload/c_lpad,h_15,w_15,f_auto,q_auto:eco/v1413265600/yos3vcohir2yxnb3jtpf.png)](https://opensource.org) **We love Open Source**

[![Maven Central](https://img.shields.io/maven-central/v/io.varietas/varietas-bom.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.varietas%22%20AND%20a:%22varietas-bom%22) [![varietas.io](https://img.shields.io/badge/varietas.io-active-ff69b4.svg)](https://varietas.io) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 

# BOM/Parent POM of varietas.io
The consistently code building, testing and improving lead us to a common BOM/Parent POM for java-based artifacts and applications. We update the BOM constantly for the newest versions of external dependencies and build plugins. We include to our build the following things:

* **Checkstyle** - Code Analysis
* **JaCoCo** - Code Coverage
* **SpotBugs** - Bug Analysis

### Usage

Include the following code into your POM file:

```xml
<parent>
    <groupId>io.varietas</groupId>
    <artifactId>varietas-bom</artifactId>
    <version>y.x.z</version>
</parent>
```

Replace `x.y.z` with the currently newest version released [here](g:io.varietas AND a:varietas-bom).

#### Ticket

The ticket handling is separated into a "background" and an issue ticket-system. Tickets for improvements, features and suggestions are located on the project [Workboard](https://team.varietas.io/project/view/1/). Issues of the project are located in the repository Issues.

#### Bug reporting

If you find a bug, please create a JUnit test that reproduces the issue. This test will be used to fix the problem and will ensure that this issue never occurs again in further development iterations. A pull request with an implemented fix by yourself is also possible. Please add Unit-Tests for verification of your solution.

## About varietas.io

The [varietas.io](https://varietas.io) project is a pure Open Source Community and a framework at the same time. The community aims to help other OS projects succeed, connect developers and give them a platform (or better a home) for their projects. Feel free to join us.
The framework is a kind of plug-in framework for monolithic applications that allows the use of microservices to distribute functions. Read more on the project page.