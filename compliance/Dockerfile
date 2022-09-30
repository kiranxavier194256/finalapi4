FROM openjdk:8
LABEL maintainer="kiranxavier"
	EXPOSE 8081
	ADD pacman-api-compliance.jar complianceapi.jar
	ENTRYPOINT ["java","-jar","complianceapi.jar"]
