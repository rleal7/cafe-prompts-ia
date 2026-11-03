# Respuestas de los 15 casos

Cada caso trae el prompt completo, tal como va en la presentación, y la respuesta que dio Claude, para que compare con la suya.

**Por qué nunca sale idéntica.** La IA redacta distinto cada vez, igual que una persona que escribe dos veces el mismo correo. Lo que sí debe repetirse es la estructura, los números que vienen del prompt y la conclusión. Si a alguien le sale otra conclusión, casi siempre le faltó contexto. Las instrucciones guardadas (al final de esta pestaña) y un formato muy claro hacen que las respuestas salgan parecidas.

**Un solo negocio en los casos 1 a 7:** Eléctrica Monte Alto, distribuidora de material eléctrico en Monterrey (ficticia), con matriz y 4 sucursales, $120 millones de venta al año y 420 clientes. El dueño tiene 45 años, está casado y tiene 3 hijos (la misma familia del caso 8). Cambie “material eléctrico” por lo que usted vende: el prompt funciona igual.

## Caso 1 · Cobrar sin perder al cliente

**Prompt.** Soy dueño de una distribuidora de material eléctrico. Constructora Treviño, cliente de 10 años, me debe $180,000 de 3 facturas (1042, 1057 y 1063) con 90 días de vencidas y ya no contesta. Hoy es martes 3 de noviembre. Redáctame 3 mensajes para cobrarle, de menos a más presión: un recordatorio; una propuesta de pago en dos partes con fecha límite; y el aviso de que suspenderemos su crédito. WhatsApp de máximo 5 líneas cada uno, con el día y la hora para mandarlo; el tercero, también por correo desde la cuenta de cobranza. Al final, lo que NO debo decir. De usted, respetuoso y mexicano: el primero cordial, el segundo firme con una propuesta concreta y el tercero formal. Sin amenazas ni mayúsculas: valoro 10 años de relación.

**Respuesta.**

1. **Cordial · mañana, miércoles 4 de noviembre, 10:00 am.** “Hola, Ing. Treviño, buen día. Le doy seguimiento a las facturas 1042, 1057 y 1063 por $180,000. ¿Me apoya confirmando la fecha de pago? Saludos.”
2. **Firme · viernes 6, 10:00 am (dos días después).** “Ing. Treviño, las facturas por $180,000 ya suman 90 días. Para no afectar su crédito, le propongo $90,000 el viernes 13 y el resto el 27 de noviembre. ¿Me confirma a más tardar el lunes 9?”
3. **Formal · martes 10, 10:00 am (dos días hábiles después), por WhatsApp y por correo desde la cuenta de cobranza.** “Estimado Ing. Treviño: si no tenemos noticias del saldo de $180,000 antes del viernes 13, tendremos que suspender su crédito. Le envío este aviso también por correo.”

**Por qué ese calendario:** a media mañana de un día hábil se leen más los mensajes; dos días entre uno y otro dan tiempo de contestar sin que se enfríe; el correo del tercero deja constancia por escrito, desde una cuenta de la empresa y no desde su celular.

**Qué NO decir:** abogados o buró de crédito en el primer mensaje; mayúsculas o signos de admiración; reclamos personales (“ya me cansé”, “siempre es lo mismo”); mensajes fuera de horario o en fin de semana; amenazas que no va a cumplir.

## Caso 2 · La junta que nadie recuerda

**Transcripción que se le pega a la IA (ficticia, resumida).**

> Jorge (director): Cerremos el pedido de fin de año para Sierra Alta.
> Carlos (compras, Constructora Garza): Necesitamos 600 rollos de THW calibre 12 y 200 centros de carga de 12 circuitos.
> Jorge: Si son más de 500 rollos, te lo dejo en $1,450 el rollo; los centros de carga, en $1,180. El precio te lo sostengo hasta el 30 de noviembre, por el cobre.
> Carlos: ¿Me lo entregan en dos partes, mitad el 15 de diciembre y mitad el 12 de enero?
> Ana (almacén): Tengo 350 rollos; el resto lo pido a fábrica y te confirmo el viernes 6.
> Carlos: El ingeniero Mario me pasa la lista final el miércoles y te mando la orden el lunes 9. Y necesitamos 45 días de crédito.
> Jorge: Te lo amplío a 45 días si me mandas tus estados financieros a más tardar el 13.
> Carlos: Otra cosa: la factura 2291 de septiembre nos llegó con otro precio.
> Jorge: Laura, revísala y llámale. — Laura (cobranza): El lunes 9 le marco.
> Carlos: Y las entregas antes de las 9, que después no dejan entrar a la obra.
> Jorge: Anotado. Te mando la cotización formal el martes, y los precios de 2027 los vemos en enero.

**Prompt.** Soy dueño de una distribuidora de material eléctrico. Te paso la transcripción de la junta de 45 minutos con Constructora Garza para cerrar su pedido de fin de año. Haz la minuta de seguimiento: datos de la sesión (proyecto, fecha, duración, participantes), contexto, acuerdos, tareas nuestras y del cliente con responsable, fecha y prioridad, pendientes, riesgos, próximos pasos y notas. Documento Word con una tabla por sección, máximo 2 páginas. Incluye “Datos por confirmar”: nombres, cargos y cifras que no quedaron claros. Profesional y neutro. No inventes: si algo no se dijo, márcalo “por confirmar”.

**Respuesta.** La minuta completa, en el formato de 10 secciones (datos de la sesión, contexto, acuerdos, tareas del equipo, tareas del cliente, pendientes, datos por confirmar, riesgos, próximos pasos y notas), está en el PDF *Minuta_Constructora_Garza_001.pdf* del repositorio. Lo esencial:

