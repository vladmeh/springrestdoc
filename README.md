# TestDriven Documentation. Spring RestDoc. SpringFox. Swagger2Markup. Asciidoctor.
![BOOT LOGO](img/springboot.png)

[![Build Status](https://travis-ci.org/tsypuk/springrestdoc.svg?branch=master)](https://travis-ci.org/tsypuk/springrestdoc)
[![star this repo](http://githubbadges.com/star.svg?user=tsypuk&repo=springrestdoc&style=default)](https://github.com/tsypuk/springrestdoc)
[![fork this repo](http://githubbadges.com/fork.svg?user=tsypuk&repo=springrestdoc&style=default)](https://github.com/tsypuk/springrestdoc/fork)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
---

## Agenda
* SpringFox Swagger.
* SpringRestDoc.
* AsciiDoctor is awesome.
* Swagger2Markdown. 

### SpringFox
SpringFox allows us to integrate SpringBoot app with swagger documentation.
To start using it, you need to:
1. Add dependencies:
````
compile 'io.springfox:springfox-swagger2:2.6.1'
compile 'io.springfox:springfox-swagger-ui:2.6.1'
````
2. Mark your SpringApplication.class with @EnableSwagger2 annotation
3. Register @Bean Docket
4. Mark your code with io.swagger.annotations

Now you have two more things in your application:
1. The swagger specification in json form by address:
````
http://localhost:8080/v2/api-docs?group=Module API
````
2. The seagger UI page followed by URL:
````
http://localhost:8080/swagger-ui.html
````

### SpringRestDoc

### AsciiDoctor is awesome

Example of how to use diagrams in our documentation.

### Swagger2Markup
I'm showing the pipeline, that allows to migrate your project from swagger to asciidoc and start using spring rest docs
Test Driven Documentation.

It can be done in two ways:
1. Using swaggerToMarkUp maven/gradle plugins
2. By using io.github.swagger2markup from tests.

This two flows are implemented.

Plus like bonus you can move your swagger resource to git markdown/ confluence wiki formats.
See tests.

## TODO ITEMS

- [x] Create springboot app for springfox (swagger annotations).
- [x] Create springboot app restdoc.
- [x] Create springboot app ascidocisawsome. To show advanced features and diagrams.
- [x] Create springboot app swagger2markup. Migration.
- [x] Add build to static resource pdf/html in jar. 
- [x] Internal/External Docs. public to git pages.