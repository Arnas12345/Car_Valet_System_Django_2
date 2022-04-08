This was a 4th year college project which involved building a system using Django and some design patterns.
These design patterns were the composite, command, builder, prototype, visitor, pluggable adapter, and the factory design pattern. We also implemented the interceptor architectural pattern.

We used docker to deploy the system. Instructions to run docker are found below.

**RUN DOCKER CONTAINER INSTRUCTIONS**

1.  docker build --tag python-django .
2.  docker run --publish 8080:8080 python-django