| Acuerdo | Detalle |
|---|---|
| Volumen | 600 rollos de THW calibre 12 y 200 centros de carga de 12 circuitos |
| Precio | $1,450 por rollo (más de 500 rollos), sostenido hasta el 30 de noviembre; centros de carga a $1,180 |
| Entregas | 50% el 15 de diciembre y 50% el 12 de enero, en obra |
| Crédito | De 30 a 45 días si el cliente entrega estados financieros |

| Tarea | Responsable | Fecha |
|---|---|---|
| Enviar cotización formal | Jorge Elizondo | Martes 3 nov |
| Lista final de material (cliente) | Ing. Mario | Miércoles 4 nov |
| Confirmar con fábrica los 250 rollos faltantes | Ana Martínez | Viernes 6 nov |
| Orden de compra formal (cliente) | Carlos | Lunes 9 nov |
| Revisar la factura 2291 y llamar a Carlos | Laura Ríos | Lunes 9 nov |
| Estados financieros (cliente) | Carlos | Viernes 13 nov |

**Riesgos:** que fábrica no surta a tiempo; que suba el cobre; que la factura 2291 frene la orden.

**Datos por confirmar:** apellido de Carlos y nombre completo del residente; si los precios incluyen IVA; si el mínimo de 500 rollos es por entrega o por pedido total; dirección y horario de entrega en obra.

## Caso 3 · Una página que le pida cotizaciones

**Prompt.** Eléctrica Monte Alto, distribuidora de material eléctrico en Monterrey, con 4 sucursales. Clientes: contratistas y constructoras. Nos distingue la entrega el mismo día en obra. Crea la página web de mi negocio para que los contratistas me pidan cotización por WhatsApp. Un archivo HTML, perfecto en celular: propuesta de valor, 3 beneficios, cómo trabajamos, preguntas frecuentes y botón de WhatsApp a wa.me/52[NÚMERO]. Moderno y limpio, en azul marino y naranja; textos cortos y directos para gente de obra.

**Respuesta (el contenido de la página).**

- **Encabezado:** “Material eléctrico para su obra, hoy mismo.” Distribuidora para contratistas en Monterrey · 4 sucursales. Botones: Cotizar por WhatsApp · Ver catálogo.
- **Beneficios:** Mismo día (pida antes de las 12 y llega hoy) · Precio de contratista (lista especial por volumen) · Crédito a 30 días (para constructoras con historial).
- **Cómo trabajamos:** 1) mande su lista por WhatsApp; 2) le cotizamos en minutos; 3) entregamos en la obra.
- **Preguntas frecuentes:** a qué zonas entregan; si hay mínimo de compra; si facturan; formas de pago.

Es la página completa, lista para publicar; publicarla con su dominio y conectarla a su CRM es el siguiente paso. En vivo sale con otro diseño cada vez; lo que se repite son las secciones que pidió el formato.

## Caso 4 · Gana dinero, pero no le alcanza

**Prompt (versión completa).** Dirijo una distribuidora de material eléctrico con matriz y 4 sucursales. Te adjunto el estado de resultados y el balance de cada uno de los últimos 12 meses, exportados de mi contabilidad. Haz una radiografía financiera: separa lo que es desempeño del negocio de lo que es calidad del registro contable, explica por qué perdió cada mes en pérdida y cuantifica cuánto vale arreglar cada cosa. Entrégalo como una página web con: resumen ejecutivo de 4 hallazgos; tablero con semáforo de margen bruto y neto, días de cartera, inventario y proveedores, ciclo de efectivo, ROE y punto de equilibrio; venta y margen mes a mes; y 6 recomendaciones ordenadas por impacto, cada una con monto y plazo. Escribe como director financiero que reporta al consejo: cifras exactas, sin jerga, y dime cuándo un dato no alcanza para concluir.

**Respuesta: los 4 hallazgos.**

1. Vende $120 millones al año y gana, pero su capital rinde 5.2%: menos que CETES.
2. Tiene $28 millones de inventario que no se movió en 12 meses.
3. Hay $6.8 millones de mercancía entregada que no se ha facturado.
4. El margen mensual brinca de −4% (abril) a 30.1% (julio) con la venta estable: el costo no se está registrando junto con la venta.

**Los indicadores:** margen bruto promedio 19.4%; utilidad neta $3.4 M; ROE 5.2%; cartera 75 días; inventario 58 días; proveedores 35 días; ciclo de efectivo 99 días; punto de equilibrio $7.6 M al mes, con margen de seguridad de 23.5%; 3 de 12 meses en pérdida.

**Las 6 acciones.**

| # | Acción | Vale | Plazo |
|---|---|---|---|
| 1 | Facturar la mercancía ya entregada | $6.8 M | 30 a 60 días |
| 2 | Depurar el inventario sin movimiento | $28 M | 60 a 90 días |
| 3 | Costear la venta junto con la venta | $1.2 M por punto de margen | 90 a 120 días |
| 4 | Separar el ingreso por sucursal | Visibilidad | 30 días |
| 5 | Bajar la cartera de 75 a 60 días | $4.97 M liberados | — |
| 6 | Presupuestar las cuentas sin destino | $2.3 M | — |

Empresa ficticia. Con 12 meses, la relación entre margen y costo indica dirección, no prueba la causa.

## Caso 5 · ¿Quién dejó de comprarme?

**Prompt.** Soy dueño de una distribuidora de material eléctrico con 420 clientes. Te paso las ventas de los últimos 12 meses del ERP: cliente, fecha y monto. Haz un análisis RFM: qué tan reciente compró cada cliente, qué tan frecuente compra y cuánto monto deja. Agrúpalos en segmentos. Tabla de segmentos con número de clientes, % de la venta y una acción para cada uno, más la lista de clientes en riesgo. Práctico, para mi equipo de ventas: nada de estadística.

**Respuesta.**

