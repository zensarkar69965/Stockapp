FROM openjdk:11
ADD target/stock-0.0.1-SNAPSHOT.jar stockapp.jar
ENTRYPOINT ["java", "-jar", "stockapp.jar"]
EXPOSE 7777
ENV spring.datasource.url=jdbc:mysql://stockpricesappdb.cxp2rqrarauv.ap-south-1.rds.amazonaws.com:3306/stockpricesappdb