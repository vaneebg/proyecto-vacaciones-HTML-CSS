# PROYECTO VACACIONES HTML Y CSS

### Este mini proyecto trata sobre la consolidación de los conocimientos de HTML y CSS para trabajar conjuntamente con ellos. En este caso, el objetivo es replicar la página de login y de inicio de twitter o instagram.
---

## Descripción ##
### Ha consistido en realizar la réplica de una de las dos redes sociales. Primeramente la sección inicial que corresponde al login, y después al hacer click sobre inicio de sesión, nos llevará a una nueva página que sería una réplica de la web principal de estas redes sociales.
---

## Partes de las que consta el proyecto ##

Tendremos dos carpetas diferentes. Una para instagram y otra para twitter. Dentro de cada una encontramos el index.html que corresponde a la página del login con el css al que se enlaza. Además encontramos varias carpetas:
- *Assets* : Formada por todo el contenido multimedia.
- *Pages* : Dónde estará la página principal a la que accedemos al darle al botón Login/Inicia sesión.
- *Script*: Si hay js enlazado a estas páginas, se encontraría aquí.
- *Styles*: Aquí se encuentra el css que corresponde a la página principal.


En lo referente a las 2 páginas que tiene cada red social:
- **Index** : Página inicial de ambas redes. Consta a mano izquierda de algún tipo de maquetación estética y a mano derecha un mini formulario para iniciar sesión. 
    - **_IG_**: La parte izq consta de una animación cambiando opacidad y visibilidad de cada una de las 4 fotos. Con la finalidad de corregir el problema de que al finalizar la animación completa el móvil se quede en negro, se ha cambiado el estado final de la animación de la foto 1, haciendo que vuelva a su estado inicial (opacidad 1), y así se quede permanente. Modificando los tiempos de inicio del resto de fotos, se consigue que la img1 pase desapercibida hasta el final de la animación pese a que está visible.
- **Ig dentro/twitter dentro** : Formada por las publicaciones, varios botones para redigirir a las diferentes cuentas, opciones, etc.
    - **_IG_**: En **la barra superior** se encuentran tres enlaces, los de las esquinas deben redirigir a la app de fotos y de mensajes directos (no implementadas), mientras que el título de Instagram te dirige de nuevo a la página de index. 
    Después encontramos otra **barra con las stories**, que posee un scroll que no se muestra para que solamente con el desplazamiento táctil hacia la derecha vayas explorando. La segunda storie es un enlace de prueba que te llevaría al perfil de esa persona en concreto. El resto son imágenes sin funcionalidad.
    En lo referente al **contenido**, es un bloque formado por la foto y el nombre de la persona en cuestión (el nombre es un enlace que te llevaría a su perfil), y a la derecha un icono formado por 3 puntos que te dirigiría a las opciones.
    Abajo tendríamos el icono de comentario, me gusta y guardado. El único implementado con funcionalidad es el comentario, que nos dirige al textarea de abajo para escribir. Finalmente está el **botón de publicar** que se trata de un enlace que redirigiría a la web de nuevo con el comentario hecho.
    **La barra inferior** también sticky al igual que la superior, tiene las imágenes en forma de enlace. La única con funcionalidad es la imagen de Home, que nos llevaría a la parte superior de la página de nuevo.

---
## Herramientas usadas en el proyecto ####
_Este proyecto fue desarrollado con las siguientes tecnologias:_ 

* HTML
* CSS

---

## Instalacion y despliegue ####
Para desplegar este proyecto, lo primero que debes hacer es clonarte el repositorio que enlazo aquí:

```

```

### Una vez entres en el link, debes dirigirte al _botón de Code_. Ahí encontrarás varias opciones como descargar en formato zip o la posibilidad de clonarte el repositorio copiando el enlace y poniendo en la consola de git : _git clone titulorepo1_
---
## Vista Previa ##
* **INDEX IG:** 
![foto](/instagram/assets/igvistapreviaindex.png)
* **IG DENTRO:**
![foto](/instagram/assets/IGDENTROVISTAPREVIA.png)

---

## Aplicaciones posteriores ####
Adaptar el diseño responsive.
Añadir más funcionalidad con javascript.

## Autor ##
Este proyecto fue desarrollado por [Vanesa Beltrán Guillén](https://github.com/vaneebg)