| Segmento | Clientes | % de la venta | Qué hacer |
|---|---|---|---|
| Campeones | 38 | 41% | Trato VIP y crédito preferente |
| Leales | 64 | 22% | Ofrecer complementarios |
| Potenciales leales | 30 | 6% | Programa de lealtad |
| Nuevos | 40 | 4% | Bienvenida y segunda venta |
| No se pueden perder | 12 | 9% | Llamada del director |
| En riesgo | 49 | 8% | Su vendedor les llama esta semana |
| A punto de dormir | 57 | 4% | Oferta por WhatsApp |
| Dormidos | 130 | 6% | Campaña de reactivación |

**Conclusión:** 102 clientes (24%) hacen 63% de la venta. Hay 61 clientes en riesgo que valen 17% de la venta. Datos ficticios; con datos reales, la IA entrega además la lista con nombre de cada cliente en riesgo.

## Caso 6 · Tengo $1 millón disponible

**Prompt.** Tengo $1,000,000 MXN, 45 años, casado y 3 hijos, soy dueño de una distribuidora de material eléctrico. Horizonte de 5 años, riesgo medio. Mi empresa rinde 5% sobre el capital, pero un proyecto concreto de reinversión me dejaría 18%. Compara CETES, fondos de deuda, ETF, bienes raíces, dólares, cripto y reinvertir en mi empresa; dime si me conviene un seguro de hombre clave y cómo repartir el millón. Una tabla con rendimiento, cómo gana (ingreso o plusvalía, pasivo o activo), riesgo y si le gana a la inflación y a mi empresa. Luego la distribución y 5 preguntas para mi asesor. Como asesor independiente en México: sin venderme productos, con tasas actuales y fuentes.

**Respuesta: la tabla.** CETES son datos actuales; lo demás, rangos históricos, no promesas.

| Opción | Rendimiento anual | Cómo gana | Riesgo | ¿Gana a inflación / a su empresa? |
|---|---|---|---|---|
| CETES | 6.2% a 7.1% bruto (~5.5% a 6.2% neto) | Ingreso · pasivo | Muy bajo | Sí / No |
| Fondos de deuda | ~5.5% a 7% neto | Ingreso · pasivo | Bajo | Por poco / No |
| ETF de acciones | ~8% a 10% en dólares, histórico | Plusvalía · pasivo | Medio-alto | Probable / No |
| FIBRAs | ~6% a 9% + precio | Ingreso · pasivo | Medio | Sí / No |
| Un inmueble propio | Renta 5% a 6% + plusvalía | Ingreso · activo | Medio, ilíquido | Sí / No |
| Dólares | ± tipo de cambio | Cobertura · pasivo | Medio | Depende / No |
| Bitcoin | Sin rendimiento esperable | Especulación | Muy alto | Incierto |
| Proyecto en su empresa | 18% (su cálculo) | Ingreso · activo | Alto por concentración | Sí / — |

**Cómo repartir el millón (~9% a 10% al año, ilustrativo, bruto, antes de impuestos y comisiones):** 15% liquidez en CETES 28 días ($150,000); 25% deuda en CETES 1 año o Udibonos ($250,000); 25% ETF global en dólares ($250,000); 20% un proyecto concreto de su empresa ($200,000); 10% FIBRAs ($100,000); 5% bitcoin, opcional ($50,000).

**Seguro de hombre clave:** sí, pero no es lo primero. Con 3 hijos, lo urgente es un seguro de vida personal a plazo; el de hombre clave protege a la empresa, no a su familia. Las primas salen del flujo, no del millón.

**5 preguntas para su asesor:** ¿cómo te pagan?; ¿cuál es el rendimiento neto de comisiones e ISR comparado con CETES a 1 año?; ¿cuál fue la peor caída y cuánto tardó en recuperarse?; ¿cómo me diversificas si mi ingreso y mi patrimonio ya dependen de mi distribuidora?; ¿qué suma asegurada necesito en vida y en hombre clave, y quién es contratante y beneficiario?

Datos al 1 de noviembre de 2026: CETES de la subasta del 27 de octubre (28 días 6.22%, 182 días 6.80%, 1 año 7.11%), Banxico 6.50%, inflación 3.62% en la 1a quincena de octubre (INEGI). No es asesoría financiera.

## Caso 7 · La camioneta del director comercial

**Prompt (versión completa).** Mi distribuidora de material eléctrico (persona moral, ISR 30%) va a comprar una camioneta SUV de $700,000 más IVA para mi director comercial. Me ofrecen arrendamiento puro a 36 meses en $19,500 más IVA, o arrendamiento financiero con 10% de enganche al 15% anual y opción de compra. Mi línea de crédito me cuesta 18% al año, y a 3 años la camioneta valdrá 55% de su precio; si es mía, la vendo en ese momento. Compara puro, financiero y contado: deducción de ISR, IVA acreditable, ISR al venderla, caja y de quién es al final. Dame una tabla lado a lado con lo que pago, lo que recupero y el costo real a 3 años, en pesos y en valor presente al 18%. Dime qué cambia si fuera una pick-up de carga. Al final, tu recomendación en una frase. Responde como contador fiscalista en México, con la ley vigente de 2026 y citando los artículos.

**Respuesta: SUV (miles de pesos).**

| Concepto | Contado | Financiero | Puro |
|---|---|---|---|
| Lo que paga en 3 años, con IVA | $812 | $993 | $814 |
| − IVA que recupera | −$28 | −$34 | −$35 |
| − ISR que se ahorra | −$39 | −$51 | −$66 |
| − Lo que recibe al venderla, menos su ISR | −$283 | −$283 | No es suya |
| **= Le cuesta en pesos** | **$462** | **$625** | **$714** |
| **= En valor presente al 18%** | **$581** | **$555** | **$559** |

**Si es pick-up de carga:** en pesos, contado $221, financiero $330, puro $491; en valor presente, $381, $327 y $385.

