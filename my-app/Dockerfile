FROM ubuntu:16.04
RUN mkdir -p /home/my-app
ADD target/my-app-1.0-SNAPSHOT.jar /home/my-app
RUN apt-get -y update > /dev/null
RUN apt-get -y install default-jre > /dev/null
RUN java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App