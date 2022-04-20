FROM node:16-alpine

LABEL name="serverjs_image"
LABEL version="0.1"
LABEL description="Node JS Server"

WORKDIR /usr/src/server

COPY . /usr/src/server

RUN ls -la
RUN npm install
CMD [ "node", "server.js" ]
EXPOSE 3000