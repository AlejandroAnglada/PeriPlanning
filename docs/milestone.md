# Milestones

**CAMBIO TEMPORAL PARA QUE GITHUB NO LOS DETECTE COMO RENOMBRADO**

### [M0] Modelado del problema de las peritaciones (interna)

Este milestone modela el problema definido en HU001, y se parte del CSV descrito en la jornada de usuario.

Para el desarrollo de este producto, se aplica _Domain Driven Design_ al diseño del problema del peritaje.

Se considera que el producto mínimo es viable cuando existe una entidad en el lenguaje elegido, resultado del análisis DDD.

### [M1] Lógica de negocio (interna)

Este milestone aborda el problema definido en la historia de usuario 1, construyéndose sobre el modelo de dominio definido en el milestone 0.

Se considera que el producto mínimo es viable cuando dicho producto pasa los tests automáticos escritos a partir de la historia de usuario 1, que se desarrollan en base a los criterios de penalización definidos en dicha jornada de uusario, y que se ajustan al problema de HU001.

### [M2] Modelado del problema de las minutas (interna)

Este milestone modela el problema definido en HU002, y se parte del CSV de minutas.

Este producto mínimo será considerado viable si existe una entidad en el lenguaje elegido, resultando del análisis DDD.

### [M3] Cálculo de minutas acumuladas a final de mes (interna)

Este milestone parte del problema en HU002, tomando como base el milestone 2.

Este producto mínimo será considerado viable si, partiendo de la tabla que contiene las minutas a percibir por los informes cerrados a lo largo del mes, se obtiene una suma tras aplicar impuestos y cuota de autónomos, que se corresponde al sueldo real a percibir ese mes (usando como referencia un mes ya pasado, del que se conoce lo percibido y el CSV).

### [M4] Acceso distribuido al sistema (externa)

Este milestone usa como problema base la historia de usuario HU003, y parte de las versiones de los milestones M1 y M3. El producto es entregado como un servicio usable desplegado en la nube.

Este producto mínimo es considerado viable cuando el servicio a ofrecer (es decir, tal y como se especifica en los milestones 1 y 3, poder obtener el informe más prioritario en el momento y poder calcular el sueldo a percibir dada la tabla de minutas) está alojado en la nube, y el usuario final puede acceder a dicho servicio desde el ordenador de la oficina y el teléfono móvil obteniendo el mismo resultado desde ambos.

**CAMBIO TEMPORAL PARA QUE GITHUB NO LOS DETECTE COMO RENOMBRADO**