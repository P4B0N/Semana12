Codo A Codo 4.0
# Semana12 
Sobre la realizacion del TP
***************************

Realizamos un sitio web con 4 páginas activas, evaluables.
    Además preparamos un esbozo de frontend de una aplicación web
    que seguiremos desarrollando con el curso de backend.
    La cual es posible de acceder desde un link en el último slide del
    carrusel de la página principal (Inicio), mediante un botón que dice
    "Prueba Gratuita", a partir de ahí es solo a modo de prueba.
    No es parte evaluable del TP, pero si lo quiere ver seria genial,
    tenga en cuenta que está en fase de desarrollo.

El repositorio esta subido a GitHub y publicado el sitio en GitHub Pages,
    trabajamos en pareja a través del repositorio, colaborando desde el propio 
    usuario cada uno a través de Git. *FUE UNA GRAN EXPERIENCIA Y TODO UN DESAFÍO*

El sitio está totalmente maquetado con flexbox, se le puso a propósito
    un color llamativo a los aside para poder ver su comportamiento, sería
    mejor quizá usar un color uniforme para disimular su movimiento pero en
    este caso se buscó mostrarlo. Solo en la última página (CVs) se le puso una
    letra como contenido para que no desaparezcan y se aprecie el lugar
    que van ocupando a medida que cambia el tamaño de la pantalla.

En la segunda página (Nosotros) se aprovechó para colocar la pseudo ubicación
    de nuestra empresa mediante un iframe que lleva a Atos (oficinas de empresas IT).

El carrusel está compuesto por 3 slides que tienen una transición de 1/2 segundo
    en su opacidad al ser seleccionados desde el menú que está debajo tres círculos 
    linkeados a cada slide que hacen que se vean aumentando su opacidad.

Pusimos 3 puntos de corte: hasta 700px, hasta 960px y más de 960px, la navbar en
    la medida más pequeña (celulares) se transforma en un menú hamburguesa que aparece
    de derecha a izquierda con los links ordenados verticalmente, luego en la
    siguiente medida (tablet) se muestra la navbar tal cual y a partir de esa medida 
    se mantiene en el centro para que en tamaños muy grandes de pantalla no se pierdan
    los links en tan larga barra.

El formulario es completamente responsive, en el mismo se buscó mostrar una 
    amplia gama de tipos de dato para poder hacer una buena variedad de validaciones,
    se utiliza el método post ya es más seguro ya que no muestra el contenido de lo 
    que se envía a través del mismo en la URL. Se usaron campos de tipo text para
    poder hacer las validaciones y e.preventDefault() para que no se cierre el 
    formulario y se envíen los datos al cerrar el alert, para así poder seguir 
    completando el formulario desde donde se cometió el error.

Se usaron etiquetas semánticas, iconos, fuentes y colores de fuentes.
