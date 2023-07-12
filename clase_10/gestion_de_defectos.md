# Gestión de defectos.

## Testing Bueno vs. Testing Exitoso

**Testing Bueno:**
El testing bueno se refiere a un enfoque de prueba que tiene una alta probabilidad de detectar defectos que aún no han sido descubiertos en el software. Se centra en la búsqueda activa de fallas y en la implementación de técnicas y estrategias efectivas para encontrar posibles problemas en el sistema. El objetivo del testing bueno es maximizar la capacidad de detección de defectos y garantizar la calidad del software.

**Testing Exitoso:**
El testing exitoso se refiere a una prueba que ha logrado encontrar una cantidad significativa de defectos en el software. Cuando el testing es exitoso, se descubren y reportan numerosos errores y problemas en el sistema, lo que proporciona información valiosa para su corrección y mejora. Un testing exitoso demuestra la eficacia del proceso de prueba y la capacidad del equipo de identificar y documentar los defectos encontrados.

Es importante destacar que el desarrollo exitoso de un software puede llevar a un testing no exitoso, es decir, un testing que no encuentra defectos. Esto no significa necesariamente que el software esté libre de fallas, sino que el enfoque de prueba utilizado no ha logrado identificarlas. En este caso, es necesario revisar y mejorar las estrategias de prueba para asegurar una cobertura más exhaustiva y una detección efectiva de los defectos presentes en el sistema.

## Buen Testing

El buen testing se refiere a un enfoque de prueba de software en el cual cada actividad del desarrollo de software tiene una correspondiente actividad de testing asociada. Esto implica que el proceso de prueba está alineado y sincronizado con el proceso de desarrollo, asegurando que cada etapa del desarrollo sea validada y verificada adecuadamente.

En el buen testing, se reconoce la importancia de tener un enfoque estructurado y planificado para las actividades de prueba en cada nivel del desarrollo de software. Cada nivel de testing, como el unitario, de integración, de sistema y de aceptación, tiene objetivos específicos que se centran en probar y validar aspectos particulares del software.

Algunos ejemplos de los objetivos específicos de cada nivel de testing son:

- Testing unitario: Verificar la funcionalidad y el comportamiento correcto de los componentes individuales del software.
- Testing de integración: Probar la interacción y la integración correcta entre los diferentes componentes del software.
- Testing de sistema: Evaluar el cumplimiento de los requisitos del sistema y verificar su funcionamiento adecuado en un entorno completo.
- Testing de aceptación: Validar que el software cumple con los requisitos del cliente y se ajusta a sus necesidades y expectativas.

El buen testing implica un enfoque holístico y completo, abordando todas las etapas del desarrollo y aplicando técnicas y metodologías adecuadas para cada nivel de testing. Además, implica la planificación adecuada, la identificación y documentación de casos de prueba efectivos, la ejecución rigurosa de las pruebas y la evaluación exhaustiva de los resultados.

## Testing Exitoso

El testing exitoso se refiere a un proceso de prueba de software que logra alcanzar sus objetivos y produce resultados satisfactorios. En otras palabras, implica realizar pruebas efectivas que encuentren una cantidad significativa de defectos y ayuden a mejorar la calidad del software.

Un testing exitoso se caracteriza por los siguientes aspectos:

- **Detección de defectos:** Durante el proceso de prueba, se identifican y reportan un número considerable de defectos en el software. Estos defectos pueden ser errores de funcionamiento, comportamientos inesperados, problemas de rendimiento, entre otros. La detección de estos defectos proporciona información valiosa para corregirlos y mejorar el software.

- **Cumplimiento de objetivos:** El testing exitoso cumple con los objetivos establecidos previamente. Estos objetivos pueden incluir la cobertura de determinadas funcionalidades, la validación de requisitos específicos o la evaluación del rendimiento del sistema. Al lograr cumplir con estos objetivos, se demuestra la efectividad del proceso de prueba.

- **Mejora de la calidad:** El testing exitoso contribuye a la mejora de la calidad del software. Al encontrar y corregir defectos, se reducen los errores en el producto final, lo que a su vez mejora la experiencia del usuario y la confiabilidad del software. Además, el testing exitoso permite identificar áreas de mejora en el proceso de desarrollo y establecer medidas correctivas para evitar futuros problemas.

