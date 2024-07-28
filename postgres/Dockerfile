# Utiliser l'image postgres officielle
FROM postgres:latest

# Copier le fichier de script SQL dans le répertoire par défaut de postgres
COPY bd.sql /docker-entrypoint-initdb.d/
