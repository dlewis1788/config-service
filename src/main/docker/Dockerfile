FROM openjdk:9-b181-jre
VOLUME /tmp
ADD config-service-0.0.1-SNAPSHOT.jar config-service-0.0.1-SNAPSHOT.jar
RUN sh -c 'touch /config-service-0.0.1-SNAPSHOT.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /config-service-0.0.1-SNAPSHOT.jar" ]