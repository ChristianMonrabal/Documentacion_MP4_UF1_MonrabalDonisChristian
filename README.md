
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

Git es otro software que vamos a utilizar para poder clonar repositorios desde GitHub a nuestro ordenador y poder trabajar en VSC de forma local. También se utiliza para exportar de VSC a GitHub Se puede descargar mediante este [enlace](https://git-scm.com/downloads).

### Clonar repositorio de GitHub a VSC

Una vez instalado los 2 software, procedemos a clonar un repositorio:

![Imagen4](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/4.png?raw=true)

Una vez cogida la url del repositorio entramos a VSC entraremos a su terminal (ctrl + ñ).

Escribiremos "git clone y la url del repositorio"

![Imagen5](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/5.png?raw=true)

![Imagen6](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/6.png?raw=true)

Si hemos realizado cambios en local y queremos subirlos a GitHub hay que utilizar esta linea de comandos:
- git add .
- git commit -m "texto que indica la ultima actualización"
- git push

### GitHub Pages
En el caso de que hayamos escrito codigo html entre otros y queremos que sea una pagina publica, utilizaremos esta función:

Dentro del repositorio, entramos en configuración y vamos al apartado "pages".

Dentro vamos al apartado "branch", veremos un cuadrado donde esta escrito "none", hay que cambiarlo por "main" y "save" para guardar los cambios.

Una vez hecho nos aparecera la url de la página.

![Imagen7](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/7.png?raw=true)

Cuando tengamos la url, la copiamos (ctrl C + ctrl V) y tenemos que pegarla igual que en la imagen:

![Imagen8](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/8.png?raw=true)

![Imagen9](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/9.png?raw=true)

## HTML en Visual Studio Code

Las paginas web tienen como mínimo una página creada con HTML, la primera página html tiene que tener el nombre de "index.html" ya que el navegador entenderia que esa es la página principal y es la primera que va amostrar.

Para crear una página HTML hay que seguir estos pasos:

![imagen10](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/10.png?raw=true)

Para empezar a escribir html haremos esto:

Escribiremos "html" en nuestra página "index.html" y seleccionaremos la opción "html:5"

![Imagen11](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/11.png?raw=true)

Una vez hecho "index.html" tendria que tener esta estructura:

![Imagen12](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/12.png?raw=true)

Para poder visualizar nuestra página en nuestro navegador haremos (Shfit + alt + r) y se abrira la carpeta donde esta almacenada todo el proyecto de VSC, una vez dentro clicaremos en "index.html" y la podremos visualizar

![Imagen13](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/13.png?raw=true)

### Etiquetas HTML (head)
Lo primero que debemos saber es que la mayoria de etiquetas se tienen que abrir y cerrar. Para crear una etiqueta debemos escribir <etiqueta> y para cerrar </etiqueta>.

La primera etiqueta que debemos conocer es "<title>", se utiliza para el titulo de cada página en el navegador:

![Imagen14](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/14.png?raw=true)
  
![Imagen15](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/15.png?raw=true)
  
La siguiente es <link:favicon>, se utiliza para poner un icono en la página, para ello crearemos una carpeta llamada "img", donde guardaremos todas las iamgenes que queramos guardar:
  
![Imagen16](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/16.png?raw=true)
  
Una vez hecho, descargaremos una imagen (cualquiera) y la meteremos en la carpeta "img" desde el explorador de archivos:

![Imagen17](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/17.png?raw=true)
  
Utilizaremos la etiqueta "<link:favicon>" justo debajo de "<title>", esta es la estructura:
  
![Imagen18](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/18.png?raw=true)

Este es el resultado:

![Imagen19](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/19.png?raw=true)

## Etiquetas HTML (body)

![Imagen20](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/20.png?raw=true)
  
## Estilos CSS
  
El CSS es el lenguaje para modificar el diseño al html.
  
Para vincular la hoja de estilos CSS al html, debemos crear un link en el head del html:
  
![Imagen21](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/21.png)
  
## Tipos de selectores CSS
  
### Selector Tipo:
  
Se utiliza para todas las mismas etiquetas de la pagina html
  
En el caso de la siguiente imagen, tenemos un h6, este selector modificara de tal forma que __TODOS__ los h6 sean de color "aqua"

![Imagen22](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/22.png)
  
### Selector de clase
  
El selector de clase selecciona todos los elementos con una determinada clase. Se representa con el símbolo . seguido del nombre de la clase
  
En la pagina html, tenemos que expresar mediante el atributo "class", el nombre de la clase
  
![Imagen23](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/23.png)

![Imagen24](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/24.png)
  
### Selector ID:
  
Selecciona un elemento basándose en el valor de su atributo id.
  
Se expresa mediante un #
  
Este selector es como el DNI de las personas, solo puede haber 1 igual, no se puede repetir, en este caso el mismo id.

![Imagen25](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/25.png)
  
![Imagen26](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/26.png)
  
### Selector Universal:

Selecciona todos los elementos.

Se expresa mediante *

![Imagen27](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/27.png)
  
## Atributos CSS

![Imagen28](https://github.com/ChristianMonrabal/Documentacion_MP4_UF1_MonrabalDonisChristian/blob/main/28.png)

  