**Fundamento.** SUV o auto de pasajeros: inversión deducible hasta $175,000 (art. 36, fracción II, LISR); renta de arrendamiento puro deducible hasta $200 diarios (art. 28, fracción XIII, LISR); IVA acreditable en la misma proporción (art. 5, fracción I, LIVA); intereses deducibles en la misma proporción (25%). Pick-up: solo si la factura y la tarjeta de circulación la clasifican como camión de carga y se usa en el negocio (las doble cabina de uso personal son las que el SAT cuestiona). Entonces no aplica el tope: se deduce completa al 25% anual (art. 34, fracción VI, LISR), los intereses y la renta del puro son 100% deducibles, y el IVA es 100% acreditable. Híbridos y eléctricos: $250,000 y $285 diarios.

**Recomendación:** arrendamiento financiero. Empata con el puro en una SUV y gana por unos $55 mil en una pick-up, y la camioneta es suya. El puro no pierde por la deducción (en pick-up es 100% deducible): pierde porque paga el 100% del precio en rentas y no se queda con nada. En pesos nominales gana el contado; si su dinero le cuesta 18% en el banco, lo que cuenta es el valor presente.

Supuestos: persona moral, ISR 30%; venta al mes 36 en $385,000 con ISR sobre la ganancia; arrendamiento financiero con IVA en cada pago; puro sin depósito ni opción de compra. No incluye seguro, mantenimiento ni comisiones. No es asesoría fiscal: confírmelo con su contador.

## Caso 8 · Las vacaciones de diciembre

**Prompt.** Somos una familia de Monterrey: 2 adultos y 3 hijos de 8, 11 y 14 años; podemos manejar hasta 6 horas o volar; presupuesto total de $140,000 MXN. Nos gusta la playa, la naturaleza y la buena comida; no nos gustan las filas largas. Proponme 4 destinos para 6 días en diciembre, dime cuáles descartas y por qué, y recomiéndame uno. Una tabla con costo, clima, qué tan bueno es para mis hijos, traslado y riesgos. Después, el itinerario día por día con plan B si llueve. Directo y práctico. Usa precios actuales de Booking, Expedia o Best Day con su enlace; si algo no cabe en el presupuesto, dímelo.

**Respuesta.** Fechas cotizadas: sábado 19 al jueves 24 de diciembre (regresan para Nochebuena). Vuelos en Expedia y hoteles todo incluido en Booking, consultados el 1 de noviembre de 2026.

| Destino | Traslado | Total | Clima dic. | Para sus hijos | Veredicto |
|---|---|---|---|---|---|
| Riviera Nayarit (Nuevo Vallarta) | Vuelo directo 1 h 40 | ~$124,000 | 27°/18°, seco | Islas Marietas, ballenas, surf en Sayulita | **Recomendado** |
| Riviera Maya (Playa del Carmen) | Vuelo 2 h 20 + 1 h | ~$100,000 | 28°/20°, posibles nortes | Cenotes, tortugas, parques | Alternativa |
| Los Cabos | Vuelo directo 2 h | ~$140,000 | 26°/15° | Arco y ballenas; mar poco nadable | Descartado |
| Huasteca Potosina | Auto, ~6 h | ~$50,000 | 24°/13° | Cascadas, sin playa; agua fría | Descartado |

**Urgente:** Booking muestra que 97% a 98% de los todo incluido de playa ya no tiene lugar para esas fechas. Aparte esta semana con cancelación gratis.

**Presupuesto Riviera Nayarit:** vuelos Volaris directos $22,645; maletas ~$5,000; Marival Emotions, suite de 2 recámaras, todo incluido, 5 noches $69,927; traslados $1,500; tour Islas Marietas $11,000; ballenas o tirolesa $7,500; Sayulita $2,500; extras $4,000. Total ~$124,000; sobran ~$16,000.

**Itinerario.** Sáb 19: vuelo 9:45, check-in y playa. Dom 20: Islas Marietas (si el oleaje cancela el barco, pasa al martes). Lun 21: Sayulita y San Pancho, clase de surf para los de 11 y 14 (plan B: centro de Puerto Vallarta). Mar 22: ballenas o tirolesa (plan B: Jardín Botánico). Mié 23: mañana libre, cena en el Malecón. Jue 24: última playa y vuelo de regreso a mediodía.

Los precios cambian a diario; los de tours, maletas y traslados son estimados.

## Caso 9 · Las llantas de la camioneta

**Prompt.** Camioneta familiar: Toyota RAV4 2022, llantas 225/65 R17; vivimos en Cumbres, Monterrey. Máximo 120 km/h en ciudad y 160 en carretera. Confirma la letra de velocidad y la carga originales. Recomiéndame opciones económica, intermedia y premium, y dime cuál comprarías tú y cuál si el precio no importara. Una tabla con marca y modelo, letra de velocidad, carga, precio por llanta y por juego de 4, y dónde comprarla cerca de casa. Honesto y concreto: cita de dónde sacaste cada precio y avísame qué costos no incluye.

**Respuesta.** Especificación de fábrica: 225/65 R17 102H (carga 850 kg por llanta, hasta 210 km/h). Regla: carga 102 o más y letra H o más. Confírmela en la etiqueta del marco de la puerta del conductor.

| Nivel | Llanta | Velocidad | Carga | Por llanta | Juego de 4 | Dónde |
|---|---|---|---|---|---|---|
| Económica | Firestone All Season | H · 210 | 850 kg | $2,599 | $10,396 | Costco (Liverpool $2,358) |
| Intermedia | Continental ProContact TX | H · 210 | 850 kg | $3,109 | $12,436 | Liverpool (marketplace) |
| **Premium** | **Michelin Primacy SUV+ XL** | **H · 210** | **950 kg** | **$3,699** | **$14,796** | **Costco Cumbres** |
| Sin límite | Michelin Pilot Sport 4 SUV XL | V · 240 | 950 kg | $4,178 | $16,711 | Liverpool |

**Evite la Bridgestone Dueler 102T** ($3,199 en Costco): buena llanta, pero la letra T (190 km/h) está abajo de la H de fábrica.

