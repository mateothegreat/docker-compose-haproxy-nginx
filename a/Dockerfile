FROM nginx

COPY default.conf   /etc/nginx/conf.d/
COPY index.html     /usr/share/nginx/html/
COPY otherfile.html /usr/share/nginx/html/

ENTRYPOINT ["nginx", "-g", "daemon off;"]