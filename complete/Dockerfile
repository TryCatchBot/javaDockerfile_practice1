FROM ubuntu:latest


RUN \
# Update
apt-get update -y && \
# Install Java
apt-get install default-jre -y

EXPOSE 8080

CMD java -jar spring-mvc-example.jar




# https://medium.com/cloud-tidbits/dockerize-your-java-application-ec7ac056d066
