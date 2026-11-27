[English](README.md) · **Español**

# expense me

**Tus finanzas personales, privadas y gratis, en tu Mac.** Una app de
[Otherwise Technologies LLC](https://otherwisetech.com).

Recibos, cuentas y extractos, tarjetas, créditos, presupuesto, pagos pendientes, suscripciones,
ingresos y patrimonio en un solo lugar, en tu computador. Sin cuenta, sin suscripción.

> **Este repositorio solo tiene builds y documentación.** expense me es software propietario de
> código cerrado (gratis para usar); el código no está aquí. Aquí encuentras las descargas, las
> notas de cada versión y el lugar para reportar problemas.

## Qué hace

- **Inicio**: cuánto puedes gastar hoy sin pasarte, lo que vence pronto y lo que merece una mirada.
- **Recibos**: arrastra fotos o PDF a la ventana; se leen en tu computador y esperan a que los
  revises y los guardes.
- **Cuentas y extractos**: suelta tus extractos (PDF con contraseña, Excel, CSV) y quedan en la cuenta
  correcta, con sus movimientos y categorías.
- **Lo que debo**, **Mis tarjetas**, **Mis créditos** y **Simular un crédito**: saldos, tasas, cuotas,
  fechas de corte y de pago, un plan para salir de deudas y ofertas de crédito lado a lado.
- **Ingresos**, **Mi presupuesto**, **Pagos pendientes**, **Suscripciones**, **Patrimonio**, **Hogar**,
  **Calendario**, **Línea de tiempo** y **En qué se me va**.
- **Asistente** (⌘J), opcional: tu propio Claude Code, Codex u opencode, o un modelo de Ollama en tu
  computador, lee el libro abierto; cada cambio que propone es una tarjeta que tú aceptas (⌘Z lo deshace).
- En español, inglés, portugués y francés.

## Descargar e instalar

Requisitos: **macOS 11 o posterior en un Mac con Apple silicon** (M1 o posterior). Por ahora no hay
versión para Mac con Intel, Windows ni Linux.

1. Descarga **[expense-me-macos-arm64.zip](https://github.com/otherwisetech/expense-me-releases/releases/latest/download/expense-me-macos-arm64.zip)**
   (o elige una versión en [Releases](https://github.com/otherwisetech/expense-me-releases/releases)).
2. Abre el `.zip` y arrastra **expense me** a la carpeta **Aplicaciones**.
3. **La primera vez**, haz clic derecho (o Control-clic) sobre **expense me** → **Abrir** → **Abrir**.
   La app tiene firma *ad hoc* y no está notarizada por Apple, por eso macOS pregunta. Si macOS solo
   ofrece "Listo" o "Mover a la papelera" (macOS 15 o posterior), ve a **Ajustes del Sistema →
   Privacidad y seguridad** y pulsa **Abrir igualmente**. Después se abre normal. Si actualizas desde la 0.3.17 o
   anterior, macOS puede pedir una última vez acceso al llavero, para pasar tus claves guardadas:
   elige "Permitir siempre". Desde la 0.3.18, expense me las guarda en un archivo de tu computador
   que solo tu usuario puede leer, y no vuelve a preguntar.

También puedes instalarla y mantenerla al día con **Otherwise Hub**, el instalador gratuito de las
apps de Otherwise ([otherwisetech.com](https://otherwisetech.com)).

Para comprobar la descarga, cada release trae un archivo `.sha256`:

```
shasum -a 256 -c expense-me-macos-arm64.zip.sha256
```

## Privacidad: tus datos se quedan en tu computador

- Tus libros (recibos, extractos, movimientos) se guardan en una carpeta de tu computador que tú
  eliges (puede ser, por ejemplo, una carpeta de OneDrive). No hay cuenta ni servidor de Otherwise.
- expense me no envía tus datos a Otherwise ni a nadie. Solo se conecta a internet cuando tú lo pides:
  el servidor de correo que configures para recibir recibos, "Traer tasa de hoy en línea" (solo envía
  el par de monedas y la fecha) y, si lo usas, el asistente: lo que lee tu herramienta de IA va al
  proveedor de esa herramienta, salvo que uses Ollama en tu computador.
- Los avisos no muestran comercios ni valores, a menos que lo actives en Ajustes.

## Reportar un problema o pedir algo

Abre un [issue](https://github.com/otherwisetech/expense-me-releases/issues/new/choose) con la
plantilla de error o de idea. **Los issues son públicos: nunca incluyas datos personales ni
financieros reales** (nombres, montos, números de cuenta o tarjeta, extractos, recibos, rutas de tu
computador). Tapa esos datos en las capturas. Nunca te pediremos tu libro ni tus extractos.

Para una vulnerabilidad de seguridad, no abras un issue: lee [SECURITY.md](SECURITY.md).

## Licencia

Software propietario, gratis para usar. © 2026 Otherwise Technologies LLC, Wyoming, EE. UU. Todos los
derechos reservados. Ver [LICENSE](LICENSE). Los componentes de terceros conservan sus propias
licencias: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md). Cambios por versión:
[CHANGELOG.md](CHANGELOG.md).
