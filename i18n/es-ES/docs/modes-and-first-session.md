# Modos de Citrine y lista de comprobación de la primera sesión

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Elija la responsabilidad, no solo el saldo

| Modo | Punto de partida | ¿Envía órdenes reales? | Uso adecuado |
| --- | --- | --- | --- |
| Paper | Un saldo hipotético elegido por usted | No | Conocer el espacio de trabajo y seguir una sesión simulada sin importar una clave API |
| Shadow | Datos de una cuenta autenticada, seguidos de su propia sesión simulada | No | Comparar una simulación basada en los datos de la cuenta con las condiciones del mercado |
| Observation | Vista de la cuenta real | No, tampoco cierres manuales ni gestión de protecciones | Supervisar la cuenta sin convertir este dispositivo en un dispositivo de ejecución |
| Standard | Cuenta real | Sí, cuando Complete y el acceso al trading autorizado están activos | Ejecutar entradas reales y la gestión de posiciones admitida |

El backtesting es una reproducción histórica, no un quinto modo de cuenta real.
La demostración guiada (Guided Demo) presenta la interfaz con una cuenta de
ejemplo y no requiere realizar una operación.

## Antes de una sesión Paper

- Abra Tutorial desde Support para iniciar la demostración guiada si no conoce
  el espacio de trabajo.
- Elija de forma deliberada el saldo inicial y la asignación. Mantenga esos
  valores si piensa comparar sesiones más adelante.
- Lea el modo y el estado de ejecución. Que se muestre un gráfico no significa
  por sí solo que haya una sesión en marcha o que se cumplan las condiciones de entrada.
- Revise los detalles de Edge, los detalles del resultado y sus explicaciones,
  en lugar de interpretar un único número fuera de contexto.
- Conserve las fechas, el modo y la exportación de la sesión al hacer comparaciones.

## Antes del uso con una cuenta conectada

- Confirme que utiliza una cuenta Coinbase Advanced que cumple los requisitos
  para los contratos perpetuos BTC y ETH admitidos de Coinbase Derivatives Exchange
  (CDE), no productos al contado ni productos de Coinbase International Exchange (INTX).
- Consulte la [disponibilidad actual por país](https://citrineedge.com/es-es/availability/)
  antes de conectar una cuenta. En Canadá, el acceso está limitado a las cuentas
  que cumplen los requisitos en las provincias o territorios admitidos.
- Siga la [configuración actual de la clave](https://citrineedge.com/es-es/coinbase-api-setup/).
  Importe las credenciales en la aplicación, nunca en una incidencia, mensaje
  o formulario de asistencia.
- El permiso View permite acceder a la cuenta. El trading real también necesita
  Trade. Citrine no requiere permisos Transfer, Receive ni de retirada de fondos.
- Compruebe la validación, el modo seleccionado, la asignación, los fondos
  disponibles, la capacidad y cualquier estado que requiera atención. Que una
  condición Edge esté lista no garantiza que se envíe una orden de inmediato.
- Mantenga el dispositivo Android con alimentación, conectado y configurado
  para que la aplicación funcione en segundo plano. Un dispositivo adicional
  es una opción, no un requisito.
- Mantenga disponible el acceso directo a Coinbase para consultar la cuenta o actuar con urgencia.

## Pausar y salir son acciones distintas

**Pause** detiene las nuevas entradas; la gestión admitida de posiciones reales
puede continuar. **Exit Citrine** detiene la ejecución local. No cierra
automáticamente las posiciones abiertas ni cancela las órdenes existentes en la bolsa.

La protección aceptada y alojada por Coinbase es distinta de la gestión en el
dispositivo. Observation no gestiona protecciones. Tras una interrupción,
compruebe el estado real de la ejecución y de la bolsa en lugar de asumir que
el trading se ha reanudado.

[Guía completa del producto](https://citrineedge.com/es-es/guide/) |
[Responsabilidades de seguridad](https://citrineedge.com/es-es/security/) |
[Volver al manual](../README.md)
