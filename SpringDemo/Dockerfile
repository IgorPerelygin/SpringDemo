FROM openjdk:18-jdk-alpine
VOLUME /tmp
ADD target/SpringDemo-0.0.1-SNAPSHOT.jar springdemo.jar
RUN sh -c 'touch /springdemo.jar'
CMD mvn spring-boot:run
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/springdemo.jar"]





