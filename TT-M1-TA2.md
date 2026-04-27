# Práctica de comandos de Linux

Estudiante: Gabriel Sotomayor

Fecha: 26/4/2026

Duración: 1h



## Fundamentos



Docker es una plataforma que permite crear, ejecutar y administrar aplicaciones dentro de contenedores. Un contenedor es como una “caja” ligera y portátil que incluye todo lo necesario para que una aplicación funcione: el código de la aplicación, sus librerías y dependencias, configuraciones específicas. De esta forma, la aplicación corre siempre igual sin importar el sistema operativo o la máquina donde se ejecute.



## Conocimientos previos



Necesario tener claro los siguientes temas:

* Comandos Linux
* Manejo de GitBash
* Comandos Docker



## Objetivos



* Dominar comandos básicos de Docker
* Crear y modificar contenedores Docker.



## Equipo necesario:



* Computadora.
* Terminal de GitBash.
* Docker Desktop instalado
* DataGrip instalado



## Material de apoyo



* Guía de comandos básicos de Docker



## Procedimiento



* Desplegar dos servidores web basados en la imagen de Nginx:
* Crea el primer contenedor Nginx llamado nginx1 exponiendo el puerto 8089: docker run -d --name nginx1 -p 8089:80 nginx
* Crea el segundo contenedor Nginx llamado nginx2 exponiendo el puerto 8090: docker run -d --name nginx2 -p 8090:80 nginx
* Editar el archivo index.html para personalizar el contenido en cada servidor:
* En el primer contenedor, se mostrará información institucional.
* En el segundo contenedor, se colocará información personal del estudiante.

## Resultados



Imágenes de las evidencias de la terminal de GitBash:

!\[Evidencia1](imagenes/evidencia1.png)

!\[Evidencia2](imagenes/evidencia2.png)

!\[Evidencia3](imagenes/evidencia3.png)

