#FROM node:lts-alpine
FROM node:16.4.0
WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

RUN npm install @vue/cli@4.5.13 -g

COPY package.json .
COPY package-lock.json .
RUN npm install

CMD ["npm", "run", "serve"]
