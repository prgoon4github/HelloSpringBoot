FROM centos
VOLUME /tmp
FROM openjdk:8u111-jre-alpine
EXPOSE 8080
ADD sample-0.1.0.jar sample.jar
RUN sh -c 'touch /sample.jar'
CMD ["java", "-jar","/sample.jar"]
