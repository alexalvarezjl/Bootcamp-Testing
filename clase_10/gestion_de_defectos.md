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


