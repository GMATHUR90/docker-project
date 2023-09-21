#Getting base image

FROM openjdk:11

#Working directory where all code will be kept

WORKDIR app/

#Copy the app to the current directory of container
COPY Hello.java .

#Compile Code
RUN javac Hello.java

#Run java compile code
CMD ["java","Hello"]

