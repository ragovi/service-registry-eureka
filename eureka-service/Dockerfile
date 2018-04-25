FROM java:8
MAINTAINER Raúl González <raul.gzv@gmail.com>
ARG JAR_FILE
ADD target/${JAR_FILE} app.jar
EXPOSE 8761
ENTRYPOINT ["/usr/bin/java", "-jar", "app.jar"]