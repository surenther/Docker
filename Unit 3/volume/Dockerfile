FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ARG DEFAULT_PORT=8000

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

CMD ["npm","start"]

