# Comandos-usados-en-modulo-8

 Instalación y uso básico de Docker en RHEL 8
1. Preparar el sistema
sudo dnf update -y
sudo dnf install -y yum-utils device-mapper-persistent-data lvm2

2. Agregar repositorio de Docker
sudo dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo

3. Instalar Docker
sudo dnf install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin --allowerasing
sudo systemctl start docker
sudo systemctl enable docker
sudo docker version

4. Comandos básicos de Docker 
Crear el index.html

sudo mkdir -p /home/website

sudo nano /home/website/index.html


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NGINX en Docker</title>
</head>
<body>
    <h1>Thaziel Brea</h1>
    <h1>2025-2192</h1>
</body>
</html>

a) Descargar imagen:
sudo docker pull nginx:latest 

cat  /home/website/index.html

b) Ejecutar contenedor con mapeo de puerto:
sudo docker rm -f mi_httpd  =borramos el que existe

 Mapear volumen (para servir tus propios archivos):

sudo docker run -d \
  --name SO3-nginx \
  -p 8888:80 \
  -v /home/website:/usr/share/nginx/html:Z \
  nginx:latest
::
sudo docker ps

sudo firewall-cmd --permanent --add-port=8888/tcp
sudo firewall-cmd --reload


Ahora abre http://TU_IP:8080 y verás la página de Apache.

c) Ver contenedores:
sudo docker ps
sudo docker ps -a

d) Detener/Iniciar contenedor:
sudo docker stop mi_httpd
sudo docker start mi_httpd

e) Eliminar contenedor:
sudo docker rm -f mi_httpd
sudo docker rm mi_httpd

g) Eliminar imagen:
sudo docker rmi httpd:latest



