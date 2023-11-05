FROM nginx:1.25.3

COPY default.conf /etc/nginx/conf.d

EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]