FROM openjdk:8-jre
MAINTAINER pdai
WORKDIR /
ADD target/todo-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar"]
CMD ["app.jar"]