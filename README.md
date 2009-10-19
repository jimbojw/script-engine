## script-engine

Backport of the [ScriptEngine API](http://java.sun.com/developer/technicalArticles/J2SE/Desktop/scripting/) for Java 1.5.  Implementation code was adapted from the [OpenJDK 6](http://openjdk.java.net/projects/jdk6/) project.

**Note**: This is not a clone of the [JSR 223](http://jcp.org/en/jsr/detail?id=223) implementation.  The API differed slightly between the reference implementation and the final version which shipped with Java 1.6.

### Adapted by

* Jim R. Wilson (jimbojw)

### GitHub repository

* [http://github.com/jimbojw/trephine/](http://github.com/jimbojw/script-engine/)

### Deliverables

This project creates two jars:

* `dist/script.jar` - Implementation of the ScriptEnigne API, and
* `dist/js-engine.jar` - Adapter for the JavaScript engine, [Rhino](http://www.mozilla.org/rhino/)

### Building

This project uses [Maven](http://maven.apache.org/) to build:

* `run "mvn clean install"`

### Licenses

All non-test Java source code for this project was adapted from the OpenJDK project, and thus carries the same licensing terms: [GNU General Public License, version 2, with the Classpath Exception](http://openjdk.java.net/legal/gplv2+ce.html)

Code specifically written for this project (such as this README and the maven project descriptors) is released under [The MIT License](http://www.opensource.org/licenses/mit-license.php)

