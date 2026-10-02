# Sistema experto: perfil del inversionista

Proyecto académico de Sistemas Inteligentes que clasifica el perfil de un inversionista mediante un cuestionario de 14 preguntas y reglas definidas previamente.

## Objetivo

Representar criterios de evaluación financiera en un sistema experto capaz de obtener un perfil y explicar las reglas que llevaron a esa conclusión.

## Base de conocimientos

Reúne las preguntas, sus opciones de respuesta, los puntos asignados a cada opción y los perfiles posibles. El cuestionario considera la edad, el horizonte de inversión, la situación económica, la experiencia, la tolerancia a pérdidas y las necesidades de liquidez.

## Motor de inferencia

El sistema parte de las respuestas del usuario, revisa su validez y evalúa una regla prioritaria: si la pregunta 12 indica que el usuario se considera inversionista sofisticado, asigna ese perfil. En los demás casos, suma los puntos y compara el total con los rangos establecidos.

Cada evaluación incluye una traza de razonamiento que registra las reglas aplicadas y justifica el resultado.

## Interfaz de usuario

Un cuestionario interactivo permite registrar las respuestas y mostrar el perfil asignado, su descripción, el puntaje cuando corresponde y la explicación de la decisión.

## Perfiles de inversionista

- **Adverso al Riesgo:** prioriza preservar el capital y reducir la exposición al riesgo.
- **Moderado:** busca un equilibrio entre seguridad y rendimiento.
- **Propenso al Riesgo:** acepta mayor exposición al riesgo para buscar mayor rentabilidad.
- **Sofisticado:** se asigna mediante la regla especial de la pregunta 12.

## Alcance de la primera entrega

La entrega comprende la base de conocimientos, el motor de inferencia y la interfaz, acompañados de un marco teórico y un ejemplo de evaluación. El repositorio contiene el [cuaderno del proyecto](Primera_Entrega_Sistema_Experto.ipynb) y la [presentación para clase](index.html).

La implementación utiliza Python e ipywidgets. Las reglas se conservan del cuestionario original; el proyecto no comprueba documentación financiera ni recomienda productos de inversión.
