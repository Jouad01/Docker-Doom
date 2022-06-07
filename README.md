# Docker-Doom

*Práctica realziada con una máquina virtual - Ubuntu Desktop 20.04*

## Instalación

Una vez tengamos docker instalado ejecutamos los siguientes comandos.

```
- sudo chmod 666 /var/run/docker.sock
- for i in {1..2} ; do docker run -d -t ubuntu:14.04; done
```
![](Images/Screenshot_1.png)

Descargamos la imagen **dockerdoomd** y nos situamos en el mismo directorio

![](Images/Screenshot_2.png)

La ejecutamos para comprobar el puerto

![](Images/Screenshot_3.png)

Con VNC Viewer instalado es suficiente con ejecutar el mismo puerto para tener el juego a nuestra disposición.

![](Images/Screenshot_6.png)
![](Images/Screenshot_4.png)
![](Images/Screenshot_5.png)
