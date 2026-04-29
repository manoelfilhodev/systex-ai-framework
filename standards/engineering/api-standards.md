# Padroes de API

## Regras obrigatorias

- Usar versionamento, preferencialmente `/api/v1`.
- Definir contratos antes dos endpoints.
- Validar entrada de forma explicita.
- Usar padrao de resposta consistente.
- Aplicar status HTTP coerente.
- Implementar autenticacao e autorizacao conforme risco.
- Registrar logs relevantes.
- Garantir rastreabilidade de acoes criticas.

## Contratos

Todo endpoint deve ter objetivo, metodo, rota, parametros, payload, resposta esperada, erros possiveis e regras de autorizacao.

## Respostas

APIs devem evitar respostas ambiguas. Erros devem ser compreensiveis para integracao e seguros para exposicao.

## Governanca

Nenhum endpoint critico deve ser implementado sem contrato minimo aprovado por PROMETEU e validado por HADES quando envolver seguranca.
