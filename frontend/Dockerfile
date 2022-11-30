FROM node:18-alpine AS frontend
WORKDIR /usr/src/app/next
COPY . /usr/src/app/next

RUN npm install

ENTRYPOINT ["npm", "run", "dev"]