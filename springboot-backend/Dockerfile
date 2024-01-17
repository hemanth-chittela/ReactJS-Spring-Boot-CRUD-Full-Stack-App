# pulling the image 
FROM ubuntu
# updating the packages
RUN apt update
# installing the java
RUN apt install -y default-jre
# installing the maven software
RUN apt install -y maven
# copying the files in to the ubuntu
COPY * /
# running the mvn clean package
RUN mvn clean package

