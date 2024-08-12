FROM node:22-alpine3.19

ENV VUE_APP_API_URL=http://api.belajar-docker.com

RUN mkdir /app

COPY . /app

RUN yarn --cwd /app install

CMD ["yarn", "--cwd" ,"/app", "serve"]
