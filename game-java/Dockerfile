FROM openjdk:alpine

LABEL version="1.0"

COPY . /usr/src/game

WORKDIR /usr/src/game/

RUN javac game.java

CMD ["java", "game"]