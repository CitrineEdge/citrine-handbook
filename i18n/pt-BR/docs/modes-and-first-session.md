# Modos do Citrine e lista de verificação da primeira sessão

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Escolha a responsabilidade, não apenas o saldo

| Modo | Ponto de partida | Envia ordens reais? | Uso adequado |
| --- | --- | --- | --- |
| Paper | Um saldo hipotético escolhido por você | Não | Conhecer a área de trabalho e acompanhar uma sessão simulada sem importar uma chave API |
| Shadow | Dados de uma conta autenticada, seguidos de uma sessão simulada própria | Não | Comparar uma simulação que utiliza dados da conta com as condições do mercado |
| Observation | Visualização da conta real | Não, incluindo fechamentos manuais ou gerenciamento de proteções | Monitorar a conta sem transformar este dispositivo em um dispositivo de execução |
| Standard | Conta real | Sim, quando o Complete e o acesso elegível à negociação estão ativos | Executar entradas reais e o gerenciamento de posições permitido |

Nos detalhes da carteira, Standard e Observation aparecem como **Padrão** e
**Observação**; o controle do modo mantém o nome **Modo Observation**.

O backtesting é uma reprodução histórica, não um quinto modo de conta real.
A demonstração guiada (Guided Demo) apresenta a interface com uma conta de
exemplo e não exige qualquer operação.

## Antes de uma sessão Paper

- Abra **Tutorial** em **Suporte** para iniciar a demonstração guiada se ainda
  não conhecer a área de trabalho.
- Escolha deliberadamente o saldo inicial e a alocação de fundos. Mantenha esses
  valores se quiser comparar sessões mais tarde.
- Leia o modo e o estado de execução. A presença de um gráfico, por si só, não
  significa que uma sessão esteja em andamento ou que as condições de entrada estejam atendidas.
- Consulte os detalhes Edge, os detalhes do resultado e as respectivas explicações,
  em vez de interpretar um único número fora de contexto.
- Guarde as datas, o modo e a exportação da sessão para fazer comparações.

## Antes do uso com uma conta conectada

- Confirme que utiliza uma conta Coinbase Advanced elegível para os contratos
  perpétuos BTC e ETH compatíveis da Coinbase Derivatives Exchange (CDE), não
  produtos à vista nem produtos da Coinbase International Exchange (INTX).
- Verifique a [disponibilidade atual por país](https://citrineedge.com/pt-br/availability/)
  antes de conectar uma conta. No Canadá, o acesso está limitado às contas que
  cumprem os requisitos nas províncias ou territórios atendidos.
- Siga a [configuração atual da chave](https://citrineedge.com/pt-br/coinbase-api-setup/).
  Importe as credenciais no aplicativo, nunca em um chamado, mensagem ou formulário de suporte.
- A permissão View permite o acesso à conta. A negociação real também requer
  Trade. O Citrine não requer permissões Transfer, Receive ou de saque.
- Verifique a validação, o modo selecionado, a alocação de fundos, os fundos
  disponíveis, a capacidade e qualquer estado que exija atenção. Uma condição
  Edge marcada como pronta não promete o envio imediato de uma ordem.
- Mantenha o dispositivo Android com alimentação, conectado à rede e configurado para
  o aplicativo funcionar em segundo plano. Um dispositivo adicional é uma opção,
  não um requisito.
- Mantenha disponível o acesso direto à Coinbase para verificar a conta ou agir com urgência.

## Pausar e sair são ações diferentes

**Pausar negociação** suspende novas entradas; o gerenciamento permitido das posições reais pode
continuar. **Sair da Citrine** interrompe a execução local. Não fecha automaticamente
posições abertas nem cancela ordens existentes na plataforma de negociação.

Uma proteção aceita e hospedada na Coinbase é diferente do gerenciamento no dispositivo.
Observation não gerencia proteções. Após uma interrupção, verifique o estado real
da execução e da plataforma, em vez de presumir que a negociação foi retomada.

[Guia completo do produto](https://citrineedge.com/pt-br/guide/) |
[Responsabilidades de segurança](https://citrineedge.com/pt-br/security/) |
[Voltar ao manual](../README.md)
