# Diagnóstico seguro para a negociação no dispositivo

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Um relatório claro é mais útil do que uma cópia integral dos dados da conta.
Registe o comportamento antes de alterar definições ou reinstalar a aplicação,
pois isso pode eliminar provas locais úteis.

## Campos úteis para o relatório

```text
Versão/build da aplicação:
Versão do Android e modelo do dispositivo:
Modo e estado de execução:
Hora aproximada do evento e fuso horário:
Ecrã ou ação:
Comportamento esperado:
Comportamento observado:
É reproduzível? Se sim, passos mínimos:
Eventual texto de erro, sem identificadores da conta:
```

Não inclua chaves API, chaves privadas, frases de recuperação, tokens de acesso,
tokens de compra do Google Play, documentos bancários ou fiscais nem
identificadores completos de ordens da plataforma. Oculte nomes de contas,
saldos e conteúdo de notificações em capturas de ecrã públicas quando não forem
necessários. Reveja as exportações antes de as partilhar; um ficheiro JSON não
é anónimo apenas por não se parecer com uma fotografia.

## Observe primeiro

- Distinga um ecrã ainda a carregar de um zero confirmado, um dado indisponível
  ou uma execução em pausa. Registe o estado exato, em vez de o parafrasear.
- Indique se uma posição foi aberta externamente ou pela aplicação e qual era
  o dispositivo que a geria. Observation monitoriza, não controla a execução.
- Consulte diretamente a Coinbase quando a questão envolver uma ordem ou posição
  real. Não repita uma ação de ordem apenas porque a apresentação está atrasada.
- Registe a conectividade, reinícios, alterações ao funcionamento em segundo
  plano e a hora das atualizações. São pistas de diagnóstico, não provas de uma causa.
- Não efetue operações apenas para reproduzir um problema da interface. Comece
  com Paper ou uma reprodução sem negociação, sempre que possível.

## Para onde enviar

Utilize o [apoio do Citrine](https://citrineedge.com/pt/support/) para ajuda
específica da conta. O repositório público de documentação destina-se a corrigir
o manual, não ao apoio privado à negociação. Consulte a
[comunicação de problemas de segurança](../SECURITY.md) se suspeitar de
vulnerabilidades. Nunca publique credenciais, mesmo que uma conta não verificada lhas peça.

[Voltar ao manual](../README.md)
