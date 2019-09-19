FROM node:latest

RUN mkdir -p /rasa-ui
WORKDIR /rasa-ui

COPY . .

RUN npm install

EXPOSE 5001

ENTRYPOINT ["npm", "run"]
CMD ["start"]