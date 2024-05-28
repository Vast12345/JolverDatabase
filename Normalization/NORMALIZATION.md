# **Database Design**

### **Normalization**

* Primer: Todos los atributos deben tener un unico valor.

* Segundo: Un atributo debe depender de todo el UID de su entidad

* Tercero: Los atributos que no son UID pueden ser dependientes de ontro atributo no UID

**Primer Forma Normal**

* *El primer formato normal necestia que no existan atributos de varios valores*
* *Para comprobar si hay 1NF, asegurase de que cada atributo tenga un valor unico para cada instancia de la entidad.*
* *Si un atributo tiene varios valores, cree una entidad adicional y relacionela con la entidad original con una relacion 1:M*

**Segunda Forma Normal**

* *El segundo formato normal (2NF) necesita que cualquier atributo que np sea UID dependa de (sea propiedad de o una caracterista de) todo el UID*
* *Si el UID es un UID compuesto, cada atributo debe depender de todas las partes del UID compuesto*
* *Si un atributo no depende de todo el UID , cree una entidad adicional con el UID parcial*

