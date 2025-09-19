FROM openjdk

COPY . /java

WORKDIR /java

EXPOSE 88

RUN javac Main.java

CMD [ "java", "Main" ]