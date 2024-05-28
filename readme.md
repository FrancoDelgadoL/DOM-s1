# DOM

## getElement

- getElementById : Se usa cuando quiero usar un elemento mediante un ID, solo se puede de esa manera.

- getSelector: Tiene casi la misma funcion que el getElementById pero no necesito obligatoriamente un Id para poder usar algun elemento.

- getSelectorAll: La diferencia con el getSelector es que nos permite acceder a todos los elementos mientras que los dos anteriores solo a uno a la vez.

## Modificar 

- textContent: Nos permite añadir contenido a nuestro HTML pero solo texto.

- innerHTML: A diferencia de textContent, podemos usar etiquetas html para añadir contenido.

## propiedad style

- style: Nos permite añadir estilos de manera inline.

- classList.add: Nos permite añadir clases

- classList.remove: Nos permite borrar clases

- classList.toggle: Agrega clase si esta no existe de lo contrario la remueve.

## Dom Traversing

- parentElement: Nos permite navegar hacia el elemento padre de una etiqueta.

- children: Nos permite navegar hacia el elemento hijo de uan etiqueta.

## Create element

createElement consta de 4 partes:

- Crear el elemento

- Agregar el contenido 

- Agregar atributos pero este es de forma opcional

- Renderizar elemento