FROM openjdk:18-jdk-alpine
VOLUME /tmp
ADD target/SpringDemo.jar springdemo.jar
RUN sh -c 'touch /springdemo.jar'
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/springdemo.jar"]





