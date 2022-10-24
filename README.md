# Documentacion MP4_UF1

## GitHub

### Creación de un repositorio:
Crear un repositorio en GitHub es muy senzillo, desde este [enlace](https://github.com/new) se accede a la pestaña de creación.

![Imagen1](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/1.png?raw=true)

Una vez creado el repositorio podemos utilizar un lenguaje de marcas llamado Markdown para escribir dentro del readme.md.

### Markdown (Lenguaje de marcas)
Este lenguaje de marcas es el predefinido por GitHub y asi es como se utiliza:

Para empezar los encabezados o títulos, tenemos 6 tamaños y siempre sigue la misma estructura, un # y el texto.

Para poner el mas grande seria " # Encabezado mas grande "

El mas pequeño seria " ###### Encabezado mas pequeño "

Para decorar el texto podemos hacer que sea negrita o cursiva:

Para la __negrita__ escribimos "__ texto__" todo junto.

Para la _cursiva_ escribimos "_ texto_" todo junto.

Para crear listas tenemos 2 opciones: Ordenadas o desordenadas:

Para la lista ordenada basta con escribir un " 1. " y automaticamente se autogenerarian en cada linea.
1. Ejemplo 
2. Ejemplo 

Para la lista desordenada se puede hacer de 3 maneras (+, *, -).
+ (+) Ejemplo 1
+ (+) Ejemplo 2
- (-) Ejemplo 1
- (-) Ejemplo 2
* (*) Ejemplo 1
* (*) Ejemplo 2

Para introducir un enlace, la estructura es: " [Texto que queremos que se vea](Enlace/Url de la pagina)

[Ejemplo Enlace](https://github.com/ChristianMonrabal?tab=repositories)

Para insertar una imagen en Markdown, hay que subir la imagen desde local a el repositorio:

![Imagen2](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/2.png?raw=true)

![Imagen3](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/3.png?raw=true)

Su estructura es " ![Texto por si no carga la imagen](url de la imagen subida a github) "

## Git y Visual Studio Code

Visual Studio code es un software donde se puede escribir lenguajes de marcas como (html, css, javaScript, PHP) entre otros. Al ser un software se trabaja en local por lo que mediante este [enlace](https://code.visualstudio.com/download) podras descargarlo.

Para nosotros, es una herramienta que nos permite escribir codigo en local y poder subirlo a GitHub. Para ello utilizamos otra herramienta llamada Git.

Git es otro software que vamos a utilizar para poder clonar repositorios desde GitHub a nuestro ordenador y poder trabajar en VSC de forma local. Se puede descargar mediante este [enlace](https://git-scm.com/downloads).

### Clonar repositorio de GitHub a VSC

Una vez instalado los 2 software, procedemos a clonar un repositorio:

Imagen4

Una vez cogida la url del repositorio entramos a VSC entraremos a su terminal (ctrl + ñ).

Escribiremos "git clone y la url del repositorio"

Imagen5

Imagen6

Si hemos realizado cambios en local y queremos subirlos a GitHub hay que utilizar esta linea de comandos:
- git add .
- git commit -m "texto que indica la ultima actualización"
- git push

### GitHub Pages
En el caso de que hayamos escrito codigo html entre otros y queremos que sea una pagina publica, utilizaremos esta función:

Dentro del repositorio, entramos en configuración y vamos al apartado "pages".

Dentro vamos al apartado "branch", veremos un cuadrado donde esta escrito "none", hay que cambiarlo por "main" y "save" para guardar los cambios.

Una vez hecho nos aparecera la url de la página.

Imagen7

Cuando tengamos la url, la copiamos (ctrl C + ctrl V) y tenemos que pegarla igual que en la imagen:

Imagen8

## HTML en Visual Studio Code

