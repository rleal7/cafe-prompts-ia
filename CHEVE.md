# Los 15 prompts con la fórmula CHEVE

La CHEVE es el CAFÉ con un ingrediente extra: **un ejemplo de lo que espera**. Darle a la IA un ejemplo del resultado es de lo que más mejora la respuesta.

| Letra | Qué va |
|---|---|
| **C**ontexto | Quién es usted y su negocio |
| **H**azme | La acción, directo y sin rodeos |
| **E**jemplo | Muéstrele cómo lo quiere: una línea, una fila o un formato |
| **V**ista | En qué formato se lo entrega |
| **E**stilo | El tono y lo que no debe hacer |

Cambie lo que está entre [corchetes] por sus datos. Los casos 1 a 7 son de un mismo negocio ficticio: una distribuidora de material eléctrico en Monterrey. La versión CAFÉ, sin el ejemplo, está en el [README](README.md). En PDF: [15-prompts-CHEVE-Roberto-Leal.pdf](15-prompts-CHEVE-Roberto-Leal.pdf).

## 1 · Cobrar sin perder al cliente
*Negocio*

```text
Soy dueño de [una distribuidora de material eléctrico]. [Constructora Treviño], cliente de [10 años], me debe [$180,000 de 3 facturas (1042, 1057 y 1063) con 90 días] de vencidas y ya no contesta. Hoy es [martes 3 de noviembre]. Redáctame 3 mensajes para cobrarle, de menos a más presión: un recordatorio; una propuesta de pago en dos partes con fecha límite; y el aviso de que suspenderemos su crédito. Que el primero suene algo así: “Hola, Ing. Treviño, buen día. Le doy seguimiento a las facturas 1042, 1057 y 1063 por $180,000. ¿Me apoya confirmando la fecha de pago? Saludos.” WhatsApp de máximo 5 líneas cada uno, con [el día y la hora para mandarlo]; el tercero, también por correo desde la cuenta de cobranza. Al final, lo que NO debo decir. De usted, respetuoso y mexicano: el primero cordial, el segundo firme con una propuesta concreta y el tercero formal. Sin amenazas ni mayúsculas: valoro [10 años] de relación.
```

- **C · Contexto:** Soy dueño de [una distribuidora de material eléctrico]. [Constructora Treviño], cliente de [10 años], me debe [$180,000 de 3 facturas (1042, 1057 y 1063) con 90 días] de vencidas y ya no contesta. Hoy es [martes 3 de noviembre].
- **H · Hazme:** Redáctame 3 mensajes para cobrarle, de menos a más presión: un recordatorio; una propuesta de pago en dos partes con fecha límite; y el aviso de que suspenderemos su crédito.
- **E · Ejemplo:** Que el primero suene algo así: “Hola, Ing. Treviño, buen día. Le doy seguimiento a las facturas 1042, 1057 y 1063 por $180,000. ¿Me apoya confirmando la fecha de pago? Saludos.”
- **V · Vista:** WhatsApp de máximo 5 líneas cada uno, con [el día y la hora para mandarlo]; el tercero, también por correo desde la cuenta de cobranza. Al final, lo que NO debo decir.
- **E · Estilo:** De usted, respetuoso y mexicano: el primero cordial, el segundo firme con una propuesta concreta y el tercero formal. Sin amenazas ni mayúsculas: valoro [10 años] de relación.

## 2 · Una minuta que sí da seguimiento
*Negocio*

```text
Soy dueño de [una distribuidora de material eléctrico]. Te paso la transcripción de la junta de [45 minutos con Constructora Garza] para [cerrar su pedido de fin de año]. Haz la minuta de seguimiento: datos de la sesión (proyecto, fecha, duración, participantes), contexto, acuerdos, tareas nuestras y del cliente con responsable, fecha y prioridad, pendientes, riesgos, próximos pasos y notas. Usa este formato, el de mis minutas: 1. Datos de la sesión (tabla de dos columnas) · 2. Contexto · 3. Acuerdos (# | Acuerdo | Detalle) · 4. Tareas nuestras (# | Tarea | Responsable | Fecha | Prioridad | Status) · 5. Tareas del cliente · 6. Pendientes · 7. Datos por confirmar · 8. Riesgos · 9. Próximos pasos · 10. Notas. Documento Word con una tabla por sección, máximo 2 páginas. Incluye “Datos por confirmar”: nombres, cargos y cifras que no quedaron claros. Profesional y neutro. No inventes: si algo no se dijo, márcalo “por confirmar”.
```

