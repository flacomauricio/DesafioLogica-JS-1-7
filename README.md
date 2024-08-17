7 Days of Code: Día 1 - Comparación en JavaScript es parte del desafío #7DaysOfCode de Alura Latam. 
 Descripción
En el primer día del desafío, nos centraremos en uno de los aspectos más importantes y comunes de JavaScript: la comparación de valores y el manejo de tipos. En lenguajes compilados como Java o C#, los problemas con los tipos de variables se detectan en tiempo de compilación. Sin embargo, en JavaScript, estos errores solo se revelan en tiempo de ejecución debido a su naturaleza dinámica.

Hoy aprenderás sobre los problemas que pueden surgir al comparar valores de diferentes tipos y cómo resolverlos.

Problemas de Comparación en JavaScript

JavaScript realiza conversiones de tipo implícitas durante las comparaciones, lo que puede llevar a resultados inesperados. Por ejemplo:
console.log(false == '0');          // true
console.log(null == undefined);     // true
console.log(" \t\r\n" == 0);        // true
console.log(' ' == 0);              // true

(Puedes probar todo esto yendo a tu navegador, haciendo clic con el botón derecho, eligiendo la opción “Inspeccionar” y la pestaña “Consola”. En esa pestaña, basta con copiar y pegar cada una de las líneas anteriores para confirmar que todas realmente retornan true).


Tu Tarea
Por lo tanto, tu tarea de hoy es reescribir el código a continuación para que imprima la información de manera correcta, que tenga sentido y sin errores:

let numeroUn = 1;
let stringUn = '1';
let numeroTreinta = 30;
let stringTreinta = '30';
let numeroDiez = 10;
let stringDiez = '10';

if (COMPARAR numeroUn y stringUn) {
  console.log('Las variables numeroUn y stringUn tienen el mismo valor, pero tipos diferentes');
} else {
  console.log('Las variables numeroUn y stringUn no tienen el mismo valor');
}

if (COMPARAR numeroTreinta y stringTreinta) {
  console.log('Las variables numeroTreinta y stringTreinta tienen el mismo valor y el mismo tipo');
} else {
  console.log('Las variables numeroTreinta y stringTreinta no tienen el mismo tipo');
}

if (COMPARAR numeroDiez y stringDiez) {
  console.log('Las variables numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes');
} else {
  console.log('Las variables numeroDiez y stringDiez no tienen el mismo valor');
}


Consejo
Si no estás familiarizado con editores de código como Visual Studio Code, puedes usar la consola del navegador para ejecutar el código. Solo necesitas:

Hacer clic derecho en cualquier página web.
Seleccionar "Inspeccionar" y ir a la pestaña "Consola".
Escribir o pegar tu código ahí.
¡Muy fácil, verdad?

 Extra
Para profundizar más sobre operadores de comparación en JavaScript, te recomiendo leer este artículo en Alura.
