# Observabilidade

## Objetivo

Observabilidade permite entender comportamento do sistema em producao, investigar falhas e validar saude operacional.

## Logs

- Registrar eventos relevantes.
- Padronizar formato sempre que possivel.
- Evitar dados sensiveis.
- Garantir logs para erros, autenticacao, integracoes e operacoes criticas.

## Metricas

- Monitorar disponibilidade.
- Monitorar tempo de resposta quando aplicavel.
- Monitorar volume de erros.
- Monitorar recursos basicos do ambiente quando possivel.

## Erros

- Erros devem ser rastreaveis.
- Falhas criticas devem gerar alerta ou rotina de acompanhamento.
- Mensagens ao usuario devem ser seguras e objetivas.

## Rastreabilidade de acoes

Sistemas com operacoes sensiveis devem registrar usuario, acao, data, origem e contexto minimo.

## Monitoramento basico

Todo projeto em producao deve ter ao menos verificacao de disponibilidade, analise de logs e processo de resposta a incidentes.