Es importante destacar que el éxito del testing no se limita únicamente a encontrar defectos, sino también a cumplir con los criterios de calidad establecidos, asegurar el correcto funcionamiento del software y satisfacer las necesidades y expectativas de los usuarios.

## Defecto, Error y Falla

- **Error:** Se refiere a una acción humana que produce un resultado incorrecto o inesperado en el software. Puede ser causado por un malentendido de los requisitos, una implementación incorrecta, un error de cálculo, entre otros factores. Un error es considerado como una acción incorrecta por parte de las personas involucradas en el desarrollo o uso del software.

- **Defecto:** Un defecto se produce cuando hay un paso, proceso o definición de datos incorrectos en el software. Es una desviación del comportamiento esperado o una falta de cierta característica que debería estar presente. Los defectos son problemas inherentes al software y pueden ser el resultado de errores humanos, malas interpretaciones de los requisitos o limitaciones técnicas.

- **Falla:** Una falla es el resultado de la ejecución incorrecta del software, es decir, cuando el software no produce el resultado esperado. Puede manifestarse como un comportamiento incorrecto, errores de funcionamiento, bloqueos o cualquier otra forma de comportamiento no deseado. Las fallas son visibles para los usuarios o para el sistema en sí, y pueden ser causadas por defectos o errores en el software.

Es importante destacar que los errores son la causa de los defectos, y los defectos pueden conducir a fallas en la ejecución del software. La detección y corrección de defectos es esencial para prevenir fallas y garantizar la calidad del software.

_Una persona comete un error, este introduce un defecto que causa una falla_

## Ejemplo de Defecto, Error y Falla

**Error:** El programador comete un error al escribir el código y utiliza la operación de comparación incorrecta en la validación de edad. En lugar de utilizar ">=" (mayor o igual que), utiliza "<=" (menor o igual que), lo cual es incorrecto. El error se produce debido a una acción incorrecta del programador al implementar la lógica de validación.

**Defecto:** El defecto se encuentra en el código, específicamente en la validación de edad. El programador ha definido incorrectamente la condición para permitir el acceso al sitio web. En lugar de verificar si la edad es mayor o igual a 18 años, se verifica si la edad es menor o igual a 18 años. Este defecto implica una desviación del comportamiento esperado y puede permitir el acceso a usuarios menores de 18 años.

**Falla:** La falla se produce cuando se ejecuta el código con el defecto en la validación de edad. Como resultado, el programa permite el acceso a usuarios que no cumplen con el requisito de tener 18 años o más. Esto implica que el programa no está funcionando correctamente y presenta un comportamiento no deseado. La falla es visible para los usuarios del sitio web, ya que se les permite el acceso incluso si no cumplen con el requisito de edad.

En este ejemplo, el error es la acción incorrecta del programador al escribir el código, el defecto es la presencia del error en el código y la falla es el resultado incorrecto de la ejecución del programa. Identificar y corregir el defecto es fundamental para solucionar la falla y asegurar que el programa funcione de acuerdo a los requisitos establecidos.

## Relación Defecto - Falla

- Un defecto puede producir 0, 1 o más fallas.
- Una falla puede estar causada por 1 o más defectos.

En el desarrollo de software, los defectos son desviaciones o errores en el código, diseño, requisitos, etc., que pueden dar lugar a un comportamiento incorrecto del software. Dependiendo de la naturaleza y gravedad del defecto, puede ocurrir ninguna falla si el defecto no se activa durante la ejecución del software, una falla si el defecto produce un resultado incorrecto en una única instancia o varias fallas si el defecto se manifiesta en diferentes situaciones o escenarios.

Una falla es un comportamiento incorrecto o indeseado del software durante su ejecución. Puede estar causada por uno o más defectos. Mientras que un solo defecto puede ser la causa directa de una falla, también es posible que múltiples defectos interactúen entre sí y contribuyan a la ocurrencia de la falla.

Es importante destacar que los defectos son la raíz de las fallas en el software. Identificar y corregir los defectos es esencial para prevenir o solucionar las fallas y garantizar que el software funcione correctamente.

