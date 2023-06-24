<h1>Tipos de Pruebas</h1>
<ol>
<li><a href="#enlace-1">Pruebas Funcionales</a></li>
<li><a href="#enlace-2">Pruebas No Funcionales</a></li>
</ol>

<h1 id="enlace-1">Pruebas Funcionales</h1>

Se basan en un análisis de las especifiaciones de la funcionalidad de un componente o sistema. Estas son:
- Funciones de Negocios
- Interfaces de Usuarios

A su vez, estas pruebas se pueden encarar desde 2 perspectivas:
- Basadas en Requerimientos
- Basasdas en Procesos de Negocios

## Pruebas Funcionales Basadas en Funciones de Negocio

Las pruebas funcionales basadas en funciones de negocio se centran en verificar que las funciones y características del software cumplan con los requisitos y especificaciones definidos para el negocio. Estas pruebas se realizan en todos los niveles del proceso de testing y tienen como objetivo principal evaluar la funcionalidad del sistema desde la perspectiva de su uso en el contexto empresarial.

**Objetivo:** Evaluar la función del objeto de prueba basado en las necesidades y requerimientos del negocio.

**Alcance:** Las pruebas funcionales se aplican a todas las funciones y características del sistema que están relacionadas con los procesos de negocio y que se pueden especificar o entender claramente.

**Limitantes:** Los limitantes pueden incluir la disponibilidad de recursos, restricciones de tiempo o presupuesto, y la capacidad para replicar exactamente el entorno de producción.

**Ejemplo:**

En un sistema de gestión de pedidos en línea, se realiza una prueba funcional para verificar que la función de procesamiento de pagos cumple con los siguientes criterios:

- Se aceptan múltiples métodos de pago (tarjeta de crédito, PayPal, transferencia bancaria).
- El importe del pago se calcula correctamente, incluyendo impuestos y descuentos.
- Se generan notificaciones y confirmaciones de pago para el cliente y el vendedor.

## Pruebas Funcionales Basadas en Interfaces de Usuario

Las pruebas funcionales basadas en interfaces de usuario se enfocan en verificar que las interfaces de usuario cumplan con los requisitos especificados. Estas pruebas evalúan cómo interactúa un usuario con el sistema y se centran en garantizar que todas las funciones de la interfaz sean intuitivas, eficientes y cumplan con las expectativas del usuario.

**Objetivo:** Evaluar la usabilidad y funcionalidad de la interfaz de usuario desde la perspectiva de los requerimientos establecidos.

**Alcance:** Estas pruebas se aplican a todas las características y funcionalidades de la interfaz de usuario que sean accesibles y visibles para el usuario final.

**Limitantes:** Los limitantes pueden incluir restricciones de tiempo y recursos, así como la disponibilidad de dispositivos o navegadores específicos necesarios para probar la interfaz.

**Ejemplo:**

En una aplicación móvil de redes sociales, se realiza una prueba funcional basada en la interfaz de usuario para verificar que la función de publicación de mensajes cumple con los siguientes criterios:

- El usuario puede redactar y publicar mensajes correctamente.
- Los mensajes publicados se muestran en el feed de noticias de los seguidores del usuario.
- Se pueden adjuntar imágenes o enlaces a los mensajes.
- Los mensajes publicados se pueden editar o eliminar según los permisos establecidos.

<h1 id="enlace-2">Pruebas No Funcionales</h1>

Donde los atributos de un componente o sistema pueden no estar relacionados a la funcionalidad

- Test de Performance
- Test de Seguridad
- Test de Estrés
- Test de Carga o Volumen
- Test de Configuración
- Test de Instalación o Portabilidad
- Test de Usabilidad

## Test de Performance

Los tests de performance son pruebas realizadas para evaluar el rendimiento y la capacidad de respuesta de una aplicación, sistema o componente bajo diferentes cargas y condiciones. Estas pruebas tienen como objetivo medir y mejorar la eficiencia y el rendimiento del sistema. A continuación se detallan los aspectos clave de las pruebas de rendimiento:

