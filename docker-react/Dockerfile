FROM node:lts

WORKDIR /app

COPY ./docker-react/react/package*.json ./

RUN npm install

COPY ./docker-react/react/ ./

CMD ["npm","run","dev"]
