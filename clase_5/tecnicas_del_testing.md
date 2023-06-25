<h1>Técnicas del Testing</h1>
<ol>
<li><a href="#enlace-1">Técnicas de Pruebas</a></li>
<li><a href="#enlace-2">Testing Estático vs Dinámico.</a></li>
<li><a href="#enlace-3">Técnicas de Pruebas</a></li>
<li><a href="#enlace-4">Técnicas de Caja Blanca</a></li>
<li><a href="#enlace-5">Técnicas de Caja Negra</a></li>
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

Considere el siguiente código en lenguaje java:

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

## Pruebas de Sentencia y Cobertura

Las pruebas de sentencia son un tipo de prueba que tiene como objetivo garantizar que cada sentencia en el código sea ejecutada al menos una vez durante la ejecución de las pruebas. Se centra en validar la ejecución correcta de cada instrucción individual del programa.

La cobertura es una métrica utilizada para medir el grado en que el código fuente del programa es ejecutado durante las pruebas. La cobertura de sentencia se refiere al porcentaje de sentencias ejecutadas en relación con el total de sentencias en el código.

El objetivo principal de las pruebas de sentencia y cobertura es identificar y alcanzar una alta cobertura de código para asegurar que todas las instrucciones sean probadas y evitar la presencia de código muerto o no ejecutado.

Existen diferentes niveles de cobertura, entre ellos:

- Cobertura de sentencia (Statement coverage): se asegura de que cada sentencia sea ejecutada al menos una vez.
- Cobertura de decisión (Decision coverage): se asegura de que todas las decisiones lógicas (if, switch, etc.) sean evaluadas en ambas direcciones (verdadero y falso).
- Cobertura de condición (Condition coverage): se asegura de que todas las condiciones en cada decisión lógica sean evaluadas en ambos resultados posibles (verdadero y falso).
- Cobertura de condición múltiple (Multiple condition coverage): se asegura de que todas las combinaciones posibles de condiciones en una decisión lógica sean evaluadas.

El objetivo de estas pruebas es garantizar una mayor confianza en la calidad del software, ya que una alta cobertura de código indica que se ha probado de manera exhaustiva.

### Ejemplo

Considere el siguiente código en lenguaje java:

```java
public class PositiveNumberChecker {
    public static void main(String[] args) {
        int num = 10;
        
        if (num > 0) {
            System.out.println("El número es positivo.");
        } else {
            System.out.println("El número es negativo o cero.");
        }
    }
}
```
_En este ejemplo, se puede aplicar una prueba de sentencia para asegurarse de que ambas sentencias printf sean ejecutadas al menos una vez. También se puede calcular la cobertura de sentencia, que en este caso sería del 100%, ya que todas las sentencias han sido ejecutadas._

## Pruebas de Decisión

Las pruebas de decisión son un tipo de prueba que se enfoca en validar todas las posibles decisiones lógicas dentro de un programa. El objetivo principal es garantizar que todas las decisiones, como las estructuras condicionales (if, switch, etc.), sean evaluadas en ambas direcciones (verdadero y falso).

La cobertura de decisión es una métrica utilizada para medir el grado en que se evalúan todas las decisiones lógicas durante las pruebas. La cobertura de decisión busca asegurar que todas las decisiones sean evaluadas al menos una vez en ambas direcciones.

El alcance de las pruebas de decisión abarca las estructuras condicionales del programa y todas las posibles combinaciones de resultados (verdadero y falso) de cada decisión.

Los objetivos de las pruebas de decisión son:

- Verificar la corrección de las decisiones lógicas dentro del programa.
- Identificar y corregir posibles errores en las condiciones y en la lógica de las decisiones.
- Lograr una alta cobertura de decisión para garantizar que todas las ramas lógicas sean evaluadas adecuadamente.

### Ejemplo

Considera el siguiente código en lenguaje Java:

```java
public class Calculator {
    public int divide(int dividend, int divisor) {
        if (divisor == 0) {
            throw new IllegalArgumentException("Divisor cannot be zero.");
        }
        
        int result = dividend / divisor;
        
        if (result > 10) {
            System.out.println("Result is greater than 10.");
        } else {
            System.out.println("Result is less than or equal to 10.");
        }
        
        return result;
    }
}
```
_En este ejemplo, se pueden realizar pruebas de decisión para evaluar ambas ramas de la condición result > 10 y result <= 10. Además, se puede calcular la cobertura de decisión, que en este caso sería del 100%, ya que todas las decisiones han sido evaluadas en ambas direcciones._

