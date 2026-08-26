# Utiliser une image Nginx légère
FROM nginx:alpine

# Copier les fichiers du site dans le répertoire web de Nginx
COPY . /usr/share/nginx/html

# Exposer le port 80
EXPOSE 80

# Démarrer Nginx
CMD ["nginx", "-g", "daemon off;"]