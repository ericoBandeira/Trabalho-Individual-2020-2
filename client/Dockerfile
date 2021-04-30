FROM node:14.16.1

WORKDIR /front

COPY . . 

RUN yarn global add @quasar/cli

RUN yarn install

CMD yarn && quasar dev
