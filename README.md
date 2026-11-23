Pregunta 1. ¿Qué representan los pesos?

Los pesos representan la importancia que tiene cada dato de entrada en la decisión del perceptrón. En este laboratorio, permiten determinar cuánto influyen los ingresos mensuales y el historial crediticio en la aprobación de un crédito.

Pregunta 2. ¿Qué función cumple el bias?

El bias o sesgo permite ajustar el resultado de la neurona artificial, modificando el límite de decisión para facilitar la clasificación entre créditos aprobados y rechazados.

Pregunta 3. ¿Cómo aprende el perceptrón?

El perceptrón aprende mediante un proceso de entrenamiento en el que compara sus predicciones con los resultados esperados. Cuando comete un error, ajusta sus pesos y el bias para mejorar sus próximas predicciones.

Pregunta 4. ¿Por qué el perceptrón no puede resolver XOR?

El perceptrón simple no puede resolver el problema XOR porque este requiere una separación no lineal entre los resultados. Una sola neurona solamente puede establecer una frontera de decisión lineal.

Pregunta 5. ¿Qué ventajas tiene un perceptrón multicapa?

El perceptrón multicapa puede resolver problemas más complejos porque utiliza varias capas de neuronas artificiales. Permite aprender relaciones no lineales, reconocer patrones más difíciles y resolver problemas como XOR.



RETO MIT: Problema XOR

¿Por qué un perceptrón simple no puede resolver el problema XOR?

El problema XOR consiste en obtener un resultado de 1 cuando las dos entradas son diferentes y 0 cuando son iguales. Un perceptrón simple no puede resolverlo porque solamente permite establecer una separación lineal entre los datos. En el caso de XOR, los resultados no pueden separarse correctamente mediante una sola línea recta.

¿Cómo podría resolverlo un perceptrón multicapa?

Un perceptrón multicapa puede resolver el problema XOR utilizando una capa de entrada, una capa oculta y una capa de salida. La capa oculta permite combinar las entradas mediante funciones de activación no lineales, logrando identificar patrones que un perceptrón simple no puede reconocer.

Conclusión:

El problema XOR demuestra las limitaciones del perceptrón simple frente a problemas no lineales. En cambio, el perceptrón multicapa puede resolverlos gracias a sus capas ocultas, que permiten aprender relaciones más complejas entre los datos.