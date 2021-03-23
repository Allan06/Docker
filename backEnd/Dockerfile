FROM openjdk:8-jdk-alpine

# cd /opt/app
WORKDIR /app/backend

# cp target/spring-boot-web.jar /opt/app/app.jar
COPY target/asi2-backendmarket-SNAPSHOT app.jar

# java -jar /opt/app/app.jar
ENTRYPOINT ["java","-jar","app.jar"]