# Imagen basde de ubuntu
FROM ubuntu:latest
# Actualizar , Instalar
RUN apt-get update && apt-get upgrade -y && apt-get install -y python3 python3-pip && rm -f /usr/lib/python*/EXTERNALLY-MANAGED
# Install Flask
RUN pip3 install Flask
RUN pip3 install Flask-Cors
# Directorio de trabajo
WORKDIR /app
# Copiar api.py al contenedor
COPY ./api.py /app/api.py
EXPOSE 5252
CMD ["python3", "api.py"]