FROM node:lts

WORKDIR /app

COPY ./docker-react/react/package*.json ./

RUN npm ci

CMD ["npm","run","dev"]
