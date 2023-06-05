# POO - Parcial No. 2

## Junto a su compañero de equipo, realice el análisis, diseño (incluya el diagrama de clases en este README) y construcción de una app, bajo el patrón MVC, para la siguiente situación:

Se requiere crear una aplicación en Java para gestionar una Libreta.  La libreta tiene un número total de hojas, un número determinado de hojas limpias y un número determinado de hojas utilizadas.  Cada hoja puede estar limpia, utilizada o arrancada. 

El funcionamiento de la libreta sería de la siguiente manera: 

- Al crear una libreta se indicará cuántas hojas iniciales contendrá.  El mínimo de hojas es 10 y el máximo es 150.  Si hay algún intento de crear una libreta con un número de hojas por fuera de los rangos mencionados la libreta ser creará con 50 hojas por default. 

- Usar un arreglo de caracteres, y tome cada una de sus celdas para considerar el estado de cada una de las hojas: ‘O’ es hoja limpia, ‘A’ es hoja arrancada y ‘X’ es hoja utilizada. 

- Es posible arrancar las hojas de la libreta, indicando el número de hojas que se requiere arrancar.  Pueden arrancarse hojas una a una de manera repetitiva, hasta indicar un número de hoja inexistente. 

- Es posible utilizar hojas de la libreta, indicando el número de hoja que se quiere utilizar.  Pueden utilizarse hojas una a una de manera repetitiva, hasta indicar un número de hoja inexistente. 

- Es posible agregar hojas a la libreta considerando que no debe rebasar el límite de 150 hojas. 

- Es posible ver las características actuales de la libreta, para lo cual debe imprimirse el número de hojas de la libreta, cuántas han sido arrancadas, cuántas están utilizadas y cuántas están limpias. 


Se requiere: 

- Diseñas las clases requeridas de acuerdo a las especificaciones anteriores. 

- Crear y gestionar una libreta de acuerdo a los requerimientos dados. 