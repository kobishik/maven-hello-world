FROM ubuntu:16.04
RUN mkdir -p /home/my-app
ADD /home/vsts/work/1/my-app/target/my-app-1.0-SNAPSHOT.jar /home/my-app
RUN java -cp /home/my-app/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
RUN echo ===== && pwd && echo ===== && ls -lR
EXPOSE 8080
