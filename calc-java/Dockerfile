FROM openjdk:alpine

LABEL version="1.0"

COPY . /usr/src/java

WORKDIR /usr/src/java

RUN javac calc.java

CMD ["java", "calc"]