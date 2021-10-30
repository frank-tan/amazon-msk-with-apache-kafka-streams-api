FROM adoptopenjdk/openjdk15:jre-15.0.2_7-alpine
ARG JAR_FILE=build/libs/*.jar

COPY ${JAR_FILE} kafka-streams-msk.jar

ENTRYPOINT ["java","-jar","-Xmx2g", "-Xms2g","/kafka-streams-msk.jar"]