## Enmascaramiento de Error (Defect Masking)

El enmascaramiento de error (defect masking) se refiere a una situación en la cual un defecto presente en el software impide la detección de otro defecto.

**Definición:** "Ocurrencia en la cual un defecto impide la detección de otro." [IEEE Standard Glossary of Software Engineering Terminology]

El enmascaramiento de error puede ocurrir cuando un defecto existente en una parte del código o sistema de software oculta o disfraza la manifestación de otro defecto. Esto dificulta la identificación y solución del defecto enmascarado, ya que la atención se centra en el defecto que lo está ocultando.

Este fenómeno puede tener consecuencias negativas, ya que los defectos enmascarados pueden pasar desapercibidos durante las pruebas o la revisión del software, lo que a su vez puede llevar a la entrega de un producto con errores o fallas no detectadas.

Para evitar el enmascaramiento de errores, es importante llevar a cabo pruebas exhaustivas y una revisión minuciosa del software. Además, se debe fomentar una cultura de calidad y colaboración en el equipo de desarrollo, donde se promueva la detección temprana y la resolución de defectos de manera efectiva.

En resumen, el enmascaramiento de error es una situación en la que un defecto impide la detección de otro defecto en el software, lo que puede comprometer la calidad y confiabilidad del producto final.

Fuente: IEEE Standard Glossary of Software Engineering Terminology (IEEE Std 610.12-1990)

## Gestión de Defectos.

**La palabra gestión implica:**

- Alta
- Baja
- Modificación
- Consulta

## Alta de un Defecto (Reportar un Incidente)

El alta de un defecto, también conocido como reportar un incidente, es el proceso de registrar y documentar un problema o error encontrado durante las actividades de prueba o uso del software. Es una parte fundamental de la gestión de defectos y tiene como objetivo principal capturar y comunicar de manera efectiva la información relacionada con el defecto encontrado.

### Registro de Incidentes

En el contexto de la gestión de defectos, es importante registrar cualquier diferencia entre el resultado actual y el esperado como un incidente. Un incidente puede referirse a diferentes términos, como bug, defecto, error, issue, entre otros, dependiendo de la terminología utilizada en el proyecto o la organización.

De acuerdo con la definición del IEEE 1008, un incidente se refiere a cualquier ocurrencia de un suceso que requiere investigación. Esto significa que cualquier discrepancia o comportamiento incorrecto del software en comparación con las expectativas debe ser registrado y tratado como un incidente.


El proceso de alta de un defecto generalmente sigue los siguientes pasos:

1. Identificar el defecto: En primer lugar, se debe identificar y comprender claramente el problema o error en el software. Esto implica reproducir el defecto de manera consistente para poder describirlo adecuadamente.

2. Documentar el defecto: Una vez identificado, se debe documentar el defecto de manera clara y completa. Esto implica proporcionar información detallada sobre el comportamiento incorrecto, los pasos para reproducir el problema, los datos de entrada utilizados, mensajes de error o cualquier otra información relevante que ayude a comprender y resolver el defecto.

3. Asignar prioridad y severidad: El defecto reportado debe ser evaluado en términos de su importancia y su impacto en el sistema. Esto implica asignar una prioridad que indique la urgencia de su resolución y una severidad que indique el impacto que tiene en la funcionalidad del software.

4. Registrar el defecto en el sistema de seguimiento: El defecto debe ser registrado en un sistema de seguimiento de defectos o herramienta de gestión de incidencias. Esto garantiza que el defecto sea rastreado y asignado a los responsables adecuados para su resolución.

5. Comunicar el defecto: Una vez registrado, el defecto debe ser comunicado a los miembros relevantes del equipo de desarrollo, incluyendo desarrolladores, probadores y responsables de la gestión de proyectos. Esto asegura que el defecto sea reconocido y se tomen las acciones necesarias para su resolución.

6. Seguimiento y actualización: A medida que se realice el seguimiento del defecto, se pueden requerir actualizaciones adicionales, como información adicional, resultados de pruebas adicionales o cambios en el estado del defecto. Estas actualizaciones deben ser registradas en el sistema de seguimiento para mantener un registro completo del defecto.

