# Instalación de Ubuntu 24.04 en VirtualBox
---
## Índice

1. Obtención de la imagen ISO
2. Creación de la máquina virtual
3. Configuración de la máquina virtual
---
## 1. Obtención de la imagen ISO

Para obtener la imagen ISO de Ubuntu, vamos a nuestro buscador de preferencia y en la barra de búsqueda introducimos *Ubuntu 24.04 ISO* y entramos al enlace que dice *Ubuntu 24.04 (Noble Numbat)*.

![Buscador Ubuntu](imagenes/Ubuntu.png)
<small>El resultado puede variar, tanto la vesión de Ubuntu 24.04.x, como el nombre que recibe la release</small>

**Es importante asegurarse de que el enlace es original, porque existe el riesgo de descargar una imagen infectada en caso de no obtener la imagen de un enlace lícito.**

Una vez accedido al enlace de descaga de la imagen, nos recibiría una web como esta:

![Inicio web Ubuntu](imagenes/Web_Ubuntu.png)

En el primer elemento de la tabla, donde pone *Desktop Image*, pinchamos en el enlace de la columna de a derecha, donde pone 64-bit PC (AMD64) desktop image, o pinchando en este [enlace](https://releases.ubuntu.com/noble/ubuntu-24.04.5.1-desktop-amd64.iso).

Pinchando en el enlace, comenzaría la descarga, la cuál será visible pulsando Ctrl + j, para ir al administrado de descargas, viéndose algo así:

![Administrador de descargas](imagenes/Descarga%20Ubuntu.png)

Una vez descargada la imagen ISO, deberemos localizarla en nuestro equipo. **Por defecto se encuentra en la carpeta *Descargas***

---

## 2. Creación de la máquina virtual

Para crear la máquina virtual, accederemos al *VirtualBox*. Donde nos recibirá una página de inicio como esta:

![Inicio Vbox](./Imagenes/Vbox.png)

En el panel superior, podemos ver una serie de opciones, algo similiar a esto 

![botones Vbox](./Imagenes/Captura%20de%20pantalla%20de%202026-10-14%2010-32-54.png)

Pinchamos en la estrella azul que pone '*nueva*', y se desplegará un menú de configuración inicial con varios campos. Algo similar a esto:

![nueva](./Imagenes/nueva.png)

Ahora cubriremos todos los campos ajustándose a nuestras necesidades. En cada campo irá esta información

| Campo | Información|
|:-----:|:-------:|
|VM Name|Nombre de la máquina virtual|
|VM Folder|Ruta donde se guardará la carpeta con los datos de la MV|
|ISO Image|Imagen ISO con el Sistema Operativo que queremos usar en la MV|
|OS Edition|Versión del sistema operativo|
|OS|Sistema Operativo|
|OS Distribution|Para sistemas linux|
|||