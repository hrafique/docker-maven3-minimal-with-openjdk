Docker - Trusted Build for a minimal install of maven3 using OpenJDK
===

This is a docker bulid for [Maven 3](http://maven.apache.org/) with a very
minimal install (from a `.tar.gz`) using OpenJDK (Oracle JDK was not used
because of potential licensing issues when using an unattended install).

You can test it out by issuing:
```
docker run hrafique/maven3-minimal-openjdk mvn -version
```
which should give output similar to:
```
Apache Maven 3.0.5 (r01de14724cdef164cd33c7c8c2fe155faf9602da; 2013-02-19 13:51:28+0000)
Maven home: /opt/maven
Java version: 1.7.0_25, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-7-openjdk-amd64/jre
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "3.12.1-tinycore64", arch: "amd64", family: "unix"
```
