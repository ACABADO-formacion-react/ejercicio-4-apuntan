# Ejercicio - Señores que te apuntan con el dedo

## Enunciado

A partir de esta maqueta HTML+CSS, tendrás que programar una aplicación con React.

1. Crea una nueva aplicación React y eliminar los archivos innecesarios.
2. Copia el favicon y la carpeta `img` de la maqueta al directorio correspondiente de tu aplicación React.
3. Traslada el HTML y el CSS de la maqueta a la aplicación React. Recuerda adaptar el HTML a la sintaxis JSX.
4. La maqueta tiene tres dependencias de terceros: la tipografía Open Sans, la tipografía Font Awesome y el framework Bootstrap (sólo la parte CSS). Trasládalas a tu aplicación React, cargándolas en el `<head>` igual que en la maqueta.
5. Cuando compruebes que todo está bien, quita la carga de bootstrap del `<head>` e instálalo por medio de `npm`.
6. Importa el CSS de bootstrap en el archivo `index.js` de tu aplicación, antes de importar los estilos generales. Comprueba que todo se sigue viendo igual.
7. Quita la carga de la tipografía Open Sans del `<head>` e instálala por medio de `npm`.
8. Importa el CSS de la Open Sans en el archivo `index.js` de tu aplicación, antes de importar los estilos generales. Comprueba que todo se sigue viendo igual.
9. Quita la carga de la tipografía Font Awesome del `<head>` e instala mediante `npm` el paquete de iconos `react-icons`.
10. En el componente App, importa el icono `FaCheck` del paquete `react-icons`. Busca las etiquetas `<i>` con clases `"fas fa-check"` y sustitúyelas por el componente `FaCheck`, con clase `"icono"`.
11. En el CSS, busca el selector `i.fas` y sustitúyelo por `svg.icono`. Añádele un padding de 4px. Comprueba que tu aplicación se ve igual que la maqueta.
12. En esta maqueta tienes un archivo `senyores.js` con un array de datos. Cópialo y pégalo en tu componente App, pero fuera de la función que crea el componente. Renombra el array a `senyoresAPI`.
13. Crea una variable de estado llamada `senyores`, e inicialízala con el array de señores, pero añadiéndole a cada uno una nueva propiedad llamada `marcado`, con valor `false`. Inspecciona el estado del componente con React Developer Tools para comprobar que tiene la información que quieres.
14. Crea dos variables, una que almacene un array de señores marcados y otra que almacene el número total de éstos. Estas variables no tienen que pertenecer al estado, son variables normales.
15. Vincula el texto que muestra el total de señores marcados con la variable correspondiente. Utiliza las Dev Tools para modificar la propiedad `marcado` y comprobar si el texto se actualiza correctamente.
16. Elimina la segunda y tercera etiqueta `<article>` y sus contenidos, de manera que quede una sola ficha de señor. Haz que se rendericen tantos elementos `<article>` como señores haya en el array. Si te da un warning referente a la propiedad "key", soluciónalo.
17. Vincula los textos de nombre, profesión, estado y twitter a los datos correspondientes. Comprueba que aparecen todos los datos en la vista. Modifica algunos datos en las Dev Tools para comprobar que la vista se actualiza.
18. Crea una función dentro del componente, que reciba un nombre y devuelva su inicial en mayúsculas. Si el nombre tiene varias palabras y la primera tiene menos de tres letras, debe devolver la inicial de la segunda palabra (Julio Iglesias = J, El Fary = F);
19. Vincula la inicial de la vista con la función anterior.
20. Vincula la imagen de cada señor con el dato correspondiente.
21. Haz que el icono de check sólo aparezca si el señor está marcado.
22. Haz que cuando se haga clic en la ficha de un señor (elemento `<article>`) se marque o desmarque. Recuerda que debes modificar la propiedad `marcado` del lugar que corresponda en el array de señores.
23. Haz que el elemento con clase `avatar` tenga o no la clase `marcado` dependiendo de si el señor está marcado o no.
24. Crea una variable (no tiene que ser de estado) que contenga el texto "Marcar" o "Desmarcar" dependiendo de si todos los señores están marcados o no. Si están todos marcados, el texto será "Desmarcar", en caso contrario será "Marcar".
25. Vincula el texto del botón a la variable anterior, de manera que contenga "Marcar todos" o "Desmarcar todos" según el caso.
26. Crea una función dentro del componente que se encargue de marcar o desmarcar todos los señores. Dependiendo de si todos están marcados o no, hará una cosa u otra. Vincula el clic sobre el botón anterior para que llame a esta función.

