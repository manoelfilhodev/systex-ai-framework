# systex-ai-framework

Framework operacional para times de engenharia que usam agentes de IA especializados para planejar, construir, validar e operar software com padrão profissional.

## O que é

`systex-ai-framework` define:

- Um orquestrador central (`ATLAS`) para coordenar decisões.
- Um conjunto de agentes especialistas com responsabilidades claras.
- Prompts rápidos para tarefas críticas de engenharia.
- Templates de kickoff e handoff para reduzir perda de contexto.

O objetivo é permitir execução consistente em projetos reais, com rastreabilidade técnica, qualidade e segurança desde o início.

## Estrutura

- `atlas/`: definição e prompt mestre do orquestrador.
- `agents/`: contratos operacionais de cada agente.
- `prompts/`: comandos curtos para acionar trilhas especializadas.
- `templates/`: documentos padrão de início e transição de trabalho.

## Como usar

1. Copie esta estrutura para o repositório do projeto.
2. Preencha `templates/project-start.md` com contexto de negócio e restrições.
3. Use `atlas/atlas-prompt.txt` como prompt principal do orquestrador.
4. Acione agentes por necessidade técnica com os comandos em `prompts/*.txt`.
5. Formalize entregas com os templates de handoff.

## Fluxo de trabalho com agentes

1. **Kickoff**
   - `ATLAS` consolida escopo, riscos, dependências e plano de execução.
2. **Arquitetura e decomposição**
   - `ATHENA` define arquitetura e contratos.
   - `PROMETEU` quebra backend em incrementos.
   - `GAIA` conduz interface, UX e integração com APIs.
3. **Construção e validação**
   - `VULCAN` prepara CI/CD, ambientes e automação.
   - `APOLLO` valida qualidade com testes e critérios de aceite.
   - `ARES` revisa segurança de ponta a ponta.
4. **Entrega e operação**
   - `ORION` instrumenta observabilidade e SLOs.
   - `HERMES` consolida documentação e handoffs.
   - `HADES` cobre riscos operacionais, conformidade e resposta a incidentes.
5. **Governança contínua**
   - `ATLAS` monitora desvios, prioriza trade-offs e redefine próximos passos.

## Princípios de execução

- Responsabilidade explícita por agente.
- Decisões sempre com contexto técnico e impacto.
- Entrega incremental com verificação objetiva.
- Segurança, qualidade e operação tratadas como requisitos de produto.

## Resultado esperado

Um ciclo de engenharia repetível, auditável e pronto para produção, sem depender de improviso entre áreas.

