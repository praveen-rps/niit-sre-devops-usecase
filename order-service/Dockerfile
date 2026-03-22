FROM openjdk:27-ea-jdk
RUN mkdir /service
COPY order-service-0.0.1-SNAPSHOT.jar /service
EXPOSE 8082
CMD ["java","-jar","/service/order-service-0.0.1-SNAPSHOT.jar"]