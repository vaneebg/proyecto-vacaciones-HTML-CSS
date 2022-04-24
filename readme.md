# PROYECTO VACACIONES HTML Y CSS

### Este mini proyecto trata sobre la consolidación de los conocimientos de HTML y CSS para trabajar conjuntamente con ellos. En este caso, el objetivo es replicar la página de login y de inicio de twitter o instagram.
---

## Descripción ##
### Ha consistido en realizar la réplica de una de las dos redes sociales. En mi caso he optado por hacer ambas ya que cada una tenía sus retos diferentes. Ambas tienen su title y favicon referente. Primeramente, está la sección inicial que corresponde al login, y después al hacer click sobre inicio de sesión, nos llevará a una nueva página que sería una réplica de la web principal de estas redes sociales. Como el objetivo principal era la maquetación, la mayor parte de botones no tienen aún implementada funcionalidad. 
---

## Partes de las que consta el proyecto ##

Tendremos dos carpetas diferentes. Una para instagram y otra para twitter. Dentro de cada una encontramos el index.html que corresponde a la página del login con el css al que se enlaza. Además encontramos varias carpetas:
- *Assets* : Formada por todo el contenido multimedia.
- *Pages* : Dónde estará la página principal a la que accedemos al darle al botón Login/Inicia sesión.

- *Styles*: Aquí se encuentra el css que corresponde a la página principal.


En lo referente a las 2 páginas que tiene cada red social:
- **Index** : Página inicial de ambas redes. Consta a mano izquierda de algún tipo de maquetación estética y a mano derecha un mini formulario para iniciar sesión. 
    - **_IG_**: La parte izq consta de una animación cambiando opacidad y visibilidad de cada una de las 4 fotos. Con la finalidad de corregir el problema de que al finalizar la animación completa el móvil se quede en negro, se ha cambiado el estado final de la animación de la foto 1, haciendo que vuelva a su estado inicial (opacidad 1), y así se quede permanente. Modificando los tiempos de inicio del resto de fotos, se consigue que la img1 pase desapercibida hasta el final de la animación pese a que está visible. La parte derecha es un sencillo formulario con un input text y password. Debajo hay enlaces tanto para iniciar sesión con facebook como para descargar la app en Apple Google Play. El link que corresponder a Iniciar Sesión es el que nos lleva a la página principal en una nueva pestaña.
    En el footer encontramos enlaces de varias índoles y un datalist del lenguaje a elegir.
    - **_Twitter_**: dos partes: derecha formada por una imagen, izquierda formada por diferentes enlaces con forma de botón. Todos enlazarían a diferentes páginas pero el único con funcionalidad es "Iniciar sesión" que nos llevaría a la página principal de twitter en una nueva pestaña. Todos los botones tienen diferentes hover al igual que la página original de Twitter.
    
    ---

- **Ig/twitter dentro** : Formada por las publicaciones, varios botones para redigirir a las diferentes cuentas, opciones, etc.

    - **_IG_**: En **la barra superior** se encuentran tres enlaces, los de las esquinas deben redirigir a la app de fotos y de mensajes directos (no implementadas), mientras que el título de Instagram te dirige de nuevo a la página de index. 
    Después encontramos otra **barra con las stories**, que posee un scroll oculto para que solamente con el desplazamiento táctil hacia la derecha vayas explorando. La segunda storie es un enlace de prueba que te llevaría al perfil de esa persona en concreto. El resto son imágenes sin funcionalidad para rellenar la maquetación.
    En lo referente al **contenido**, es un bloque formado por la foto y el nombre de la persona en cuestión (el nombre es un enlace que te llevaría a su perfil), y a la derecha un icono formado por 3 puntos que te dirigiría a las opciones (no funcional).
    Abajo tendríamos el icono de comentario, me gusta y guardado. El único implementado con funcionalidad es el comentario, que nos dirige directamente al textarea de abajo para escribir. Finalmente está el **botón de publicar** que se trata de un enlace que redirigiría a la web de nuevo con el comentario hecho.
    **La barra inferior** también sticky al igual que la superior, tiene las imágenes en forma de enlace. La única con funcionalidad es la imagen de Home, que nos llevaría a la parte superior de la página de nuevo.
    - **_Twitter_**: 2 filas y 3 columnas. La **primera fila** es un sticky con efecto blur para que conforme vayas bajando por la web, todo lo que entre en la barra se vea difuminado. Consta del título Inicio y una barra de búsqueda a mano derecha (sin funcionalidad)
    La **segunda** es en sí todo el contenido, entendiendo tanto la barra izq sticky como las publicaciones principales y el lateral izq de noticias y seguimiento.
    Dentro de ésta, **primera columna** se trata de la barra sticky que tendremos disponible siempre independientemente de cuánto bajemos la página. Consta de varios enlaces, entre ellos el icono de Twitter te volvería a llevar al index del mismo, además de Home, Explorar, Notificaciones, Mensajes,etc., todos con su hover correspondiente (no tienen funcionalidad).
    La **segunda** son, por un lado, un textarea junto a tu perfil para que publiques un comentario, y abajo, las publicaciones como tal.
    Todos los iconos tanto de tu propia publicación como de las otras, (me gusta, retwittear,etc), son links (sin funcionalidad) y tienen su hover.
    Por último, la **tercera columna** es un apartado de noticias, cada una rellenada con algo de texto y una imagen con varios hover cuando pasemos el cursor por cada una de ellas, al igual que los seguimientos.
    Abajo hay un ejemplo de "A quién seguir", con su correspondiente icono, el nombre y un botón de seguir a lado derecha(sin funcionalidad)
    Más abajo se encuentran los link correspondientes al footer.
    
    

---
## Herramientas usadas en el proyecto ####
_Este proyecto fue desarrollado con las siguientes tecnologias:_ 

* HTML
* CSS

---

## Instalacion y despliegue ####
Para desplegar este proyecto, lo primero que debes hacer es clonarte el repositorio que enlazo aquí:

```
[GitHub](https://github.com/vaneebg/vacaciones-HTML-CSS)

```

### Una vez entres en el link, debes dirigirte al _botón de Code_. Ahí encontrarás varias opciones como descargar en formato zip o la posibilidad de clonarte el repositorio copiando el enlace y poniendo en la consola de git : _git clone titulorepo1_
---
## Vista Previa ##
* **INDEX IG:** 
![foto](/instagram/assets/igvistapreviaindex.png)
* **IG DENTRO:**
![foto](/instagram/assets/IGDENTROVISTAPREVIA.png)


* **INDEX TWITTER:**
![foto](/twitter/VISTAPREVIA%20INICIO%20TWITTER.png)
* **TWITTER DENTRO:**
![foto](/twitter/VISTAPREVIADENTRO.png)

---

## Aplicaciones posteriores ####
Adaptar el diseño responsive.
Añadir más funcionalidad con javascript, por ejemplo el carrusel de imágenes del index IG.
Añadir funcionalidad a cada uno de los link.

## Autor ##
Este proyecto fue desarrollado por [Vanesa Beltrán Guillén](https://github.com/vaneebg)

