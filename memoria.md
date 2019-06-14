En esta practica final empece por implementar la plantilla basica de html es decir: 
1- definir tipo de documento (html)
2- usar la etiqueta "html" para contener las etiquetas "head" y "body"
3- En "head" contengo a la etiqueta "meta" y "title" 
    meta: me permite por medio del atributo charset utilizar un fortamo de transformacion que este caso fue el UTF-8 para tener acceso a todos los caracteres en español.
    title: me permite mostrar en la pestaña del navegador el nombre que quiera referente al contenido de la pagina en este caso decidi poner el nombre de la practica.
4 - En "body" contengo la etiqueta "h1" y cuatro secciones utilizando la etiqueta "section"
    h1: la utilizo para mostrar un titulo de bienvenida a mi pagina web de cuidado de mascotas.
    section:
        a. section: en esta seccion contengo la informacion de quienes somos haciendo uso de las etiquetas "h2" y "span"
                h2: para mostrar de manera remarcada y en mayos tamaño la pregunta de ¿Quienes somos?
                span: para dar una breve descripcion de quienes somos y lo que hacemos.

        b. section: en esta seccion contengo la informacion de los productos que se ofrecen utilizo una etiqueta "h3", "ul", "li", "p", "a",        "strong", "table", "tr", "th", "td"
                h3: para cumplir ciertas reglas de visualizacion descarto h1 y h2, utilizo h3 reiteradas veces
                ul: con esta etiqueta hago una lista sin ordenar para mencionar los distintos productos y servicios
                li: esta etiqueta contiene el text de cada producto y servicio
                p: utilizo esta etiqueta para mostrar un texto que por ser elemento de bloque viene con salto de linea por defecto de esta forma mejora la visualizacion.
                a: utilizo la etiqueta de anchor para redirigir directamente a la seccion de "Contactanos".
                strong: la utilizo para resaltar el enlace a "Contactanos".
                table: utilizo de esta etiqueta para mejor la accesibilidad, por la que agrego unos atibutos "cellspacing, cellpadding, border" para mejorar la visibilidad.
                tr: con esta etiqueta pinto toda las filas.
                th: con esta etiqueta pinto la cabecera de la tabla especificando los productos, precios, divisa.
                td: con esta etiqueta pinto todas las columnas alineadas con las cabecera para identificar la informacion que se muestra.

        c. section: esta seccion es dedidacada a una imagen, ya que la pagina web va de animales, pues puse una foto de un oso.

        d. section: esta ultima seccion contiene el formulario y la informacion para contactarnos por supuesto los datos expuestos son una invencion mia.  el numero es "petnannys". las etiqueta utilizadas son "h3", "a", "p", "strong", "span", "form", "label", "br", "input","select", "option", "button".
                h3: como comentaba anteriormente la utilice reiteradas veces para dar formato de subtitulo.
                a: en este caso utilice la etiqueta anchor con el atributo name para ser la referencia del anchor utilizado anteriormente en la segunda seccion (b).
                p: esta etiqueta la uso de nuevo por ser elemento de bloque asi aprovecho su espaciado por defecto.
                strong: resalto el email de contacto para mejorar la visualizacion y que el contraste de textos no sean tan grande.
                span: esta etiqueta la utilizo para mostrar un mensaje adicional sin tanto resaltado.
                form: en esta etiqueta contengo el formulario con todos sus input y opciones.
                label: esta etiqueta es para informar al usuario que tipo de dato tiene que introducir en el campo
                br: esta etiqueta la utilizo para dar espaciado al finalizar me parecio mas practico que meterlo dentro de un elemento de bloque y seguir aunmentando el anidado.
                input: en esta etiqueta recibo los datos. aprvechando el atributo type para recibir distintos tipos de datos como "text, number, email, date , button".
                select: con esta etiqueta contengo todas las opciones de mascotas que se ve como lista desplegable.
                option: en esta etiqueta guardo la informacion de la opciones de las mascotas.
                button: por ultimo esta etiqueta la utilizo porque no puede faltar un boton en un formulario, tambien para variar un poco entre tanto input, esta etiqueta usa un atributo onclick que llama a una funcion que no existe. solo por diversion
                


