# Milestones

Hitos del proyecto. Cada milestone representa un producto mínimamente viable (PMV), que es una definición sobre el problema que se aborda, cómo se entrega al objetivo y cómo se considera viable.

### [M0] Modelado del problema y datos (interna)

Este milestone aborda el problema definido por HU001, y se parte del CSV que le es proporcionado a Manuel. El producto es empaquetado y entregado como una versión del repositorio, de tal manera que los desarrolladores pueden partir de este milestone para el correcto desarrollo de los siguientes.

Se considera entonces que el producto mínimo es viable cuando:
1. El flujo con el que la historia de usuario relacionada se cierra es: HU -> issue -> commit.
2. Los datos preparados se corresponden a un CSV real, siendo contrastados por Manuel.

### [M1] Lógica de negocio (interna)

Este milestone se desarrolla sobre los problemas de las historias de usuario HU002, HU003 y HU004, y se parte del milestone 0. El producto es empaquetado y entregado como una versión del repositorio, permitiendo que los desarrolladores sean capaces de partir de este milestone para poder desarrollar los siguientes.

Se considera que el producto mínimo es viable cuando:
1. El flujo con el que las historias de usuarios se cierran es: HU -> issue -> commit.
2. Los datos obtenidos mediante el producto mínimo viable de M0 son categorizados en función de los criterios definidos en las historias de usuario, tal y como Manuel los clasificaría manualmente.

### [M2] Ordenación de informes (interna)

Este milestone parte del problema HU006, usando como base el milestone 1. El producto es empaquetado y entregado como una versión más del repositorio, permitiendo que Manuel logre ver de forma ordenada los partes.

Consideramos que el producto mínimo es viable cuando:
1. El flujo con el que se cierra la historia de usuario es: HU -> issue -> commit.
2. Los datos obtenidos del milestone 0 son clasificados tal y como Manuel lo haría manualmente, y además Manuel obtiene cuál(es) son los partes más prioritarios.

### [M3] Minutas acumuladas a final de mes (interna)

Este milestone parte del problema en HU005. El producto es empaquetado y entregado como una versión del repositorio, de tal manera que Manuel puede saber cuánto cobrará en un mes con el CSV de entrada.

Este producto mínimo será considerado viable si:
1. El flujo con el que se cierra la historia de usuario es: HU -> issue -> commit.
2. El sueldo obtenido en función de los datos procesados del CSV de minutas se corresponde al sueldo real que Manuel percibe a final del mes usado como referencia.

### [M4] Acceso distribuido al sistema

Este milestone usa como problema base la historia de usuario HU007, y parte del milestone M3 como base. El producto es empaquetado y entregado como un artefacto desplegado en la nube, permitiendo que Manuel acceda a toda funcionalidad desde cualquier dispositivo.

Este producto mínimo es considerado viable cuando:
1. El flujo con el que se cierra la historia de usuario es: HU -> issue -> commit.
2. Manuel puede acceder desde cualquiera de sus dispositivos a las funcionalidades de M3 y M2.