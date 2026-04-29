# Systex AI Engineering Framework

## Sistema operacional oficial de engenharia da Systex

O Systex AI Engineering Framework e o framework oficial da Systex para iniciar, planejar, padronizar, executar e governar projetos de software com apoio de agentes de IA.

Este repositorio nao e apenas uma colecao de prompts. Ele define como a Systex entende problemas, organiza decisoes, valida riscos, estrutura arquitetura, documenta contratos, aplica padroes tecnicos e entrega sistemas com previsibilidade empresarial.

Todo novo projeto da Systex deve iniciar por este framework.

## Filosofia oficial

Codigo nao e o comeco. Codigo e consequencia.

Antes de qualquer implementacao, um projeto precisa ter entendimento do negocio, regras claras, arquitetura definida, modelagem de dados, contratos de API, padroes visuais, requisitos de seguranca, estrategia de testes, plano de deploy e criterio de aceite.

A IA acelera execucao, reduz retrabalho e amplia qualidade, mas nao substitui decisao, responsabilidade tecnica ou governanca. A decisao continua humana. A responsabilidade continua humana. A entrega continua profissional.

## Objetivo

Garantir que todos os projetos da Systex sigam um padrao consistente de:

- entendimento de negocio;
- arquitetura e estrutura tecnica;
- Design System Systex;
- politica White Label / Client Branding;
- padroes tecnicos por stack;
- seguranca e qualidade;
- banco de dados e contratos de API;
- operacao, deploy e observabilidade;
- documentacao viva;
- governanca de entrega.

## Estrutura do framework

```text
agents/      -> definicao dos agentes oficiais
atlas/       -> orquestracao principal
prompts/     -> comandos e prompts operacionais
templates/   -> templates de handoff e fluxo
docs/        -> documentacao gerada por projeto
flows/       -> fluxos oficiais por stack
standards/   -> regras tecnicas, visuais e operacionais obrigatorias
```

## Fluxo obrigatorio de agentes

Todo projeto deve seguir a ordem oficial de acionamento dos agentes:

```text
1. ATLAS                  -> orquestracao e direcao
2. ATHENA                 -> regras de negocio
3. PROMETEU               -> arquitetura
4. GAIA                   -> banco de dados
5. VULCAN                 -> estrutura base
6. PROMETEU               -> contratos e API
7. ARES / APOLLO / HERMES -> execucao backend, frontend e mobile
8. ORION / HADES          -> validacao tecnica, testes e seguranca
9. CRONOS / MERCURIUS / AURORA / THEMIS -> sustentacao empresarial
10. TITAN                 -> implantacao, operacao, entrega e pos-venda
```

Quebrar essa ordem aumenta retrabalho, divida tecnica, risco operacional, custo invisivel e perda de previsibilidade.

## Agentes oficiais

| Agente | Funcao |
| --- | --- |
| ATLAS | Orquestracao e direcao do projeto |
| ATHENA | Regras de negocio |
| PROMETEU | Arquitetura |
| GAIA | Banco de dados |
| VULCAN | Estrutura base |
| ARES | Backend / API |
| APOLLO | Frontend / Admin |
| HERMES | Mobile / Flutter |
| ORION | Testes e qualidade |
| HADES | Seguranca |
| CRONOS | Financeiro / MRR / viabilidade |
| MERCURIUS | Comercial / CRM / vendas |
| AURORA | Marketing / branding / posicionamento |
| THEMIS | Juridico / contratos / SLA |
| TITAN | Operacoes / implantacao / entrega / Customer Success |

## Design System oficial Systex

O Design System Systex define a base visual oficial para produtos, dashboards, plataformas administrativas, aplicativos e interfaces institucionais. O padrao visual principal e premium, empresarial, dark-first e orientado a clareza operacional.

Documentos oficiais:

- [Paleta oficial Systex](standards/design-system/systex-colors.md)
- [Design tokens](standards/design-system/design-tokens.md)
- [Tipografia](standards/design-system/typography.md)
- [Regras de UI](standards/design-system/ui-rules.md)
- [Padroes de componentes](standards/design-system/components-patterns.md)
- [Politica White Label / Client Branding](standards/design-system/white-label-policy.md)
- [Guidelines premium enterprise](standards/design-system/premium-enterprise-guidelines.md)

## Politica White Label / Client Branding

Todo projeto deve declarar, antes do inicio, qual modelo visual sera utilizado:

- SYSTEX Default: aplica o Design System oficial Systex.
- White Label / Client Branding: adapta a experiencia visual a identidade do cliente.

Personalizacao visual do cliente e escopo premium. Ela exige maior prazo, maior custo, mais validacao, maior manutencao e contrato mais robusto. Nenhum projeto deve assumir White Label implicitamente.

Referencia: [white-label-policy.md](standards/design-system/white-label-policy.md)

## Padroes tecnicos por stack

Cada projeto deve declarar a stack principal e seguir os padroes tecnicos correspondentes:

- [PHP / Laravel](standards/engineering/php-laravel-standards.md)
- [Python](standards/engineering/python-standards.md)
- [Flutter](standards/engineering/flutter-standards.md)
- [Node.js](standards/engineering/node-standards.md)
- [APIs](standards/engineering/api-standards.md)
- [Banco de dados](standards/engineering/database-standards.md)
- [Checklist de code review](standards/engineering/code-review-checklist.md)

## Padroes de entrega e operacao

Entrega profissional exige criterio antes, durante e depois do deploy. Todo projeto deve ter estrategia de implantacao, backup, ambiente de hospedagem, validacao pos-deploy, rollback planejado e observabilidade minima.

Documentos oficiais:

- [Regras de deploy](standards/operations/deployment-rules.md)
- [Padroes de hospedagem](standards/operations/hosting-standards.md)
- [Politica de backup](standards/operations/backup-policy.md)
- [Observabilidade](standards/operations/observability.md)

## Regras de governanca

- ATLAS deve validar o modelo visual antes de iniciar qualquer projeto.
- ATHENA deve consolidar regras de negocio antes da execucao tecnica.
- PROMETEU deve definir arquitetura e contratos antes da implementacao.
- GAIA deve validar modelagem antes da criacao de tabelas.
- ARES, APOLLO e HERMES devem implementar conforme padroes da stack.
- ORION deve validar testes, fluxos criticos e criterios de aceite.
- HADES deve validar seguranca antes da entrega.
- TITAN deve garantir estrategia de deploy, operacao, rollback e pos-venda.
- Decisoes relevantes devem registrar motivo, impacto e risco residual.
- Excecoes tecnicas devem ser explicitas, justificadas e aprovadas.

## Non-negotiables

- Nao iniciar codigo antes de entendimento, regras de negocio, arquitetura, banco, contratos e criterio de aceite.
- Nao criar tabelas sem modelagem validada.
- Nao abrir endpoints sem contrato definido.
- Nao entregar sem validacao de ORION e HADES.
- Nao assumir White Label sem escopo, prazo, custo e contrato adequados.
- Nao ignorar padroes oficiais da stack.
- Nao fazer deploy critico sem backup e rollback planejado.
- Nao considerar projeto pronto sem documentacao minima e evidencias.

## Como utilizar

1. Criar o novo projeto usando este repositorio como base.
2. Acionar ATLAS para diagnostico, classificacao do modelo visual e plano de execucao.
3. Executar os agentes na ordem oficial.
4. Gerar documentacao obrigatoria de negocio, arquitetura, dados, API, seguranca, testes e operacao.
5. Iniciar desenvolvimento somente apos as validacoes minimas.
6. Validar entrega com ORION, HADES e TITAN antes do go-live.

## Posicionamento

A Systex nao vende apenas software. A Systex entrega engenharia.

Nao construimos sistemas no improviso. Construimos com metodo, estrutura, responsabilidade e governanca.

## Assinatura

Systex Sistemas Inteligentes
