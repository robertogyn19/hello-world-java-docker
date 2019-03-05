FROM java:8-alpine
LABEL MAINTAINER="Roberto Rodrigues Junior <robertogyn19@gmail.com>"
LABEL tag=hello-world

ADD . /code
WORKDIR /code
RUN javac src/HelloWorld.java
RUN jar cfve hello-world.jar HelloWorld -C src HelloWorld.class

CMD [ "java", "-jar", "hello-world.jar" ]
