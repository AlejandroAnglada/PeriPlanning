# Jornadas de usuario

Las jornadas de usuario describen la rutina que siguen los usuarios con respecto al sistema que estamos implementando. En mi caso se describe la de una persona, que es **Manuel Anglada Romero**, el perito.

## Jornada de Usuario 1: Manuel Anglada Romero

Cada vez que reciba el listado con las peritaciones, el usuario sube el CSV, que posee 16 columnas y tantas filas como informes hayan registrados ese mes, y accede al sistema. Esto es una vez al día, que es cuando la plataforma actualiza la tabla (se reinicia el primer día de cada mes). Normalmente accede a la tabla y al sistema desde el ordenador de la oficina, pero si lo necesita accede desde el teléfono móvil. Una vez que entre al sistema, consulta las peritaciones que tiene aún pendientes. De un vistazo puede saber qué peritaciones son urgentes. Con la peritación pertinente seleccionada, debe o bien llamar al asegurado si aún no ha sido contactado o programar la peritación presencial si ya fue contactado. Una vez que ha contactado o peritado al asegurado, lo marca en el sistema. De no hacerlo, el sistema es capaz de reflejarlo con la siguiente actualización de la tabla. Una vez hecho esto, se desconecta del sistema.

Una vez que llega el último día del mes, el usuario accede al sistema e introduce de nuevo una tabla en formato CSV. En este caso se trata de la tabla de minutas cobradas por peritación, que además permite ver si se ha ejecutado alguna penalización en los pagos. Una vez introducida la tabla, consulta cuánto dinero se espera que se le ingrese este mes, y cuánto se espera que tenga disponible tras reservar el IVA pertinente (que le es cobrado cada tres meses, y corresponde a un 21% del total, debido a que su labor cae en la categoría de IVA general) y la cuota de autónomos (que depende del tramo económico del mes).

Las 16 columnas de la tabla son en orden: Siniestro, Asegurado, Estado, Perito, Gestor pericial, Días abierto, Días restantes, Código Postal, Dirección, Lugar, Características, Compañía, Reserva, Tasación, Días inactivo y Notas.

### Criterios de penalización

Hay varios criterios que determinan ciertas características de las peritaciones, que son la presencialidad, la novedad y la urgencia. Se recogen aquí:
1. Si el siniestro es de Meridiano, Santander, AXA empresas o Mapfre empresas, siempre debe ser visto presencialmente.
2. Si la cuantía aproximada de los daños supera los 4000€ (que es un dato que _no siempre_ está presente, porque no siempre hay prevaloración de daños), debe ser visto presencialmente.
3. Para los siniestros de Mapfre empresas y AXA empresas, si el perito no contacta con el asegurado en un plazo de dos días, y no lo cierra en un plazo de 6 días desde el contacto con el asegurado, el perito sufre una penalización.
4. Los siniestros nuevos con más de 30 días sin haber sido vistos penalizan al perito.
5. Para todos los siniestros, si el asegurado no ha sido contactado en un plazo de 4 días, el perito es penalizado.

Las penalizaciones se recogen en un sistema de "warnings". 
- **Un warning** supone una reducción del 5% de la minuta a percibir de la peritación. 
- **Dos warnings** hace que la peritación se "bloquee", por lo que el perito debe comunicarle a su supervisor que desea seguir con el informe, y la reducción de la minuta aumenta al 10%.
- **Tres warnings** supone la devolución del expediente, siendo éste reasignado a otro perito.
Si se sufre una penalización por tiempo, el contador se reinicia; es decir, si pasa el plazo para comunicar al asegurado dos veces seguidas (serían ocho días para cualquier siniestro), se emiten dos warnings. El tercero (y la retirada del informe) llegaría a los doce días.