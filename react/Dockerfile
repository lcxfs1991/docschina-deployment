FROM node:18-alpine as base
RUN apk add --no-cache g++ make py3-pip libc6-compat curl
RUN mkdir -p /app
WORKDIR /app

COPY . .

RUN yarn
RUN yarn build

EXPOSE 3000

CMD ["npm", "start"]