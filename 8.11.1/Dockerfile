FROM node:20.12.0-alpine@sha256:eaa20a0b947202bff49ac9667688a109af6d5ddda168cd03aca600603cf433d9

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
