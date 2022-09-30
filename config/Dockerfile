FROM openjdk:8
LABEL maintainer="kiranxavier"
	EXPOSE 8888
	ADD config.jar configapi.jar
	ENTRYPOINT ["java","-jar","configapi.jar"]
