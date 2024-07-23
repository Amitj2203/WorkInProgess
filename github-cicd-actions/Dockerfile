FROM openjdk:22
EXPOSE 8080
ADD ./github-cicd-actions/target/springboot-image.jar springboot-image.jar
ENTRYPOINT ["java","-jar","springboot-image.jar"]