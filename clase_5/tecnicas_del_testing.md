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

## Técnicas de Caja Blanca y Caja Negra

Las técnicas de caja blanca y caja negra son dos enfoques diferentes utilizados en pruebas de software. A continuación, se presentan sus características principales:

### Caja Blanca

- También conocida como prueba estructural o de caja clara.
- Se basa en el conocimiento interno del sistema y la estructura interna del código.
- Se examina y prueba el código fuente y las estructuras internas, como las funciones y los caminos de ejecución.
- El objetivo es evaluar la calidad del código, la cobertura de las pruebas y la lógica interna.
- Requiere acceso al código fuente y conocimiento técnico detallado.
- Ejemplo: Pruebas de unidad, pruebas de flujo de control.

### Caja Negra

- También conocida como prueba funcional o de caja cerrada.
- Se enfoca en el comportamiento externo del software, sin considerar su implementación interna.
- Se prueba la funcionalidad, las interfaces y los flujos de entrada y salida del sistema.
- El objetivo es evaluar si el software cumple con los requisitos y expectativas del usuario.
- No se requiere conocimiento detallado de la implementación interna.
- Ejemplo: Pruebas de aceptación, pruebas de usabilidad.

### Diferencias

| Técnicas de Caja Blanca | Técnicas de Caja Negra |
|------------------------|-----------------------|
| Se basa en la estructura interna del software | Se basa en el comportamiento externo del software |
| Examina y prueba el código fuente y las estructuras internas | Prueba la funcionalidad, interfaces y flujos de entrada/salida |
| Requiere conocimiento técnico detallado | No requiere conocimiento detallado de la implementación |
| Evalúa la calidad del código y la cobertura de pruebas | Evalúa si el software cumple con los requisitos del usuario |

### Importancia y Alcance

Ambas técnicas son importantes en el proceso de pruebas de software:

- Las pruebas de caja blanca ayudan a identificar problemas en la lógica interna y a mejorar la calidad del código.
- Las pruebas de caja negra validan si el software cumple con los requisitos y expectativas del usuario.

El alcance de las pruebas de caja blanca y caja negra puede variar según los objetivos del proyecto y los recursos disponibles.

### Limitantes

- Las pruebas de caja blanca pueden ser limitadas si no se dispone del acceso al código fuente o si el conocimiento técnico es insuficiente.
- Las pruebas de caja negra pueden no detectar problemas internos del software debido a la falta de visibilidad de la implementación.

<h1 id="enlace-4">Técnicas de Caja Blanca</h1>

## Pruebas de Caja Blanca

Las pruebas de caja blanca son un enfoque de pruebas que se basa en un examen minucioso de los detalles procedimentales y la lógica interna del programa. Se centran en comprobar los caminos lógicos, los bucles, las condiciones y el estado del programa en varios puntos. El objetivo es asegurarse de que todas las sentencias de código sean ejecutadas al menos una vez.

### Tipos de Pruebas de Caja Blanca

1. Pruebas de Sentencia: Se enfocan en probar cada sentencia individual dentro del código para verificar su correcto funcionamiento.

2. Pruebas de Decisión: Se prueban todas las posibles decisiones que pueden ser tomadas en el código, evaluando tanto los caminos verdaderos como los falsos.

3. Pruebas de Condición: Se centran en probar todas las combinaciones posibles de condiciones en el código, verificando cómo afectan al flujo del programa.

4. Pruebas de Condición Múltiple: Se prueban múltiples condiciones combinadas en una sola expresión, con el objetivo de validar el comportamiento del programa en diferentes escenarios.

### Importancia y Beneficios

- Las pruebas de caja blanca ayudan a identificar y corregir errores en la lógica interna del programa.
- Permiten una mayor cobertura de código al asegurarse de que todas las sentencias sean ejecutadas.
- Ayudan a mejorar la calidad y confiabilidad del software.

### Consideraciones Adicionales

- Es necesario tener acceso al código fuente y un conocimiento detallado de su implementación para realizar pruebas de caja blanca.
- Las pruebas de caja blanca son complementarias a otras técnicas de pruebas, como las pruebas de caja negra, para obtener una cobertura más completa.

## Complejidad Ciclomática

La complejidad ciclomática es una métrica utilizada en el campo de la ingeniería de software para medir la complejidad de un programa. Fue propuesta por Thomas J. McCabe en 1976 como una forma de cuantificar el número de caminos lógicos independientes en un código fuente.

### Definición

La complejidad ciclomática se calcula contando el número de regiones linealesmente independientes en un grafo de flujo del programa. Una región independiente representa un conjunto de instrucciones que se ejecutan secuencialmente sin bifurcaciones ni bucles.

### Importancia y Beneficios

- La complejidad ciclomática puede ayudar a identificar partes del código que son difíciles de entender, mantener y probar. Cuanto mayor sea la complejidad ciclomática, mayor será la complejidad del programa.
- Permite detectar áreas potenciales de riesgo y puntos críticos donde se pueden producir errores.
- Proporciona una medida cuantitativa de la complejidad, lo que ayuda en la toma de decisiones relacionadas con la refactorización, optimización y prueba del software.

### Interpretación de los valores

- Se calcula mediante la fórmula CC = A - N + 2, donde A son las aristas (flechas) del grafo o condiciones, y N son los nodos del grafo o sentencias. De acuerdo al resultado de la métrica CC, se asigna una valoración al software en términos de mantenibilidad y facilidad de prueba. Por lo general, se utilizan los siguientes rangos:
    - 1 a 10: Simple de mantener y probar.
    - 11 a 20: Moderado de mantener y probar.
    - 21 a 50: Complejo de probar y difícil de mantener.
    - Mayor a 51: El código es muy riesgoso y debe ser refactorizado.

La complejidad ciclomática es una herramienta importante para identificar áreas de riesgo y evaluar la calidad del código en términos de mantenibilidad y pruebas.

### Ejemplo

```java
public void validateUserAge(int age) {
    if (age >= 18) {
        System.out.println("El usuario es mayor de edad.");
        if (age >= 65) {
            System.out.println("El usuario es elegible para descuentos especiales.");
        }
    } else {
        System.out.println("El usuario es menor de edad.");
    }
} 
```
_En este ejemplo, el cálculo de la complejidad ciclomática utilizando la fórmula CC = A - N + 2 sería: A = 4 (4 condiciones) y N = 4 (4 sentencias). Por lo tanto, CC = 4 - 4 + 2 = 2. El código se consideraría simple de mantener y probar según el rango establecido._


<h2 id="enlace-5">Técnicas de Caja Negra</h2>

<h2 id="enlace-6">¿Qué es calidad?</h2>

<h2 id="enlace-7">¿Qué es calidad?</h2>