- **C · Contexto:** Soy dueño de [una distribuidora de material eléctrico]. Te paso la transcripción de la junta de [45 minutos con Constructora Garza] para [cerrar su pedido de fin de año].
- **H · Hazme:** Haz la minuta de seguimiento: datos de la sesión (proyecto, fecha, duración, participantes), contexto, acuerdos, tareas nuestras y del cliente con responsable, fecha y prioridad, pendientes, riesgos, próximos pasos y notas.
- **E · Ejemplo:** Usa este formato, el de mis minutas: 1. Datos de la sesión (tabla de dos columnas) · 2. Contexto · 3. Acuerdos (# | Acuerdo | Detalle) · 4. Tareas nuestras (# | Tarea | Responsable | Fecha | Prioridad | Status) · 5. Tareas del cliente · 6. Pendientes · 7. Datos por confirmar · 8. Riesgos · 9. Próximos pasos · 10. Notas.
- **V · Vista:** Documento Word con una tabla por sección, máximo 2 páginas. Incluye “Datos por confirmar”: nombres, cargos y cifras que no quedaron claros.
- **E · Estilo:** Profesional y neutro. No inventes: si algo no se dijo, márcalo “por confirmar”.

> Para probarlo con el mismo texto de la charla, pegue esta transcripción (ficticia; la minuta completa está en el repositorio): Jorge (director): “Cerremos el pedido de fin de año para Sierra Alta.” Carlos (compras, Constructora Garza): “Necesitamos 600 rollos de THW calibre 12 y 200 centros de carga de 12 circuitos.” Jorge: “Si son más de 500 rollos, te lo dejo en $1,450 el rollo; los centros de carga, en $1,180. El precio te lo sostengo hasta el 30 de noviembre, por el cobre.” Carlos: “¿Me lo entregan en dos partes, mitad el 15 de diciembre y mitad el 12 de enero?” Ana (almacén): “Tengo 350 rollos; el resto lo pido a fábrica y te confirmo el viernes 6.” Carlos: “El ingeniero Mario me pasa la lista final el miércoles y te mando la orden el lunes 9. Y necesitamos 45 días de crédito.” Jorge: “Te lo amplío a 45 días si me mandas tus estados financieros a más tardar el 13.” Carlos: “Otra cosa: la factura 2291 de septiembre nos llegó con otro precio.” Jorge: “Laura, revísala y llámale.” Laura (cobranza): “El lunes 9 le marco.” Carlos: “Y las entregas antes de las 9, que después no dejan entrar a la obra.” Jorge: “Anotado. Te mando la cotización formal el martes, y los precios de 2027 los vemos en enero.”

## 3 · Su página web en 2 minutos
*Negocio*

```text
[Eléctrica Monte Alto], distribuidora de [material eléctrico] en [Monterrey], con 4 sucursales. Clientes: [contratistas y constructoras]. Nos distingue [la entrega el mismo día en obra]. Crea la página web de mi negocio para que [los contratistas] me pidan cotización por WhatsApp. Que se parezca a esta página que me gusta: [enlace a una página de referencia]. Por ejemplo, el encabezado: “Material eléctrico para su obra, hoy mismo.” Un archivo HTML, perfecto en celular: propuesta de valor, 3 beneficios, cómo trabajamos, preguntas frecuentes y botón de WhatsApp a wa.me/52[su número]. Moderno y limpio, en [azul marino y naranja]; textos cortos y directos para [gente de obra].
```

- **C · Contexto:** [Eléctrica Monte Alto], distribuidora de [material eléctrico] en [Monterrey], con 4 sucursales. Clientes: [contratistas y constructoras]. Nos distingue [la entrega el mismo día en obra].
- **H · Hazme:** Crea la página web de mi negocio para que [los contratistas] me pidan cotización por WhatsApp.
- **E · Ejemplo:** Que se parezca a esta página que me gusta: [enlace a una página de referencia]. Por ejemplo, el encabezado: “Material eléctrico para su obra, hoy mismo.”
- **V · Vista:** Un archivo HTML, perfecto en celular: propuesta de valor, 3 beneficios, cómo trabajamos, preguntas frecuentes y botón de WhatsApp a wa.me/52[su número].
- **E · Estilo:** Moderno y limpio, en [azul marino y naranja]; textos cortos y directos para [gente de obra].

## 4 · La radiografía financiera de 12 meses
*Negocio*

```text
Dirijo [una distribuidora de material eléctrico con matriz y 4 sucursales]. Te paso el estado de resultados y el balance de cada uno de los últimos 12 meses, exportados de mi contabilidad. Separa lo que es desempeño del negocio de lo que es error de registro contable, explica qué pasó en los meses malos y dime cuánto vale arreglar cada cosa. Cada hallazgo, así de concreto: “Hay $6.8 M de mercancía entregada sin facturar: facturarla en 30 días libera $6.8 M de caja.” Una página web: 4 hallazgos; tablero con semáforo de margen bruto y neto, días de cartera, inventario y proveedores, ciclo de efectivo, ROE y punto de equilibrio; margen mes a mes y 6 acciones con monto y plazo. Como director financiero ante el consejo: cifras exactas, sin jerga, y dime cuándo un dato no alcanza para concluir.
```

- **C · Contexto:** Dirijo [una distribuidora de material eléctrico con matriz y 4 sucursales]. Te paso el estado de resultados y el balance de cada uno de los últimos 12 meses, exportados de mi contabilidad.
- **H · Hazme:** Separa lo que es desempeño del negocio de lo que es error de registro contable, explica qué pasó en los meses malos y dime cuánto vale arreglar cada cosa.
- **E · Ejemplo:** Cada hallazgo, así de concreto: “Hay $6.8 M de mercancía entregada sin facturar: facturarla en 30 días libera $6.8 M de caja.”
- **V · Vista:** Una página web: 4 hallazgos; tablero con semáforo de margen bruto y neto, días de cartera, inventario y proveedores, ciclo de efectivo, ROE y punto de equilibrio; margen mes a mes y 6 acciones con monto y plazo.
- **E · Estilo:** Como director financiero ante el consejo: cifras exactas, sin jerga, y dime cuándo un dato no alcanza para concluir.

## 5 · ¿Quiénes son sus mejores clientes? (análisis RFM)
*Negocio*

```text
Soy dueño de [una distribuidora de material eléctrico con 420 clientes]. Te paso las ventas de los últimos 12 meses del ERP: cliente, fecha y monto. Haz un análisis RFM: qué tan reciente compró cada cliente, qué tan frecuente compra y cuánto monto deja. Agrúpalos en segmentos. Cada acción, así de concreta: “En riesgo (49 clientes, 8% de la venta): su vendedor les llama esta semana y les ofrece la entrega del mismo día.” Tabla de segmentos con número de clientes, % de la venta y una acción para cada uno, más la lista de clientes en riesgo. Práctico, para mi equipo de ventas: nada de estadística.
```

- **C · Contexto:** Soy dueño de [una distribuidora de material eléctrico con 420 clientes]. Te paso las ventas de los últimos 12 meses del ERP: cliente, fecha y monto.
- **H · Hazme:** Haz un análisis RFM: qué tan reciente compró cada cliente, qué tan frecuente compra y cuánto monto deja. Agrúpalos en segmentos.
- **E · Ejemplo:** Cada acción, así de concreta: “En riesgo (49 clientes, 8% de la venta): su vendedor les llama esta semana y les ofrece la entrega del mismo día.”
- **V · Vista:** Tabla de segmentos con número de clientes, % de la venta y una acción para cada uno, más la lista de clientes en riesgo.
- **E · Estilo:** Práctico, para mi equipo de ventas: nada de estadística.

## 6 · Tengo $1,000,000. ¿Dónde lo invierto?
*Dinero*

```text
Tengo [$1,000,000 MXN], [45 años], [casado y 3 hijos], soy dueño de [una distribuidora de material eléctrico]. Horizonte de [5 años], riesgo [medio]. Mi empresa rinde [5%] sobre el capital, pero un proyecto concreto de reinversión me dejaría [18%]. Compara CETES, fondos de deuda, ETF, bienes raíces, dólares, cripto y reinvertir en mi empresa; dime si me conviene un seguro de hombre clave y cómo repartir el dinero. Cada fila de la tabla así: “CETES | 6.2% a 7.1% | Ingreso · pasivo | Muy bajo | Sí / No”. Una tabla con rendimiento, cómo gana (ingreso o plusvalía, pasivo o activo), riesgo y si le gana a la inflación y a mi empresa. Luego la distribución y 5 preguntas para mi asesor. Como asesor independiente en México: sin venderme productos, con tasas actuales y fuentes.
```

- **C · Contexto:** Tengo [$1,000,000 MXN], [45 años], [casado y 3 hijos], soy dueño de [una distribuidora de material eléctrico]. Horizonte de [5 años], riesgo [medio]. Mi empresa rinde [5%] sobre el capital, pero un proyecto concreto de reinversión me dejaría [18%].
- **H · Hazme:** Compara CETES, fondos de deuda, ETF, bienes raíces, dólares, cripto y reinvertir en mi empresa; dime si me conviene un seguro de hombre clave y cómo repartir el dinero.
- **E · Ejemplo:** Cada fila de la tabla así: “CETES | 6.2% a 7.1% | Ingreso · pasivo | Muy bajo | Sí / No”.
- **V · Vista:** Una tabla con rendimiento, cómo gana (ingreso o plusvalía, pasivo o activo), riesgo y si le gana a la inflación y a mi empresa. Luego la distribución y 5 preguntas para mi asesor.
- **E · Estilo:** Como asesor independiente en México: sin venderme productos, con tasas actuales y fuentes.

## 7 · ¿Arrendamiento puro, financiero o de contado?
*Dinero*

```text
Mi distribuidora, persona moral, comprará [una camioneta SUV de $700,000 + IVA]. Opciones: puro a [36 meses en $19,500] o financiero con [10% de enganche al 15%]. Mi crédito bancario me cuesta [18%] al año. A 3 años, la camioneta valdrá [55%]. Compara puro, financiero y contado: ISR, IVA, caja y de quién es al final. Dime qué cambia si fuera pick-up. Una fila de la tabla así (en miles): “Lo que pago en 3 años, con IVA | Contado $812 | Financiero $993 | Puro $814”. Tabla con lo que pago, lo que recupero y el costo real a 3 años, en pesos y en valor presente, y tu recomendación en una frase. Como contador fiscalista en México, con la ley de 2026 y citando los artículos.
```

- **C · Contexto:** Mi distribuidora, persona moral, comprará [una camioneta SUV de $700,000 + IVA]. Opciones: puro a [36 meses en $19,500] o financiero con [10% de enganche al 15%]. Mi crédito bancario me cuesta [18%] al año. A 3 años, la camioneta valdrá [55%].
- **H · Hazme:** Compara puro, financiero y contado: ISR, IVA, caja y de quién es al final. Dime qué cambia si fuera pick-up.
- **E · Ejemplo:** Una fila de la tabla así (en miles): “Lo que pago en 3 años, con IVA | Contado $812 | Financiero $993 | Puro $814”.
- **V · Vista:** Tabla con lo que pago, lo que recupero y el costo real a 3 años, en pesos y en valor presente, y tu recomendación en una frase.
- **E · Estilo:** Como contador fiscalista en México, con la ley de 2026 y citando los artículos.

## 8 · Planear el viaje familiar
*Vida*

```text
Somos una familia de [Monterrey]: [2 adultos y 3 hijos de 8, 11 y 14 años]; podemos manejar hasta [6 horas] o volar; presupuesto total de [$140,000 MXN]. Nos gusta [la playa, la naturaleza y la buena comida]; no nos gustan [las filas largas]. Proponme 4 destinos para [6 días en diciembre], dime cuáles descartas y por qué, y recomiéndame uno. Cada día del itinerario así: “Dom 20: Islas Marietas en la mañana. Plan B si hay oleaje: día de alberca y club de niños.” Una tabla con costo, clima, qué tan bueno es para mis hijos, traslado y riesgos. Después, el itinerario día por día con plan B si llueve. Directo y práctico. Usa precios actuales de Booking, Expedia o Best Day con su enlace; si algo no cabe en el presupuesto, dímelo.
```

- **C · Contexto:** Somos una familia de [Monterrey]: [2 adultos y 3 hijos de 8, 11 y 14 años]; podemos manejar hasta [6 horas] o volar; presupuesto total de [$140,000 MXN]. Nos gusta [la playa, la naturaleza y la buena comida]; no nos gustan [las filas largas].
- **H · Hazme:** Proponme 4 destinos para [6 días en diciembre], dime cuáles descartas y por qué, y recomiéndame uno.
- **E · Ejemplo:** Cada día del itinerario así: “Dom 20: Islas Marietas en la mañana. Plan B si hay oleaje: día de alberca y club de niños.”
- **V · Vista:** Una tabla con costo, clima, qué tan bueno es para mis hijos, traslado y riesgos. Después, el itinerario día por día con plan B si llueve.
- **E · Estilo:** Directo y práctico. Usa precios actuales de Booking, Expedia o Best Day con su enlace; si algo no cabe en el presupuesto, dímelo.

## 9 · Las llantas de la camioneta
*Vida*

```text
Camioneta familiar: [Toyota RAV4 2022, llantas 225/65 R17]; vivimos en [Cumbres, Monterrey]. Máximo [120 km/h en ciudad y 160 en carretera]. Confirma la letra de velocidad y la carga originales. Recomiéndame opciones económica, intermedia y premium, y dime cuál comprarías tú y cuál si el precio no importara. Una fila de la tabla así: “Económica | Firestone All Season | H · 210 km/h | 102 | $2,599 | $10,396 | Costco”. Una tabla con marca y modelo, letra de velocidad, carga, precio por llanta y por juego de 4, y dónde comprarla cerca de casa. Honesto y concreto: cita de dónde sacaste cada precio y avísame qué costos no incluye.
```

- **C · Contexto:** Camioneta familiar: [Toyota RAV4 2022, llantas 225/65 R17]; vivimos en [Cumbres, Monterrey]. Máximo [120 km/h en ciudad y 160 en carretera].
- **H · Hazme:** Confirma la letra de velocidad y la carga originales. Recomiéndame opciones económica, intermedia y premium, y dime cuál comprarías tú y cuál si el precio no importara.
- **E · Ejemplo:** Una fila de la tabla así: “Económica | Firestone All Season | H · 210 km/h | 102 | $2,599 | $10,396 | Costco”.
- **V · Vista:** Una tabla con marca y modelo, letra de velocidad, carga, precio por llanta y por juego de 4, y dónde comprarla cerca de casa.
- **E · Estilo:** Honesto y concreto: cita de dónde sacaste cada precio y avísame qué costos no incluye.

## 10 · Carne asada
*Vida*

```text
Voy a hacer una carne asada en [mi casa en Monterrey] para [12 adultos y 20 niños]. Tengo [$5,000] para todo y queremos comer a las [3:00 pm]. Dime cuántos kilos de qué cortes comprar, qué más necesito y a qué hora prendo el carbón. La lista del súper así: “Carnicería: 3.5 kg de arrachera… · Súper: tortillas, carbón, cebollitas… · Bebidas: …”. Una tabla con cantidad, precio aproximado y dónde comprarlo; luego la lista del súper por sección y un horario desde que prendo el carbón hasta que se sirve. Práctico, como un parrillero con experiencia. Si no alcanza el presupuesto, dime qué quitar o qué corte cambiar.
```

- **C · Contexto:** Voy a hacer una carne asada en [mi casa en Monterrey] para [12 adultos y 20 niños]. Tengo [$5,000] para todo y queremos comer a las [3:00 pm].
- **H · Hazme:** Dime cuántos kilos de qué cortes comprar, qué más necesito y a qué hora prendo el carbón.
- **E · Ejemplo:** La lista del súper así: “Carnicería: 3.5 kg de arrachera… · Súper: tortillas, carbón, cebollitas… · Bebidas: …”.
- **V · Vista:** Una tabla con cantidad, precio aproximado y dónde comprarlo; luego la lista del súper por sección y un horario desde que prendo el carbón hasta que se sirve.
- **E · Estilo:** Práctico, como un parrillero con experiencia. Si no alcanza el presupuesto, dime qué quitar o qué corte cambiar.

## 11 · Mis estudios de laboratorio
*Vida*

```text
Tengo [45 años], soy [hombre o mujer]. Te adjunto mis estudios de laboratorio de [fecha]; ya tapé mi nombre y mis datos personales. Explícame mis resultados en palabras sencillas: qué está bien, qué está fuera de rango y qué significa. Una fila de la tabla así: “Glucosa | 104 | 70 a 99 | Un poco alta: pregúntele a su doctor si conviene repetirla en ayunas.” Una tabla con estudio, mi resultado, rango normal y qué significa en una línea. Al final, las 5 preguntas que le debo hacer a mi doctor. Claro y tranquilo, sin alarmar. No diagnostiques ni recetes; si algo requiere atención pronto, dímelo directo.
```

- **C · Contexto:** Tengo [45 años], soy [hombre o mujer]. Te adjunto mis estudios de laboratorio de [fecha]; ya tapé mi nombre y mis datos personales.
- **H · Hazme:** Explícame mis resultados en palabras sencillas: qué está bien, qué está fuera de rango y qué significa.
- **E · Ejemplo:** Una fila de la tabla así: “Glucosa | 104 | 70 a 99 | Un poco alta: pregúntele a su doctor si conviene repetirla en ayunas.”
- **V · Vista:** Una tabla con estudio, mi resultado, rango normal y qué significa en una línea. Al final, las 5 preguntas que le debo hacer a mi doctor.
- **E · Estilo:** Claro y tranquilo, sin alarmar. No diagnostiques ni recetes; si algo requiere atención pronto, dímelo directo.

> No sustituye al médico. Tape su nombre, CURP y número de expediente antes de subir el archivo.

## 12 · Asesor vocacional para mi hijo
*Vida*

```text
Mi hijo tiene [16 años] y estudia [preparatoria] en [Monterrey]. Le gusta [lo que usted sepa de él] y no sabe qué estudiar. Entrevístalo con 15 preguntas, de una o dos a la vez, esperando su respuesta. Al final, proponle 3 carreras con futuro frente a la IA. Las preguntas, de este tipo: “¿Qué materia te hace perder la noción del tiempo?” o “¿Prefieres trabajar con personas, con datos o con cosas?”. Al terminar, una tabla con las 3 carreras: por qué le queda, cómo la va a cambiar la IA, dónde se estudia en [Monterrey] y un primer paso para probarla este semestre. Háblale de tú, directo y sin sermones. Basa todo en sus respuestas, no en lo que yo quiera.
```

- **C · Contexto:** Mi hijo tiene [16 años] y estudia [preparatoria] en [Monterrey]. Le gusta [lo que usted sepa de él] y no sabe qué estudiar.
- **H · Hazme:** Entrevístalo con 15 preguntas, de una o dos a la vez, esperando su respuesta. Al final, proponle 3 carreras con futuro frente a la IA.
- **E · Ejemplo:** Las preguntas, de este tipo: “¿Qué materia te hace perder la noción del tiempo?” o “¿Prefieres trabajar con personas, con datos o con cosas?”.
- **V · Vista:** Al terminar, una tabla con las 3 carreras: por qué le queda, cómo la va a cambiar la IA, dónde se estudia en [Monterrey] y un primer paso para probarla este semestre.
- **E · Estilo:** Háblale de tú, directo y sin sermones. Basa todo en sus respuestas, no en lo que yo quiera.

> Que él escriba las respuestas, sin que nadie lo corrija.

## 13 · Remodelar su espacio
*Negocio*

```text
Te adjunto una foto de mi [oficina, taller o almacén] de [80 m²]. Ahí trabajan [6 personas] y lo que más se mueve es [el producto que más sale]. Propón un mejor acomodo para que se camine menos y todo se encuentre más rápido, y muéstrame cómo se vería. Cada cambio así: “Mover el producto que más sale junto a la salida: un 40% menos de caminata, costo $0.” Una lista de cambios ordenada por impacto, con costo aproximado de cada uno; luego una imagen de cómo quedaría. Práctico y con presupuesto de PyME: primero lo que se hace con lo que ya tengo.
```

- **C · Contexto:** Te adjunto una foto de mi [oficina, taller o almacén] de [80 m²]. Ahí trabajan [6 personas] y lo que más se mueve es [el producto que más sale].
- **H · Hazme:** Propón un mejor acomodo para que se camine menos y todo se encuentre más rápido, y muéstrame cómo se vería.
- **E · Ejemplo:** Cada cambio así: “Mover el producto que más sale junto a la salida: un 40% menos de caminata, costo $0.”
- **V · Vista:** Una lista de cambios ordenada por impacto, con costo aproximado de cada uno; luego una imagen de cómo quedaría.
- **E · Estilo:** Práctico y con presupuesto de PyME: primero lo que se hace con lo que ya tengo.

> La imagen la genera ChatGPT o Gemini; Claude le da el acomodo por escrito.

## 14 · Correr 5 km sin lastimarme
*Vida*

```text
Tengo [45 años], peso [85 kg], no corro desde hace [años] y tengo [3 mañanas de 30 minutos] a la semana. [No tengo lesiones]. Arma un plan de [8 semanas] para correr 5 km sin lastimarme. Cada semana así: “Semana 1: lunes, miércoles y viernes, 1 minuto trotando y 2 caminando, 8 veces.” Una tabla semana por semana con lo que hago cada día; aparte, el calentamiento, una rutina de fuerza de 10 minutos y las señales para parar. Como entrenador realista: progresión lenta y sin presiones. Recuérdame revisarme con mi médico antes de empezar.
```

- **C · Contexto:** Tengo [45 años], peso [85 kg], no corro desde hace [años] y tengo [3 mañanas de 30 minutos] a la semana. [No tengo lesiones].
- **H · Hazme:** Arma un plan de [8 semanas] para correr 5 km sin lastimarme.
- **E · Ejemplo:** Cada semana así: “Semana 1: lunes, miércoles y viernes, 1 minuto trotando y 2 caminando, 8 veces.”
- **V · Vista:** Una tabla semana por semana con lo que hago cada día; aparte, el calentamiento, una rutina de fuerza de 10 minutos y las señales para parar.
- **E · Estilo:** Como entrenador realista: progresión lenta y sin presiones. Recuérdame revisarme con mi médico antes de empezar.

## 15 · Un contrato antes de firmar
*Negocio*

```text
Soy [dueño de una distribuidora de material eléctrico] y me van a hacer firmar este [contrato de arrendamiento del local de la nueva sucursal]. Te lo adjunto; ya quité datos personales y cuentas. Revísalo y dime qué cláusulas me perjudican y qué puedo negociar. Una fila de la tabla así: “Renovación automática | Lo amarra 3 años más sin aviso | Alto | Propuesta: renovar solo con aviso por escrito 60 días antes.” Una tabla con cláusula, por qué me perjudica, riesgo (alto, medio o bajo) y una redacción alternativa que pueda proponer. Al final, las 3 que no firmaría así. Como abogado mexicano de mi lado, en lenguaje sencillo. Cita la ley cuando aplique y dime qué debe revisar mi abogado antes de firmar.
```

- **C · Contexto:** Soy [dueño de una distribuidora de material eléctrico] y me van a hacer firmar este [contrato de arrendamiento del local de la nueva sucursal]. Te lo adjunto; ya quité datos personales y cuentas.
- **H · Hazme:** Revísalo y dime qué cláusulas me perjudican y qué puedo negociar.
- **E · Ejemplo:** Una fila de la tabla así: “Renovación automática | Lo amarra 3 años más sin aviso | Alto | Propuesta: renovar solo con aviso por escrito 60 días antes.”
- **V · Vista:** Una tabla con cláusula, por qué me perjudica, riesgo (alto, medio o bajo) y una redacción alternativa que pueda proponer. Al final, las 3 que no firmaría así.
- **E · Estilo:** Como abogado mexicano de mi lado, en lenguaje sencillo. Cita la ley cuando aplique y dime qué debe revisar mi abogado antes de firmar.
