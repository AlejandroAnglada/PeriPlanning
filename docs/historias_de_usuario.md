# Historias de usuario

Las historias de usuario reflejan los problemas a los que se enfrentan los usuarios del sistema. Están asociadas al perfil de **Manuel Anglada Romero**.

### [HU001] Clasificación de informes

Tal y como se me presenta la tabla, no es fácil comprobar de un vistazo qué características tiene cada uno de los informes. Esto da lugar a un desorden que puede acabar haciendo que sufra penalizaciones, se acumule el trabajo y baje mucho el rendimiento. Entonces, es imperativo que se puedan ordenar los informes en función de su urgencia para evitarlo.

Hay varios [criterios](jornadas_usuario.md#criterios_de_penalizacion) que determinan si soy penalizado o no.

### [HU002] Heurística de urgencia (interna)

Para poder resolver el problema de la ordenación de informes, se debe determinar con precisión _qué_ es la urgencia, y modelar una heurística en base a esa determinación.

### [HU003] Cálculo de minutas a final de mes

A final de mes se me presenta una tabla con las minutas asociadas a cada informe que ha cerrado. Esta tabla posee las minutas en bruto, es decir, antes de que se le aplique el 21% de IVA. Además, no refleja las penalizaciones que han podido aplicarse al informe. Por último, todos los meses se me cobra una cuota de autónomos en función de lo que haya facturado. Todos estos detalles hacen que calcular lo que cobro en el mes sea difícil y lento.

### [HU004] Cálculo de IVA y cuota de autónomos (interna)

Con el objetivo de calcular las minutas a final de mes, en función del CSV con las minutas, se tienen que aplicar correctamente las penalizaciones (si hubiese), el IVA y la cuota de autónomos.

### [HU005] Acceder al sistema desde cualquier parte

Muchas veces la actualización de la tabla me pilla en la calle peritando, por lo que tengo que verla desde el teléfono móvil. Sería conveniente poder ver y gestionar todo desde el teléfono igual que lo hago desde mi oficina.