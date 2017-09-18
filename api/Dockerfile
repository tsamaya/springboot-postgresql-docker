FROM openjdk:8-jdk-alpine

# ENV SPRING_PROFILES_ACTIVE test

# set working directory
RUN mkdir -p /srv/app

WORKDIR /srv/app

COPY build/libs/api-0.0.1-SNAPSHOT.war /srv/app

EXPOSE 8080

# start app
CMD ["java", "-jar", "api-0.0.1-SNAPSHOT.war"]
