FROM nginx:alpine

# Copier le fichier HTML
COPY index.html /usr/share/nginx/html/

# Configuration UTF-8 en une ligne
RUN echo 'charset utf-8;' > /etc/nginx/conf.d/charset.conf

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]