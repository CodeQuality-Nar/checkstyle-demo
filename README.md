# checkstyle-demo

Useful Links:
=======================
<a>https://maven.apache.org/plugins/maven-checkstyle-plugin/index.html</a>

<a>https://maven.apache.org/plugins/maven-checkstyle-plugin/usage.html</a>


<b>google search:</b> maven-checkstyle-plugin pom.xml configuration.

Maven Checkstyle plugin comes with a default Checkstyle version: for maven-checkstyle-plugin 3.0.0, Checkstyle 6.18 is used by default.

Style files:
================
•	sun_checks.xml - Sun Microsystems Definition (default).  Need to use valid version for checkstyle plugin  <br>
•	google_checks.xml <br>
https://github.com/checkstyle/checkstyle/tree/master/src/main/resources

Suppression:
=================
Need to to configure in pom.xml

checkstyle-suppressions.xml

<a>https://maven.apache.org/plugins/maven-checkstyle-plugin/examples/suppressions-filter.html</a>

Comments
===============
Read about maven report checkstyle generation but didnt get.

Used sun checkstyle and modified in this project.

Commented some checks in this project.
