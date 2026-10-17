# Leer backtests, comisiones y financiación (funding)

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Una comparación útil comienza con el mismo instrumento, fechas, zona horaria,
fondos iniciales, asignación y supuestos de costes. Paper, Shadow, la reproducción
histórica y la ejecución real no tienen datos de entrada ni ejecuciones idénticos.

## Una hoja de comparación

Anote estos datos junto a ambos resultados antes de comparar el importe final en dólares:

| Dato | Por qué importa |
| --- | --- |
| Producto y dirección | Los contratos de BTC y ETH no son intercambiables; el contado y los futuros son productos distintos |
| Inicio, fin y zona horaria | Un límite diferente puede incluir otra entrada, cierre o evento de financiación |
| Fondos iniciales y asignación | Una capacidad diferente puede cambiar la cantidad de contratos |
| Operaciones cerradas y exposición abierta | El total de operaciones completadas no equivale a una cuenta con una posición abierta |
| Precios de ejecución y comisiones | La simulación y las ejecuciones reales pueden diferir; las comisiones de la cuenta y las predeterminadas no son intercambiables |
| Cobertura y signo de la financiación | Un abono, un cargo, un cero verificado y una información no disponible significan cosas diferentes |
| Base contable y periodo | Un componente del saldo comunicado por la bolsa no es automáticamente el resultado de una sesión |

## No reste dos veces la misma comisión

Cálculo exclusivamente hipotético: suponga que el PnL bruto de operaciones
cerradas es **+$24**, las comisiones de trading son **$4** y la financiación
incluida es un abono de **+$1**. Si el resultado realizado comunicado ya es neto
de esas comisiones, es de **+$20**. Al añadir el abono de financiación se obtiene
**+$21**. Restar los $4 otra vez supondría contarlos dos veces.

Este ejemplo explica el principio de conciliación; no es una fórmula universal
para todas las pantallas o extractos de una bolsa. Lea la base indicada, los
costes incluidos, la cobertura de financiación y la exposición abierta. La
financiación es un componente contable propio y no tiene por qué formar parte
del resultado de las operaciones cerradas.

## Un dato ausente no es cero

Un cero numérico puede representar un cero conocido. La falta de cobertura de
financiación no demuestra que no hubiera un cargo o un abono. La reproducción
histórica usa los datos de financiación disponibles que cumplen los criterios;
consulte los detalles del resultado antes de compararlo con la liquidación de
la bolsa. No deduzca una financiación exacta de la diferencia entre dos saldos redondeados.

## El drawdown no es solo la peor operación

El drawdown máximo mide una caída desde un máximo anterior en la serie elegida
de patrimonio de la cuenta o saldo. Una serie hipotética de
**$1000 -> $1030 -> $1018** tiene una caída del máximo al mínimo de **$12**,
aunque termina por encima del saldo inicial. Varias operaciones perdedoras pueden
contribuir a un mismo drawdown.

La base de muestreo importa. Una serie basada en cierres es distinta de la
valoración continua del patrimonio con posiciones abiertas y puede no mostrar
su mínimo durante una operación. Use la base descrita en los detalles de
resultados de Citrine; no interprete una cifra basada en cierres como la mayor
pérdida real posible ni asuma que las órdenes stop garantizan un precio de ejecución concreto.

## Cuando dos ejecuciones difieren

Compare primero cantidades y marcas de tiempo de ejecución; después, precios,
origen de las comisiones, financiación y exposición abierta. Conserve las
exportaciones originales sin cambios. Para asistencia, describa la discrepancia
y proporcione solo la información solicitada; no publique exportaciones completas de cuentas.

[Metodología de backtesting](https://citrineedge.com/es-es/backtesting/) |
[Diagnóstico seguro de problemas](safe-troubleshooting.md) |
[Volver al manual](../README.md)
