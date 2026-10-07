# Milestones

### [M0] Modelado del problema y datos (interna)

Este milestone aborda el problema definido por HU001, y se parte del CSV que le es proporcionado a Manuel. El producto es empaquetado y entregado como una versión del repositorio.

Se considera entonces que el producto mínimo es viable cuando, dado un fichero CSV de entrada con 16 columnas, el producto expone correctamente la información mínima necesaria para poder clasificar los informes (es decir, la compañía, los días inactivo, los días abierto y, de tener, la tasación previa), y el número de informes de salida coincide con las entradas de la tabla CSV.

### [M1] Lógica de negocio (interna)

Este milestone se desarrolla sobre los problemas de las historias de usuario HU002, HU003 y HU004, y se parte de la versión empaquetada en el milestone 0. El producto es empaquetado y entregado como una versión del repositorio.

Se considera que el producto mínimo es viable cuando los datos obtenidos mediante la funcionalidad de M0 son categorizados en función de su urgencia, novedad y necesidad de presencialidad, tal y como se describe en las historias de usuario 2, 3 y 4.

### [M2] Ordenación de informes (interna)

Este milestone parte del problema HU006, usando como base la versión empaquetada en el milestone 1. El producto es empaquetado y entregado como una versión más del repositorio.

Consideramos que el producto mínimo es viable cuando, partiendo de la clasificación de los datos del milestone 1, se puede obtener cuál es el más urgente según una heurística.

### [M3] Minutas acumuladas a final de mes (interna)

Este milestone parte del problema en HU005. El producto es empaquetado y entregado como una versión del repositorio.

Este producto mínimo será considerado viable si, partiendo de la tabla que contiene las minutas a percibir por los informes cerrados a lo largo del mes, se obtiene una suma tras aplicar impuestos y cuota de autónomos de forma pertinente, que se corresponde al sueldo real a percibir ese mes.

### [M4] Acceso distribuido al sistema

Este milestone usa como problema base la historia de usuario HU007, y parte de las versiones empaquetadas de los milestones M2 y M3. El producto es empaquetado y entregado como un artefacto desplegado en la nube.

Este producto mínimo es considerado viable cuando el servicio a ofrecer (es decir, tal y como se especifica en los milestones 2 y 3, poder obtener el informe más prioritario en el momento y poder calcular el sueldo a percibir dada la tabla de minutas) está alojado en la nube, y el usuario final puede acceder a dicho servicio desde cualquier dispositivo que sea necesario.