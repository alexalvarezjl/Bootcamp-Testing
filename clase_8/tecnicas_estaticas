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

