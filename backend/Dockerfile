FROM node

COPY ./app /home/app

WORKDIR /home/app

RUN [ "bash", "-c", "npm install;" ]

CMD [ "npm", "start" ]