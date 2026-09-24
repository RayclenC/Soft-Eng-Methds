FROM amazoncorretto:17
COPY ./target/classes/com /tmp/com
WORKDIR /tmp
LABEL authors="raycl"
ENTRYPOINT ["java", "com.napier.sem.Main"]

