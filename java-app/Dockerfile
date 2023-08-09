# Getting base image
FROM openjdk:17

# Working directory where all code will be kept
WORKDIR app/

# Copy the app to the current directory of container
COPY Hello.java .

# Compile code
RUN javac Hello.java

# Run java compiled code (byte code)
CMD ["java", "Hello"]


