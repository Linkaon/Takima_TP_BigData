# Utiliser l'image officielle Apache
FROM httpd:latest

# Copier la configuration personnalisée dans le conteneur
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf

# Copier la page index.html par défaut
COPY ./index.html /usr/local/apache2/htdocs/index.html
