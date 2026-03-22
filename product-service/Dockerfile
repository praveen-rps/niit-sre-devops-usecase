FROM openjdk:27-ea-jdk
RUN mkdir /service
COPY product-service-0.0.1-SNAPSHOT.jar /service
EXPOSE 8083
CMD ["java","-jar","/service/product-service-0.0.1-SNAPSHOT.jar"]