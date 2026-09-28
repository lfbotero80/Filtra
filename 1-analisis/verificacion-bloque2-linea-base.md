# Verificación del bloque 2 — línea base de ventas, margen y clientes

Documento de trabajo para Luis Felipe. Revisión del archivo `Ventas x línea segmento.xlsx` contra lo que exigían los ítems 2.1 a 2.4 del backlog.

## Qué llegó y qué falta

El archivo trae tres hojas visibles y cinco ocultas, entre ellas la base cruda de más de cincuenta mil registros de la que salen las tablas dinámicas. Eso es bueno: los agregados son auditables contra el detalle y no hay que creerles a ciegas.

El ítem 2.2, ventas y margen bruto por línea de producto para 2024, 2025 y 2026, está completo.

El ítem 2.3, ventas y margen bruto por segmento, está completo en datos pero tiene un problema de construcción que se explica más abajo.

El ítem 2.4, base de clientes recurrentes, llegó a medias. Está el conteo de clientes que compraron cada año y la distribución de frecuencia por número de meses con compra, que es más de lo que había. No está lo que el ítem pedía además: cuánto factura cada cliente, qué porcentaje del total representa cada uno, y desde cuándo son clientes. Los números que aparecen junto a cada nombre no son pesos, son conteos de movimientos, y con eso no se puede decir qué peso tiene cada cliente en la facturación.

Ese faltante no es menor. Sin facturación por cliente no se puede saber si la concentración de ingreso es alta o baja, no se puede priorizar la recuperación comercial por valor, y la meta de clientes recurrentes que va en el plan 2027 seguiría siendo direccional.

## El hallazgo que bloquea: el margen de APL no coincide con el margen contable

Las ventas de las dos fuentes coinciden casi exactamente. El archivo reporta 12.239.382.848 para 2025 y el estado de resultados auditado reporta 12.235.716.458. La diferencia es de 0,03 por ciento, es decir, la misma facturación.

El margen bruto no coincide. El archivo reporta 24,98 por ciento para 2025. El estado de resultados auditado reporta 27,64 por ciento. La brecha es de 2,66 puntos, equivalente a unos 325 millones de pesos de utilidad bruta.

Como las ventas cuadran y el margen no, la diferencia está toda en el costo. APL está registrando un costo de ventas más alto que el que quedó en la contabilidad, o la contabilidad está reconociendo en el costo algo que APL no ve. No puedo determinar cuál de las dos con los archivos disponibles, y no voy a suponerlo.

Hay un detalle que hace la pregunta más interesante y menos obvia: la brecha no es constante. Para 2026 las dos fuentes casi coinciden, 26,69 por ciento en el estado de resultados del primer semestre contra 26,27 por ciento en APL hasta septiembre. Si fuera una diferencia estructural de método de costeo, debería aparecer todos los años por igual. Que aparezca fuerte en 2025 y casi desaparezca en 2026 sugiere un ajuste puntual en el cierre de 2025, algo como una corrección de inventario, una reclasificación o el reconocimiento de descuentos financieros de proveedor dentro del costo. Es una hipótesis, no una conclusión, y la responde contabilidad en una reunión.

**Por qué esto bloquea.** El manual de funciones que entregué la semana pasada fija la meta de margen bruto en 27,5 por ciento para gerencia, dirección comercial, asesores externos y dirección de compras, anclada al 27,64 por ciento contable de 2025. Si el tablero se alimenta de APL, esa meta es inalcanzable por construcción: APL no ha mostrado un margen superior a 26,3 por ciento en ninguno de los tres años. Los equipos verían un indicador permanentemente en rojo por una diferencia de fuente y no por su desempeño, y en dos meses dejarían de mirarlo.

Antes de construir el tablero hay que decidir una de dos cosas: o el margen se mide con el cierre contable y APL se usa solo para desagregar por línea y segmento, o el margen se mide con APL y las metas se recalibran a esa escala. Las dos son defendibles; lo que no funciona es fijar la meta en una fuente y medirla en otra.

## Lo que muestran las líneas de producto

Cifras del archivo. Para 2026 anualicé linealmente el acumulado a septiembre 3, que corresponde al 67,4 por ciento del año. La anualización asume distribución mensual uniforme, supuesto que la propia empresa cuestiona al sostener que el segundo semestre rinde mejor, así que las cifras anualizadas son direccionales y no proyecciones.