**La que compraría:** Michelin Primacy SUV+ en Costco Cumbres ($14,796 el juego): $4,400 más que la Firestone, frena mejor en mojado, dura más y es más silenciosa. **Si el precio no importara:** la Pilot Sport 4 SUV agarra mejor, pero es deportiva, dura menos y es menos cómoda; para este uso, la Primacy de todos modos.

**Lo que no incluyen los precios:** membresía de Costco (a cambio incluye montaje, válvulas, balanceo, rotación y ponchaduras de por vida); en Liverpool, montaje, balanceo y válvulas; alineación; sensores de presión si se dañan; desecho de llantas viejas.

Precios con IVA consultados el 1 de noviembre de 2026 en costco.com.mx y liverpool.com.mx. Caso ficticio.

## Casos 10 a 15 · Para usar desde mañana

Respuestas de Claude con datos de ejemplo. En los casos 11, 13 y 15 el prompt pide adjuntar un archivo (estudios, foto o contrato): aquí se usó uno ficticio para mostrar cómo responde. Con su archivo, la respuesta sale sobre sus datos.

## Caso 10 · Carne asada

**Prompt.** Voy a hacer una carne asada en [mi casa en Monterrey] para [12 adultos y 20 niños]. Tengo [$5,000] para todo y queremos comer a las [3:00 pm]. Dime cuántos kilos de qué cortes comprar, qué más necesito y a qué hora prendo el carbón. Una tabla con cantidad, precio aproximado y dónde comprarlo; luego la lista del súper por sección y un horario desde que prendo el carbón hasta que se sirve. Práctico, como un parrillero con experiencia. Si no alcanza el presupuesto, dime qué quitar o qué corte cambiar.

**Respuesta.** Cuenta: 350 g de carne por adulto y 200 g por niño, unos 8 kg en total. Sí alcanza: gasta unos $4,550 y le sobran unos $450 para imprevistos.

| Qué | Cantidad | Precio aprox. | Dónde |
|---|---|---|---|
| Arrachera | 3 kg | $1,140 | Carnicería de confianza o HEB |
| Aguja norteña o diezmillo | 2.5 kg | $600 | Carnicería |
| Salchicha para asar (los niños) | 1.5 kg | $180 | HEB o Soriana |
| Chorizo | 1 kg | $130 | Carnicería |
| Tortillas de harina y de maíz | 60 de harina y 2 kg de maíz | $230 | Tortillería |
| Carbón | 3 bolsas de 4 kg | $330 | HEB o gasolinera |
| Verdura: cebollitas, chiles, aguacate, tomate, cebolla, cilantro, limón | Para 32 personas | $390 | Mercado o HEB |
| Frijoles charros | 1 olla grande | $200 | HEB |
| Queso para asar o panela | 1 kg | $180 | HEB |
| Botana: papas, totopos, salsa | Para la espera | $250 | HEB |
| Bebidas: refresco, agua, hielo | 8 refrescos de 3 L, agua y 4 bolsas de hielo | $590 | HEB u Oxxo |
| Desechables y aluminio | Platos, vasos, servilletas | $330 | HEB |
| **Total** | | **~$4,550** | |

**Lista del súper por sección.** Carnicería: arrachera, aguja, chorizo. Salchichonería: salchicha, queso. Frutas y verduras: cebollitas, jalapeños, aguacate, tomate, cebolla, cilantro, limones. Abarrotes: frijoles, totopos, papas, salsa, sal de grano. Bebidas: refrescos, agua, hielo. Varios: carbón, encendedor o chimenea para prender, papel aluminio, platos, vasos, servilletas.

**Horario para comer a las 3:00**

| Hora | Qué hacer |
|---|---|
| 1:45 | Prenda el carbón. Con chimenea, sin petróleo |
| 2:15 | Brasas blancas. Salchicha, chorizo, cebollitas y queso |
| 2:30 | Comen los niños. Entra la aguja |
| 2:45 | Arrachera, 4 a 5 minutos por lado. Que repose 5 minutos antes de cortarla |
| 3:00 | Se sirve a los adultos |

**Si no alcanza:** cambie 1 kg de arrachera por aguja y se ahorra unos $140. La cerveza no cabe en el presupuesto: que cada quien traiga la suya.

Precios aproximados en Monterrey, noviembre de 2026; cambian por carnicería.

## Caso 11 · Mis estudios de laboratorio

**Prompt.** Tengo [45 años], soy [hombre o mujer]. Te adjunto mis estudios de laboratorio de [fecha]; ya tapé mi nombre y mis datos personales. Explícame mis resultados en palabras sencillas: qué está bien, qué está fuera de rango y qué significa. Una tabla con estudio, mi resultado, rango normal y qué significa en una línea. Al final, las 5 preguntas que le debo hacer a mi doctor. Claro y tranquilo, sin alarmar. No diagnostiques ni recetes; si algo requiere atención pronto, dímelo directo.

**Respuesta (estudio de ejemplo, ficticio, de un hombre de 45 años).** En general, bien: la sangre, los riñones y la tiroides están en rango. Lo que hay que trabajar son las grasas en la sangre y el azúcar, que salieron un poco arriba. Nada de esto es urgente, pero vale la pena verlo con su médico en las próximas semanas.

| Estudio | Su resultado | Rango normal | Qué significa |
|---|---|---|---|
| Glucosa en ayuno | 108 mg/dL | 70–99 | Un poco arriba. Si se repite, su doctor puede pedir hemoglobina glucosilada |
| Colesterol total | 228 mg/dL | Menos de 200 | Alto |
| Colesterol LDL ("malo") | 148 mg/dL | Menos de 130 | Alto: es el que se pega en las arterias |
| Colesterol HDL ("bueno") | 38 mg/dL | Más de 40 | Bajo: conviene subirlo |
| Triglicéridos | 210 mg/dL | Menos de 150 | Altos. Suelen subir con azúcares, harinas y alcohol |
| Hemoglobina | 15.2 g/dL | 13.5–17.5 | Bien: no hay anemia |
| Leucocitos | 6,800 | 4,500–11,000 | Bien: sin señal de infección |
| Plaquetas | 250,000 | 150,000–450,000 | Bien |
| Creatinina | 1.0 mg/dL | 0.7–1.3 | Bien: los riñones filtran normal |
| TGP (ALT), hígado | 52 U/L | 7–41 | Ligeramente alta. Es común con triglicéridos altos |
| Ácido úrico | 7.4 mg/dL | 3.5–7.2 | Ligeramente alto |
| TSH, tiroides | 2.1 µUI/mL | 0.4–4.0 | Bien |

