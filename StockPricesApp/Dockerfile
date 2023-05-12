FROM openjdk:11
ADD target/stock-0.0.1-SNAPSHOT.jar stockapp.jar
ENTRYPOINT ["java", "-jar", "stockapp.jar"]
EXPOSE 7777
ENV spring.datasource.url=jdbc:mysql://host.docker.internal:3306/stocks