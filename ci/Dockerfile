FROM alpine:edge
RUN apk update
RUN apk add nodejs-current

ADD . /ci
WORKDIR /ci

CMD npm start
