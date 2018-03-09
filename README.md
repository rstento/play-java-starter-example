[<img src="https://img.shields.io/travis/playframework/play-java-starter-example.svg"/>](https://travis-ci.org/playframework/play-java-starter-example)

# play-java-starter-example

This application demonstrates how Play works and includes a Hello World tutorial.  Run the example as described below to view the tutorial.



## Prerequisites

If you downloaded the example from github, make sure that you have the correct version of Java and <code>sbt</code> installed. If you downloaded a zip file from Lightbend [Tech Hub](https://developer.lightbend.com/start/?group=play), the <code>sbt-dist</code> directory includes a distribution of <code>sbt</code> so you don't have to install it separately. This example requires:

* Java Software Developer's Kit (SE) 1.8 or higher
* sbt 0.13.13 or higher

To check your Java version, enter the following in a command window:

```bash
java -version
```

To check your sbt version, enter the following in a command window:

```bash
sbt sbt-version
```

If you do not have the required versions, follow these links to obtain them:

* [Java SE](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [sbt](http://www.scala-sbt.org/download.html)

## Run the example

1. In a command window, change into the project directory, for example: `cd play-java-starter`

1. Enter: `sbt run`

    The project builds and starts the embedded HTTP server. Since this downloads libraries and dependencies, the amount of time required depends on the speed of your connection.

1. After the message `Server started, ...` displays, enter the following URL in a browser:

    <http://localhost:9000>
    
    The welcome page displays the Hello World tutorial.


