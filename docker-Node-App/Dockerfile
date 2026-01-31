FROM node
ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=qwerty

RUN mkdir -p /nodeapp

COPY . /nodeapp
EXPOSE 5050

CMD ["node", "/nodeapp/server.js"]


# to build the docker image
# docker build -t mynodeapp .