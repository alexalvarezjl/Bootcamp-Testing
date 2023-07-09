## Verificación estática

La verificación estática es una técnica de prueba que se realiza sin ejecutar el software. Se centra en examinar los artefactos y documentos relacionados con el desarrollo del software para identificar posibles problemas, errores o incumplimientos de estándares. El objetivo es mejorar la calidad y la precisión de estos documentos antes de avanzar en el proceso de desarrollo.

### Aplicación de la verificación estática

La verificación estática se puede aplicar a diferentes elementos del desarrollo de software:

1. Casos de negocio: Se verifica la coherencia y la viabilidad de los casos de negocio, asegurándose de que estén bien documentados y cubran los requerimientos del sistema.

2. Libros de requerimientos: Se realiza una verificación estática de los libros de requerimientos para identificar inconsistencias, ambigüedades o falta de información. Se asegura que todos los requerimientos estén correctamente especificados y sean comprensibles.

3. Diseño de sistema: Se aplican técnicas de verificación estática al diseño de sistema para revisar diagramas, modelos y especificaciones técnicas. Se busca identificar problemas de diseño, como falta de modularidad, acoplamiento excesivo o violaciones de buenas prácticas.

4. Código fuente: Se realiza verificación estática del código fuente para identificar posibles errores, problemas de estilo, vulnerabilidades de seguridad o malas prácticas de programación. Se utiliza herramientas automáticas o revisión manual para este propósito.

5. Manuales de usuario: Se revisan los manuales de usuario para asegurarse de que sean claros, precisos y completos. Se busca detectar posibles ambigüedades, falta de información o instrucciones confusas.

La verificación estática se basa en la revisión minuciosa y el análisis exhaustivo de los documentos y artefactos del desarrollo de software, lo que ayuda a identificar problemas antes de ejecutar las pruebas funcionales o implementar el software. Esto ayuda a reducir costos y mejorar la calidad del producto final.

Es importante tener en cuenta que la verificación estática es complementaria a las pruebas dinámicas y juntas contribuyen a garantizar un software de alta calidad.


### Caso de Negocio: Registro de Usuarios

- Descripción: El sistema permitirá a los usuarios registrarse en la plataforma para acceder a funcionalidades exclusivas.
- Objetivo: Capturar la información básica del usuario y almacenarla en la base de datos para su posterior uso.
- Actores: Usuario, Administrador del sistema.
- Flujo básico: 
  1. El usuario accede a la página de registro.
  2. El usuario ingresa su nombre, dirección de correo electrónico y contraseña.
  3. El sistema valida los datos ingresados.
  4. El sistema crea un registro de usuario y lo almacena en la base de datos.
  5. El sistema muestra un mensaje de confirmación de registro exitoso.

### Libro de Requerimientos del Sistema de Gestión de Ventas

| ID | Requerimiento | Descripción |
|----|---------------|-------------|
| RQ1 | Registro de Clientes | El sistema debe permitir el registro de clientes nuevos. Se deben capturar campos como nombre, dirección y número de teléfono. |
| RQ2 | Gestión de Inventario | El sistema debe llevar un registro actualizado del inventario de productos. Se deben registrar los datos como nombre del producto, cantidad disponible y precio unitario. |
| RQ3 | Generación de Informes | El sistema debe ser capaz de generar informes de ventas diarios, semanales y mensuales. Los informes deben incluir información como ventas totales, productos más vendidos y clientes frecuentes. |

### Diagrama de Clases del Sistema de Reservas de Hoteles

[Hotel]
- nombre: string
- dirección: string
- estrellas: int
- habitaciones: Habitación[]

[Miembro]
- nombre: string
- dirección: string
- correoElectrónico: string
- reservas: Reserva[]

[Reserva]
- miembro: Miembro
- habitación: Habitación
- fechaEntrada: Fecha
- fechaSalida: Fecha

[Habitación]
- número: int
- tipo: string
- capacidad: int
- precio: float

[Fecha]
- día: int
- mes: int
- año: int

