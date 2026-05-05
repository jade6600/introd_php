# Exposicion 1


## Comentarios, variables, constantes
### Comentarios

Son notas dentro del código que el servidor ignora por completo; sirven para explicar, documentar o aclarar qué hace el programa.

Una sola línea: Se usan dos barras // o una almohadilla #.

Varias líneas: Se encierran entre /* y */.


## Variables y Constantes

Ambas sirven para guardar informacion, pero funcionan de forma distinta:

Variables: Son "Contenedores" para datos que puedan cambiar durante la ejecucion.

Siempre empiezan con el signo peso ($) seguido del nombre de la variable. (ejemplo: $edad = 25; )

## Constantes

Son valores fijos que NO pueden modificarse ni eliminarse una vez definidos. 
Se crean usando la función define() o la palabra clave const, y a diferencia de las variables, no llevan el signo $ antes de su nombre.

## Arrays y Arrays Asociativos
Un array permite almacenar múltiples valores en una sola variable, funcionando como una lista potente.

Arrays (Indexados): Los datos se organizan por posiciones numéricas (índices), que automáticamente empiezan desde el 0.
Por ejemplo, en una lista de frutas, la primera sería la posición 0, la segunda la 1, y así sucesivamente.

Arrays Asociativos: En lugar de usar números, utilizas nombres o "claves" personalizadas para guardar y encontrar los datos.

Se escriben en formato clave → valor (ejemplo: "nombre" => "Ana"). 

Son ideales cuando quieres asociar etiquetas con significado a los valores, como los detalles de un usuario.


# Operadores 


- Aritmeticos
- Asignacion
- Comparacion
- logicos
- incremento/decremento

- Aritméticos: Se usan para cálculos matemáticos comunes.+ (Suma), - (Resta), * (Multiplicación), / (División), % (Módulo/Resto) y ** (Exponenciación).

- De Asignación: Permiten escribir valores en variables.= (Asignación básica), += (Suma y asigna), -= (Resta y asigna).

- De Comparación: Comparan dos valores y devuelven un booleano (true o false).== (Igualdad), === (Idéntico: igual valor y tipo), != (No igual), <> (No igual), < (Menor que), > (Mayor que).

- Lógicos: Utilizados para combinar sentencias condicionales.&& o and (Y lógico), || o or (O lógico), ! (Negación), xor (O exclusivo).

- De Incremento/Decremento: Aumentan o disminuyen el valor de una variable en uno.++$x (Pre-incremento), $x++ (Post-incremento), --$x (Pre-decremento), $x-- (Post-decremento).

