# Milestones

### [M0] Modelado del problema de las peritaciones (interna)

Este milestone aborda el problema definido en HU001, y se parte del CSV descrito en la jornada de usuario. El producto es empaquetado y entregado como una versión del repositorio.

Para el desarrollo de este producto, se aplica _Domain Driven Design_ centrando el desarrollo de los modelos siguientes en la lógica del problema del peritaje.

Se considera que el producto mínimo es viable cuando existe una entidad en el lenguaje elegido, almacenada en un fichero específico, que supera la comprobación sintáctica y las pruebas del linter del lenguaje, y cuyos atributos reflejan las especificaciones de la historia de usuario 1.

### [M1] Lógica de negocio (interna)

Este milestone se desarrolla sobre el problema comprendido en la historia de usuario 2, y se parte de la versión empaquetada en el milestone 0. El producto es empaquetado y entregado como una versión del repositorio.

Se considera que el producto mínimo es viable cuando el modelo de M0 pasa los tests que aplican las reglas de prioridad, basadas en la heurística explicada en el problema de la historia de usuario 2.

### [M2] Modelado del problema de las minutas (interna)

Este milestone parte del problema en HU003. El producto es empaquetado y entregado como una versión del repositorio.

Este producto mínimo será considerado viable si existe una entidad en el lenguaje elegido, almacenada en un fichero específico, que supera la comprobación sintáctica del problema y las pruebas del linter del lenguaje, y cuyos atributos reflejan las especificaciones de la historia de usuario 3.

### [M3] Cálculo acumuladas a final de mes (interna)

Este milestone parte del problema en HU003, tomando como base la versión empaquetada del milestone 2. El producto es empaquetado y entregado como una versión del repositorio.

Este producto mínimo será considerado viable si, partiendo de la tabla que contiene las minutas a percibir por los informes cerrados a lo largo del mes, se obtiene una suma tras aplicar impuestos y cuota de autónomos, que se corresponde al sueldo real a percibir ese mes (usando como referencia un mes ya pasado, del que se conoce lo percibido y el CSV).

### [M4] Acceso distribuido al sistema (externa)

Este milestone usa como problema base la historia de usuario HU006, y parte de las versiones empaquetadas de los milestones M2 y M3. El producto es empaquetado y entregado como un artefacto desplegado en la nube.

Este producto mínimo es considerado viable cuando el servicio a ofrecer (es decir, tal y como se especifica en los milestones 2 y 3, poder obtener el informe más prioritario en el momento y poder calcular el sueldo a percibir dada la tabla de minutas) está alojado en la nube, y el usuario final puede acceder a dicho servicio desde el ordenador de la oficina y el teléfono móvil obteniendo el mismo resultado desde ambos.