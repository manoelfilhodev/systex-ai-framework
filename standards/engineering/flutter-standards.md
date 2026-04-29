# Padroes Flutter

## Padroes obrigatorios

- Seguir Effective Dart.
- Usar arquitetura modular por feature.
- Manter tema centralizado.
- Tratar loading, erro e empty state.
- Aplicar offline-first quando exigido pelo produto.

## Separacao recomendada

- screens;
- widgets;
- services;
- models/dtos;
- repositories.

## Regras

- Screens coordenam layout e interacao.
- Widgets devem ser reutilizaveis quando houver repeticao real.
- Services tratam integracoes e regras de aplicacao.
- Repositories isolam acesso a dados locais ou remotos.
- Models/DTOs representam dados e contratos.
- Estados de rede, erro e carregamento devem ser visiveis para o usuario.

## Qualidade

Fluxos criticos devem ser testados em tamanhos de tela relevantes e com estados de falha.
