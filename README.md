
Prerequisites:
==============
For now it is tested to build and run on:
java version "1.8.0"
Java(TM) SE Runtime Environment (build 1.8.0-b132)
Java HotSpot(TM) 64-Bit Server VM (build 25.0-b70, mixed mode)

Build:
======
mvn install


Use:
====

After installing, add the plugin to your plugins section and the
dependency in your pom:

      <plugin>
        <groupId>edu.illinois</groupId>
        <artifactId>nondex-maven-plugin</artifactId>
        <version>1.0-SNAPSHOT</version>
      </plugin>



    <dependency>
      <groupId>edu.illinois</groupId>
      <artifactId>nondex-maven-plugin</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>

To find if you have bad tests, run:
   mvn nondex:nondex

To debug, run:
   mvn nondex:debug