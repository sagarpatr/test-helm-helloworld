FROM sbo-cicd-docker-release-local.artifactory-lvn.broadcom.net/broadcom-custom-images-legacy/centos/8/mvn:latest
COPY target/SpringBootHelloWorld-0.0.1-SNAPSHOT.jar SpringBootHelloWorld-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["sh", "-c", "java -jar /SpringBootHelloWorld-0.0.1-SNAPSHOT.jar"]
