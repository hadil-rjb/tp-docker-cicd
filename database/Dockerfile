FROM postgres:15-alpine

# Copier le script d'initialisation dans le dossier attendu par PostgreSQL
COPY init.sql /docker-entrypoint-initdb.d/init.sql

EXPOSE 5432
