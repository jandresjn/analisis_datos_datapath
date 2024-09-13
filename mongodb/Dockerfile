# Usar la imagen de MongoDB Community Server
FROM mongodb/mongodb-community-server:latest

# Crear el directorio donde se almacenará la base de datos
RUN mkdir -p /data/db

# Exponer el puerto 27017
EXPOSE 27017

# Comando por defecto para iniciar MongoDB
CMD ["mongod"]