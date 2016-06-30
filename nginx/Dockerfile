FROM nginx:alpine

MAINTAINER Daniel Noyola <danielnv18@gmail.com>

COPY nginx.conf /etc/nginx/nginx.conf
COPY lemp.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]
