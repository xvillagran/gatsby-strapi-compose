FROM node:18
LABEL maintainer="xuanvillagran@gmail.com"

EXPOSE 8000

RUN npm install -g gatsby-cli

RUN mkdir -p /frontend
WORKDIR /frontend
VOLUME /frontend

USER node

CMD ["gatsby", "develop", "--host", "0.0.0.0"]