- **Objetivo**: Evaluar y validar el rendimiento de una aplicación en términos de tiempo de respuesta, velocidad, estabilidad y eficiencia bajo diversas cargas y situaciones.

- **Alcance**: Las pruebas de rendimiento pueden abarcar diferentes áreas, como la velocidad de carga de páginas web, el rendimiento de transacciones en sistemas de bases de datos, la capacidad de respuesta de aplicaciones en momentos de alto tráfico, entre otros.

- **Limitantes**: Las pruebas de rendimiento pueden verse limitadas por recursos técnicos, como hardware insuficiente o limitado, falta de acceso a ambientes de producción reales, restricciones de tiempo y presupuesto.

- **Ejemplo**: Una prueba de rendimiento puede consistir en simular una carga de trabajo alta en un sistema de comercio electrónico para evaluar la capacidad de respuesta y estabilidad del sistema bajo una gran afluencia de usuarios concurrentes.

Las pruebas de rendimiento suelen evaluar aspectos como:

1. **Tiempo de respuesta:** mide el tiempo que tarda el sistema en responder a una solicitud del usuario.
2. **Capacidad de carga:** evalúa el comportamiento del sistema bajo cargas de trabajo crecientes, para determinar su capacidad máxima y cómo responde ante dichas cargas.
3. **Estabilidad:** verifica la estabilidad y la consistencia del sistema durante un período prolongado de tiempo y bajo diferentes condiciones.
4. **Escalabilidad:** evalúa cómo el sistema maneja el aumento de la carga de trabajo al agregar más recursos, como usuarios concurrentes o transacciones.
5. **Uso de recursos:** monitorea y analiza el consumo de recursos del sistema, como CPU, memoria, ancho de banda de red, para identificar posibles problemas de rendimiento relacionados con la utilización eficiente de recursos.

_Las herramientas especializadas de prueba de rendimiento ayudan en la ejecución, monitorización y análisis de estas pruebas, recopilando datos relevantes y generando informes que permiten identificar problemas y tomar decisiones informadas para mejorar el rendimiento del sistema._

## Tests de Seguridad

Los tests de seguridad son pruebas diseñadas para evaluar la resistencia y robustez de un sistema o aplicación frente a posibles vulnerabilidades y ataques maliciosos. El objetivo principal de estas pruebas es identificar y remediar posibles brechas de seguridad antes de que puedan ser explotadas por terceros no autorizados.

**Objetivo:** El objetivo de los tests de seguridad es garantizar la integridad, confidencialidad y disponibilidad de los datos y recursos del sistema, así como prevenir posibles violaciones de seguridad y proteger la información sensible.

**Alcance:** Estas pruebas pueden abarcar diferentes aspectos de seguridad, como la autenticación, autorización, cifrado, validación de entradas, gestión de sesiones, configuración segura del sistema, entre otros. El alcance puede variar dependiendo de las características y requisitos específicos del sistema o aplicación bajo prueba.

**Limitantes:** Algunos posibles limitantes de los tests de seguridad pueden incluir restricciones de tiempo, acceso limitado a ciertos recursos o información, falta de conocimiento detallado sobre el entorno objetivo, y limitaciones éticas y legales que pueden restringir ciertas actividades de prueba.

**Ejemplo:** Un ejemplo de test de seguridad es realizar pruebas de penetración, donde se simulan ataques controlados para identificar vulnerabilidades en el sistema. Esto puede incluir intentos de explotación de debilidades en el código, pruebas de inyección de SQL, ataques de denegación de servicio, entre otros escenarios de amenazas comunes.

## Tests de Estrés

Los tests de estrés son pruebas diseñadas para evaluar el rendimiento y la estabilidad de un sistema o aplicación bajo cargas extremas o condiciones límite. El objetivo principal de estas pruebas es determinar cómo responde el sistema ante una sobrecarga intensa y prolongada, identificando posibles puntos de falla y evaluando su capacidad para mantener un rendimiento óptimo.

