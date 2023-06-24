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

Las pruebas de rendimiento son pruebas realizadas para evaluar el rendimiento y la capacidad de respuesta de una aplicación, sistema o componente bajo diferentes cargas y condiciones. Estas pruebas tienen como objetivo medir y mejorar la eficiencia y el rendimiento del sistema. A continuación se detallan los aspectos clave de las pruebas de rendimiento:

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
