FROM openjdk:8

ADD constellation-manager/target/constellation-manager-0.0.1-SNAPSHOT constellation-manager.jar
EXPOSE 8080

ENTRYPOINT ["java","-jar","constellation-manager.jar"]
