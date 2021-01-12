iaw-practica-11

1.1 WPScan
La herramienta que vamos a utilizar para realizar la auditoría de nuestro sitio web WordPress es wpscan.

Si ejecutamos wpscan --help podemos ver todas las opciones que podemos realizar con wpscan.

1.2 Ejemplo básico de uso
Para obtener la lista de plugins instalados en nuestro sitio WordPress podemos ejecutar:

wpscan --url http://192.168.22.20 --enumerate p
Donde 192.168.22.20 será la dirección IP de nuestro balanceador web.

1.3 Contenedor Docker con WPScan
Vamos a utilizar una imagen Docker que ya contiene la utilidad WPScan. El archivo Dockerfile que se ha utilizado para crear la imagen está disponible en el repositorio GitHub del proyecto.

La imagen de WPScan está disponible en Docker Hub:

https://hub.docker.com/r/wpscanteam/wpscan/
Ejemplo básico de uso

Para obtener la lista de plugins instalados en nuestro sitio WordPress podemos ejecutar:

docker run -it --rm wpscanteam/wpscan --url http://192.168.22.20  --enumerate p
Donde 192.168.22.20 será la dirección IP de nuestro balanceador web.