Los rangos cambian por laboratorio: use los que vienen en su hoja.

**Las 5 preguntas para su doctor**
1. ¿Mi glucosa de 108 amerita una hemoglobina glucosilada?
2. Con mi colesterol y mis triglicéridos, ¿cuál es mi riesgo cardiovascular y en cuánto tiempo repito el estudio?
3. ¿Qué cambios de comida y ejercicio me recomienda primero, antes de pensar en medicamento?
4. La TGP un poco alta, ¿necesita un ultrasonido de hígado?
5. El ácido úrico, ¿qué tengo que cuidar y cuándo lo vuelvo a medir?

No sustituye al médico: es para llegar a la consulta sabiendo qué preguntar.

## Caso 12 · Asesor vocacional para mi hijo

**Prompt.** Mi hijo tiene [16 años] y estudia [preparatoria] en [Monterrey]. Le gusta [lo que usted sepa de él] y no sabe qué estudiar. Entrevístalo con 15 preguntas, de una o dos a la vez, esperando su respuesta. Al final, proponle 3 carreras con futuro frente a la IA. Al terminar, una tabla con las 3 carreras: por qué le queda, cómo la va a cambiar la IA, dónde se estudia en [Monterrey] y un primer paso para probarla este semestre. Háblale de tú, directo y sin sermones. Basa todo en sus respuestas, no en lo que yo quiera.

**Respuesta.** Claude empieza así: "Hola. No hay respuestas buenas ni malas, y nada de esto es un examen. Primera: ¿qué materia o actividad te hace perder la noción del tiempo?" Y así sigue, de una o dos preguntas a la vez. Las 15 preguntas:

1. ¿Qué materia o actividad te hace perder la noción del tiempo?
2. ¿Qué materia te cuesta más, y es porque no te gusta o porque no le entiendes?
3. ¿Prefieres trabajar con personas, con datos o con cosas que se arman?
4. Si tuvieras un sábado libre y $1,000, ¿en qué los gastarías?
5. ¿Qué te piden tus amigos que les ayudes a hacer?
6. ¿Te gusta más planear o ejecutar?
7. ¿Qué problema de tu ciudad o del mundo te gustaría resolver?
8. ¿Te ves en una oficina, en campo, en un laboratorio o viajando?
9. ¿Qué video de YouTube o qué tema has investigado por tu cuenta, sin que te lo pidan?
10. ¿Prefieres un trabajo estable o uno con riesgo y más premio?
11. ¿Cómo te va cuando tienes que hablar en público o convencer a alguien?
12. ¿Qué es lo que menos quieres hacer el resto de tu vida?
13. ¿A quién admiras por su trabajo, y por qué?
14. Si la IA hiciera la parte aburrida de cualquier trabajo, ¿qué parte te quedarías tú?
15. ¿Qué carrera te han dicho que estudies, y qué opinas tú?

**Ejemplo de resultado (respuestas de un alumno ficticio):** le gustan las matemáticas y armar cosas, juega videojuegos, es capitán de su equipo de futbol y no le gusta memorizar.

| Carrera | Por qué te queda | Cómo la va a cambiar la IA | Dónde en Monterrey | Primer paso este semestre |
|---|---|---|---|---|
| Ingeniería en robótica o mecatrónica | Te gusta armar cosas y las matemáticas te salen | La IA diseña y simula; tú decides, construyes y lo pones a funcionar en el mundo real | Tec de Monterrey, UANL (FIME), UDEM | Un taller de robótica o un kit de Arduino en casa |
| Ingeniería en ciencia de datos | Te gustan los números y no memorizar | La IA hace los cálculos; vale más quien sabe qué preguntar y cómo explicarlo | Tec de Monterrey, UANL (FCFM) | Un curso gratis de Python y analizar las estadísticas de tu equipo |
| Ingeniería industrial y de sistemas | Eres capitán: organizas gente y procesos | La IA optimiza rutas e inventarios; tú diriges a las personas que la usan | Tec de Monterrey, UDEM, UANL (FIME) | Visitar una planta o un centro de distribución con alguien que trabaje ahí |

Confirma nombres y planes de estudio en la página de cada universidad, porque cambian.

## Caso 13 · Remodelar su espacio

**Prompt.** Te adjunto una foto de mi [oficina, taller o almacén] de [80 m²]. Ahí trabajan [6 personas] y lo que más se mueve es [el producto que más sale]. Propón un mejor acomodo para que se camine menos y todo se encuentre más rápido, y muéstrame cómo se vería. Una lista de cambios ordenada por impacto, con costo aproximado de cada uno; luego una imagen de cómo quedaría. Práctico y con presupuesto de PyME: primero lo que se hace con lo que ya tengo.

**Respuesta (ejemplo: almacén de una sucursal de 80 m², 6 personas; lo que más sale es cable THW calibre 12, contactos y apagadores).** La regla: lo que más sale va más cerca del mostrador y a la altura de la cintura. Lo que menos sale va al fondo y arriba.

