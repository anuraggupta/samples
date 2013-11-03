Samples
=======

In this repository you can find the various samples I reference in my blog (http://www.clempinch.com)

sample-continuation
-------------------

This is a simple demonstration of the Apache CXF Continuation API. See: http://www.clempinch.com/cxf-and-the-continuation-api/

The project should be built with Maven:

    mvn package

You obtain a WAR to deploy a Web application sever. I tested it with Tomcat 7.0.35.

The created REST service can be accessed with a GET at:

    http://[server_address]/continuation_example-0.0.1-SNAPSHOT/my_rest_service/say_hello/world
