FROM eclipse-temurin:21-jre

ENV JAVA_OPTS="-Xms512m -Xmx512m -Djava.security.egd=file:/dev/./urandom"

WORKDIR /app

COPY ../../../target/kbe-rest-brewery-0.0.1-SNAPSHOT.jar ./

ENTRYPOINT ["java", "-jar", "kbe-rest-brewery-0.0.1-SNAPSHOT.jar"]