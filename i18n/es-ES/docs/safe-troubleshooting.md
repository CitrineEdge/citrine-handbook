# Diagnóstico seguro para el trading en el dispositivo

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Un informe claro es más útil que un volcado completo de la cuenta. Registre el
comportamiento antes de cambiar ajustes o reinstalar la aplicación, ya que esto
puede eliminar pruebas locales útiles.

## Campos útiles para el informe

```text
Versión/build de la aplicación:
Versión de Android y modelo del dispositivo:
Modo y estado de ejecución:
Hora aproximada del evento y zona horaria:
Pantalla o acción:
Comportamiento esperado:
Comportamiento observado:
¿Se puede repetir? En caso afirmativo, pasos mínimos:
Texto de error, si existe, sin identificadores de cuenta:
```

No incluya claves API, claves privadas, frases de recuperación, tokens de acceso,
tokens de compra de Google Play, registros bancarios o fiscales ni identificadores
completos de órdenes de la bolsa. Oculte nombres de cuenta, saldos y contenido de
notificaciones en capturas públicas cuando no sean necesarios. Revise las
exportaciones antes de compartirlas; un archivo JSON no es anónimo por no parecerse a una fotografía.

## Observe primero

- Distinga una pantalla que aún carga de un cero confirmado, un dato no disponible
  o una ejecución pausada. Registre el estado exacto en vez de parafrasearlo.
- Indique si la posición se abrió externamente o desde la aplicación y qué
  dispositivo la gestionaba. Observation supervisa, no controla la ejecución.
- Consulte Coinbase directamente cuando se trate de una orden o posición real.
  No pulse repetidamente una acción de orden solo porque la pantalla tarde en actualizarse.
- Anote conectividad, reinicios, cambios de funcionamiento en segundo plano y
  momento de las actualizaciones. Son pistas de diagnóstico, no pruebas de una causa.
- No realice operaciones solo para reproducir un fallo de interfaz. Empiece con
  Paper o con una reproducción sin trading cuando sea posible.

## Dónde enviarlo

Use la [asistencia de Citrine](https://citrineedge.com/es-es/support/) para ayuda
específica de su cuenta. El repositorio público de documentación sirve para
corregir el manual, no para asistencia privada de trading. Consulte
[Notificaciones de seguridad](../SECURITY.md) si sospecha de una vulnerabilidad.
Nunca publique credenciales, aunque se las pida una cuenta no verificada.

[Volver al manual](../README.md)
