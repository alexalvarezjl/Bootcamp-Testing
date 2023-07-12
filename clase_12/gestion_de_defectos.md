# Gestión de Defectos

## Bugs: Ciclo de Vida

El ciclo de vida de un bug o defecto en un proyecto de software se compone de diferentes etapas que abarcan desde su detección hasta su resolución. El seguimiento y gestión de estos bugs se realiza a través de una herramienta específica de seguimiento de bugs, la cual define los posibles estados y transiciones que puede experimentar un bug a lo largo del tiempo.

El ciclo de vida típico de un bug incluye los siguientes estados:

1. Nuevo: El bug ha sido reportado y aún no ha sido revisado o asignado a un responsable.

2. Asignado: El bug ha sido revisado y asignado a un desarrollador o equipo para su resolución.

3. En Progreso: El desarrollador o equipo está trabajando en la solución del bug.

4. En Revisión: El bug corregido está siendo revisado por un responsable de calidad para verificar que la solución sea correcta.

5. Resuelto: El bug ha sido corregido y se ha determinado que la solución es adecuada.

6. Cerrado: El bug ha sido verificado y se ha confirmado que está completamente resuelto.

Durante el ciclo de vida del bug, es posible que se realicen transiciones entre estos estados, dependiendo del progreso y la evolución de la resolución del bug. Esta información se registra y se gestiona a través de la herramienta de seguimiento de bugs, lo que permite un control efectivo de los bugs en el proyecto.

## Nuevo Requerimiento

Cuando el líder de desarrollo rechaza un defecto, muchas veces el motivo es que se trata de un *Nuevo Requerimiento*. Esto ocurre cuando el usuario, al interactuar con la aplicación y evaluar su funcionamiento, identifica la necesidad de agregarle más funcionalidades que no fueron acordadas al inicio del proyecto.

También puede suceder que el esfuerzo requerido para corregir un defecto sea tan alto que se considere más apropiado tratarlo como una nueva funcionalidad en lugar de una simple corrección.

Es importante reconocer estos casos durante la gestión de defectos, ya que permiten tomar decisiones adecuadas y satisfacer las necesidades del usuario de manera efectiva. Al identificar estos nuevos requerimientos, es posible analizar y priorizar su implementación en etapas posteriores del ciclo de vida del proyecto.

Este enfoque flexible y receptivo a los nuevos requerimientos permite adaptarse a las necesidades cambiantes del usuario y brindar un producto final más completo y ajustado a sus expectativas.

## Prueba de Confirmación o Re-Testing

Después de que un defecto ha sido detectado y solucionado, es necesario realizar una prueba de confirmación o re-testing. El objetivo de esta prueba es verificar que el defecto original ha sido corregido de manera adecuada.

La prueba de confirmación debe consistir en volver a ejecutar los pasos de reproducción reportados en el bug para confirmar si el defecto ha sido arreglado o no. Se deben seguir los mismos pasos y utilizar los mismos datos de entrada que se utilizaron para reproducir el defecto inicialmente.

Durante la prueba de confirmación, se debe verificar si el resultado actual coincide con el resultado esperado después de la corrección del defecto. Si el resultado actual coincide con el resultado esperado, se considera que el defecto ha sido corregido correctamente. En caso contrario, se debe informar nuevamente del defecto para su corrección.

Realizar una prueba de confirmación es una práctica importante en el proceso de desarrollo de software, ya que garantiza que los defectos reportados han sido solucionados de manera efectiva y que el software cumple con los requisitos establecidos.

