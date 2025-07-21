    # Utilise l'image officielle de Nginx
FROM nginx:alpine

# Copie les fichiers de configuration personnalisée (optionnel)
COPY nginx.conf /etc/nginx/nginx.conf

# Copie les fichiers statiques vers le dossier servi par Nginx
COPY ./html /usr/share/nginx/html

# Expose le port 80
EXPOSE 80

# Démarre Nginx en mode foreground
CMD ["nginx", "-g", "daemon off;"]
