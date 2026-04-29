# Padroes de banco de dados

## Regras obrigatorias

- Modelar antes de criar tabela.
- Definir chaves primarias.
- Definir chaves estrangeiras quando aplicavel.
- Criar indices para consultas relevantes.
- Usar nomenclatura consistente.
- Prever auditoria basica quando necessario.
- Usar migrations quando possivel.
- Documentar entidades principais.

## Modelagem

GAIA deve validar entidades, relacionamentos, cardinalidade, integridade, campos obrigatorios, indices e riscos de crescimento.

## Nomenclatura

Nomes de tabelas, colunas, constraints e indices devem seguir padrao da stack e do projeto. Mistura de idiomas ou convencoes deve ser evitada.

## Governanca

Alteracoes criticas de schema exigem avaliacao de impacto, backup e plano de rollback.
