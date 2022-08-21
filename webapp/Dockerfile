FROM node:16

ENV APP_HOME /app
RUN mkdir -p $APP_HOME
WORKDIR $APP_HOME

RUN apt-get update 
COPY package.json .
RUN npm install