FROM openjdk:11.0-jdk
WORKDIR /app
COPY . /app
RUN ./mvnw compile assembly:single
CMD  ["java", "-jar", "/app/target/sameple-app-1.0.0-jar-with-dependencies.jar"]                                                                                                                                                                                                                                                                                    
