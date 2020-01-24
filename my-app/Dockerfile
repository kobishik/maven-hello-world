FROM ubuntu:16.04
RUN mkdir -p /home/my-app
ADD target/my-app-1.0-SNAPSHOT.jar /home/my-app
RUN apt-get update
#RUN apt-get install default-jdk
RUN java -cp /home/my-app/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
RUN ls -lR
EXPOSE 8080
