# syntax=docker/dockerfile:1

FROM node:12.18.1

WORKDIR /client

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install --production

COPY . .

CMD [ "npm" ,"start" ]


.