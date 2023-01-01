FROM node:7
WORKDIR /app
COPY package.json /app/
RUN npm insatall
COPY ./ app
CMD node server.js
EXPOSE 3000