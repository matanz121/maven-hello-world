FROM ubuntu:16.04
RUN mkdir -p /home/my-app
ADD target/my-app-1.0-SNAPSHOT.jar /home/my-app
RUN apt-get -y update > /dev/null
RUN apt-get -y install default-jre > /dev/null
CMD java -jar /home/my-app/my-app-1.0-SNAPSHOT.jar