FROM alpine:edge
RUN apk update
RUN apk add nginx

RUN mkdir -p /var/cache/nginx/
RUN chown nginx:nginx /var/cache/nginx/

CMD ["nginx", "-g", "pid /tmp/nginx.pid; daemon off;"]
