FROM openjdk:8
EXPOSE 1234
ADD target/jenkins-springboot.jar jenkins-springboot.jar
ENTRYPOINT ["java","-jar","/jenkins-springboot.jar"]