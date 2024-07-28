# Utiliser l'image nginx officielle
FROM nginx:latest

# Copier le fichier mypage.html dans le répertoire par défaut de nginx
COPY mypage.html /usr/share/nginx/html/

# Copier le fichier de configuration personnalisé
COPY default.conf /etc/nginx/conf.d/default.conf

# Exposer le port 80
EXPOSE 80

