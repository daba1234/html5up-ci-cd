# Utiliser une image Nginx légère
FROM nginx:alpine

# Copier les fichiers du site dans le répertoire web de Nginx
COPY . /usr/share/nginx/html

# Exposer le port 8080
EXPOSE 8080

# Démarrer Nginx
CMD ["nginx", "-g", "daemon off;"]