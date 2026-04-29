# Checklist de code review

## Seguranca

- Entradas validadas.
- Autenticacao e autorizacao verificadas.
- Segredos fora do codigo.
- Dados sensiveis protegidos.

## Legibilidade

- Codigo claro, coeso e com responsabilidades bem separadas.
- Nomes consistentes.
- Comentarios usados apenas quando agregam contexto real.

## Padrao da stack

- Convencoes oficiais respeitadas.
- Estrutura do projeto consistente.
- Dependencias justificadas.

## Validacao

- Requests, DTOs, schemas ou validators aplicados.
- Regras de negocio verificadas no ponto correto.

## Logs

- Logs relevantes para falhas e eventos criticos.
- Ausencia de dados sensiveis em logs.

## Tratamento de erro

- Erros tratados explicitamente.
- Mensagens seguras e compreensiveis.
- Fluxos de excecao testados quando criticos.

## Performance

- Consultas e loops avaliados.
- Indices considerados.
- Processos pesados enviados para filas quando necessario.

## Documentacao

- Contratos, decisoes e instrucoes atualizados quando impactados.

## Testes

- Testes criados ou ajustados para comportamento relevante.
- Fluxos criticos validados.
- Evidencias de teste registradas quando exigido.
