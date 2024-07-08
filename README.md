**Patrón Creacional: Factory Method**
**Propósito del patrón:**
El patrón Factory Method proporciona una interfaz para crear objetos en una superclase, pero permite a las subclases alterar el tipo de objetos que se crearán. Esto promueve el principio de diseño "abrir para extender, cerrado para modificar".

**Situaciones útiles para aplicar este patrón:**
Es útil cuando se necesita delegar la creación de objetos a subclases, dependiendo de ciertas condiciones o contextos durante la ejecución del programa. Esto facilita la adición de nuevas clases de productos sin modificar el código existente que utiliza la interfaz común.



**Patrón Estructural: Decorator**
**Propósito del patrón:**
El patrón Decorator permite agregar comportamiento a objetos individuales de manera dinámica y transparente, sin afectar a otros objetos de la misma clase. Esto es útil para extender funcionalidades de forma flexible y sin necesidad de crear subclases excesivas.

**Situaciones útiles para aplicar este patrón:**
Es útil cuando se necesita añadir funcionalidades a objetos existentes de manera dinámica y en tiempo de ejecución, sin modificar su estructura. Por ejemplo, añadir funcionalidades de encriptación a un flujo de datos sin afectar la lógica de los datos mismos.



**Patrón de Comportamiento: Observer**
**Propósito del patrón:**
El patrón Observer establece una relación uno-a-muchos entre objetos, de modo que cuando un objeto cambia su estado, todos los objetos dependientes son notificados y actualizados automáticamente. Esto promueve la desacoplación entre el sujeto (objeto que cambia su estado) y los observadores (objetos que necesitan ser notificados de los cambios).

**Situaciones útiles para aplicar este patrón:**
Es útil cuando se necesita mantener una consistencia entre objetos relacionados sin acoplarlos de manera fuerte. Por ejemplo, en interfaces de usuario donde cambios en un modelo deben reflejarse automáticamente en las vistas asociadas.