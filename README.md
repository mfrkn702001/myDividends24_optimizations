ABOUT
=====

A simple tool to calculate the overall performance of an investment portfolio.

See http://buchen.github.com/portfolio/ for more details.


BUILDING WITH MAVEN
===================

Install [SWTChart](http://www.swtchart.org/) into your local Maven repository:
```
mvn install:install-file
    -Dfile=path/to/org.swtchart_0.8.0.v20120301.jar
    -DgroupId=org.swtchart
    -DartifactId=org.swtchart
    -Dversion=0.8.0
    -Dpackaging=jar
    -DgeneratePom=true
```

Run Maven 3.0.x in the 'portfolio-app' directory:
```
mvn clean verify
```

DEVELOP WITH ECLIPSE IDE
========================

Download [Eclipse 3.7.2](http://eclipse.org/downloads/) including the RCP Tools.

Clone the git repository and import the projects.

Setup a target platform (Preferences -> Plug-in Development -> Target Platform) including
* an Eclipse 3.7.2 installation
* a directory containing the following 3rd party libraries
  * com.springsource.* bundles
  * org.swtchart.* bundle 
* (optionally) add the Eclipse Babel language pack
