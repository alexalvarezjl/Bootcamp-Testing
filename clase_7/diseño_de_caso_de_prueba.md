# Diseño de Casos de Prueba

## Tipos de Pruebas

### Funcionales

- Funciones de Negeocio
- Interfaz de Usuario

### No Funcionales

- Performance / Rendimiento
- Seguridad
- Estres
- Volumen
- Instalación
- Usabilidad

## Funciones de Negocio

Los casos de prueba para funciones de negocio se enfocan en verificar que el software provea los servicios esperados relacionados con las funciones de negocio. Estos casos de prueba demuestran que la aplicación cumple con los requerimientos del usuario y pueden abarcar tanto escenarios positivos como negativos.

La motivación detrás del diseño de estos casos de prueba es demostrar que el software puede resistir pruebas con datos válidos e inválidos, es decir, se pone a prueba la capacidad del software para manejar diferentes escenarios y situaciones.

### Puntos a tener en cuenta en el Diseño de Casos de Pruebas de Funciones de Negocio

Al diseñar casos de prueba para funciones de negocio, es importante considerar los siguientes puntos:

1. Conocer los distintos escenarios: Es necesario identificar y comprender los diferentes escenarios o situaciones que pueden surgir en relación con las funciones de negocio. Esto incluye conocer los datos permitidos, el flujo de la información permitida, las excepciones que pueden surgir, los perfiles de usuario involucrados, la tecnología utilizada y el nivel de la aplicación.

2. Crear tests considerando aspectos como el reuso: Se deben diseñar los casos de prueba de manera que puedan ser reutilizados en diferentes situaciones. Esto ayuda a ahorrar tiempo y esfuerzo al no tener que crear nuevos casos de prueba desde cero para escenarios similares.

3. Rapidez de ejecución: Los casos de prueba deben ser diseñados de manera que su ejecución sea rápida y eficiente. Esto es especialmente importante cuando se tienen grandes conjuntos de pruebas que se ejecutan de manera regular.

4. Fácil mantenimiento: Los casos de prueba deben ser diseñados de manera que su mantenimiento sea sencillo. Esto implica utilizar una estructura clara y comprensible, y mantener una buena documentación de los casos de prueba.

5. Integridad: Los casos de prueba deben cubrir todas las funcionalidades críticas y escenarios importantes relacionados con las funciones de negocio. Se deben considerar todas las situaciones relevantes para garantizar la integridad del software.

6. Claridad en los tipos de test abarcados: Es importante asegurarse de que los casos de prueba diseñados cubran los diferentes tipos de pruebas necesarios para validar las funciones de negocio. Esto puede incluir pruebas de aceptación, pruebas de regresión, pruebas de integración, entre otras.

El diseño de casos de prueba para funciones de negocio requiere un buen entendimiento de las necesidades del negocio, así como de los requerimientos y especificaciones del software. Esto ayuda a garantizar que las pruebas cubran adecuadamente las funcionalidades y escenarios críticos del sistema.

## Interfaz de Usuario

Las pruebas de interfaz de usuario se centran en el diseño y la validación de la interacción entre el usuario y la aplicación, así como en la apariencia visual de la interfaz. El objetivo principal de un buen diseño de GUI (interfaz gráfica de usuario) es brindar una experiencia agradable al usuario y garantizar que la aplicación sea fácil de usar.

Un buen diseño de GUI tiene dos componentes principales: interacción y apariencia. La interacción se refiere a cómo el usuario interactúa con la aplicación, incluyendo la navegación, la entrada de datos y la respuesta del sistema. La apariencia se refiere al aspecto visual de la interfaz, como el diseño, los colores, los íconos y las etiquetas.

### Puntos a tener en cuenta en el Diseño de Casos de Pruebas de Interfaces de Usuario

Al diseñar casos de prueba para las interfaces de usuario, es importante considerar los siguientes puntos:

1. Identificar los componentes de la aplicación: Es necesario identificar y comprender los diferentes componentes de la interfaz de usuario, como la ventana principal, las ventanas emergentes, el menú, las cajas de texto, las etiquetas, los íconos y los controles. Cada uno de estos componentes puede requerir pruebas específicas para garantizar su correcto funcionamiento.