El proceso de alta de un defecto es crucial para garantizar una gestión efectiva de los defectos en el software. Proporciona un mecanismo para capturar y comunicar problemas de manera estructurada, lo que ayuda a mejorar la calidad del software y facilita su resolución oportuna.

Recuerda que es importante seguir los procedimientos y estándares establecidos por tu organización o proyecto en particular al reportar un incidente.

## Registro de Incidentes en el Ciclo de Vida del Desarrollo del Sistema

Un incidente puede ser registrado en cualquier punto del ciclo de vida de desarrollo del sistema, incluyendo las siguientes etapas:

- Revisión de requerimientos: Durante la revisión de los requerimientos del sistema, es posible identificar discrepancias, ambigüedades o problemas en los requisitos que deben ser registrados como incidentes.

- Revisión de diseño: Durante la revisión del diseño del sistema, es posible identificar aspectos que no cumplen con los requisitos o que podrían generar problemas en la implementación. Estos hallazgos deben ser registrados como incidentes.

- Codificación: Durante el proceso de codificación, pueden surgir errores, problemas de lógica o incumplimiento de estándares de codificación que deben ser registrados como incidentes para su posterior corrección.

- Pruebas: Durante las actividades de prueba, pueden identificarse fallos, comportamientos inesperados o cualquier desviación del comportamiento esperado. Estos hallazgos deben ser registrados como incidentes para su análisis y resolución.

Es importante registrar los incidentes en cualquier punto del ciclo de vida de desarrollo del sistema porque proporciona alertas tempranas sobre problemas o discrepancias que pueden afectar la calidad del software. Al registrar los incidentes, se crea un registro de los problemas encontrados y se permite su seguimiento y resolución adecuada.

Además, el registro de incidentes puede ayudar a identificar necesidades de capacitación o mejoras en determinadas áreas. Por ejemplo, si se identifica que un área específica necesita capacitación en un tema determinado, esto puede registrarse como un incidente y ser abordado en el proceso de mejora continua.

## Registro de Defectos en el Ciclo de Vida del Producto

Un defecto puede ser registrado contra cualquier producto dentro del ciclo de vida del sistema, incluyendo los siguientes:

- Libro de Requerimientos: Durante la revisión de los requerimientos del sistema, es posible identificar inconsistencias, ambigüedades o requisitos faltantes que deben ser registrados como defectos.

- Diseño de Sistema: Durante la etapa de diseño del sistema, pueden surgir problemas de diseño, falta de coherencia con los requerimientos o deficiencias en la arquitectura. Estos problemas deben ser registrados como defectos.

- Código Fuente: Durante la codificación del sistema, pueden introducirse errores de programación, problemas de lógica o incumplimiento de estándares de codificación. Estos errores deben ser registrados como defectos para su corrección.

- Material de Pruebas: Durante las actividades de prueba, pueden identificarse fallas en los casos de prueba, problemas en los datos de prueba o resultados inesperados. Estas fallas deben ser registradas como defectos.

- Manuales o Guías de Usuarios: Durante la revisión de los manuales o guías de usuarios, pueden encontrarse errores de contenido, instrucciones ambiguas o falta de información relevante. Estos errores deben ser registrados como defectos.

Es importante registrar los defectos contra los diferentes productos dentro del ciclo de vida del sistema para poder darles seguimiento y asegurar su corrección. Al registrar los defectos, se crea un registro de los problemas identificados y se facilita su resolución posterior.

## Objetivos del Reporte de Defectos

El reporte de defectos tiene los siguientes objetivos:

1. Proporcionar información a los desarrolladores y otras partes interesadas: El reporte de defectos busca brindar a los desarrolladores y otras partes involucradas en el proyecto la información necesaria sobre el problema identificado. Esto permite la identificación, el aislamiento y la corrección del defecto en caso necesario. El reporte debe ser claro, preciso y detallado para facilitar la comprensión del problema y su solución.

2. Permitir el seguimiento de la calidad del sistema bajo prueba: El reporte de defectos también sirve como un medio de seguimiento de la calidad del sistema durante las pruebas. Permite al Test Lead o responsable de pruebas evaluar la cantidad y la gravedad de los defectos encontrados, así como monitorear el progreso de las pruebas en relación a la detección y resolución de los defectos.

