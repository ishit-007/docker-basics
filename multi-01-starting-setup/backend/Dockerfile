FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGODB_USERNAME=ishit

ENV MONGODB_PASSWORD=secret

CMD ["npm","start"] 