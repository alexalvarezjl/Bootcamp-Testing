<h1>Técnicas del Testing</h1>
<ol>
<li><a href="#enlace-1">Técnicas de Pruebas</a></li>
<li><a href="#enlace-2">Testing Estático vs Dinámico.</a></li>
<li><a href="#enlace-3">Técnicas de Pruebas</a></li>
<li><a href="#enlace-4">Técnicas de Caja Blanca</a></li>
<li><a href="#enlace-5">Técnicas de Caja Negra</a></li>
<li><a href="#enlace-6">Principios del testing</a></li>
<li><a href="#enlace-7">Actividades y Roles dentro del testing</a></li>
</ol>


<h1 id="enlace-1">Técnicas de Pruebas</h1>

## Técnicas de Pruebas

Las técnicas de pruebas son enfoques y metodologías utilizadas para diseñar y ejecutar pruebas de software de manera efectiva. Estas técnicas son fundamentales para descubrir defectos, mejorar la calidad del software y garantizar un producto confiable. A continuación, se presentan algunos aspectos clave sobre las técnicas de pruebas:

### Importancia de las técnicas de pruebas

- Diseño efectivo de pruebas: Las técnicas de pruebas permiten identificar los escenarios de prueba más relevantes, maximizando la cobertura y la detección de defectos.

- Optimización de recursos: Al utilizar técnicas adecuadas, se pueden ahorrar recursos y tiempo al enfocarse en las áreas críticas del software.

- Mejora de la calidad del software: Las técnicas de pruebas ayudan a identificar y corregir defectos en etapas tempranas del ciclo de vida del software, lo que resulta en un producto final más confiable.

### Alcance de las técnicas de pruebas

- Aplicabilidad universal: Las técnicas de pruebas son aplicables a diferentes niveles de pruebas, como pruebas unitarias, de integración, de sistema y de aceptación.

- Adaptabilidad: Las técnicas de pruebas se pueden adaptar a diferentes contextos y tipos de software, ya sea basado en web, móvil, embebido, entre otros.

### Objetivos de las técnicas de pruebas

- Maximizar la cobertura de pruebas: Las técnicas de pruebas buscan garantizar que se prueben todas las funcionalidades, caminos y casos relevantes del software.

- Detección temprana de defectos: Las técnicas de pruebas permiten descubrir defectos en etapas tempranas del ciclo de vida del software, lo que facilita su corrección y reduce costos.

### Limitantes de las técnicas de pruebas

- Dependencia del conocimiento: Al aplicar técnicas de pruebas, es importante contar con un buen entendimiento del sistema, requisitos y funcionalidades para diseñar pruebas efectivas.

- Cobertura limitada: Aunque las técnicas de pruebas ayudan a maximizar la cobertura, es posible que no se puedan probar todos los escenarios posibles debido a limitaciones de tiempo o recursos.

### Ejemplo

Un ejemplo de técnica de pruebas es la técnica de "Particiones de Equivalencia". Esta técnica se utiliza para reducir la redundancia en los casos de prueba al agrupar conjuntos de datos en clases de equivalencia. Por ejemplo, si se están probando campos de entrada numérica en un formulario, una partición de equivalencia podría ser dividir los valores en clases válidas (por ejemplo, números del 1 al 100) y clases inválidas (por ejemplo, números negativos o letras). Al diseñar casos de prueba, se pueden seleccionar valores representativos de cada clase para garantizar una cobertura adecuada.

<h1 id="enlace-2">Testing Estático vs Dinámico.</h1>

## Técnicas Estáticas y Dinámicas de Pruebas

Las técnicas de pruebas se pueden clasificar en estáticas y dinámicas, cada una con enfoques y objetivos diferentes. A continuación, se presentan los aspectos clave de cada una:

### Técnicas Estáticas de Pruebas

Las técnicas estáticas de pruebas se centran en la revisión y análisis del software sin ejecutarlo. Estas técnicas se aplican durante la fase de diseño o revisión de documentos y código fuente. Algunos puntos importantes son:

- Importancia: Las técnicas estáticas ayudan a encontrar defectos tempranamente, antes de que se ejecuten las pruebas dinámicas. Esto permite ahorrar tiempo y recursos.

- Alcance: Las técnicas estáticas se aplican en documentos, requisitos, especificaciones, diagramas, código fuente y otros artefactos del software.

- Objetivos: Los objetivos de las técnicas estáticas incluyen la detección de defectos, la mejora de la calidad del software y la reducción de costos.

- Limitantes: Las técnicas estáticas dependen del conocimiento y la experiencia de los revisores. Además, no pueden identificar todos los defectos potenciales, ya que no se ejecuta el software.

- Ejemplo: Una técnica estática común es la revisión de código, donde los programadores analizan el código fuente para encontrar errores, ineficiencias o incumplimientos de estándares de codificación.

### Técnicas Dinámicas de Pruebas

Las técnicas dinámicas de pruebas se basan en la ejecución del software para validar su comportamiento y funcionalidad. Estas técnicas se aplican a través de pruebas funcionales y no funcionales. Algunos aspectos a considerar son:

- Importancia: Las técnicas dinámicas permiten evaluar el rendimiento, la funcionalidad y la usabilidad del software en ejecución, brindando una visión real del comportamiento del sistema.

- Alcance: Las técnicas dinámicas se aplican durante las diferentes etapas de prueba, como pruebas unitarias, de integración, de sistema y de aceptación.

- Objetivos: Los objetivos de las técnicas dinámicas incluyen la detección de defectos, la validación de la funcionalidad y el rendimiento del software, y la mejora de la calidad del sistema.

- Limitantes: Las técnicas dinámicas pueden ser limitadas por el tiempo disponible, los recursos de prueba y las posibles limitaciones del entorno de prueba.

- Ejemplo: Un ejemplo de técnica dinámica es la prueba de regresión, donde se ejecutan pruebas después de realizar cambios en el software para asegurarse de que las modificaciones no hayan introducido nuevos defectos o afectado el funcionamiento existente.

## Diferencias entre Técnicas Estáticas y Dinámicas

A continuación se presentan las principales diferencias entre las técnicas estáticas y dinámicas de pruebas:

| Técnicas Estáticas | Técnicas Dinámicas |
|--------------------|-------------------|
| Se aplican sin ejecutar el software | Se aplican ejecutando el software |
| Se centran en la revisión y análisis del software | Se centran en la validación del comportamiento y funcionalidad del software |
| Se aplican en documentos y código fuente | Se aplican a través de pruebas funcionales y no funcionales |
| Detectan defectos tempranamente | Validan la calidad y el rendimiento del software |
| Ahorran tiempo y recursos | Brindan una visión real del sistema en ejecución |
| Requieren conocimiento y experiencia de los revisores | Requieren planificación y ejecución de pruebas |
| No pueden identificar todos los defectos potenciales | Pueden identificar defectos específicos al ejecutar el software |
| Mejoran la calidad del software | Mejoran la calidad del sistema |
| Ejemplos: revisión de código, análisis estático | Ejemplos: pruebas de regresión, pruebas de carga |


<h2 id="enlace-3">Técnicas de Pruebas</h2>

<h2 id="enlace-4">Técnicas de Caja Blanca</h2>

<h2 id="enlace-5">Técnicas de Caja Negra</h2>

<h2 id="enlace-6">¿Qué es calidad?</h2>

<h2 id="enlace-7">¿Qué es calidad?</h2>
