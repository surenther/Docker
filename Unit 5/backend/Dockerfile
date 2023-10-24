FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGO_USERNAME=root
ENV MONGO_PASS=secret

CMD [ "npm" , "start" ]

