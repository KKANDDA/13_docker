#이름은 정해져있다. Dockerfile

FROM eclipse-temurin:17
RUN mkdir /opt/app
    #관습적으로 사용하는 경로이다.
COPY build/libs/docker-test-app-0.0.1-SNAPSHOT.jar /opt/app/kkandda_app.jar
CMD ["java", "-jar", "/opt/app/kkandda_app.jar"]
EXPOSE 8804
    #강제성이 없다
