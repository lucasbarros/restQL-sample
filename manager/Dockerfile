from b2wdigital/restql-manager:latest

ARG MONGODB_URI="mongodb://localhost:27017/restql-test"
ENV MONGO_URL=$MONGODB_URI
RUN export MONGO_URL=$MONGO_URL

ARG RESTQL_SERVER_URL="http://localhost:9000"
ENV RESTQL_SERVER_URL=$RESTQL_SERVER_URL
RUN export RESTQL_SERVER_URL=$RESTQL_SERVER_URL