## Pruebas de Condición

Las pruebas de condición son un tipo de prueba que se enfoca en validar las distintas combinaciones de condiciones dentro de una estructura condicional. El objetivo principal es asegurar que todas las posibles combinaciones de condiciones sean evaluadas durante las pruebas.

La cobertura de condición es una métrica utilizada para medir el grado en que se evalúan todas las combinaciones de condiciones durante las pruebas. La cobertura de condición busca asegurar que todas las combinaciones de condiciones sean evaluadas al menos una vez.

El alcance de las pruebas de condición abarca todas las combinaciones de condiciones dentro de una estructura condicional, teniendo en cuenta tanto las condiciones individuales como las combinaciones de múltiples condiciones.

Los objetivos de las pruebas de condición son:

- Verificar la corrección de las condiciones y su interacción dentro de una estructura condicional.
- Identificar y corregir posibles errores en las condiciones y en la lógica de las combinaciones de condiciones.
- Lograr una alta cobertura de condición para garantizar que todas las combinaciones de condiciones sean evaluadas adecuadamente.

### Ejemplo

Considera el siguiente código en lenguaje Java:

```java
public class GradeCalculator {
    public String calculateGrade(int score) {
        String grade;
        
        if (score >= 90) {
            grade = "A";
        } else if (score >= 80) {
            grade = "B";
        } else if (score >= 70) {
            grade = "C";
        } else if (score >= 60) {
            grade = "D";
        } else {
            grade = "F";
        }
        
        return grade;
    }
}
```
_En este ejemplo, se pueden realizar pruebas de condición para evaluar todas las posibles combinaciones de condiciones dentro de la estructura condicional. Se debe garantizar que todas las condiciones individuales y combinaciones sean evaluadas durante las pruebas._

## Pruebas de Condición Múltiple

Las pruebas de condición múltiple, también conocidas como pruebas de decisión múltiple, se utilizan para evaluar el comportamiento del software en diferentes combinaciones de condiciones. Estas pruebas tienen como objetivo asegurar que todas las posibles ramas de decisión se ejecuten correctamente.

**Cobertura:** Las pruebas de condición múltiple tienen como objetivo lograr una cobertura exhaustiva de todas las combinaciones posibles de condiciones. Esto implica evaluar todas las combinaciones de verdadero/falso para cada condición en la decisión múltiple.

**Alcance:** El alcance de las pruebas de condición múltiple se centra en probar todas las combinaciones posibles de condiciones dentro de una estructura de decisión. Esto implica considerar tanto las condiciones independientes como las condiciones dependientes.

**Objetivos:** Los objetivos principales de las pruebas de condición múltiple son:

1. Validar que todas las combinaciones de condiciones se evalúen correctamente.
2. Identificar y corregir posibles errores en la evaluación de las condiciones.
3. Asegurarse de que se cumplan todos los requisitos y reglas de negocio definidos en la estructura de decisión.
4. Mejorar la calidad y confiabilidad del software al garantizar que se cubran todas las ramas de decisión.

**Ejemplo:**

Supongamos que tenemos una función que determina la calificación de un estudiante en base a tres criterios: participación, tareas y exámenes. La calificación final se calcula según la siguiente estructura de decisión:

```java
if (participacion >= 70 && tareas >= 80 && examen >= 60) {
    calificacion = "Aprobado";
} else if (participacion >= 60 && tareas >= 70 && examen >= 50) {
    calificacion = "Aprobado con condicional";
} else {
    calificacion = "Reprobado";
}
```
_Para probar esta estructura de decisión, se deben considerar todas las combinaciones posibles de condiciones. Por ejemplo, se deben probar casos donde todas las condiciones sean verdaderas, casos donde solo algunas condiciones sean verdaderas y casos donde todas las condiciones sean falsas. De esta manera, se garantiza una cobertura exhaustiva y se evalúa el comportamiento del software en cada combinación._

<h1 id="enlace-5">Técnicas de Caja Negra</h1>

## Pruebas de Caja Negra

Las pruebas de Caja Negra son una técnica que se centra en evaluar las entradas y salidas de un sistema sin tener conocimiento de su estructura interna. Estas pruebas se basan en los requerimientos de software y las especificaciones funcionales para determinar las entradas y salidas que deben ser probadas.

