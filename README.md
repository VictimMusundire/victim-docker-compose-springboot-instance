1. Add the Dockerfile and docker-compose.yml files to your springboot project if you need to dockerize it alone
2. mvn clean package => to create a jar that is being referenced when creating an image in the Dockerfile.
3. docker-compose up => to build docker images for mysql and springboot-app and run them in containers.