### Ejemplo de Código Fuente en Java

```java
public class Calculator {
    public int add(int a, int b) {
        return a + b;
    }
  
    public int subtract(int a, int b) {
        return a - b;
    }
  
    public int multiply(int a, int b) {
        return a * b;
    }
  
    public int divide(int a, int b) {
        if (b == 0) {
            throw new ArithmeticException("Cannot divide by zero");
        }
        return a / b;
    }
} 
```

### Manual de Usuario: Aplicación de Notas

- Introducción: El manual de usuario proporciona instrucciones detalladas sobre cómo utilizar la aplicación de notas para gestionar y organizar tus notas de manera eficiente.
- Requisitos previos: Asegúrate de tener instalada la última versión de la aplicación en tu dispositivo móvil.
- Contenido:
  - Creación de una nueva nota: Haz clic en el botón "Nueva Nota" para crear una nota nueva. Ingresa el título y el contenido de la nota, luego guarda los cambios.
  - Edición de una nota existente: Selecciona la nota que deseas editar y haz clic en el botón "Editar". Realiza las modificaciones necesarias y guarda los cambios.
  - Eliminación de una nota: Para eliminar una nota, selecciona la nota y haz clic en el botón "Eliminar". Confirma la acción en el mensaje de confirmación.
  - Búsqueda de notas: Utiliza la barra de búsqueda para encontrar notas específicas. Ingresa palabras clave relacionadas con la nota que estás buscando y presiona Enter.
  - Cierre de sesión: Para cerrar sesión, ve al menú de opciones y selecciona la opción "Cerrar Sesión".


## Verificación Estática: Ventajas y Desventajas

### Ventajas:

- Defectos corregidos y detectados en etapas tempranas del desarrollo.
- Reducción de costos de testing.
- Mejora de la productividad en el desarrollo.
- Mejora de la comunicación del equipo.
- Reducción de riesgos de propagación de errores o fallas.
- Detección de defectos que rara vez son detectados por la verificación dinámica.

### Desventajas:

- Requiere una considerable inversión de tiempo.
- Pueden surgir situaciones de estrés en casos de confrontación directa con el autor.
- Los expertos involucrados en las revisiones deben adquirir conocimiento específico sobre el producto.
- Se necesita el soporte necesario por parte de los responsables de la gestión del proyecto.

## Verificación Estática: Tipos de Defectos Encontrados

- Derivación de estándares: Se detectan defectos relacionados con el incumplimiento de los estándares establecidos para el desarrollo de software.

- Defectos en los Requerimientos: Se identifican problemas o ambigüedades en los requerimientos del sistema.

- Defectos en el Diseño: Se encuentran errores o deficiencias en el diseño del sistema.

- Insuficiente capacidad de ser mantenido: Se detecta la falta de mantenibilidad en el diseño o código del software.

- Especificación de interfaces incorrecta: Se encuentran defectos en la especificación de interfaces entre componentes o módulos del sistema.

Estos tipos de defectos son detectados durante la verificación estática, lo que permite corregirlos antes de la ejecución del software y mejorar la calidad del producto.


## Verificación Estática: Revisión Informal

- Descripción: La revisión informal es un tipo de verificación estática que no sigue ningún proceso formal. También se conoce como revisión de pares o primera revisión.

- Características:
  - Líder técnico involucrado: En la revisión informal, el líder técnico o experto puede participar para revisar el código o el diseño del sistema.
  - Ausencia de documentación y medición de tiempos: Por lo general, no se documentan formalmente los hallazgos ni se mide el tiempo dedicado a la revisión.
  - Economía de recursos: La revisión informal es una forma económica de obtener beneficios al detectar defectos o mejoras en el sistema.

La revisión informal puede ser una estrategia efectiva para realizar una verificación rápida y obtener retroalimentación temprana sobre el código o el diseño del sistema. Sin embargo, es importante tener en cuenta que al ser informal, puede ser menos estructurada y menos rigurosa en comparación con otras técnicas de revisión estática más formales.