**Tipos:**
- **Particiones de Equivalencia:** Esta técnica se basa en dividir el conjunto de posibles valores de entrada en grupos o particiones y probar un valor representativo de cada partición. Esto permite reducir la cantidad de casos de prueba necesarios sin comprometer la cobertura.
- **Análisis de Valores Límites:** Esta técnica se enfoca en probar los límites de las particiones de equivalencia, es decir, los valores extremos y cercanos a los límites. Esto ayuda a identificar posibles errores relacionados con los límites de los valores de entrada.
- **Tabla de Decisiones:** Esta técnica se utiliza cuando el comportamiento del sistema depende de combinaciones específicas de valores de entrada. Se crea una tabla que enumera todas las combinaciones posibles y se prueba cada una de ellas para garantizar que el sistema se comporte correctamente en todas las situaciones.
- **Diagramas de Transición de Estados:** Esta técnica se utiliza para probar sistemas basados en estados, donde el comportamiento del sistema depende de cambios en su estado interno. Se crean diagramas que representan los posibles estados y las transiciones entre ellos, y se prueban las diferentes rutas de transición para asegurar un funcionamiento correcto.

Las pruebas de Caja Negra son importantes porque permiten evaluar el software desde la perspectiva del usuario final y validar que cumpla con los requerimientos y especificaciones funcionales. Al no requerir conocimiento interno del sistema, estas pruebas pueden ser realizadas por personas que no estén familiarizadas con la programación, lo que facilita su ejecución.

Estas técnicas proporcionan un enfoque estructurado para diseñar casos de prueba efectivos y garantizar una buena cobertura de los escenarios de uso más relevantes. Sin embargo, las pruebas de Caja Negra tienen limitaciones, ya que no revelan información detallada sobre posibles errores internos o problemas de rendimiento. Por lo tanto, es recomendable combinarlas con otras técnicas, como las pruebas de Caja Blanca y las pruebas de rendimiento, para obtener una evaluación completa del software.

| Ventajas de las pruebas de Caja Negra | Desventajas de las pruebas de Caja Negra |
|--------------------------------------|----------------------------------------|
| No requieren conocimiento interno del sistema, lo que facilita la ejecución por parte de personal no técnico. | No revelan información detallada sobre posibles errores internos o problemas de rendimiento. |
| Evalúan el software desde la perspectiva del usuario final, validando que cumpla con los requerimientos y especificaciones funcionales. | No permiten una cobertura exhaustiva de todos los caminos y escenarios posibles dentro del software. |
| Ayudan a identificar errores o discrepancias entre la implementación y los requerimientos establecidos. | Pueden pasar por alto errores relacionados con la lógica interna del software o con situaciones excepcionales no previstas. |
| Permiten una mayor independencia entre el equipo de pruebas y el equipo de desarrollo, lo que fomenta la detección de problemas desde una perspectiva externa. | No brindan información directa sobre la estructura interna del software o su calidad de código. |
| Son efectivas para verificar la funcionalidad y usabilidad del software, así como para detectar problemas de integración con otros sistemas. | Dependen en gran medida de la calidad de los requerimientos y especificaciones proporcionados. |

## Pruebas de Particiones de Equivalencia

Las pruebas de particiones de equivalencia son una técnica de prueba de caja negra que se centra en dividir el conjunto de datos de entrada en grupos o particiones y seleccionar un conjunto representativo de datos de cada partición para probar. 

Las pruebas de particiones de equivalencia se basan en la idea de que, si un caso de prueba dentro de una partición es válido, se espera que todos los demás casos de prueba en la misma partición también sean válidos. Por lo tanto, en lugar de probar todos los valores posibles, se prueban representantes de cada partición.

- **Cobertura**: Las pruebas de particiones de equivalencia tienen como objetivo cubrir diferentes grupos o particiones de datos de entrada. Se espera que se prueben casos de prueba que representen cada partición, lo que ayuda a reducir la redundancia de las pruebas y aumenta la cobertura.

- **Alcance**: Las pruebas de particiones de equivalencia se centran en las entradas válidas y no válidas, dividiendo el conjunto de datos de entrada en particiones. El alcance incluye identificar las particiones, seleccionar casos de prueba representativos de cada partición y ejecutar los casos de prueba correspondientes.

