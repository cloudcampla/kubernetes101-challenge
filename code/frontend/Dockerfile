FROM node:16.10.0

ADD . .
RUN rm yarn.lock
RUN yarn install
RUN yarn build

CMD ["yarn", "start"]

