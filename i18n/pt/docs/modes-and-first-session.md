# Modos do Citrine e lista de verificação da primeira sessão

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Escolha a responsabilidade, não apenas o saldo

| Modo | Ponto de partida | Envia ordens reais? | Utilização adequada |
| --- | --- | --- | --- |
| Paper | Um saldo hipotético escolhido por si | Não | Conhecer a área de trabalho e acompanhar uma sessão simulada sem importar uma chave API |
| Shadow | Dados de uma conta autenticada, seguidos de uma sessão simulada própria | Não | Comparar uma simulação que utiliza dados da conta com as condições do mercado |
| Observation | Vista da conta real | Não, incluindo fechos manuais ou gestão de proteções | Monitorizar a conta sem tornar este dispositivo num dispositivo de execução |
| Standard | Conta real | Sim, quando o Complete e o acesso elegível à negociação estão ativos | Executar entradas reais e a gestão de posições permitida |

O backtesting é uma reprodução histórica, não um quinto modo de conta real.
A demonstração guiada (Guided Demo) apresenta a interface com uma conta de
exemplo e não exige qualquer operação.

## Antes de uma sessão Paper

- Abra Tutorial a partir de Support para iniciar a demonstração guiada se ainda
  não conhecer a área de trabalho.
- Escolha deliberadamente o saldo inicial e a afetação de fundos. Mantenha esses
  valores se pretender comparar sessões mais tarde.
- Leia o modo e o estado de execução. A presença de um gráfico, por si só, não
  significa que uma sessão esteja em curso ou que as condições de entrada estejam reunidas.
- Consulte os detalhes Edge, os detalhes do resultado e as respetivas explicações,
  em vez de interpretar um único número fora de contexto.
- Guarde as datas, o modo e a exportação da sessão para fazer comparações.

## Antes da utilização com uma conta ligada

- Confirme que utiliza uma conta Coinbase Advanced elegível para os contratos
  perpétuos BTC e ETH suportados da Coinbase Derivatives Exchange (CDE), não
  produtos à vista nem produtos da Coinbase International Exchange (INTX).
- Verifique a [disponibilidade atual por país](https://citrineedge.com/pt/availability/)
  antes de ligar uma conta. No Canadá, o acesso está limitado às contas que
  cumprem os requisitos nas províncias ou territórios suportados.
- Siga a [configuração atual da chave](https://citrineedge.com/pt/coinbase-api-setup/).
  Importe as credenciais na aplicação, nunca num pedido, mensagem ou formulário de apoio.
- A permissão View permite o acesso à conta. A negociação real também requer
  Trade. O Citrine não requer permissões Transfer, Receive ou de levantamento.
- Verifique a validação, o modo selecionado, a afetação de fundos, os fundos
  disponíveis, a capacidade e qualquer estado que exija atenção. Uma condição
  Edge assinalada como pronta não promete o envio imediato de uma ordem.
- Mantenha o dispositivo Android alimentado, ligado à rede e configurado para
  a aplicação funcionar em segundo plano. Um dispositivo adicional é uma opção,
  não um requisito.
- Mantenha disponível o acesso direto à Coinbase para verificar a conta ou agir com urgência.

## Pausar e sair são ações diferentes

**Pause** suspende novas entradas; a gestão permitida das posições reais pode
continuar. **Exit Citrine** para a execução local. Não fecha automaticamente
posições abertas nem cancela ordens existentes na plataforma de negociação.

Uma proteção aceite e alojada na Coinbase é diferente da gestão no dispositivo.
Observation não gere proteções. Após uma interrupção, verifique o estado real
da execução e da plataforma, em vez de presumir que a negociação foi retomada.

[Guia completo do produto](https://citrineedge.com/pt/guide/) |
[Responsabilidades de segurança](https://citrineedge.com/pt/security/) |
[Voltar ao manual](../README.md)
