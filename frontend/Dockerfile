FROM node:20.11

COPY ./app /home/app

WORKDIR /home/app

RUN [ "bash", "-c", "npm install; run build;" ]

CMD [ "npm", "start" ]