# Step 1: Use lightweight JDK base image
FROM openjdk:17-jdk-slim

# Step 2: Copy jar file from target folder
COPY target/devops-docker-demo-1.0.jar app.jar

# Step 3: Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]
