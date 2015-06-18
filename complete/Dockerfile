FROM 10.52.179.232:5000/maven:3.2-jdk-8

WORKDIR /opt

# This copies to local fat jar inside the image
ADD ./target/*.jar /app/app.jar

# What to run when the container starts
ENTRYPOINT [ "java", "-jar", "/app/appname.jar" ]

# Ports used by the app
EXPOSE 8080 