- **Objetivos**: Los objetivos de las pruebas de particiones de equivalencia son:
   - Identificar casos de prueba efectivos y representativos que cubran diferentes rangos de valores de entrada.
   - Reducir la redundancia de las pruebas al seleccionar solo un caso de prueba por partición.
   - Aumentar la cobertura de pruebas al abordar las diferentes condiciones lógicas y comportamientos esperados en cada partición.

- **Ejemplos**:
   1. Prueba de una aplicación de registro de usuarios:
      - Partición 1: Edades válidas (18-60 años).
      - Partición 2: Edades no válidas (<18 años y >60 años).
      Ejemplo de caso de prueba: Ingresar una edad válida (25 años).
   
   2. Prueba de una función de cálculo de descuento:
      - Partición 1: Montos válidos (100-1000 dólares).
      - Partición 2: Montos no válidos (<100 dólares y >1000 dólares).
      Ejemplo de caso de prueba: Ingresar un monto válido (500 dólares).
   
   3. Prueba de un formulario de registro con campos obligatorios:
      - Partición 1: Campos obligatorios completos.
      - Partición 2: Campos obligatorios faltantes.
      Ejemplo de caso de prueba: Completar todos los campos obligatorios correctamente.

### Pasos para realizar pruebas de particiones de equivalencia

1. **Identificar las clases**: Analiza las especificaciones y los requisitos del software para identificar las clases o particiones de equivalencia. Una clase de equivalencia representa un conjunto de datos de entrada que deberían producir resultados similares o comportamientos equivalentes en el software.

2. **Definir los límites de cada clase**: Determina los límites o rangos de valores para cada clase de equivalencia. Estos límites ayudarán a definir los casos de prueba para cada partición.

3. **Seleccionar casos de prueba válidos**: Elije al menos un caso de prueba representativo para cada clase de equivalencia válida. Estos casos de prueba deben cubrir el rango completo de valores dentro de cada clase.

4. **Seleccionar casos de prueba no válidos**: Selecciona casos de prueba que estén fuera de los límites definidos para cada clase de equivalencia. Estos casos de prueba deben verificar cómo el software maneja los datos de entrada no válidos.

5. **Ejecutar los casos de prueba**: Ejecuta los casos de prueba seleccionados y registra los resultados. Comprueba si el software produce los resultados esperados para cada clase de equivalencia.

6. **Evaluar la cobertura**: Verifica si los casos de prueba seleccionados cubren todas las clases de equivalencia definidas. Asegúrate de que no haya clases de equivalencia sin casos de prueba asociados.

7. **Ajustar y mejorar los casos de prueba**: Revisa los resultados de las pruebas y realiza ajustes en los casos de prueba si es necesario. Asegúrate de que los casos de prueba sean representativos y efectivos para cada partición.

_Estos pasos son una guía general y se pueden adaptar según el contexto y los requisitos del software a probar. Además, es recomendable documentar los pasos seguidos y los resultados obtenidos para futuras referencias._

## Pruebas de Análisis de Valores Límites

Las pruebas de análisis de valores límites son una técnica de prueba que se enfoca en los valores extremos y límites de las particiones de entrada. Su objetivo principal es encontrar errores que puedan ocurrir en los bordes o límites de los rangos de valores. Estas pruebas se centran en los valores mínimos y máximos permitidos, así como en los valores justo dentro y justo fuera de los límites.

**Cobertura:** Las pruebas de análisis de valores límites ofrecen una cobertura efectiva de los casos extremos y límites, lo que ayuda a identificar errores que podrían pasar desapercibidos con otras técnicas de prueba.

**Alcance:** Estas pruebas se centran en los rangos de valores y límites especificados en los requisitos del software. Se pueden aplicar a diferentes tipos de datos, como números, fechas, horas, cadenas de texto, etc.

**Objetivos:**
- Identificar errores que puedan ocurrir en los límites del rango de valores permitidos.
- Verificar el comportamiento del software ante valores mínimos y máximos.
- Comprobar cómo el software maneja los valores justo dentro y justo fuera de los límites especificados.

**Cómo se hacen:**
1. Identificar los rangos de valores: Analiza los requisitos y especificaciones del software para identificar los límites mínimos y máximos de los rangos de valores relevantes.

2. Definir los valores límite: Determina los valores límite para cada rango identificado. Estos valores serán los puntos de prueba clave.

