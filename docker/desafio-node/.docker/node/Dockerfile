FROM node:15

WORKDIR /app

COPY .docker/node/docker-entrypoint.sh /usr/bin/docker-entrypoint

COPY package.json package-lock.json /app/

RUN npm install

EXPOSE 3000

CMD ["docker-entrypoint"]