**Objetivo:** El objetivo de los tests de estrés es medir y evaluar la capacidad de un sistema para manejar cargas máximas o situaciones adversas, identificando posibles cuellos de botella, fugas de recursos, degradación del rendimiento o colapsos.

**Alcance:** Estas pruebas pueden abarcar diferentes aspectos del sistema, como la capacidad de procesamiento, la concurrencia, la escalabilidad, la gestión de memoria y recursos, la respuesta ante solicitudes simultáneas, entre otros. El alcance dependerá de las características y requisitos específicos del sistema bajo prueba.

**Limitantes:** Algunos posibles limitantes de los tests de estrés pueden incluir restricciones de tiempo y recursos, acceso limitado a ciertos escenarios o configuraciones, falta de datos realistas para generar cargas de trabajo extremas y posibles impactos negativos en el rendimiento o la estabilidad del sistema durante las pruebas.

**Ejemplo:** Un ejemplo de test de estrés es simular un alto tráfico de usuarios simultáneos en un sitio web o una aplicación, superando su capacidad máxima prevista. Esto puede ayudar a identificar cómo se comporta el sistema bajo condiciones de carga intensa, si hay tiempos de respuesta lentos, errores de conexión o posibles bloqueos del sistema.

## Tests de Carga/Volumen

Los tests de carga/volumen son pruebas diseñadas para evaluar el rendimiento y la capacidad de un sistema o aplicación bajo cargas significativas de trabajo o volúmenes de datos elevados. El objetivo principal de estas pruebas es determinar cómo responde el sistema ante una demanda intensa y cercana a su límite de capacidad, identificando posibles problemas de rendimiento, estabilidad y escalabilidad.

**Objetivo:** El objetivo de los tests de carga/volumen es verificar la capacidad de un sistema para procesar, manejar y responder adecuadamente a un volumen alto de usuarios, transacciones o datos. Se busca identificar posibles cuellos de botella, degradación del rendimiento, errores de procesamiento o saturación del sistema.

**Alcance:** Estas pruebas se centran en evaluar el rendimiento y la estabilidad del sistema bajo diferentes cargas de trabajo o volúmenes de datos, como un número creciente de usuarios simultáneos, transacciones concurrentes o grandes conjuntos de datos. El alcance dependerá de los requisitos y características específicas del sistema bajo prueba.

**Limitantes:** Algunos posibles limitantes de los tests de carga/volumen pueden incluir restricciones de tiempo y recursos, disponibilidad limitada de datos de carga realistas, necesidad de entornos de prueba escalables y posibles impactos negativos en el rendimiento o la estabilidad del sistema durante las pruebas.

**Ejemplo:** Un ejemplo de test de carga/volumen es simular un alto número de usuarios accediendo simultáneamente a un sistema en línea y realizando transacciones. Esto permite evaluar cómo el sistema responde y mantiene su rendimiento bajo cargas pesadas, si hay retrasos significativos en las respuestas, errores de procesamiento o sobrecarga del sistema.

## Tests de Configuración/Portabilidad

Los tests de configuración/portabilidad se centran en evaluar la capacidad de una aplicación o sistema para funcionar correctamente en diferentes configuraciones de hardware, software, sistemas operativos y entornos. Estas pruebas buscan garantizar que el software sea portátil y se pueda instalar, configurar y ejecutar sin problemas en diversos entornos.

**Objetivo:** El objetivo principal de los tests de configuración/portabilidad es verificar que el software pueda ser instalado, configurado y ejecutado correctamente en diferentes configuraciones de hardware, software y sistemas operativos. Se busca identificar cualquier problema de compatibilidad, dependencia de recursos específicos o conflictos con otros componentes del sistema.

**Alcance:** Estas pruebas abarcan la evaluación de la compatibilidad del software en diferentes configuraciones, como sistemas operativos, versiones de software, configuraciones de red, requisitos de hardware, etc. El alcance puede incluir también la verificación de la funcionalidad en diferentes idiomas, regiones o entornos de implementación.

