FROM nginx:1.21-alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY certificate/nginx.crt /etc/nginx/certificate/nginx.crt
COPY certificate/nginx.key /etc/nginx/certificate/nginx.key
RUN chmod 600 /etc/nginx/certificate/nginx.key
