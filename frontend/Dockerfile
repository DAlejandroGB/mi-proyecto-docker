# Usa una imagen de Nginx para servir el sitio estático
FROM nginx:alpine

# Borra la config default de Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia tu build Angular al lugar donde Nginx sirve archivos
COPY dist/shell/ /usr/share/nginx/html

# Expón el puerto en que corre Nginx
EXPOSE 80
