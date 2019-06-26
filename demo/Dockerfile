    
FROM nginx:1.13.3-alpine

RUN rm -rf /usr/share/nginx/html/*
COPY ./build /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/ 
EXPOSE 3000
CMD ["nginx", "-g", "daemon off;"]