## Verificación Estática: Walkthrough

- Descripción: El walkthrough es una técnica de verificación estática en la cual una reunión es liderada por el autor del producto de software. El objetivo principal del walkthrough es evaluar el producto, entrenar a los participantes en relación al mismo y mejorar su calidad.

- Objetivos:
  - Evaluar el producto de software: Durante el walkthrough, se busca evaluar el producto en términos de funcionalidad, calidad y cumplimiento de los requisitos.
  - Entrenar a los participantes: Los participantes tienen la oportunidad de aprender más sobre el producto y familiarizarse con su funcionamiento.
  - Mejorar el producto: Se busca identificar y corregir defectos o áreas de mejora en el producto.
  - Considerar alternativas de implementación: Se pueden discutir diferentes enfoques o soluciones para abordar ciertos aspectos del producto.
  - Evaluar el cumplimiento de estándares y especificaciones: Se verifica si el producto cumple con los estándares y las especificaciones establecidas.
  - Intercambiar ideas o técnicas: Los participantes pueden compartir conocimientos, ideas y técnicas relacionadas con el producto.

- Método:
  - El autor del producto presenta el material a revisar y guía la reunión.
  - Se utilizan escenarios o casos reales para demostrar el funcionamiento del producto.
  - No hay límites de tiempo establecidos para el walkthrough.
  - Es una técnica semi formal, ya que sigue una estructura y proceso, pero no es tan rigurosa como otras técnicas de revisión estática.

El walkthrough proporciona una oportunidad para una revisión más detallada y una discusión interactiva del producto de software. Es una forma efectiva de involucrar a los participantes y obtener diferentes perspectivas sobre el producto. Sin embargo, es importante tener en cuenta que debido a su naturaleza menos formal, es posible que algunos defectos o problemas no sean identificados durante la sesión de walkthrough y se requiera de otras técnicas de verificación estática adicionales.


## Verificación Estática: Revisión Técnica

- Descripción: La revisión técnica es una técnica de verificación estática en la cual una reunión es liderada por un moderador entrenado, en lugar del autor del producto de software. Se basa en procesos documentados formalmente y tiene como objetivo principal encontrar defectos y mejorar la calidad del producto.

- Características:
  - Liderazgo del moderador: La reunión es liderada por un moderador entrenado, que facilita el proceso y guía la discusión.
  - Procesos documentados: La revisión técnica se basa en procesos y procedimientos documentados formalmente, lo que proporciona una estructura clara para llevar a cabo la revisión.
  - Participación de pares y expertos técnicos: Se involucran pares y expertos técnicos en la revisión, sin la participación de los jefes.
  - Etapas de la revisión: La revisión técnica consta de etapas que incluyen la pre-reunión, preparación, utilización de un checklist, generación de informe de la revisión, registro de los defectos encontrados y lista de participantes.
  
- Objetivos principales:
  - Discutir y tomar decisiones: Durante la revisión técnica, se lleva a cabo una discusión detallada del producto, lo que permite tomar decisiones informadas sobre posibles mejoras o cambios.
  - Encontrar defectos: Se busca identificar y documentar defectos o problemas en el producto, como errores de diseño, código incorrecto o incumplimiento de estándares.
  - Resolver asuntos técnicos: Se abordan asuntos técnicos relevantes relacionados con el producto y se buscan soluciones o alternativas adecuadas.
  - Validar la conformidad de las especificaciones y los estándares: Se verifica si el producto cumple con las especificaciones y los estándares establecidos.

La revisión técnica es una técnica formal de verificación estática que permite una revisión exhaustiva del producto de software. Al seguir un proceso documentado y contar con la participación de expertos técnicos, se logra encontrar y corregir defectos de manera más efectiva, lo que mejora la calidad del producto final.


## Verificación Estática: Inspecciones

- Descripción: Las inspecciones son una técnica de evaluación formal en la cual un grupo de personas examina en detalle los requerimientos de software, el diseño o el código con el objetivo de detectar defectos, desviaciones a los estándares de desarrollo y otros problemas.

