# Milestones

Hitos del proyecto. Cada milestone representa un producto mínimamente viable (PMV), que es la versión con funcionalidad mínima que cumple con lo que dice el milestone (y nada más).

### [M0] Modelado del problema y datos

Se desarrolla y entrega un PMV cuyo objetivo es el modelado y procesado de los datos, que son introducidos en formato CSV, para su posterior uso.

El cumplimiento de este milestone implica el desarrollo de una herramienta de parsing, alojada en este repositorio y documentada correctamente (casos de uso, extremos, precondiciones y poscondiciones).

### [M1] Lógica de negocio

Se desarrolla y entrega un PMV cuyo objetivo es la clasificación de informes periciales según la urgencia (HU002), la novedad (HU003) y la presencialidad (HU004) de la peritación.

Al cumplir este milestone, se garantiza que se ha desarrollado una herramienta que permite clasificar informes según diferentes métricas, habiendo sido probada de manera acorde.

### [M2] Ordenación de informes

Se desarrolla y entrega un PMV cuyo objetivo es la ordenación de los informes (HU006) en función de una heurística que toma como elemento de máxima prioridad la urgencia (tiempo hasta que se penalice el informe), seguida de la novedad del informe, y por último la presencialidad obligatoria de la peritación, en ese orden.

El cumplimiento de este milestone implica la generación de un programa funcional, testeado, que permite al usuario consultar de la tabla proporcionada cuál es recomendable que sea la primera peritación para minimizar posibles penalizaciones.

### [M3] Cálculo de minutas acumuladas a final de mes

Se desarrolla y entrega un PMV cuyo objetivo es el cómputo del importe a percibir tras aplicar impuestos dada la tabla de minutas de los contratos cerrados.

Tras cumplir este milestone se garantiza que el sistema puede calcular correctamente el sueldo a percibir a final de mes tras aplicar impuestos (IVA y cuota de autónomos en función de tramo económico).