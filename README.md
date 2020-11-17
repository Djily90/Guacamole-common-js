# What is guacamole-common-js?

guacamole-common-js is the core JavaScript library used by the Guacamole web application.
guacamole-common-js provides an efficient HTTP tunnel for transporting protocol data between JavaScript and the web application, as well as an implementation of a Guacamole protocol client and abstract synchronized drawing layers.

# Compiling and installing Apache Guacamole Client

Apache Guacamole is built using Maven. Building Guacamole compiles all classes
and packages them into a deployable .war file. This .war file can be installed
and deployed under servlet containers like Apache Tomcat or Jetty.

1) Run mvn package

    $ mvn package

    Maven will download any needed dependencies for building the .jar file.
    Once all dependencies have been downloaded, the .war file will be
    created in the guacamole/target/ subdirectory of the current directory.

2) Copy the .war file as directed in the instructions provided with
   your servlet container. 

   Apache Tomcat, Jetty, and other servlet containers have specific and
   varying locations that .war files must be placed for the web
   application to be deployed.
   
   You will likely need to do this as root.
# Source archives
https://guacamole.apache.org/doc/gug/writing-you-own-guacamole-app.html