3. Seleccionar casos de prueba: Elige casos de prueba que cubran los valores límite y los valores justo dentro y justo fuera de los límites. Es importante asegurarse de tener al menos un caso de prueba para cada límite.

**Ejemplos:**

1. Prueba de edad mínima:
   - Rango de valores: 18 - 65 años.
   - Valores límite: 18 (edad mínima permitida) y 65 (edad máxima permitida).
   - Casos de prueba: 17 (valor justo fuera del límite inferior), 18 (valor en el límite inferior), 25 (valor dentro del rango), 65 (valor en el límite superior), 66 (valor justo fuera del límite superior).

2. Prueba de longitud de contraseña:
   - Rango de valores: 8 - 20 caracteres.
   - Valores límite: 8 (longitud mínima permitida) y 20 (longitud máxima permitida).
   - Casos de prueba: "pass" (valor justo fuera del límite inferior), "password" (valor en el límite inferior), "secretpassword" (valor dentro del rango), "verylongpassword" (valor en el límite superior), "extralongpassword" (valor justo fuera del límite superior).

3. Prueba de valor de stock:
   - Rango de valores: 0 - 1000 unidades.
   - Valores límite: 0 (valor mínimo permitido) y 1000 (valor máximo permitido).
   - Casos de prueba: -1 (valor justo fuera del límite inferior), 0 (valor en el límite inferior), 500 (valor dentro del rango), 1000 (valor en el límite superior), 1001 (valor justo fuera del límite superior).

_Es importante resaltar que las pruebas de análisis de valores límites son una técnica complementaria a otras técnicas de prueba y no deben ser utilizadas como único enfoque de prueba._

## Análisis de Valores Límites: Clases Inválidas

En las pruebas de análisis de valores límites, además de probar las clases válidas, es importante también probar las clases inválidas. Estas clases inválidas incluyen el ingreso de valores de otro tipo en lugar del tipo esperado. Algunos ejemplos de clases inválidas son:

- Ingreso de valores numéricos en lugar de valores alfabéticos.
- Ingreso de valores alfabéticos en lugar de valores numéricos.
- Combinaciones de valores alfabéticos y numéricos.
- Fechas erróneas u otros formatos incorrectos.
- Y otros casos similares.

En algunos casos, la combinación de los datos de entrada puede determinar si una clase es válida o inválida. Por ejemplo:

- Si el estado civil no es "casado", los datos del cónyuge deben ser ignorados.
- El número de CUIT debe incluir el número de documento.
- El pago se realiza con tarjeta de crédito y en cuotas.

Es importante agregar condiciones "cruzadas" que se definen en la estructura del modelo de datos y que deben ser probadas. Por ejemplo, si un cliente tiene una factura impaga y realiza un segundo pedido.

Estas pruebas ayudan a identificar posibles errores en las validaciones y reglas de negocio del sistema.

_El objetivo de las pruebas de análisis de valores límites es verificar el comportamiento del sistema frente a diferentes escenarios de entrada, tanto válidos como inválidos, y asegurarse de que el software maneje correctamente todas las situaciones._

## Diseño de Casos de Prueba

Una vez que se han identificado las condiciones que se desean probar utilizando las técnicas de Partición de Equivalencias y Análisis de Valores Límites, el siguiente paso es diseñar los casos de prueba.

#### Cantidad de Casos de Prueba
La cantidad de casos de prueba puede variar dependiendo de varios factores, como la complejidad del sistema, la criticidad de las condiciones a probar y los recursos disponibles. No existe un número fijo de casos de prueba, pero se recomienda cubrir un conjunto representativo de casos para obtener una buena cobertura de las condiciones y escenarios relevantes.

#### Objetivos
Los objetivos de diseñar casos de prueba son:
- Verificar que el software cumpla con los requisitos y especificaciones establecidos.
- Detectar posibles errores o defectos en el sistema.
- Evaluar la robustez y la capacidad de respuesta del software ante diferentes condiciones de entrada.
- Asegurar la calidad y confiabilidad del software.

#### Alcance
El alcance del diseño de casos de prueba se centra en las condiciones identificadas previamente utilizando las técnicas de Partición de Equivalencias y Análisis de Valores Límites. Se deben diseñar casos de prueba que cubran todas las clases de equivalencia y los valores límites relevantes para cada condición.

