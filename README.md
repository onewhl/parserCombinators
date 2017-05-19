# parserCombinators [![Build Status](https://travis-ci.org/anlun/parserCombinators.svg?branch=master)](https://travis-ci.org/anlun/parserCombinators)

The parser combinator library written on Kotlin.  
  
# Build instruction:

* Install [Gradle](https://gradle.org)
* Add Gradle installation path to System Variables/Path (Windows. May also be needed for other OSs)
* Add JDK Installation path ("JAVA_HOME") to Environment Variables (Windows). [More about](http://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/index.html)
* Run Gradle script: for example, run Windows command prompt and type any of the followings:
    - `gradle setup` — will configure all required dependencies, .iml-file and project SDK for IntelliJ IDEA
    - `gradle test` — compile and run tests
    - `gradle tasks` — more gradle tasks (such as build, jar). You can find .jar in build/libs folder.


### OR
1. Run gradlew script (or gradlew.bat)
2. In terminal: type
    - `gradlew setup` to configure idea-based files
    - `gradlew test` -- compile and run tests
    - `gralew jar` -- create .jar-file. You can find it in build/libs

# Performance
| Language                                    | Length of string    | Time          |
|:--------------------------------------------|:-------------------:| -------------:|
|<i>a<sup>n</sup> b<sup>n</sup> c<sup>n</sup> | 900                 | **0.087** sec |
| *wcw*                                       | 401                 | **0.044** sec |
| *ww*                                        | 600                 | **0.155** sec |
