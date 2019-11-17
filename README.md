# Django-Docker
Este es una replica de un sistema monolítico usando contenedores y el Framework Django. 
Su utilidad es de uso educativo. Tener en cuenta las versiones a usar. :)

PROCEDIMIENTO:\
DESCARGAR LA IMAGEN\
sudo docker pull centos:centos7\
COMPILAR LA IMAGEN CON EL DOCKERFILE\
sudo docker build -t django:v01 .\
CORRER EL PROGRAMA\
sudo docker run -p 8080:8080 -ti --rm  id_imagen
