FROM openjdk:11-jdk-slim
VOLUME /tmp
ADD app/plataform.jar app.jar
EXPOSE 8080
RUN java -jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]