FROM ubuntu:16.04
COPY ./target/my-app-1.0-SNAPSHOT-shaded.jar /my-app-1.0-SNAPSHOT-shaded.jar
EXPOSE 8080
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/my-app-1.0-SNAPSHOT-shaded.jar"]