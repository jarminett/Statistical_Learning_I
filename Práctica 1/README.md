# Statistical_Learning_I
### Práctica I
La tarea práctica consiste en usar el mismo dataset del proyecto del curso pasado y e implementar gradient descent aplicado a regresión con este(usando la variable con mayor correlación elegida en el proyecto en anterior(solo una de las 2 del proyecto)),si no terminaron el proyecto anterior no se preocupen, no hay que hacer todo el proyecto, solo el entrenamiento con gradient descent pero usando tensorflow y usar tensorboard para monitorear que el error disminuya conforme avanzan las iteraciones "en vivo"(en lugar de hacerlo con matplotlib hasta el final como lo hicimos antes).
Pueden usar el siguiente ejemplo de regresión con tensorflow: https://www.geeksforgeeks.org/linear-regression-using-tensorflow/ o el notebook usado en clase.

Para la parte de Tensorboard, este nos permite visualizar mucha información relevante, pero nos centraremos en 2 cosas :

La curva de aprendizaje(disminución de error MSE en el tiempo)(en la la pestaña "scalars")
El grafo que representa a nuestro modelo (en la pestaña "graphs")

Requisitos:

- Utilizar solo operaciones vectorizadas.
- Usar mini-batch gradient descent (tamaño de mini-batch debe ser un hyper-parametro con el cual se debe experimentar.)