- Características:
  - Evaluación detallada: Durante las inspecciones, se realiza un examen minucioso de los artefactos del software, como los requerimientos, el diseño o el código.
  - Grupo de personas: Se requiere la participación de un grupo de personas con diferentes roles y perspectivas, como desarrolladores, testers y expertos en la materia.
  - Detección de defectos y desviaciones: El objetivo principal de las inspecciones es identificar defectos, errores, incumplimientos de estándares o desviaciones en relación a las especificaciones.
  - Evaluación formal: Las inspecciones siguen un proceso formal, que incluye la planificación, la preparación, la realización de la reunión de inspección y el registro de los hallazgos.

Las inspecciones son una técnica poderosa para identificar y corregir problemas en el software en etapas tempranas del ciclo de vida del desarrollo. Al involucrar a un grupo de personas con diferentes perspectivas, se obtiene una revisión más exhaustiva y se pueden encontrar defectos que podrían haber pasado desapercibidos de otra manera. Las inspecciones ayudan a mejorar la calidad del software y a garantizar el cumplimiento de los estándares establecidos.


## Inspecciones: Terminología

- Defecto: Un defecto se refiere a un error o problema identificado en un producto de trabajo durante el proceso de inspección. Puede ser un error en el diseño, el código, la documentación u otros artefactos del software.

- Producto de trabajo: Un producto de trabajo se refiere a cualquier salida o resultado generado como parte de las actividades del ciclo de vida de desarrollo de software. Algunos ejemplos de productos de trabajo son:

  - Plan de proyecto: Un documento que describe los objetivos, el alcance, el cronograma y los recursos del proyecto.
  - Especificación de requerimientos: Un documento que define los requisitos funcionales y no funcionales del sistema.
  - Diseño de alto nivel: Una representación visual de la arquitectura y los componentes principales del sistema.
  - Diseño de bajo nivel: Una descripción detallada del diseño de los componentes individuales del sistema.
  - Código Fuente: El conjunto de instrucciones escritas en un lenguaje de programación que conforman el software.
  - Documentos de usuario: Los materiales de referencia y guías de uso para los usuarios del sistema.
  - Plan de prueba: Un documento que describe la estrategia y los enfoques para la ejecución de pruebas.
  - Casos de prueba: Escenarios específicos diseñados para verificar el comportamiento y la funcionalidad del sistema.
  - Reportes de pruebas: Los resultados y hallazgos obtenidos durante la ejecución de las pruebas.
  - Documento de proceso: Una descripción detallada de los procedimientos, estándares y pautas a seguir en el desarrollo del software.

Estos términos son comunes en el contexto de las inspecciones y ayudan a definir y comprender mejor los conceptos relacionados con la identificación y corrección de defectos en los productos de trabajo.


## Inspecciones: Objetivos

Las inspecciones tienen como objetivo principal asistir a las organizaciones en la producción de productos de alta calidad a través de la detección temprana de fallas en el ciclo de vida del desarrollo. Algunos de los objetivos específicos de las inspecciones son:

- Encontrar fallas tempranamente: Las inspecciones permiten identificar defectos y problemas en los productos de trabajo en etapas tempranas del desarrollo, lo que ayuda a evitar la propagación de errores y reduce el costo de su corrección.

- Acuerdo sobre el contenido del producto de trabajo: Las inspecciones involucran a los diferentes participantes en el proceso de desarrollo y fomentan la discusión y el consenso sobre el contenido y los requisitos del producto de trabajo. Esto asegura que todos estén alineados y que el producto cumpla con los criterios predefinidos.

- Formalización del cumplimiento de la tarea: Durante las inspecciones, se establecen criterios de salida claros y se documentan los hallazgos y decisiones. Esto ayuda a formalizar y validar el cumplimiento de las tareas y los estándares establecidos.