#### Limitantes
Algunos limitantes a considerar en el diseño de casos de prueba son:
- Limitaciones de tiempo y recursos disponibles para realizar las pruebas.
- Complejidad del sistema y de las condiciones a probar.
- Posibilidad de no cubrir todas las combinaciones posibles debido a limitaciones prácticas.

_El diseño de casos de prueba es una actividad importante para garantizar la calidad del software y se debe realizar de manera cuidadosa y exhaustiva, teniendo en cuenta las condiciones identificadas y los objetivos establecidos._

## Tabla de Decisiones

La Tabla de Decisiones es una técnica que se utiliza cuando diferentes combinaciones de entradas resultan en diferentes acciones o resultados esperados. Se enfoca en las reglas de negocios y también se conoce como Tabla o Diagrama Causa-Efecto.

Es un enfoque sistemático para seleccionar conjuntos de casos de prueba que exploran combinaciones en las condiciones de entrada, con el objetivo de obtener un alto rendimiento en las pruebas. Es especialmente útil para la especificación funcional del software, aunque puede ser difícil de implementar.

Los pasos para derivar los casos de prueba utilizando esta técnica son los siguientes:

1. Descomponer la especificación en partes funcionales.
2. Identificar las causas y sus efectos.
3. Crear grafos de causa-efecto, representando las relaciones entre las causas y los efectos.
4. Registrar las restricciones, describiendo combinaciones de causas y/o efectos imposibles.
5. Convertir el grafo en una tabla de decisiones de entrada limitada, trazando las condiciones de estado en el grafo. Cada columna en la tabla representa un caso de prueba.

La tabla de decisiones es una herramienta efectiva para diseñar conjuntos de casos de prueba que cubran diversas combinaciones de condiciones de entrada y ayuden a verificar el cumplimiento de las reglas de negocio.

## Diagrama de Transición de Estados

El Diagrama de Transición de Estados es una técnica de prueba que utiliza un modelo para describir los diferentes estados de un sistema y las transiciones entre ellos, basadas en reglas específicas. Está especialmente enfocado en aspectos funcionales del sistema.

El diagrama consta de cuatro partes principales:

1. **Estados**: Representan las condiciones o situaciones en las que puede encontrarse el sistema durante su ejecución.

2. **Transiciones**: Son los cambios de estado que ocurren en el sistema en respuesta a eventos específicos.

3. **Eventos**: Son las acciones o sucesos que desencadenan las transiciones de un estado a otro.

4. **Acciones**: Representan las operaciones o tareas que se realizan como resultado de una transición de estado.

Esta técnica permite identificar los diferentes escenarios posibles dentro del sistema y diseñar casos de prueba que cubran las distintas combinaciones de estados y transiciones, validando así el comportamiento del software.

_El Diagrama de Transición de Estados se centra en el flujo lógico del sistema y en cómo responde a los eventos específicos. Es especialmente útil para probar la lógica de negocio y asegurar que los estados y transiciones se comporten correctamente._

### Ejemplo de Diagrama de Transición de Estados

A continuación se presenta un ejemplo simplificado de un diagrama de transición de estados para un sistema de reproducción de música:

**Estados:**
- Estado Inicial: El sistema está en espera.
- Estado Reproduciendo: El sistema está reproduciendo una canción.
- Estado Pausado: La reproducción se encuentra en pausa.
- Estado Detenido: La reproducción se ha detenido.

**Transiciones:**
- Play: Permite pasar del estado Inicial al estado Reproduciendo.
- Pause: Transición del estado Reproduciendo al estado Pausado.
- Stop: Permite volver al estado Inicial desde los estados Reproduciendo y Pausado.

**Eventos y Acciones:**
- Play:
  - Evento: Se presiona el botón de reproducción.
  - Acción: Inicia la reproducción de la canción.
- Pause:
  - Evento: Se presiona el botón de pausa.
  - Acción: Pausa la reproducción actual.
- Stop:
  - Evento: Se presiona el botón de detener.
  - Acción: Detiene la reproducción y regresa al estado Inicial.

En este ejemplo, el diagrama muestra cómo el sistema de reproducción de música cambia de estado en respuesta a eventos específicos, como presionar los botones de reproducción, pausa y detener. Los estados y las transiciones definen el flujo de ejecución del sistema y las acciones que ocurren en cada transición.
