FROM alpine:edge
RUN apk update
RUN apk add nginx

CMD ["nginx", "-g", "pid /tmp/nginx.pid; daemon off;"]
