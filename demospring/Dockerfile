FROM ope
njdk:17-jdk-alpine
EXPOSE 8888
ARG JAR_FILE=target/*.jar
COPY target/spring-boot-docker.jar spring-boot-docker.jar
ENTRYPOINT ["java","-jar","/spring-boot-docker.jar"]