**Limitantes:** Algunos posibles limitantes de los tests de configuración/portabilidad pueden ser la disponibilidad limitada de diferentes configuraciones de hardware y software para las pruebas, la complejidad de simular entornos diversos y la variabilidad en los resultados debido a las diferencias en las configuraciones utilizadas.

**Ejemplo:** Un ejemplo de test de configuración/portabilidad es instalar y ejecutar una aplicación en diferentes sistemas operativos (Windows, Linux, macOS) para verificar su compatibilidad y funcionamiento correcto. También se pueden probar diferentes configuraciones de hardware, como dispositivos móviles con diferentes versiones de sistemas operativos, para evaluar la portabilidad del software.

## Tests de Instalación

Los tests de instalación se enfocan en verificar que el proceso de instalación de un software o sistema sea realizado correctamente y sin problemas. Estas pruebas evalúan la instalación del software en diferentes entornos y configuraciones, asegurándose de que todos los componentes necesarios se instalen adecuadamente y que el software funcione correctamente después de la instalación.

**Objetivo:** El objetivo principal de los tests de instalación es asegurar que el proceso de instalación sea exitoso y que el software se pueda configurar y ejecutar correctamente en el entorno objetivo. Se busca identificar cualquier problema relacionado con la instalación, como errores en la configuración, dependencias faltantes o conflictos con otros componentes del sistema.

**Alcance:** Estas pruebas abarcan la evaluación del proceso de instalación del software en diferentes entornos, como sistemas operativos, versiones de software, configuraciones de red, etc. El alcance puede incluir la verificación de la instalación de componentes adicionales, la configuración de parámetros de software y la comprobación de la funcionalidad básica después de la instalación.

**Limitantes:** Algunos posibles limitantes de los tests de instalación pueden ser la disponibilidad limitada de diferentes configuraciones de hardware y software para las pruebas, la complejidad de simular entornos diversos y la variabilidad en los resultados debido a las diferencias en las configuraciones utilizadas.

**Ejemplo:** Un ejemplo de test de instalación sería realizar la instalación de un software en diferentes sistemas operativos (Windows, Linux, macOS) y verificar que todos los pasos del proceso de instalación se realicen correctamente, incluyendo la instalación de dependencias, la configuración de parámetros y la validación de la funcionalidad básica después de la instalación.

## Tests de Usabilidad

Los tests de usabilidad se centran en evaluar la facilidad de uso y la experiencia del usuario al interactuar con un software o sistema. Estas pruebas se enfocan en identificar y solucionar problemas de usabilidad que puedan afectar la eficiencia, la satisfacción y la efectividad del usuario al utilizar el software.

**Objetivo:** El objetivo principal de los tests de usabilidad es asegurar que el software sea intuitivo, fácil de aprender y utilizar para los usuarios. Se busca identificar problemas de diseño, navegación confusa, falta de retroalimentación o cualquier otra dificultad que pueda afectar negativamente la experiencia del usuario.

**Alcance:** Estas pruebas abarcan la evaluación de la interfaz de usuario, el flujo de navegación, la organización de la información, la legibilidad del texto, la disponibilidad de funciones clave y la respuesta del sistema a las acciones del usuario. El alcance puede incluir pruebas con usuarios reales, recopilación de comentarios y métricas de usabilidad.

**Limitantes:** Algunos posibles limitantes de los tests de usabilidad son la disponibilidad de usuarios representativos para las pruebas, la subjetividad de la evaluación de la usabilidad y la dificultad de medir la satisfacción del usuario de manera objetiva.

**Ejemplo:** Un ejemplo de test de usabilidad sería solicitar a usuarios representativos que realicen una serie de tareas específicas utilizando el software y observar cómo interactúan con la interfaz, qué dificultades encuentran y cómo se sienten al utilizar el sistema. Se pueden recopilar comentarios, registrar tiempos de realización de tareas y realizar mejoras en base a los resultados obtenidos.