| Línea | 2024 | 2025 | 2026 anualizado | Variación | MB 2024 | MB 2025 | MB 2026 |
|---|---|---|---|---|---|---|---|
| Consumibles | 11.373 | 10.917 | 9.545 | −12,6% | 25,9% | 24,9% | 26,3% |
| Equipos | 1.601 | 1.056 | 880 | −16,7% | 23,8% | 25,1% | 19,2% |
| Mobiliario | 173 | 203 | 712 | +250,2% | 26,7% | 26,2% | 32,9% |
| Equipos marca propia | 399 | 57 | 34 | −39,4% | 34,0% | 31,4% | 56,1% |

Cifras en millones de pesos.

**Consumibles es el 89 por ciento del negocio.** Toda la conversación de portafolio, de crecimiento y de margen es en la práctica una conversación sobre consumibles. Su margen se está recuperando en 2026, y como pesa casi nueve de cada diez pesos, esa recuperación explica por sí sola la mejora del margen general del año.

**Mobiliario es la única historia buena del portafolio y nadie la mencionó.** Multiplicó su venta por 2,4 veces frente a todo 2025 cuando aún faltan cuatro meses del año, y su margen subió de 26,2 a 32,9 por ciento. Crece y mejora margen al tiempo, que es lo difícil. Vale entender qué pasó ahí antes de diseñar cualquier estrategia de crecimiento para 2027, porque puede ser un cliente grande no repetible, un contrato de dotación, o una capacidad real que se puede escalar. Son tres cosas distintas y llevan a decisiones distintas.

**Equipos es el problema serio.** Cae 16,7 por ciento y su margen se desplomó de 25,1 a 19,2 por ciento. Es la única línea que pierde volumen y rentabilidad simultáneamente. Como equipos es donde vive la relación con proveedores internacionales, esto conecta directamente con el frente de Merck Sigma y con la línea de microbiología que compras señaló como problema de precio.

**Equipos de marca propia prácticamente desapareció y era la línea de mejor margen.** Vendía 399 millones en 2024 con 34 por ciento de margen y hoy va en 23 millones. Es una caída del 94 por ciento en dos años sobre la línea más rentable del portafolio, y no aparece mencionada en ninguno de los tres documentos de diagnóstico de las áreas ni en las respuestas de Pacho. Esto merece una pregunta directa: ¿se dejó de vender, se dejó de comprar, se perdió una representación, o se decidió discontinuarla? El margen de 56,1 por ciento que muestra 2026 es sobre un volumen tan pequeño que probablemente corresponde a unas pocas transacciones y no es representativo.

## Lo que muestran los segmentos

| Segmento | 2025 | % del total | 2026 anualizado | Variación | MB 2025 | MB 2026 |
|---|---|---|---|---|---|---|
| Industria alimentos y bebidas | 2.277 | 18,6% | 2.065 | −9,3% | 25,6% | 26,4% |
| Farmacéutico y cosmético | 1.918 | 15,7% | 1.751 | −8,7% | 23,6% | 25,3% |
| Comercializadora | 1.871 | 15,3% | 1.583 | −15,4% | 22,6% | 26,0% |
| Industria química | 1.649 | 13,5% | 1.696 | +2,9% | 26,8% | 28,3% |
| Licitaciones SECOP | 1.626 | 13,3% | 1.908 | +17,3% | 27,7% | 28,0% |
| Académico e investigación | 1.328 | 10,9% | 1.009 | −24,0% | 23,5% | 22,9% |
| Laboratorios de servicios | 845 | 6,9% | 770 | −8,9% | 24,2% | 25,8% |
| Empresas de servicio público | 492 | 4,0% | 195 | −60,4% | 25,5% | 17,1% |
| Cannabis | 100 | 0,8% | 38 | −61,7% | 30,7% | 39,0% |
| Personas naturales | 70 | 0,6% | 103 | +48,3% | 24,6% | 25,6% |
| Clínica | 63 | 0,5% | 52 | −17,1% | 28,9% | 33,3% |
| Análisis y control metrológico | 0,5 | 0,0% | 7 | — | 30,2% | 28,9% |

Cifras en millones de pesos.

