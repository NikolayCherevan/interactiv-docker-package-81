## FROM NIK:
## This file uses for nodeJS container to build static with gulp. It should be a solution for node versions
## and a lot of problems with it. Just use bin/node-bash and work with required node version.
## Now it is 14.15-alpine3.13 just to be sure that node-sass will be work fine

FROM node:14.15-alpine3.13
ENV PYTHONUNBUFFERED=1
RUN apk add --update --no-cache build-base g++ python2 && ln -sf python2 /usr/bin/python
RUN python2 -m ensurepip
RUN pip install --no-cache --upgrade pip setuptools
RUN npm install --global gulp-cli