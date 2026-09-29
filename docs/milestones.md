# Milestones

Hitos del proyecto. Cada milestone representa un producto mínimamente viable (PMV), que es la versión con funcionalidad mínima que cumple con lo que dice el milestone (y nada más).

### [M0] Modelado del problema y datos

Se desarrolla y entrega un PMV cuyo objetivo es el parsing, normalización y preparación de la información (HU006) para ser procesada más adelante cuando se requiera. Está relacionada con la historia de usuario interna, HU006.

El cumplimiento de este milestone implica el desarrollo de una herramienta de parsing, alojada en este repositorio y documentada correctamente (casos de uso, extremos, precondiciones y poscondiciones).

### [M1] Lógica de negocio

Se desarrolla y entrega un PMV cuyo objetivo es la clasificación de informes periciales según la urgencia (HU001), la novedad (HU002) y la presencialidad (HU003) de la peritación.

### [M2] Ordenación de informes

Se desarrolla y entrega un PMV cuyo objetivo es la ordenación de los informes (HU005) en función de una heurística que toma como elemento de máxima prioridad la urgencia (tiempo hasta que se penalice el informe), seguida de la novedad del informe, y por último la presencialidad obligatoria de la peritación, en ese orden.

El cumplimiento de este milestone implica la generación de un programa funcional, testeado, que permite al usuario consultar de la tabla proporcionada cuál es recomendable que sea la primera peritación para minimizar posibles penalizaciones.

### [M3] Cálculo de minutas acumuladas a final de mes

Se desarrolla y entrega un PMV cuyo objetivo es el cómputo del importe a percibir tras aplicar impuestos dada la tabla de minutas de los contratos cerrados.