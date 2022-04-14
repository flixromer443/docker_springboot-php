FROM openjdk:11


COPY ./api_midland/target/api_midland-0.0.1-SNAPSHOT.jar /usr/src/api_midland/

WORKDIR /usr/src/api_midland/

EXPOSE 80

ENTRYPOINT ["java", "-jar", "api_midland-0.0.1-SNAPSHOT.jar"]


#mover a la raiz de docker_api_midland
#correr: docker  build -t api_midland/server .
