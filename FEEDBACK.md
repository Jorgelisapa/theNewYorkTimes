
# Revisión de Proyecto 

Antes que nada, quiero felicitarte por la actitud que has tenido para con el programa y tu dedicaci[on.

> Es más facil escribir código que leerlo.
> -Joel Spolsky (Fundador de Stack Overflow)

Los puntos que voy a tocar aquí son sobre todo para mejorar y reforzar huecos que tenemos en algunas areas.

# HTML

Para la parte de HTML los puntos que hay que recalcar son sobre todo las buenas practicas.

###  Bueno

- Uso de etiquetas de texto en el texto 

### Malo

- Utilizamos puros divs, hay más etiquetas para hacer divisiones, debemos tener una mejor estructura semántica
- Hay elementos que se podian identar mejor y no se hizo, hay espacios donde no deberian haber espacios, no tiene una lógica
- Ningún elemento tiene `id` como esperas identificarlos para futuras implementaciones
- No esta adecuado para ser escalable

Nos hace falta reforzar bastante las etiquetas de HTML y las buenas prácticas.
Te recomiendo checar este repo y esta pagina para las etiquetas:
[https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references](https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references)

[https://www.w3schools.com/TAGS/default.ASP](https://www.w3schools.com/TAGS/default.ASP)

# CSS

Para esta parte lo que hay que tener en cuenta es el escalamiento de un proyecto, la redacción y el uso de las propiedades correctas

### Bueno

- Tenemos una baja especificidad en las reglas
- Tenemos buen nombre de clases

### Malo

- No tenemos ningún sistema de diseño
- **Utilizamos solamente `px`, eso es muy muy MALO**. Para tamaño de letra se utiliza una diferente medida (em o rem), para tamaño de cosas que tengan que ver con sus padres hay más opciones y para las que tengan que ver con el tamaño de la página hay aún más, hay que ponernos a estudiar eso!
- No hay lógica en las desiciones para usar diferentes tamaños, unidades de tamaño
- No es escalable
- Para **los colores se deben de poner en hexadecimal** y en minúsculas
- Todo esta en un solo archivo, debemos de poder pensar en como se puede modularizar todo.
- Tienes muy pocas cosas documentadas, solo 2 comentarios

Hay que practicar muchísimo, te dejo links donde puedes encontrar lo que te puse:
[https://www.w3schools.com/cssref/css_units.asp](https://www.w3schools.com/cssref/css_units.asp)
[https://css-tricks.com/guides/](https://css-tricks.com/guides/)

# CONCLUSIÓN

Se trato de hacer algo que solamente funcionara y no fue suficiente con eso. Debemos intentarlo más, tienes buena organización de tus carpetas, pero **me dejaste un README vacio** recuerda que me estas hablando con tu código, y necesitas documentarlo todo
**Debemos de seguir practicando.**