| # | Cambio | Por qué | Costo aprox. |
|---|---|---|---|
| 1 | Los 20 productos que más salen, en el primer rack junto al mostrador, a la altura de la cintura | Ahí está la mayoría de los surtidos del día | $0 |
| 2 | Sacar del piso las cajas que estorban y dejar un pasillo principal de 1.2 m | Se camina en línea recta y nadie se tropieza | $0 |
| 3 | Lo voluminoso y lento (tubo conduit, charolas, registros) al fondo y en la parte alta | Libera el espacio cercano para lo que sí rota | $0 |
| 4 | Etiquetar cada rack con una ubicación (por ejemplo A-1-3) y cargarla en el sistema | Cualquiera encuentra todo, no solo el que lleva años | ~$1,500 |
| 5 | Cinta de piso para marcar pasillos, zona de recibo y zona de entrega | Orden visual y seguridad | ~$800 |
| 6 | Una mesa de surtido y empaque pegada al mostrador | Se arma el pedido sin ir y venir | ~$4,000 |
| 7 | Rack de carretes para el cable, junto a la salida, con medidor de metros | Se corta el cable sin cargar carretes | $8,000–$15,000 |
| 8 | Luz LED en los pasillos | Se lee la etiqueta a la primera | ~$6,000 |

Los primeros tres cambios cuestan $0 y son los que más se notan. Con el 4 y el 5 se gastan unos $2,300.

**La imagen.** Claude da el acomodo por escrito. Para verlo, se pide en ChatGPT o Gemini con la misma foto: "Con esta foto de mi almacén, genera una imagen de cómo se vería con este acomodo: [pegue la lista]. Vista desde la entrada, realista, iluminación blanca."

## Caso 14 · Correr 5 km sin lastimarme

**Prompt.** Tengo [45 años], peso [85 kg], no corro desde hace [años] y tengo [3 mañanas de 30 minutos] a la semana. [No tengo lesiones]. Arma un plan de [8 semanas] para correr 5 km sin lastimarme. Una tabla semana por semana con lo que hago cada día; aparte, el calentamiento, una rutina de fuerza de 10 minutos y las señales para parar. Como entrenador realista: progresión lenta y sin presiones. Recuérdame revisarme con mi médico antes de empezar.

**Respuesta.** Antes de empezar, revísese con su médico: a los 45 años y después de años sin correr, conviene un chequeo y, si él lo indica, una prueba de esfuerzo. El plan es de 3 días por semana, nunca dos días seguidos (por ejemplo, lunes, miércoles y viernes). Cada sesión empieza con 5 minutos de calentamiento caminando y termina con 3 minutos caminando.

| Semana | Lunes | Miércoles | Viernes |
|---|---|---|---|
| 1 | 6 × (1 min trote + 2 min caminar) | Igual | Igual |
| 2 | 5 × (2 min trote + 2 min caminar) | Igual | Igual |
| 3 | 4 × (3 min trote + 2 min caminar) | Igual | Igual + fuerza |
| 4 | 3 × (5 min trote + 2 min caminar) | Igual | Igual |
| 5 | 2 × (8 min trote + 2 min caminar) | Igual | Igual + fuerza |
| 6 | 2 × (10 min trote + 1 min caminar) | Igual | Igual + fuerza |
| 7 | 20 min seguidos | 2 × (12 min trote + 1 min caminar) | 22 min seguidos |
| 8 | 25 min seguidos | 20 min suaves | **5 km** a su ritmo, unos 32 a 38 minutos (ese día reserve 45) |

Si una semana le costó, repítala. No pasa nada.

**Calentamiento (5 minutos):** caminar rápido 3 minutos, círculos de tobillo y cadera, y 10 elevaciones de rodilla por lado.

**Fuerza (10 minutos, 2 vueltas):** 12 sentadillas a una silla, 10 zancadas por pierna, 12 puentes de glúteo, 15 elevaciones de talón y 30 segundos de plancha. Hágala después de correr el viernes o en un día libre.

**Señales para parar y llamar al médico:** dolor u opresión en el pecho, mareo, falta de aire que no le deja hablar ni al bajar el ritmo, o palpitaciones raras. **Señales para parar y descansar:** dolor punzante en rodilla, espinilla o tobillo, o dolor que al día siguiente está peor. Cansancio y algo de dolor muscular sí son normales.

## Caso 15 · Un contrato antes de firmar

**Prompt.** Soy [dueño de una distribuidora de material eléctrico] y me van a hacer firmar este [contrato de arrendamiento del local de la nueva sucursal]. Te lo adjunto; ya quité datos personales y cuentas. Revísalo y dime qué cláusulas me perjudican y qué puedo negociar. Una tabla con cláusula, por qué me perjudica, riesgo (alto, medio o bajo) y una redacción alternativa que pueda proponer. Al final, las 3 que no firmaría así. Como abogado mexicano de mi lado, en lenguaje sencillo. Cita la ley cuando aplique y dime qué debe revisar mi abogado antes de firmar.

**Respuesta (contrato de ejemplo, ficticio: local comercial en Monterrey, 5 años).**