2. Identificar lo permitido: Se deben identificar y probar las funcionalidades y características permitidas en la interfaz de usuario. Esto incluye la ubicación de la ventana principal, la capacidad de cambio de tamaño, el estado habilitado o deshabilitado de los controles, la navegación entre elementos, el uso de teclas de acceso rápido, el uso del botón derecho del mouse, el estilo y tamaño de las etiquetas, el acceso al menú, el doble clic y la información precargada en los controles desplegables, entre otros aspectos.

3. Identificar las transacciones permitidas: Es importante determinar y probar las diferentes transacciones que se pueden realizar a través de la interfaz de usuario, como agregar, consultar/buscar, eliminar, modificar y ordenar datos. Cada una de estas transacciones puede requerir pruebas específicas para asegurarse de que funcionen correctamente.

4. Crear tests considerando aspectos como el reuso: Se deben diseñar los casos de prueba de manera que puedan ser reutilizados en diferentes situaciones y escenarios de prueba. Esto ayuda a ahorrar tiempo y esfuerzo al no tener que crear nuevos casos de prueba desde cero para cada caso específico.

5. Rapidez de ejecución y fácil mantenimiento: Los casos de prueba deben ser diseñados de manera que su ejecución sea rápida y eficiente, y que su mantenimiento sea sencillo. Esto implica utilizar una estructura clara y comprensible, y mantener una buena documentación de los casos de prueba.

6. Integridad y claridad en los tipos de test abarcados: Los casos de prueba deben garantizar la cobertura adecuada de los diferentes tipos de pruebas necesarios para validar la interfaz de usuario. Esto puede incluir pruebas de usabilidad, pruebas de navegación, pruebas de ingreso de datos, pruebas de respuesta del sistema, entre otras.

El diseño de casos de prueba para las interfaces de usuario es fundamental para garantizar una experiencia de usuario satisfactoria y asegurar el correcto funcionamiento de la aplicación en términos de interacción y apariencia visual.

## Pruebas de Rendimiento (Performance)

Las pruebas de rendimiento se centran en verificar y validar los requisitos de rendimiento de un sistema o aplicación. Estas pruebas se diseñan para evaluar cómo el sistema se comporta y responde bajo diferentes cargas y situaciones de uso.

Al diseñar casos de prueba de rendimiento, es importante considerar los siguientes puntos:

1. Debe analizar qué se desea medir: Es necesario identificar y definir los aspectos específicos del rendimiento que se desean medir en el sistema. Esto puede incluir el uso del CPU, el uso de las entradas y salidas (IO), el número de IO por instrucción, el uso de la memoria principal y secundaria de almacenamiento, el tiempo de ejecución por módulo, el tiempo de espera entre operaciones, el tiempo de respuesta del sistema y el número de transacciones por unidad de tiempo.

2. Combinación de Caja Blanca y Caja Negra: Para diseñar pruebas de rendimiento efectivas, se requiere un enfoque que combine el conocimiento interno del sistema (Caja Blanca) con la evaluación del comportamiento externo del sistema (Caja Negra). Esto significa que es necesario entender cómo funciona internamente el sistema para identificar las áreas críticas y los cuellos de botella que pueden afectar el rendimiento.

3. Establecer escenarios de carga realistas: Es importante diseñar casos de prueba que simulen cargas de trabajo realistas y representativas del entorno de producción. Esto implica definir el número de usuarios concurrentes, los tipos de transacciones que se realizarán y los patrones de uso esperados. Estos escenarios de carga deben ser diseñados para poner a prueba el rendimiento del sistema en condiciones extremas y determinar si cumple con los requisitos establecidos.

4. Medición y monitoreo: Durante las pruebas de rendimiento, es fundamental medir y monitorear los diferentes aspectos del rendimiento del sistema en tiempo real. Esto se puede lograr utilizando herramientas especializadas que recopilen métricas relevantes, como el tiempo de respuesta, la utilización del CPU, la memoria y otros recursos. Estas mediciones permiten identificar cualquier degradación del rendimiento y ayudan a optimizar y ajustar el sistema en consecuencia.

5. Análisis de resultados: Una vez que se han ejecutado las pruebas de rendimiento, es necesario realizar un análisis exhaustivo de los resultados. Esto implica comparar los datos medidos con los criterios de rendimiento establecidos en los requisitos y determinar si se cumplen o no. Además, se deben identificar las posibles causas de cualquier problema de rendimiento y proponer soluciones o mejoras para abordarlos.

