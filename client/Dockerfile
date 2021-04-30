FROM node:14.16.1

RUN yarn global add @quasar/cli

WORKDIR /front

COPY . . 

CMD yarn && quasar dev
