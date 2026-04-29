# Padroes Python

## Padroes obrigatorios

- Seguir PEP 8.
- Usar type hints quando possivel.
- Usar ambiente virtual com venv ou ferramenta equivalente.
- Declarar dependencias em requirements.txt ou pyproject.toml.
- Aplicar logs estruturados.
- Separar config, regra de negocio e execucao.
- Tratar excecoes explicitamente.

## Organizacao recomendada

- config: variaveis, settings e leitura de ambiente.
- services: regras de negocio e casos de uso.
- repositories ou gateways: acesso externo quando necessario.
- models ou schemas: estruturas de dados e contratos.
- cli, workers ou app: pontos de entrada.
- tests: testes unitarios e de integracao quando aplicavel.

## Regras

- Nao esconder excecoes sem log.
- Nao deixar segredo hardcoded.
- Nao misturar script operacional com regra de negocio complexa.
- Preferir funcoes pequenas, legiveis e testaveis.
