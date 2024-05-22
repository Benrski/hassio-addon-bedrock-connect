FROM openjdk:11

RUN mkdir -p /docker/brc
ADD https://github.com/Pugmatt/BedrockConnect/releases/download/1.43/BedrockConnect-1.0-SNAPSHOT.jar /docker/brc
WORKDIR /docker/brc

CMD ["java", "-Xms256M", "-Xmx256M", "-jar", "BedrockConnect-1.0-SNAPSHOT.jar", "nodb=true"]
