<h1>¿Qué aprenderemos hoy?</h1>
<ol>
<li><a href="#enlace-1">Testing a través del ciclo de vida del software</a></li>
<li><a href="#enlace-2">Niveles de pruebas</a></li>
<li><a href="#enlace-3"></a></li>
<li><a href="#enlace-4"></a></li>
<li><a href="#enlace-5"></a></li>
<li><a href="#enlace-6"></a></li>
<li><a href="#enlace-7"></a></li>
</ol>


<h2 id="enlace-1">Testing a través del ciclo de vida del software</h2>

<h3>Modelo V</h3>
<p>Es el modelo de desarrollo de software más utilizado, donde el desarrollo y el testing son dos ramas que apuntan a los mismos niveles, ya que para cada nivel de desarrollo existe su correspondiente nivel de Testing.</p>

<p>En la práctica, este modelo puede tener más o menos niveles dependiendo del proyecto y el producto que se esta desarrollando. Se creó como respuesta a los distintos problemas que ocurrían en el desarrollo en cascada (Waterfall Model). El Modelo V, propone realizar testing desde el comienzo del proyecto, realizando Testing Estático en cada una de las fases de desarrollo, preparando las pruebas para esos niveles y luego ejecutando las mismas en forma ascendente se tiene siempre un control sobre cada una de las etapas.</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/alexalvarezjl/Bootcamp-Testing-Kolektor/main/assets/modelo_v_kolektor.png" alt="modelo en V kolektor">
</p>

<h3>Principios en el módelo V</h3>
<ul>
<li>Cada actividad de desarrollo debe ser probada</li>
<li>Ninguna porción del software puede quedar sin ser probada, si ha sido desarrollada tanto de forma (una unica fase) o iterativa</li>
<li>Cada nivel de prueba debería ser probado de forma especifica</li>
<li>Cada nivel de pruebas cuenta con sus objetivos de prueba propios</li>
<li>Las pruebas llevadas a cabo en cada nivel deben reflejar estos objetivos</li>
<li>El proceso de pruebas comienza con mucha antelación a la ejecucion de pruebas</li>
<li>Tan pronto como el desarrollo comienza puede comenzar la preparación de las pruebas correspondientes</li>
<li>También es el caso de las revisiones de documentos comenzando por los conceptos, especificaion y el diseño global (en conjunto).</li>
</ul>

<a href="https://josepablosarco.wordpress.com/2012/03/24/istqb-cap-2-testing-a-traves-del-ciclo-de-vida-del-software-i/">Fuente</a>

<h2 id="enlace-2">Niveles de pruebas</h2>

# Prueba de Componentes

