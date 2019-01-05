# Specify a base image
FROM openjdk:8-jre-alpine
WORKDIR /usr/app
COPY ./comeandeat-0.0.1-SNAPSHOT.jar ./
#Install some dependencies
# COPY ./package.json ./
# RUN npm install
# RUN npm install graphql --save
# COPY ./ ./

#Default command
#RUN "/usr/bin/java -version"
CMD ["/usr/bin/java","-jar", "comeandeat-0.0.1-SNAPSHOT.jar"]