- Proveer datos para el control del proceso, proyecto y producto: Las inspecciones generan datos valiosos que pueden ser utilizados para el control y la mejora del proceso de desarrollo, el seguimiento del proyecto y la evaluación de la calidad del producto. Estos datos permiten tomar decisiones informadas y realizar ajustes en función de los resultados obtenidos.

En resumen, las inspecciones se centran en encontrar y corregir fallas en etapas tempranas del desarrollo, asegurar el acuerdo y cumplimiento de los requisitos, y proporcionar datos útiles para el control y la mejora de los procesos y productos de software.


## Las Inspecciones

Las inspecciones son una forma más económica y efectiva de encontrar fallas en el proceso de desarrollo de software. Al involucrar a un grupo de personas en la revisión detallada de los productos de trabajo, se pueden identificar y corregir problemas antes de que se propaguen a etapas posteriores del ciclo de vida del desarrollo. Esto ayuda a reducir los costos asociados con la corrección de defectos en etapas avanzadas del proceso.

Además de encontrar fallas, las inspecciones también brindan oportunidades para el conocimiento cruzado. Al reunir a personas con diferentes roles y perspectivas, se promueve el intercambio de ideas, técnicas y mejores prácticas. Esto contribuye a mejorar la comprensión colectiva del producto y del proceso de desarrollo, lo que a su vez puede conducir a la identificación de soluciones innovadoras y a la mejora de la calidad general.

Otro beneficio de las inspecciones es que proporcionan métricas al proyecto. Durante el proceso de revisión, se registran los hallazgos, se documentan los defectos encontrados y se generan informes que pueden ser utilizados para evaluar la calidad del producto, medir la eficacia del proceso y realizar ajustes o mejoras. Estas métricas brindan una base objetiva para la toma de decisiones informadas y el seguimiento del progreso del proyecto.

Las inspecciones también promueven el trabajo en grupo y la colaboración. Al llevar a cabo reuniones formales de revisión, se crea un ambiente propicio para la participación activa, la discusión constructiva y el intercambio de conocimientos. Esto fomenta el trabajo en equipo, la comunicación efectiva y el compromiso conjunto hacia la mejora continua.

En resumen, las inspecciones son un método probado para mejorar la calidad del producto de software. Son una forma económica y efectiva de encontrar fallas, promover el conocimiento cruzado, proporcionar métricas al proyecto, promover el trabajo en grupo y elevar la calidad del producto en general.


## Las Inspecciones NO son

Es importante tener en cuenta que las inspecciones no están diseñadas para encontrar soluciones a las fallas identificadas durante el proceso de revisión. Si bien es cierto que se detectan problemas y se documentan, la responsabilidad de corregir y resolver esos problemas recae en los encargados del desarrollo y no en el proceso de inspección en sí mismo. Las inspecciones brindan la oportunidad de identificar y documentar las fallas, pero la resolución y corrección de los problemas debe llevarse a cabo por separado.

Además, las inspecciones no se utilizan para obtener la aprobación final de un producto de trabajo. Aunque las inspecciones pueden ayudar a identificar fallas y asegurar la calidad del producto, no son un mecanismo formal de aprobación o validación. La responsabilidad de la aprobación final del producto recae en los responsables del proyecto o los interesados relevantes, y se basa en una evaluación más amplia y completa que va más allá del proceso de inspección.

Las inspecciones tampoco se utilizan para evaluar el desempeño individual de las personas involucradas en el proceso de desarrollo. Si bien las inspecciones implican la participación de un grupo de personas y fomentan la colaboración y el trabajo en equipo, no se deben utilizar como una herramienta para medir o juzgar el rendimiento individual. La finalidad de las inspecciones es mejorar la calidad del producto y el proceso de desarrollo en su conjunto, no para evaluar o calificar a las personas involucradas.

En resumen, las inspecciones no están diseñadas para encontrar soluciones a las fallas, obtener la aprobación final de un producto de trabajo o evaluar el desempeño individual. Su objetivo principal es identificar y documentar las fallas, mejorar la calidad del producto y optimizar el proceso de desarrollo mediante la participación activa y la colaboración del equipo.