El diseño de casos de prueba de rendimiento es fundamental para garantizar que un sistema o aplicación pueda manejar las cargas de trabajo esperadas y cumpla con los requisitos de rendimiento establecidos. Estas pruebas ayudan a identificar y resolver problemas relacionados con el rendimiento antes de que el sistema se implemente en un entorno de producción.

## Pruebas de Seguridad

El diseño de pruebas de seguridad tiene como objetivo evaluar la presencia y la adecuada funcionalidad de las medidas de seguridad implementadas en una aplicación, con el fin de asegurar la integridad y confidencialidad de los datos.

Al diseñar casos de prueba de seguridad, es importante tener en cuenta los siguientes puntos:

1. Considerar los permisos de acceso: Se deben diseñar casos de prueba que verifiquen que los usuarios tienen los permisos adecuados para acceder a diferentes partes de la aplicación y a los datos correspondientes. Esto implica probar diferentes niveles de acceso y verificar que los controles de seguridad funcionen correctamente.

2. Evaluar la autorización: Los casos de prueba deben incluir escenarios que evalúen la autorización de usuarios y roles en la aplicación. Se deben verificar que los usuarios solo puedan acceder a las funciones y los datos para los cuales tienen los permisos correspondientes.

3. Probar la autenticación: Es fundamental diseñar pruebas que evalúen los mecanismos de autenticación implementados en la aplicación. Esto implica probar diferentes tipos de credenciales, como nombre de usuario y contraseña, autenticación de dos factores, autenticación biométrica, entre otros, para garantizar que solo los usuarios autorizados puedan acceder al sistema.

4. Verificar la encriptación: Se deben diseñar casos de prueba que evalúen la encriptación de los datos sensibles en la aplicación. Esto implica verificar que los datos se almacenen y transmitan de forma segura, utilizando algoritmos de encriptación adecuados y comprobando que los datos encriptados sean correctos y se puedan desencriptar correctamente.

5. Evaluar el tipo de sesiones: Los casos de prueba deben abordar los diferentes tipos de sesiones que se pueden establecer en la aplicación, como sesiones de usuario, sesiones de administrador, sesiones persistentes, entre otras. Se deben verificar que las sesiones se manejen correctamente y que se cierren de forma segura al finalizar la interacción del usuario con la aplicación.

6. Probar la conectividad y los protocolos: Es importante evaluar la seguridad de las comunicaciones en la aplicación. Esto implica probar los diferentes protocolos utilizados (como HTTPS, SSH, etc.) y verificar que se establezcan conexiones seguras y que los datos se transmitan de forma cifrada y protegida.

7. Considerar la auditoría: Los casos de prueba deben abordar la funcionalidad de auditoría, que registra y monitorea las actividades realizadas en la aplicación. Se deben verificar que los eventos relevantes se registren correctamente y que la información de auditoría esté disponible para su revisión y análisis.

El diseño de casos de prueba de seguridad es esencial para evaluar la robustez y efectividad de las medidas de seguridad implementadas en una aplicación. Estas pruebas ayudan a identificar posibles vulnerabilidades y riesgos de seguridad, permitiendo que se tomen medidas correctivas para garantizar la protección de los datos y la integridad del sistema.

### Puntos a tener en cuenta en el Diseño de Test Cases de Seguridad:

Al diseñar casos de prueba de seguridad, es importante considerar los siguientes puntos:

1. Preguntas Típicas: Las siguientes preguntas pueden guiar el diseño de los casos de prueba de seguridad:

   - ¿Los errores son registrados y capturados? Se deben probar escenarios donde se generen errores y verificar que sean registrados y capturados adecuadamente, evitando revelar información sensible al usuario.
   - ¿Es posible loguearse sin contraseña? Se debe probar el proceso de inicio de sesión para asegurarse de que se requiera una contraseña válida para acceder al sistema.
   - ¿Hay usuarios que tienen superpoderes? Se deben evaluar los diferentes roles de usuario y asegurarse de que los permisos estén asignados correctamente, evitando que usuarios no autorizados tengan acceso a funciones o datos sensibles.
   - ¿Se validan los password y están encriptados? Se deben diseñar pruebas para verificar que los passwords sean validados correctamente y que se almacenen en forma encriptada en el sistema, protegiendo la información confidencial.
   - ¿Cuál es el comportamiento del sistema al loguearse repetidas veces mal? Se deben probar escenarios donde se ingresen contraseñas incorrectas repetidamente y evaluar cómo responde el sistema, por ejemplo, bloqueando la cuenta después de varios intentos fallidos para prevenir ataques de fuerza bruta.
   - ¿Cuál es el comportamiento del sistema al acceder de forma remota? Se deben diseñar pruebas para evaluar la seguridad de las conexiones remotas al sistema, verificando que se establezcan conexiones seguras y que se utilicen protocolos de comunicación adecuados para proteger la integridad de los datos.


