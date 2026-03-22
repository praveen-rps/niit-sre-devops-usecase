FROM openjdk:27-ea-jdk
RUN mkdir /service
COPY service-registry-0.0.1-SNAPSHOT.jar /service
EXPOSE 8761
CMD ["java","-jar","/service/service-registry-0.0.1-SNAPSHOT.jar"]