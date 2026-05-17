FROM postgres:16-alpine
# Copia automáticamente el seed de base de datos para ejecutarse al iniciar
COPY init.sql /docker-entrypoint-initdb.d/01-init.sql
EXPOSE 5432