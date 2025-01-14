FROM node:20-alpine3.19

RUN adduser -D nuxt \
    && mkdir /home/nuxt/app/ \
    && mkdir /home/nuxt/logs

COPY ./frontend /home/nuxt/app/

WORKDIR /home/nuxt/app/

RUN npm install

CMD while true; do sleep 30; done;