**Licitaciones SECOP no es negocio de baja rentabilidad, y eso contradice la narrativa interna.** Deja 27,7 por ciento de margen en 2025 y 28,0 por ciento en 2026, por encima del promedio de la empresa en los dos años, y es el segmento que más crece, 17,3 por ciento anualizado. El diagnóstico de las áreas señaló "atender negocios de rentabilidad muy baja" como problema transversal y varias respuestas apuntaban a las licitaciones. Los datos dicen que el problema de rentabilidad no está ahí. Puede ser que el costo real de las licitaciones no sea de margen sino de caja atrapada, reprocesos y carga operativa, que son costos que no aparecen en el margen bruto. Eso es exactamente lo que hay que separar antes de tomar decisiones sobre licitaciones, y refuerza la utilidad del indicador de margen real contra margen esperado que quedó en el manual.

**Donde sí está el margen bajo es en comercializadora, o sea los subdistribuidores.** Es el 15,3 por ciento de la facturación con el margen más bajo de todos los segmentos en 2025, 22,6 por ciento, cuatro puntos por debajo del segmento más rentable de tamaño comparable. Vender a través de subdistribuidores es legítimo y da volumen, pero hay que decidirlo sabiendo que cada peso vendido por ahí deja significativamente menos que uno vendido directo. Buena noticia: en 2026 ese margen subió a 26,0 por ciento, así que algo se corrigió y vale la pena entender qué.

**Académico e investigación es el segmento que se está deteriorando de verdad.** Cae 24 por ciento y es el único segmento grande donde el margen también baja, de 23,5 a 22,9 por ciento. Es donde viven la Universidad de Antioquia, el ITM y el SENA. Pierde volumen y rentabilidad a la vez.

**Empresas de servicio público se desplomó**, 60 por ciento menos de venta y el margen cayó de 25,5 a 17,1 por ciento. Es el segmento de EPM.

**El segmento de licitaciones está mal construido y contamina el análisis.** Licitaciones es un canal de venta, no un tipo de cliente. Una universidad que compra por SECOP aparece en Licitaciones y no en Académico, lo que significa que los 1.626 millones de ese renglón pertenecen a clientes que también existen en otros segmentos, y que la caída de Académico puede estar sobreestimada porque parte de su venta migró a la fila de licitaciones. Para el análisis de 2027 hay que poder cruzar las dos dimensiones: segmento de cliente por un lado, canal de venta por otro. La base cruda lo permite; la tabla dinámica actual no.

Nota sobre los once segmentos declarados en la presentación corporativa: el archivo trae doce y no coinciden del todo. Aparece "Análisis y control metrológico", que no estaba declarado, y "Licitaciones SECOP" ocupa el lugar de lo que la presentación llama "entidades públicas". La numeración salta el 04, el 06, el 10 y el 13, así que hay códigos de segmento sin uso o sin mostrar. Conviene unificar la lista antes de fijar metas por segmento en el plan 2027.

## Clientes: la corrección más importante al diagnóstico

Los seis clientes que las áreas identificaron por nombre como clientes que se están perdiendo siguen comprando. Estas son las cifras del archivo, en número de movimientos, no en pesos.

| Cliente | 2024 | 2025 | 2026 a sept 3 | 2026 anualizado vs 2025 |
|---|---|---|---|---|
| SENA | 1.526 | 1.633 | 872 | −21% |
| Nutresa | 1.303 | 1.163 | 686 | −12% |
| U. de Antioquia | 1.149 | 1.123 | 701 | −7% |
| ITM | 453 | 695 | 339 | −28% |
| EPM | 188 | 332 | 86 | −61% |
| Ecar | 172 | 225 | 104 | −31% |

Cuatro de los seis crecieron en 2025 frente a 2024. El SENA, el ITM, EPM y Ecar tuvieron más movimiento en 2025 que en 2024. En 2026 los seis caen, algunos con fuerza, pero ninguno está perdido: todos siguen transando.

La lectura correcta no es "perdimos estos clientes" sino "estos clientes se están enfriando en 2026". Es un problema distinto y se ataca distinto: no hay que recuperar una cuenta cerrada, hay que entender por qué bajó el ritmo de una cuenta activa, que es más barato y más rápido.

Y hay algo que el diagnóstico no vio. Tres clientes sí están efectivamente perdidos y ninguna de las áreas los mencionó.

| Cliente | 2024 | 2025 | 2026 a sept 3 |
|---|---|---|---|
| Tecnológico de Antioquia | 196 | 111 | 1 |
| Colegio Mayor de Antioquia | 241 | 130 | 14 |
| Empresas Públicas de La Ceja | 41 | 0 | 0 |

