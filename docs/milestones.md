# Milestones

### [M0] Modelado del problema de las peritaciones (interna)

Este milestone aborda el problema definido en HU001, y se parte del CSV descrito en la jornada de usuario.

Para el desarrollo de este producto, se aplica _Domain Driven Design_ centrando el desarrollo en la lógica del problema del peritaje.

Se considera que el producto mínimo es viable cuando existe una entidad en el lenguaje elegido, resultado del análisis DDD.

### [M1] Lógica de negocio (interna)

Este milestone se desarrolla sobre el problema comprendido en la historia de usuario 1 tras haber sido modelado en el milestone 0, partiéndose del mismo.

Se considera que el producto mínimo es viable cuando el modelo de M0 pasa los tests que aplican las reglas de prioridad, basadas en la heurística requerida por la historia de usuario 1.

### [M2] Modelado del problema de las minutas (interna)

Este milestone parte del problema en HU002, y se parte del CSV de minutas.

Este producto mínimo será considerado viable si existe una entidad en el lenguaje elegido, resultando del análisis DDD.

### [M3] Cálculo de minutas acumuladas a final de mes (interna)

Este milestone parte del problema en HU002, tomando como base el milestone 2.

Este producto mínimo será considerado viable si, partiendo de la tabla que contiene las minutas a percibir por los informes cerrados a lo largo del mes, se obtiene una suma tras aplicar impuestos y cuota de autónomos, que se corresponde al sueldo real a percibir ese mes (usando como referencia un mes ya pasado, del que se conoce lo percibido y el CSV).

### [M4] Acceso distribuido al sistema (externa)

Este milestone usa como problema base la historia de usuario HU003, y parte de las versiones de los milestones M2 y M3. El producto es entregado como un servicio usable desplegado en la nube.

Este producto mínimo es considerado viable cuando el servicio a ofrecer (es decir, tal y como se especifica en los milestones 1 y 3, poder obtener el informe más prioritario en el momento y poder calcular el sueldo a percibir dada la tabla de minutas) está alojado en la nube, y el usuario final puede acceder a dicho servicio desde el ordenador de la oficina y el teléfono móvil obteniendo el mismo resultado desde ambos.