| Cláusula | Por qué le perjudica | Riesgo | Lo que puede proponer |
|---|---|---|---|
| Plazo forzoso de 5 años; si sale antes, paga todas las rentas que faltan | Si la sucursal no funciona, paga años de un local vacío | Alto | "Plazo forzoso de 12 meses. Después, el arrendatario puede terminar con aviso de 90 días y una pena de 2 meses de renta." La pena convencional no puede ser mayor que la obligación principal (art. 1843 del Código Civil Federal; el Código Civil de Nuevo León tiene una regla equivalente) |
| Incremento anual: inflación (INPC) más 5 puntos, o 10%, lo que sea mayor | En 5 años la renta sube casi 50%, aunque la inflación sea baja | Alto | "Incremento anual igual al INPC, con tope de 6%." |
| Mantenimiento mayor (techo, estructura, instalación eléctrica general) a cargo del arrendatario | Paga reparaciones de un inmueble que no es suyo | Alto | "El arrendador se encarga de la estructura, el techo y las instalaciones generales; el arrendatario, del mantenimiento menor y del desgaste por uso." Por ley, el arrendador debe conservar el local en estado de servir para lo que se rentó |
| Usted como dueño firma como obligado solidario (aval personal) | Si la empresa no paga, responde con su patrimonio | Alto | "En lugar de aval, una póliza de fianza o un depósito adicional de un mes." |
| Uso de suelo y licencias a cargo del arrendatario, sin garantía del arrendador | Si el municipio no da la licencia, sigue pagando un local que no puede abrir | Alto | "El arrendador garantiza uso de suelo comercial compatible con la venta de material eléctrico. Si no se obtiene la licencia en 60 días, el arrendatario puede terminar sin pena y se le devuelve el depósito." |
| Depósito de 3 meses, devolución "a juicio del arrendador" | Puede quedarse con el depósito sin explicar por qué | Medio | "Depósito de 1 mes, devuelto en 30 días contra acta de entrega con fotos, descontando solo daños documentados." |
| Las mejoras quedan en el inmueble sin pago | Pierde racks, aire acondicionado y la instalación que usted pagó | Medio | "El arrendatario puede retirar las instalaciones removibles; las fijas se le descuentan de la renta o se le pagan a valor en libros." |
| No puede subarrendar ni ceder, ni a empresas de su grupo | Si reestructura su empresa, el contrato estorba | Bajo | "Se permite ceder a empresas del mismo grupo con aviso por escrito." |
| Jurisdicción en tribunales de la Ciudad de México | Un pleito le costaría viajes y abogados en otra ciudad | Bajo | "Tribunales de Monterrey, Nuevo León." |

**Las 3 que no firmaría así:** la salida con todas las rentas restantes, el aval personal y la licencia sin garantía de uso de suelo. Juntas pueden costarle más que la sucursal.

**Qué debe revisar su abogado antes de firmar**
- Que quien firma sea el dueño, o un apoderado con poder vigente.
- La escritura del local y el predial al corriente.
- El uso de suelo en el municipio.
- Si el arrendador es persona física, que su contador confirme las retenciones (10% de ISR y dos terceras partes del IVA) y que el arrendador le dé CFDI.
- Que el contrato diga qué pasa si el local se inunda, se daña o lo clausuran.

No es asesoría legal: con esta tabla llega con su abogado sabiendo qué negociar.

## Ejemplo real en Claude · abogado del diablo

**Prompt.** Tengo una distribuidora de material eléctrico en Monterrey con matriz y 4 sucursales; vendemos $120 millones al año. Quiero abrir una quinta sucursal en la zona de Cumbres con $1.5 millones de inversión. Hazme de abogado del diablo: dime los 5 huecos más grandes de este plan, del más grave al menos grave, con una pregunta concreta que debo poder contestar antes de firmar la renta de cada uno. Directo, sin rodeos, en una tabla.

**Respuesta (conversación nueva en Claude).** Vendes $120 millones entre 5 puntos, unos $24 millones por punto de venta: si la nueva aspira a algo parecido, $1.5 millones no alcanzan ni para el inventario.

| # | Hueco | Pregunta antes de firmar la renta |
|---|---|---|
| 1 | No hay demanda comprobada: Cumbres es residencial y la venta fuerte viene de contratistas, constructoras e industria | ¿Qué 20 clientes u obras con nombre te van a comprar ahí en 6 meses, cuánto le compran hoy a la competencia y cuánto está confirmado? |
| 2 | $1.5 millones no cubren el capital de trabajo: con margen de 20%, rotación de 6 y 45 días de crédito, una sucursal de $18 millones necesita ~$2.4 millones de inventario y ~$2.2 millones de cartera | ¿Cuánto inventario y cartera necesitas al mes 6 y al 12, de dónde sale y qué le pasa a la matriz? |
| 3 | Canibalización: si ya surtes la zona desde otra sucursal, solo repartes la venta y duplicas gasto fijo | ¿Qué porcentaje de tu venta se entrega hoy a 5 km del local, y desde qué sucursal? |
| 4 | Sin punto de equilibrio ni costo de salida: una sucursal tarda 12 a 24 meses en madurar | ¿Cuánto debe vender al mes para no perder, cuándo llega y cuánto cuesta salirte del contrato? |
| 5 | Nadie con nombre a cargo: la sucursal la hace el gerente | ¿Quién es el gerente, qué clientes trae y quién autoriza crédito y audita inventario el primer año? |

**Regla práctica:** si no puedes contestar la 1 y la 2 con números, no firmes. Negocia una carta de intención con 60 días de exclusividad y úsalos para conseguir las respuestas.

## Instrucciones permanentes · el CAFÉ fijo

**Texto 1 · Sobre mí y mi empresa.** “Soy [su nombre], [su puesto] de [su empresa], [giro] en [ciudad]. Somos [N] personas y le vendemos a [tipo de clientes]. Usamos [su sistema o ERP].” Ejemplo de la charla: “Soy Jorge Elizondo, director de Eléctrica Monte Alto, distribuidora de material eléctrico en Monterrey, con matriz y 4 sucursales y $120 millones de venta. Le vendemos a constructoras, contratistas e industria.”

**Texto 2 · Cómo quiero que respondas.** “En español de México, de usted, directo y práctico. Primero la conclusión y luego el detalle. Usa tablas para comparar. Si te falta un dato, pregúntamelo: no lo inventes. En impuestos y leyes, cita la fuente.”

**Dónde se guarda:**

- **ChatGPT:** Configuración › Personalización › Instrucciones personalizadas. El texto 1 y el texto 2 van en sus casillas.
- **Claude:** Configuración › Perfil › Preferencias personales, para todo. O un Proyecto por área (cobranza, finanzas, ventas) con sus propias instrucciones y archivos.
- **Gemini:** un Gem con los dos textos como instrucciones, o decirle “Recuerda que…” para que lo guarde en su información.

Los menús cambian de nombre seguido: si no se encuentra, buscar “personalización” o “instrucciones”.
