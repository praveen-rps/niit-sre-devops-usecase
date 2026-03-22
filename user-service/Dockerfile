FROM openjdk:27-ea-jdk
RUN mkdir /service
COPY user-service-0.0.1-SNAPSHOT.jar /service
EXPOSE 8081
CMD ["java","-jar","/service/user-service-0.0.1-SNAPSHOT.jar"]