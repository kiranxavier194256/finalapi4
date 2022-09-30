FROM openjdk:8
LABEL maintainer="kiranxavier"
	EXPOSE 8087
	ADD pacman-api-auth.jar authapi.jar
	ENTRYPOINT ["java","-jar","authapi.jar"]
