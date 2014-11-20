To build this project use

    mvn install

You can run this project using he following Maven goal:

    mvn camel:run

To deploy the project in OSGi.

    osgi:install -s mvn:com.mycompany/camel-spring-dm/1.0.0-SNAPSHOT