3. Evaluar el cumplimiento de los criterios de aceptación: El reporte de defectos proporciona información relevante para determinar si se han alcanzado o no los criterios de aceptación establecidos para el sistema. Permite evaluar si el software cumple con los requisitos y expectativas definidos previamente, identificando las desviaciones o fallas que puedan afectar la aceptación del producto.

### IEEE 829 define un template para el reporte de incidentes.

- Identificador del Reporte de Incidentes.
- Resumen.
- Descripción del Incidente.
- Impacto.

**Identificador del Reporte de Incidentes:** [ID del incidente]

**Resumen:** [Breve resumen del incidente]

**Descripción del Incidente:**
[Detalles y contexto del incidente, incluyendo pasos para reproducirlo si es posible]

**Impacto:**
[Descripción del impacto del incidente en el sistema, funcionalidad, rendimiento, etc.]

## Reporte de Defectos

1. **Identificador:** [Identificador único del defecto]
2. **Título:** [Título descriptivo del defecto]
3. **Descripción:** [Descripción detallada del defecto]
4. **Pasos de Reproducción:** 
   1. [Primer paso para reproducir el defecto]
   2. [Segundo paso para reproducir el defecto]
   3. [Y así sucesivamente]
5. **Datos de entrada:** [Información relevante sobre los datos utilizados durante la reproducción]
6. **Resultado Esperado:** [Descripción del resultado esperado]
7. **Resultado Actual:** [Descripción del resultado actual observado]
8. **Impacto (Severidad):** [Nivel de impacto o gravedad del defecto]
9. **Prioridad:** [Nivel de prioridad asignado al defecto]
10. **Categoría:** [Categoría o tipo de defecto (por ejemplo, funcional, usabilidad, rendimiento, etc.)]
11. **Ambiente:** [Descripción del ambiente o configuración en el que se encontró el defecto]
12. **Versión:** [Versión o número de la versión del software en la que se encontró el defecto]
13. **Adjuntos:** [Archivos o capturas de pantalla relacionados con el defecto]
14. **Observaciones:** [Cualquier observación adicional o comentarios relevantes]

**Componentes de un Reporte de Defectos**

1. **Identificador:** Es un identificador único asignado al defecto para su seguimiento y referencia.

2. **Título:** Un título descriptivo que resume brevemente el defecto.

3. **Descripción:** Una descripción detallada del defecto, incluyendo cualquier información relevante que ayude a entender y reproducir el problema.

4. **Pasos de Reproducción:** Los pasos específicos necesarios para reproducir el defecto, en orden secuencial. Esto ayuda a otros a reproducir el problema y entender cómo se llegó al resultado incorrecto.

5. **Datos de entrada:** Cualquier dato o información relevante que se haya utilizado durante la reproducción del defecto. Esto puede incluir valores de entrada, configuraciones específicas, archivos adjuntos, etc.

6. **Resultado Esperado:** La descripción del resultado esperado del sistema o funcionalidad afectada por el defecto. Es lo que se espera que ocurra correctamente.

7. **Resultado Actual:** La descripción del resultado actual observado durante la reproducción del defecto. Es lo que realmente sucede y que difiere del resultado esperado.

8. **Impacto (Severidad):** La gravedad o impacto del defecto en términos de su impacto en el sistema o en el proceso de negocio. Aquí se pueden utilizar los siguientes estados de severidad:
  - Bloqueante: El defecto impide completamente el uso o funcionamiento del sistema.
  - Crítico: El defecto tiene un impacto grave en la funcionalidad principal o en la seguridad del sistema.
  - Mayor: El defecto tiene un impacto significativo en la funcionalidad, pero el sistema aún es utilizable.
  - Medio: El defecto tiene un impacto moderado y no afecta críticamente la funcionalidad principal.
  - Menor: El defecto tiene un impacto mínimo o cosmético en la funcionalidad.
  - Mejora: No es un defecto crítico, sino una sugerencia de mejora o funcionalidad adicional.

