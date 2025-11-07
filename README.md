.# Ecohuerta - Lista Filtrable (React)

Este proyecto consiste en una aplicación sencilla realizada en React, donde se muestra una lista de plantas y el usuario puede filtrarlas según un criterio de búsqueda. El objetivo principal es comprender cómo funcionan los componentes, el uso del estado con useState y el flujo de datos dentro de una aplicación en React.

1 Flujo de datos unidireccional

En este proyecto, los datos se mueven desde el componente principal hacia los componentes secundarios. El componente principal contiene el estado y pasa la información a los demás componentes mediante propiedades. Los componentes secundarios no cambian los datos directamente, sino que solo los muestran o llaman funciones que el componente principal les proporciona. Esto permite mantener un control claro sobre la información y facilita la organización del código.

2 Uso del estado con useState

El estado se utiliza para almacenar información que puede cambiar mientras la aplicación está en uso, como el texto que el usuario escribe para buscar. Cuando el estado cambia, React actualiza automáticamente la interfaz, mostrando los resultados filtrados sin recargar la página. Esto hace que la interacción sea más fluida y directa.

3 Separación en componentes

Dividir la aplicación en componentes independientes ayuda a mantener el código más organizado y legible. Cada componente tiene una función específica y se puede volver a utilizar en otras partes de la aplicación si es necesario. Esta separación facilita el mantenimiento y la ampliación del proyecto en el futuro.

4 Uso de JSX

JSX permite escribir la estructura visual de la aplicación de una manera parecida a HTML, pero dentro de JavaScript. Esto hace que el código sea más comprensible y más fácil de relacionar con la interfaz final. Además, React se encarga de actualizar solo lo necesario en la pantalla, evitando trabajo manual sobre el DOM.

5 Mejoras añadidas al proyecto

Se incorporaron tres componentes adicionales que amplían la funcionalidad sin alterar la estructura principal:

1. Componente para mostrar información más detallada de una planta.
2. Componente con un formulario sencillo para agregar nuevas plantas a la lista.
3. Componente de pie de página para organizar la información final de la aplicación.

Estos componentes se añadieron de manera que mantienen la coherencia del diseño y no afectan la lógica principal del filtrado

## Autor

Proyecto realizado con fines de aprendizaje práctico en React.
