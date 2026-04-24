# systex-ai-framework

> Framework de agentes de IA para engenharia de software da Systex.

Um framework operacional para planejar, construir, validar e operar produtos digitais com padrao de producao. O foco e transformar IA em um sistema de trabalho real: com papeis claros, handoff objetivo, criterio tecnico e governanca de entrega.

## Visao Geral

`Systex AI Framework` organiza engenharia em tres camadas:

- **Orquestracao**: ATLAS coordena prioridade, risco e sequenciamento.
- **Especializacao**: agentes com ownership tecnico por dominio.
- **Execucao**: prompts e templates para reduzir ambiguidade e acelerar entrega.

Beneficios esperados:

- Menos retrabalho entre arquitetura, backend, frontend, QA e seguranca.
- Decisoes tecnicas rastreaveis e orientadas por impacto.
- Ciclo de release mais previsivel, com qualidade e confiabilidade.

## 🚀 Fluxo Oficial de Inicialização de Projetos

Todo novo projeto deve seguir a sequência abaixo:

### 1. Criar projeto a partir do template
Use o repositório `systex-ai-framework` como base.

---

### 2. Executar ATLAS (orquestração)

Definir:
- visão geral
- módulos
- sequência de execução

---

### 3. ATHENA (regras de negócio)
Definir:
- regras de uso
- cenários de erro
- critérios de aceite

---

### 4. PROMETEU (arquitetura)
Definir:
- arquitetura geral
- módulos
- fluxos

---

### 5. GAIA (banco de dados)
Definir:
- modelagem
- relacionamentos
- integridade

Salvar em:
docs/database/

---

### 6. VULCAN (estrutura base)
Definir:
- estrutura Laravel
- estrutura Flutter
- organização do projeto

Salvar em:
docs/architecture/

---

### 7. PROMETEU (API)
Definir:
- endpoints
- contratos
- erros

Salvar em:
docs/api/

---

### 8. INICIAR CÓDIGO

Agora sim:
- backend (ARES)
- frontend admin (APOLLO)
- mobile (HERMES)

---

### 9. VALIDAÇÃO

- ORION → testes
- HADES → segurança

---

## ⚠️ Regra principal

Nenhum código deve ser escrito antes de:
- regras
- arquitetura
- banco
- API

---

## 🎯 Objetivo

Garantir:
- previsibilidade
- qualidade
- escalabilidade
- padrão Systex

## Estrutura de Pastas

```text
systex-ai-framework/
|- README.md
|- atlas/
|  |- atlas.md
|  |- atlas-prompt.txt
|- agents/
|  |- athena.md
|  |- prometeu.md
|  |- gaia.md
|  |- vulcan.md
|  |- ares.md
|  |- apollo.md
|  |- hermes.md
|  |- orion.md
|  |- hades.md
|- prompts/
|  |- atlas-master.txt
|  |- db.txt
|  |- backend.txt
|  |- frontend.txt
|  |- qa.txt
|  |- security.txt
|- templates/
   |- project-start.md
   |- handoff-db.md
   |- handoff-backend.md
   |- handoff-frontend.md
```

## Agentes do Framework

| Agente | Papel principal | Entrega chave |
|---|---|---|
| **ATLAS** | Orquestracao tecnica | Plano por fases, governanca de risco e alinhamento entre agentes |
| **PROMETEU** | Backend e dominio | APIs, regras de negocio, persistencia e integracoes |
| **ATHENA** | Arquitetura | Decisoes estruturais, boundaries e trade-offs tecnicos |
| **GAIA** | Frontend e UX | Fluxos de interface, componentes e integracao UI/API |
| **VULCAN** | Plataforma e DevOps | CI/CD, ambientes, automacao e estrategia de deploy |
| **ARES** | Seguranca | Threat modeling, controles e remediacao priorizada |
| **APOLLO** | Qualidade | Estrategia de testes, evidencia e go/no-go de release |
| **HERMES** | Documentacao e handoff | Transferencia de contexto com padrao tecnico |
| **ORION** | Observabilidade e SRE | SLI/SLO, monitoramento, alertas e runbooks |
| **HADES** | Continuidade e incidentes | Risco operacional, contingencia e resposta a incidentes |

## Comandos Rapidos

Use os atalhos abaixo no seu orquestrador/pipeline de prompts:

| Comando | Finalidade | Status |
|---|---|---|
| `/arch` | Direcionar decisoes de arquitetura (ATHENA + ATLAS) | Definido no fluxo |
| `/biz` | Refinar contexto de negocio e criterio de sucesso | Definido no fluxo |
| `/db` | Modelagem e estrategia de dados | Disponivel (`prompts/db.txt`) |
| `/be` | Design e execucao backend | Disponivel (`prompts/backend.txt`) |
| `/fe` | Design e execucao frontend | Disponivel (`prompts/frontend.txt`) |
| `/mobile` | Estrategia de cliente mobile e integracao | Definido no fluxo |
| `/qa` | Planejamento e validacao de qualidade | Disponivel (`prompts/qa.txt`) |
| `/sec` | Analise e remediacao de seguranca | Disponivel (`prompts/security.txt`) |

## Fluxo de Trabalho

1. **Kickoff do projeto**
   - Preencha `templates/project-start.md` com objetivo, escopo, restricoes e NFRs.
2. **Orquestracao inicial com ATLAS**
   - Use `atlas/atlas-prompt.txt` para gerar plano tecnico faseado.
3. **Execucao por especialidade**
   - Acione agentes por dominio (`/db`, `/be`, `/fe`, `/qa`, `/sec`).
4. **Handoffs formais**
   - Registre entregas em `templates/handoff-*.md` para continuidade sem perda de contexto.
5. **Confiabilidade e operacao**
   - Validar observabilidade (ORION), riscos operacionais (HADES) e readiness de release.

## Como Usar

### 1) Preparar o contexto

- Defina problema, objetivo de negocio e metricas de sucesso.
- Liste restricoes reais: prazo, stack, equipe e compliance.

### 2) Rodar a orquestracao

- Inicialize com o prompt mestre de ATLAS.
- Revise plano por fases, riscos e criterios de aceite.

### 3) Executar por trilhas

- Use prompts especializados para cada frente tecnica.
- Mantenha evidencias tecnicas por etapa (testes, logs, metricas, ADRs).

### 4) Fechar ciclo de entrega

- Gere handoff tecnico.
- Rode checklist de qualidade, seguranca e operacao antes do go-live.

## Proximos Passos

- **Padronizar comandos faltantes**: adicionar prompts dedicados para `/arch`, `/biz` e `/mobile`.
- **Integrar com CI**: automatizar validacoes de qualidade e seguranca no pipeline.
- **Evoluir playbooks**: ampliar templates de incidente, rollback e revisao pos-release.
- **Medir maturidade**: acompanhar lead time, taxa de falha de release e MTTR como KPI do framework.

## Posicionamento Systex

Este repositorio foi desenhado para times que precisam de uma operacao de engenharia com ritmo de produto SaaS e disciplina de producao: decisao tecnica clara, responsabilidade distribuida e entrega confiavel.
