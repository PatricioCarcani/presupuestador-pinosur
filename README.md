<h3 align="center">Presupuestador Pinosur</h3>

## Descripción
Debido al exceso de formas de pago disponibles es una tarea tediosa solamente pasarle un precio a un cliente. Asi que para agilizar la tarea, esta webapp se encarga de recibir un valor y generar una tabla con los diferentes montos por medio de pago y cuotas.

## Stack utilizado
Al ser una webapp sencilla, aproveché para dejar de lado Bootstrap por Materialize, ya que necesitaba algo básico. Además, tiene la ventaja de ser el framework de Google, lo que lo hace más amigable para el usuario de Android (tengo en vista convertirla en app con Kotlin).
En cuanto a la lógica, quería usar Vanilla JS, pero luego de comenzar me di cuenta que, para simplificar la vista, necesitaba quitar el botón y que los valores se actualicen automáticamente. Es por esto que elegí VueJS y su two-way data binding. Tiene una curva de aprendizaje mucho menos pronunciada que Angular y ReactJS, que conozco, pero son más pesados.

- Materialize CSS
- VueJS
