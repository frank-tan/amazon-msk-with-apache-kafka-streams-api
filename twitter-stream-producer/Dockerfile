FROM adoptopenjdk/openjdk15:jre-15.0.2_7-alpine
ARG JAR_FILE=build/libs/*.jar

COPY ${JAR_FILE} twitter-stream-producer.jar

ENTRYPOINT ["java","-jar","-Xmx2g", "-Xms2g","/twitter-stream-producer.jar"]