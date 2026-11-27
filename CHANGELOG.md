# Cambios en expense me

Todas las versiones son para macOS 11 o posterior en Mac con Apple silicon, con firma *ad hoc*
(la primera vez: clic derecho → Abrir). Las descargas están en
[Releases](https://github.com/otherwisetech/expense-me-releases/releases); las versiones anteriores a
0.3.17 no se publicaron en este repositorio.

## 0.3.17 (2026-11-27)

- **El aspecto de la familia de apps de Otherwise**: la barra lateral con el selector de libro, los
  atajos ⌘1–6, Ajustes y "Tus datos están en este computador"; el pie de página con la versión y
  "Acerca de"; botones y avisos iguales a los de las demás apps. Las pantallas y tus datos no cambian.
- Primera versión publicada en este repositorio público.

## 0.3.16 (2026-11-27)

- **Ingresos en cualquier moneda**: "Agregar ingreso fijo" y "Agregar ingreso esperado" tienen un
  selector de **Moneda** (COP, CAD, USD, EUR…).
- Cada valor dice su moneda ("COP $ 1.800.000", "CA$ 2,000.00"); lo que está en otra moneda muestra
  "≈ COP $ …" debajo.
- Las otras monedas se suman convertidas con la última tasa conocida en lo que esperas este mes, lo
  que puedes gastar, el pronóstico y la Línea de tiempo. Sin tasa, se muestran en su moneda y no se
  suman. Puedes escribir la tasa o pulsar **Traer tasa de hoy en línea** (solo envía el par de monedas
  y la fecha).
- Un pago en otra moneda se reconoce en una cuenta de esa moneda, o convertido.

## 0.3.15 (2026-11-26)

- **Agregar suscripción** y **Editar** en Suscripciones: quién te cobra, valor y moneda, cada cuánto
  (también "cada N meses"), próximo cobro, fin de la prueba gratis, si la pagas con una cuenta o una
  tarjeta, y cuántos días antes avisarte. ⌘Z deshace cualquier cambio.
- Las pruebas gratis muestran "Prueba gratis hasta …" y no cuentan en los totales hasta que terminan;
  recibes un aviso antes de que terminen.

## 0.3.14 (2026-11-25)

- **Lo que entra y lo que sale, mes a mes** en la Línea de tiempo: ingresos, gastos y ahorro por mes,
  los próximos tres meses estimados y el saldo de tus cuentas al final de cada mes.
- "Ya recibiste" y "Ya llegó" en Ingresos ahora coinciden; nada se cuenta dos veces.
- **Busca alternativas más económicas** en Suscripciones y en el asistente (busca solo con nombres de
  productos y categorías, nunca con números de cuenta).

## 0.3.13 (2026-11-25)

- **Mis ingresos**: tus ingresos fijos y los que esperas (seguro / probable / posible), lo esperado
  contra lo recibido este mes, con **Ya llegó** y **No va a llegar**, y un aviso cuando un pago se
  atrasa.
- Lo que puedes gastar y el pronóstico usan tus ingresos. El Calendario muestra los ingresos por llegar.

## 0.3.12 (2026-11-25)

- expense me aparece en el Calendario de **Otherwise Hub**: renovaciones, pagos de tarjeta y cuotas de
  crédito. Privado por defecto: sin valores, y las tarjetas y cuentas solo con sus últimos 4 dígitos.

## 0.3.11 (2026-11-24)

- **"Voy a pagar: Total / Mínimo / Otro monto"** en cada tarjeta de crédito, usado por el Calendario,
  lo que puedes gastar y los avisos.
- Los pagos ya no aparecen dos veces; "No mostrar más" oculta un cobro detectado.
- Saldos refinanciados de tarjetas, "Ajuste a tu favor", saldo real y cuotas en mora en Mis créditos.

## 0.3.10 (2026-11-24)

- **Línea de tiempo** (⌘6): cómo se movió tu plata día a día, con filtros, y **Lo que viene** en los
  próximos 60 días, con un aviso si una cuenta quedaría por debajo de cero.

## 0.3.8 (2026-11-24)

- **Revisa un recibo antes de guardarlo**: el documento al lado de lo que se leyó, con zoom, y corrige
  comercio, fecha, valor, moneda y categoría ahí mismo. ↑/↓ y Enter para ir rápido.

## 0.3.7 y anteriores (2026-11-23 y 2026-11-24)

- Recibos y movimientos rápidos con miles de registros; muchas menos peticiones del llavero.
- Guardar vuelve a funcionar cuando OneDrive sincroniza el libro abierto.
- Nuevo icono; nuevos diseños de Calendario, Ajustes (con apariencia clara, oscura o la del sistema),
  Recibos, Cuentas y extractos, Pagos pendientes, Mi presupuesto, En qué se me va y Patrimonio.
- Ollama en el asistente; nombres de comercios más limpios.
- Hogar, Simular un crédito con cronograma, Mis tarjetas y Mis créditos.
- 0.1.0: la primera versión: Inicio, Recibos, Cuentas, Lo que debo, Suscripciones, Mi presupuesto,
  Pagos pendientes, Patrimonio, Calendario, En qué se me va, Ajustes y el Asistente (⌘J).