Esto dice algo sobre el método de diagnóstico que conviene registrar: cuando se le pregunta a las áreas qué clientes se están perdiendo, responden con los nombres grandes y visibles, no con los que efectivamente se fueron. Es una razón concreta para que el diagnóstico de 2027 se haga con datos primero y con percepción después, y no al revés.

**Advertencia necesaria sobre estas cifras.** Son conteos de movimientos, no pesos. Un cliente puede tener muchos movimientos pequeños o pocos movimientos grandes, así que estas variaciones indican dirección pero no materialidad. Para saber cuánto pesa cada una de estas caídas en la facturación hace falta exactamente el dato que no llegó en el ítem 2.4.

## Recurrencia de clientes

El archivo mide dos poblaciones distintas y conviene no confundirlas. Los clientes que compraron en el año fueron 502 en 2024, 527 en 2025 y 419 en 2026 hasta septiembre. Sobre una base depurada que el archivo llama "sin oficina", fueron 318, 306 y 242.

Sobre esa base depurada, la frecuencia de compra en 2025 se reparte así: 57 clientes compraron los doce meses, 22 compraron once, 18 compraron diez, 16 compraron nueve, 20 compraron ocho, 17 compraron siete y 18 compraron seis. Eso da 168 clientes que compraron en seis meses o más, el 54,9 por ciento de la base. En el otro extremo, 69 clientes compraron una sola vez en el año y 30 compraron dos veces, es decir 99 clientes, el 32,4 por ciento, que son compradores ocasionales.

La comparación con 2024 muestra estabilidad en el núcleo recurrente, 53,5 por ciento entonces contra 54,9 por ciento ahora, pero un deterioro en la cola: los clientes de una sola compra al año pasaron de 56 a 69, del 17,6 al 22,6 por ciento de la base. Está entrando más cliente ocasional y eso encaja con que el número total de clientes creciera de 502 a 527 mientras la facturación caía. Se está vendiendo a más gente y menos volumen a cada uno.

Es una base de recurrencia utilizable, y es la primera que existe. Lo que le falta para servir en el plan 2027 es el peso en pesos de cada grupo. Saber que 168 clientes compran seis meses o más no dice si representan el 60 por ciento de la facturación o el 95, y esa diferencia cambia por completo la estrategia comercial.

## Calidad del archivo

Dos cosas menores que conviene corregir en la fuente antes de que alguien cite estas tablas.

La fila "50 OTROS - FLETES" de la hoja de líneas está desalineada: en las columnas de 2025 aparecen valores corridos que no corresponden a los encabezados, y la fila de total general que le sigue queda malformada. Los totales correctos son los de la fila "Total general" anterior, más esa fila de fletes.

La columna "Promedio Utilidad APL" no es utilizable en las filas de total, porque promedia porcentajes de líneas de tamaño muy distinto. En la fila de total general marca 1,2057 para 2024, que no significa nada. La columna de margen bruto sí está bien calculada y es la que hay que usar.

## Qué propondría hacer

Resolver con contabilidad la brecha de 2,66 puntos entre el margen de APL y el margen contable de 2025, y decidir cuál de las dos fuentes alimenta el tablero. Es la decisión que bloquea el bloque 3 y la que puede invalidar las metas de margen del manual de funciones.

Completar el ítem 2.4 con lo que falta: facturación por cliente, participación de cada uno en el total, y antigüedad. Con la base cruda de cincuenta mil registros que ya está en el archivo, es un trabajo de tabla dinámica, no de levantamiento nuevo.

Pedir que el análisis de segmento se pueda cruzar con canal, para separar cliente de forma de venta y poder leer bien tanto Académico como Licitaciones.

Hacerle tres preguntas concretas a Pacho, que salen directamente de los datos y no estaban sobre la mesa: qué pasó con la línea de equipos de marca propia, que perdió el 94 por ciento de su venta siendo la más rentable; qué explica el salto de mobiliario, que se multiplicó por 2,4 con el mejor margen del portafolio; y si la percepción de que las licitaciones son negocio de baja rentabilidad se sostiene, dado que el margen bruto dice lo contrario y el costo real puede estar en caja y reprocesos en lugar de en margen.

Y revisar la meta de margen bruto del manual de funciones cuando la fuente de medición quede decidida, porque hoy está anclada a una cifra contable que el sistema operativo no reproduce.
