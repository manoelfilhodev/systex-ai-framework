# Padroes Node.js

## Padroes obrigatorios

- TypeScript preferencialmente.
- ESLint + Prettier.
- Uso de .env para configuracoes sensiveis ou variaveis por ambiente.
- Logs estruturados.
- Tratamento global de erros.

## Organizacao recomendada

- modules;
- routes;
- controllers;
- services;
- repositories;
- validators;
- middlewares.

## Regras

- Controllers devem coordenar requisicao e resposta.
- Services devem conter regra de negocio.
- Validators devem validar entrada antes da execucao.
- Middlewares devem tratar autenticacao, autorizacao, contexto e cross-cutting concerns.
- Repositories devem isolar persistencia quando fizer sentido.
- Erros devem ter padrao consistente e observavel.
