FROM node:6.10

MAINTAINER Azman0101 <azman0101@gmail.com>

RUN npm install -g eslint
RUN apt-key adv --fetch-keys http://dl.yarnpkg.com/debian/pubkey.gpg && echo "deb http://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list && apt-get update -qq && apt-get install -y -qq yarn && rm -rf /var/lib/apt/lists/*
RUN npm install serverless -g
