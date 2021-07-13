FROM node:11-alpine as build
WORKDIR /app
COPY package*.json /app/
RUN npm install -g ionic
RUN npm install
COPY ./ /app/
WORKDIR /app/
RUN ionic build
RUN ionic serve