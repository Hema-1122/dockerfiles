FROM node:20
workdir /opt/server
copy package.json .
copy *.js .
RUN
ENV MONGO="true"
    MONGO_URL="mongodb://<mongodb>:27017/catalogue"
CMD ["node", "server.js"]