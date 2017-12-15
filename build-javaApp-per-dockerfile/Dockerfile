FROM fabric8/java-jboss-openjdk8-jdk:1.2
EXPOSE 8080
MAINTAINER Mario
ADD openshift-app.jar /
ENTRYPOINT ["java", "-jar", "/openshift-app.jar"]
