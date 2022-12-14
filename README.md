<h3 align = "center"> Sprint0_Android </h3>

---
<p align = "center"> En este repositorio se encuentra el c贸digo de la aplicaci贸n Android capaz de recibir beacons y subirlos a una base de datos
    <br>
</p>

## 馃摑 Tabla de contenido

- [Introducci贸n](#Getting_started)

## 馃弫 Comenzando <a name = "getting_started"> </a>

Estas instrucciones le proporcionar谩n una copia del proyecto en funcionamiento en su ordenador con fines de desarrollo y prueba

### Requisitos previos

Qu茅 necesita para instalar el software y c贸mo instalarlo.
Lo 煤nico que se debe instalar para hacer funcionar este proyecto es XAMPP y Android Studio para ser capaces de ejecutar la aplicaci贸n en nuestro dispositivo. 

```
[XAMPP](https://www.apachefriends.org/es/download.html).
```

```
[Android Studio](https://developer.android.com/studio).
```
A su vez es si no se dispone de un servidor abierto, tendremos que dirigirnos a la ruta en la que hayamos instalado XAMPP y en httdocs crear una carpeta llamada "sprint0" con dos archivos .sql

```
conexion.sql e insertarMedida.sql
```

Dichos archivos son importantes para la correcta comunicaci贸n con la base de datos.

### Instalaci贸n

Tras haber completa la instalaci贸n de los programas, abriremos el XAMPP e iniciaremos los servicios de Apache y MySQL, tambi茅n abriremos el proyecto en Android Studio

1. Dentro de la clase Logica, que se encuentra visto desde Android Studio:

```
Sprint0_Android/app/java/ctorcru.upv.sprint0android/Logica
```

2. Cambiaremos la URL, para ello necesitamos conocer nuestro ip. Para conocer la ip nos fijamos en la Ipv4 de este comando en la terminal:

```
ipconfig
```

3. A su vez necesitamos conocer el puerto por el que escucha nuestro ordenador, esto se puede ver en el XAMPP pulsado sobre config en Apache

4. Por lo tanto la URL se deber铆a cambiar siguiendo este formato:

```
http://IP:PUERTO/sprint0/insertarMedida.php
```

5. Por 煤ltimo hay que concederle permisos a la aplicaci贸n de "encontrar dispositivos cercanos" activando el blueetooth (en algunos dispositivos hay que hacerlo de forma manual la concesi贸n de permisos)