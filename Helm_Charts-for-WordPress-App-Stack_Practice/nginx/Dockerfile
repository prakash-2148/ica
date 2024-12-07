FROM nginx:latest
COPY nginx.conf /etc/nginx/conf.d/default.conf
RUN [ -f /etc/nginx/conf.d/default.conf ] && rm /etc/nginx/conf.d/default.conf || true



EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