9. **Prioridad:** La importancia relativa del defecto en términos de su resolución y su impacto en el proyecto. Aquí se pueden utilizar los siguientes estados de prioridad:
  - Crítico: El defecto requiere atención inmediata y alta prioridad para su corrección.
  - Alta: El defecto debe ser resuelto de manera oportuna, pero puede esperar un poco más que los críticos.
  - Media: El defecto es importante, pero puede ser resuelto después de los de alta prioridad.
  - Baja: El defecto tiene una prioridad baja y puede ser abordado posteriormente.

10. **Categoría:** La categoría o tipo de defecto, que puede ser funcional, de usabilidad, de rendimiento, de seguridad, etc. Esto ayuda a clasificar y organizar los defectos de acuerdo a su naturaleza.

11. **Ambiente:** Una descripción del entorno o configuración en el que se encontró el defecto. Puede incluir detalles sobre el sistema operativo, el navegador, las herramientas o cualquier otra información relevante para la reproducción del defecto.

12. **Versión:** La versión o número de la versión del software en la que se encontró el defecto. Esto ayuda a identificar si el defecto ya ha sido corregido en versiones posteriores.

13. **Adjuntos:** Cualquier archivo o captura de pantalla relevante que pueda ayudar a entender o ilustrar el defecto. Esto puede incluir registros de errores, imágenes, grabaciones de pantalla, etc.

14. **Observaciones:** Cualquier observación adicional o comentarios relevantes que se consideren necesarios para proporcionar información adicional sobre el defecto.

## Características de un buen reporte de bug:

- Objetivo: Los defectos deben ser reportados de manera objetiva, sin prejuicios ni emociones.

- Específico: Cada reporte debe enfocarse en un único defecto, evitando incluir múltiples problemas en un solo informe.

- Conciso: Los informes de defectos deben ser claros y directos, sin información innecesaria.

- Reproducible: Un reporte de defecto debe incluir los pasos detallados necesarios para reproducir el problema, permitiendo que cualquier persona pueda replicarlo fácilmente.

- Explícito: El reporte de defectos debe proporcionar información clara y precisa, o hacer referencia a fuentes específicas donde se encuentre dicha información.

- Persuasivo: El reporte de defecto debe ser convincente para que el desarrollador sienta motivación para corregirlo, proporcionando argumentos sólidos y ejemplos concretos.

Estas características contribuyen a la calidad de los reportes de defectos y facilitan la comprensión y resolución de los problemas por parte del equipo de desarrollo.

## Buenas prácticas para reportar un defecto:

- Incluir tanta información como sea posible en el reporte del defecto.
- Un defecto bien redactado debe incluir: el problema en sí y cómo recrear el problema.
- Agregar cualquier otra información relevante relacionada con el error.
- Antes de reportar el defecto, reproducirlo al menos tres veces para confirmar su consistencia.
- Conocer todas las condiciones en las que se puede reproducir el error.
- Comprender por qué ocurre el error puede ser de gran ayuda para su resolución.
- El título del defecto debe ser una única oración (pueden existir excepciones), describiendo primero el error y luego su causa.
- Proporcionar el mayor detalle posible en el título del defecto.
- La descripción del defecto debe incluir los pasos detallados para reproducir el error.

## Reporte de Defectos - Buenas Prácticas

- Verificación previa: Antes de reportar un defecto, verificar si ya ha sido reportado para evitar duplicados.

- Idioma: Todos los incidentes deben ser redactados en el mismo idioma definido durante la planificación del proyecto.

- Comunicación: El analista de control de calidad (QC) debe estar dispuesto a proporcionar más información al desarrollador cuando sea necesario.

- Redacción: Ser cuidadoso con los pronombres y evitar el uso de términos vagos como "eso" o "la ventana" que no sean claros en su referencia.

- Especificidad: El incidente debe ser específico y detallado. Si existen múltiples formas de realizar una acción, se debe indicar claramente cuál fue la forma utilizada.

- Captura de Pantalla: En casos donde sea difícil explicar el error verbalmente, se recomienda utilizar la función de captura de pantalla (Print Screen) para mostrar visualmente el problema. Esto facilita la comprensión del error y proporciona una demostración clara de lo que se está viendo en pantalla.