## Pruebas de Volumen:

El diseño de casos de prueba de volumen tiene como objetivo evaluar la capacidad del sistema para manejar un volumen específico de datos. A continuación, se presentan los puntos a considerar en el diseño de estos casos de prueba:

1. Conocer los datos: Es importante tener un entendimiento claro de los datos que serán ingresados en cada transacción. Esto incluye el tipo de datos, su estructura y la forma en que interactúan con el sistema. Conocer los datos permite diseñar pruebas que cubran diferentes escenarios y volumen de datos.

Además de estos puntos, es recomendable considerar otros aspectos relacionados con el volumen de datos, como la capacidad de almacenamiento, el rendimiento del sistema y la escalabilidad. Estos aspectos pueden influir en el diseño de los casos de prueba y ayudar a evaluar la capacidad del sistema para manejar grandes volúmenes de datos.

El objetivo principal de los casos de prueba de volumen es demostrar que el sistema puede manejar eficientemente el volumen de datos específico para el cual fue diseñado. Estas pruebas son diferentes de las pruebas de estrés, que se centran en evaluar la carga del sistema a través de cortos períodos de tiempo y bajo condiciones extremas.

Al diseñar casos de prueba de volumen, es fundamental tener en cuenta los puntos mencionados y adaptar los casos de prueba según los requisitos y características específicas del sistema que se está probando.


## Pruebas de Estrés:

El diseño de casos de prueba de estrés tiene como objetivo investigar el comportamiento del sistema bajo condiciones de sobrecarga. El enfoque principal es evaluar el impacto en los tiempos de procesamiento y la capacidad del sistema para manejar cargas extremas. A continuación, se presentan los puntos a considerar en el diseño de estos casos de prueba:

1. Conocer el número máximo de terminales: Es importante determinar si se conoce el número máximo de terminales que utilizarán el sistema o si está especificado dentro de los requerimientos. Esto permitirá diseñar pruebas que simulen una carga realista y evalúen el rendimiento del sistema en condiciones de máxima capacidad.

2. Medir diferentes aspectos bajo sobrecarga: Durante las pruebas de estrés, es necesario medir y evaluar varios aspectos del sistema, como el rendimiento del buffer, el consumo de memoria, el rendimiento de la conexión en red, el funcionamiento de las impresoras y el uso general del sistema. Estos aspectos ayudarán a identificar posibles cuellos de botella y evaluar el impacto de la sobrecarga en el rendimiento del sistema.

3. Ejecutar múltiples tareas de un simple requerimiento: Es recomendable diseñar casos de prueba que simulen la ejecución simultánea de múltiples tareas relacionadas con un mismo requerimiento. Esto permitirá evaluar cómo el sistema responde cuando se enfrenta a una carga intensa y cómo afecta a los tiempos de procesamiento.

4. Conocer los efectos esperados: Es importante tener claridad sobre los efectos correctos o esperados al ejecutar pruebas de estrés. Esto implica comprender cómo se espera que el sistema se comporte bajo condiciones de sobrecarga y qué resultados se consideran aceptables o deseables.

5. Ejecutar pruebas de estrés repetidamente: Para obtener resultados más confiables y representativos, se recomienda ejecutar las pruebas de estrés de manera repetida. Esto ayudará a identificar patrones de comportamiento, evaluar la estabilidad del sistema bajo cargas extremas y realizar análisis comparativos.

El diseño de casos de prueba de estrés requiere un enfoque cuidadoso para simular condiciones de sobrecarga realistas y evaluar el rendimiento del sistema en situaciones extremas. Considerar estos puntos ayudará a diseñar pruebas efectivas que revelen posibles problemas de rendimiento y permitan tomar medidas correctivas.


## Pruebas de Usabilidad:

El diseño de casos de prueba de usabilidad tiene como objetivo determinar qué tan bien el usuario puede usar y entender la aplicación. Para lograr esto, es importante considerar los siguientes puntos al diseñar los casos de prueba:

