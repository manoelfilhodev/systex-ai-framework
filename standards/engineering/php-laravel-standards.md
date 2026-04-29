# Padroes PHP / Laravel

## Padroes obrigatorios

Projetos PHP/Laravel devem seguir:

- PSR-1;
- PSR-3 quando aplicavel;
- PSR-4;
- PSR-7 / PSR-15 quando aplicavel;
- PSR-12;
- padroes oficiais do Laravel.

## Estrutura recomendada

- Controllers;
- Requests;
- Services;
- Models;
- Policies;
- Resources;
- Jobs;
- Events/Listeners;
- Repositories somente quando necessario.

## Regras de responsabilidade

- Nao misturar regra de negocio pesada dentro de controller.
- Controller coordena entrada, autorizacao basica, chamada de servico e resposta.
- Service executa regra de negocio e orquestra casos de uso.
- Model representa dados, relacionamentos, casts e comportamentos diretamente ligados ao dominio.
- Request valida entrada.
- Policy centraliza autorizacao.
- Resource padroniza resposta.

## Governanca

Excecoes estruturais devem ser justificadas no handoff tecnico ou na documentacao do projeto.
