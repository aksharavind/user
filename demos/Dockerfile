# Use an official OpenJDK base image to run the app
FROM openjdk:23-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container (make sure to update the JAR file name)
COPY target/demos-0.0.1-SNAPSHOT.jar app.jar


# Expose port 8080 for your application (default port for Spring Boot)
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]