1. Funciones o instrucciones complejas: Verificar si existen funciones o instrucciones excesivamente complejas que puedan dificultar la comprensión y el uso de la aplicación por parte del usuario. Se deben diseñar casos de prueba que evalúen la facilidad de uso y la comprensión de las diferentes funcionalidades.

2. Procedimiento de instalación: Evaluar el grado de dificultad del procedimiento de instalación de la aplicación. Diseñar casos de prueba que aborden aspectos como la claridad de las instrucciones, la facilidad de navegación durante la instalación y la capacidad del usuario para completar el proceso sin dificultades.

3. Mensajes de error: Evaluar el grado de complejidad de los mensajes de error y su capacidad para proporcionar información clara y útil al usuario. Diseñar casos de prueba que verifiquen la legibilidad, la comprensión y la acción recomendada en caso de errores.

4. Estandarización de la interfaz de usuario (GUI): Evaluar si la interfaz de usuario sigue estándares de usabilidad comunes y coherentes. Diseñar casos de prueba que evalúen la consistencia en el diseño, la disposición intuitiva de los elementos y la facilidad de navegación.

5. Procedimiento de inicio de sesión: Evaluar la facilidad y la claridad del procedimiento de inicio de sesión en la aplicación. Diseñar casos de prueba que verifiquen la usabilidad del proceso de autenticación, incluyendo la claridad de las instrucciones, la facilidad de ingreso de credenciales y la retroalimentación al usuario.

6. Ayuda y documentación: Evaluar si la ayuda proporcionada en la aplicación es sensible al contexto y brinda el detalle suficiente para guiar al usuario. Diseñar casos de prueba que evalúen la disponibilidad y la eficacia de la ayuda contextual, así como la calidad de la documentación proporcionada.

7. Claridad de los valores predeterminados: Evaluar la claridad y la adecuación de los valores predeterminados en la aplicación. Diseñar casos de prueba que verifiquen si los valores predeterminados son comprensibles y apropiados para el usuario, y si se brinda la opción de cambiarlos fácilmente si es necesario.

El diseño de casos de prueba de usabilidad requiere un enfoque centrado en el usuario y la evaluación de su experiencia al interactuar con la aplicación. Considerar estos puntos ayudará a diseñar pruebas que revelen posibles problemas de usabilidad y permitan realizar mejoras para ofrecer una experiencia más satisfactoria al usuario.


## Pruebas de Instalación:

El diseño de casos de prueba de instalación tiene como objetivo verificar la habilidad de instalar el sistema correctamente. Es importante considerar los siguientes puntos al diseñar los casos de prueba:

1. Usuario objetivo: Identificar quién es el usuario objetivo del procedimiento de instalación. Esto puede ser un técnico especializado, un usuario aficionado o un usuario inexperto. Diseñar casos de prueba que evalúen la facilidad de comprensión y ejecución del procedimiento de instalación para el usuario objetivo.

2. Ambientes compatibles: Determinar los ambientes o entornos en los que el procedimiento de instalación debe ser compatible. Esto puede incluir diferentes plataformas, versiones de software, hardware, redes, etc. Diseñar casos de prueba que verifiquen la instalación en diferentes ambientes y aseguren la compatibilidad requerida.

3. Cambios en el ambiente actual: Evaluar si la instalación del sistema va a modificar o afectar el ambiente actual del usuario. Por ejemplo, si se requiere modificar el archivo de configuración del sistema (config.sys) u otros archivos de configuración. Diseñar casos de prueba que evalúen la instalación en diferentes configuraciones y aseguren que no se produzcan conflictos o problemas en el ambiente existente.

4. Interacción con el usuario: Determinar si la instalación es automática o si requiere interacción con el usuario. En el caso de interacción, es importante evaluar la claridad y la facilidad de comprensión de las instrucciones proporcionadas durante el proceso de instalación. Diseñar casos de prueba que evalúen la interacción con el usuario y verifiquen la efectividad del proceso de instalación.

El diseño de casos de prueba de instalación debe garantizar que el procedimiento de instalación sea claro, consistente y fácil de seguir para el usuario. Esto incluye evaluar la documentación proporcionada, las instrucciones paso a paso, la compatibilidad con diferentes entornos y la interacción con el usuario.

Recuerda adaptar el diseño de los casos de prueba de instalación a las características específicas del sistema que se está instalando y a las necesidades del usuario objetivo.
