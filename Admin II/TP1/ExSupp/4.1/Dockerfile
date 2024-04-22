FROM httpd:latest 

#Copie des pages d'accueil personnalisées 
COPY index1.html /usr/local/apache2/htdocs/index1.html
COPY index2.html /usr/local/apache2/htdocs/index2.html

# Ajout de la configuration des VirtualHosts
COPY my-httpd.conf /usr/local/apache2/conf/httpd.conf