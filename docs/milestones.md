# Milestones

### [M0] Modelado del problema de las peritaciones (interna)

Este milestone aborda el problema definido en HU001, HU002 y HU003, y se parte del CSV descrito en la jornada de usuario. El producto es empaquetado y entregado como una versión del repositorio.

Se considera que el producto mínimo es viable cuando existe una entidad en el lenguaje elegido, almacenada en un fichero específico, que supera la comprobación sintáctica y las pruebas del linter del lenguaje, y cuyos atributos reflejan las especificaciones de las historias de usuario 1, 2 y 3.

### [M1] Lógica de negocio (interna)

Este milestone se desarrolla sobre los problemas de las historias de usuario HU001, HU002 y HU003, y se parte de la versión empaquetada en el milestone 0. El producto es empaquetado y entregado como una versión del repositorio.

Se considera que el producto mínimo es viable cuando el modelo de M0 pasa los tests que aplican las reglas de urgencia, novedad y presencialidad de las historias de usuario 1, 2 y 3.

### [M2] Ordenación de informes (interna)

Este milestone parte del problema HU004, usando como base la versión empaquetada en el milestone 1. El producto es empaquetado y entregado como una versión más del repositorio.

Consideramos que el producto mínimo es viable cuando, partiendo de la clasificación de los datos del milestone 1, se puede obtener cuál es el más prioritario según una heurística.

### [M3] Minutas acumuladas a final de mes (interna)

Este milestone parte del problema en HU005. El producto es empaquetado y entregado como una versión del repositorio.

Este producto mínimo será considerado viable si, partiendo de la tabla que contiene las minutas a percibir por los informes cerrados a lo largo del mes, se obtiene una suma tras aplicar impuestos y cuota de autónomos, que se corresponde al sueldo real a percibir ese mes.

### [M4] Acceso distribuido al sistema (externa)

Este milestone usa como problema base la historia de usuario HU006, y parte de las versiones empaquetadas de los milestones M2 y M3. El producto es empaquetado y entregado como un artefacto desplegado en la nube.

Este producto mínimo es considerado viable cuando el servicio a ofrecer (es decir, tal y como se especifica en los milestones 2 y 3, poder obtener el informe más prioritario en el momento y poder calcular el sueldo a percibir dada la tabla de minutas) está alojado en la nube, y el usuario final puede acceder a dicho servicio desde el ordenador de la oficina y el teléfono móvil obteniendo el mismo resultado desde ambos.