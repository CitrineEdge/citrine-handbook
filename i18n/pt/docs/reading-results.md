# Ler backtests, comissões e financiamento (funding)

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Uma comparação útil começa com o mesmo instrumento, datas, fuso horário,
fundos iniciais, afetação e pressupostos de custos. Paper, Shadow, reprodução
histórica e execução real não têm dados de entrada nem execuções idênticos.

## Uma ficha de comparação

Registe estes dados junto de ambos os resultados antes de comparar um montante final em dólares:

| Dado | Porque é importante |
| --- | --- |
| Produto e direção | Os contratos BTC e ETH não são intercambiáveis; os produtos à vista e os futuros são produtos diferentes |
| Início, fim e fuso horário | Um limite diferente pode incluir outra entrada, fecho ou evento de financiamento |
| Fundos iniciais e afetação | Uma capacidade diferente pode alterar o número de contratos |
| Operações fechadas e eventual exposição aberta | O total das operações concluídas não equivale a uma conta com uma posição aberta |
| Preços de execução e comissões | As execuções simuladas e reais podem diferir; as comissões da conta e as predefinidas não são intercambiáveis |
| Cobertura e sinal do financiamento | Um crédito, um débito, um zero verificado e informação indisponível significam coisas diferentes |
| Base contabilística e período | Uma componente do saldo comunicada pela plataforma não é automaticamente o resultado de uma sessão |

## Não subtraia duas vezes a mesma comissão

Cálculo apenas hipotético: suponha que o PnL bruto das operações fechadas é
**+$24**, as comissões de negociação são **$4** e o financiamento incluído é
um crédito de **+$1**. Se o resultado realizado comunicado já estiver líquido
dessas comissões, é **+$20**. Ao somar o crédito de financiamento obtém-se
**+$21**. Subtrair novamente os $4 seria contá-los duas vezes.

Este exemplo explica o princípio da reconciliação; não é uma fórmula universal
para todos os ecrãs ou extratos da plataforma. Leia a base indicada do resultado,
os custos incluídos, a cobertura do financiamento e a eventual exposição aberta.
O financiamento é uma componente contabilística própria e não tem necessariamente
de integrar o resultado das operações fechadas.

## Um dado em falta não é zero

Um zero numérico pode representar um zero conhecido. A falta de cobertura do
financiamento não prova que não tenha havido um débito ou crédito. A reprodução
histórica utiliza dados de financiamento disponíveis e elegíveis; consulte os
detalhes do resultado antes de o comparar com a liquidação da plataforma. Não
deduza financiamento exato da diferença entre dois saldos arredondados.

## O drawdown não é apenas a pior operação

O drawdown máximo mede uma descida desde um máximo anterior na série escolhida
do património da conta ou do saldo. Uma série hipotética
**$1000 -> $1030 -> $1018** apresenta uma descida do máximo ao mínimo de
**$12**, embora termine acima do saldo inicial. Várias operações com perdas
podem contribuir para um único drawdown.

A base de amostragem importa. Uma série baseada nos fechos difere de uma
avaliação contínua do património que inclui posições abertas e pode não mostrar
o mínimo durante uma operação. Utilize a base descrita nos detalhes dos
resultados do Citrine; não interprete um valor baseado nos fechos como a maior
perda real possível nem presuma que ordens stop garantem um preço de execução específico.

## Quando duas execuções diferem

Compare primeiro quantidades e horas de execução; depois, preços, origem das
comissões, financiamento e exposição aberta. Guarde as exportações originais
sem alterações. Para obter apoio, descreva a discrepância e forneça apenas a
informação efetivamente pedida; não publique exportações completas de contas.

[Metodologia de backtesting](https://citrineedge.com/pt/backtesting/) |
[Diagnóstico seguro de problemas](safe-troubleshooting.md) |
[Voltar ao manual](../README.md)
