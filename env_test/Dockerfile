# Base image OF JDK
FROM opendjdk:8
LABEL authour="DK"
LABEL organiasaiton="DEVOPS"
# Setting environmental variable
ENV applicationpath='/springpetclinic.jar'
# Defining argument 
ARG  downloadpath
ADD ${downloadpath} ${applicationpath}
EXPOSE 8080
# Command to run the application
CMD [ "java","-jar",${applicationpath} ]