Las pruebas de componentes, también conocidas como pruebas de desarrollador (developer's test), consiste en probar cada componente individualmente después de su construcción. Este tipo de pruebas se realiza en función de las convenciones de nombres específicas de cada lenguaje de programación utilizado.

## Alcance

- Se prueban componentes individuales de forma independiente.
- Los casos de prueba se derivan de especificaciones de componentes, diseños de software o modelos de datos.
- Se busca encontrar defectos y verificar el funcionamiento de los componentes (módulos, programas, objetos, clases, etc.) que pueden ser evaluados por separado.
- Puede incluir pruebas de elementos funcionales y no funcionales, como recursos del sistema y pruebas estructurales.

## Proceso y enfoque

- El testing de componentes se realiza con acceso al código bajo prueba y con el soporte de herramientas de desarrollo, como frameworks de pruebas unitarias o herramientas de depuración.
- En la práctica, generalmente implica al programador que escribió el código.
- Los errores suelen corregirse de inmediato una vez que se encuentran, sin un registro oficial de incidentes.
- Un enfoque común para el testing de componentes es el desarrollo basado en pruebas (TDD), que consiste en preparar y automatizar casos de prueba antes de codificar.
- El TDD implica ciclos repetitivos de desarrollo de casos de prueba, construcción e integración de pequeñas secciones de código y ejecución de pruebas de componentes hasta que se superen.

# Pruebas de Integración

Las pruebas de integración tienen como objetivo verificar las interfaces entre componentes y las interacciones entre las diferentes partes de un sistema, como el sistema operativo, sistema de archivos, hardware o interfaces con otros sistemas.

Puntos clave:
- Puede haber varios niveles de pruebas de integración y se pueden llevar a cabo en objetos de prueba de diferentes tamaños.
- Las pruebas de integración de componentes verifican las interacciones entre los componentes del software y se realizan después de las pruebas de componentes.
- A medida que aumenta el alcance de la integración, se vuelve más difícil aislar las fallas en elementos o sistemas específicos, lo que puede aumentar el riesgo.
- Las estrategias de integración pueden basarse en la arquitectura del sistema (por ejemplo, de arriba hacia abajo o de abajo hacia arriba), tareas funcionales, secuencias de procesamiento de transacciones u otros aspectos del sistema o componente.
- Para reducir el riesgo de encontrar errores demasiado tarde, la integración se realiza de forma incremental.

## Alcance

- Se prueban grupos de componentes.
- Puede implementarse a nivel de subsistemas si se tienen grupos de componentes relacionados.
- Las pruebas de integración verifican la interacción entre componentes con respecto a las especificaciones de interfaces.

# Pruebas de Sistema

Las pruebas de sistema se enfocan en la calidad del software desde la perspectiva del usuario. El entorno de prueba debe ser lo más similar posible al entorno de producción para minimizar el riesgo de incidentes que puedan surgir debido a diferencias ambientales no identificadas durante las pruebas. Este tipo de pruebas puede incluir pruebas basadas en riesgos y/o especificaciones de requisitos, procesos de negocio, casos de uso u otras descripciones de alto nivel del comportamiento del sistema y sus interacciones con el sistema operativo y los recursos del sistema.

Puntos clave:
- El testing de sistema investiga tanto los requisitos funcionales como los no funcionales del sistema.
- Estos requisitos pueden estar documentados en forma de texto y/o modelos.

## Alcance

Las pruebas de sistema abarcan los siguientes aspectos:

1. Adecuación (Suitability): ¿Las funciones implementadas son adecuadas para su uso previsto?
2. Exactitud (Accuracy): ¿Las funciones producen los resultados correctos según lo acordado?
3. Interoperabilidad (Interoperability): ¿Las interacciones con el entorno del sistema presentan algún problema?
4. Cumplimiento de Funcionalidad (Compliance): ¿El sistema cumple con las normas y regulaciones aplicables?
5. Seguridad (Security): ¿Los datos y programas están protegidos contra acceso no autorizado o pérdida?

# Pruebas de Aceptación

Las pruebas de aceptación es frecuentemente responsabilidad de los clientes y/o usuarios de un sistema, aunque otras partes interesadas también pueden participar. El objetivo de las pruebas de aceptación es establecer confianza en el sistema, sus componentes o características específicas, tanto funcionales como no funcionales. Encontrar defectos no es el enfoque principal en las pruebas de aceptación. Estas pruebas pueden evaluar la preparación del sistema para su uso, aunque no siempre representan el nivel final de pruebas. Por ejemplo, una prueba de integración a gran escala puede seguir a las pruebas de aceptación de un sistema.

Las pruebas de aceptación no se limitan a un solo nivel, pueden realizarse en diferentes momentos, como:
- Pruebas de aceptación al momento de la instalación o integración de un producto de software.
- Pruebas de aceptación de usabilidad durante las pruebas de componentes.
- Pruebas de aceptación de una nueva mejora funcional antes de las pruebas del sistema.

## Alcance

El objetivo de las pruebas de aceptación es verificar que el software satisfaga los requisitos del cliente.

<h2 id="enlace-3">¿Qué es calidad?</h2>

<h2 id="enlace-4">¿Qué es calidad?</h2>

<h2 id="enlace-5">¿Qué es calidad?</h2>

<h2 id="enlace-6">¿Qué es calidad?</h2>

<h2 id="enlace-7">¿Qué es calidad?</h2>