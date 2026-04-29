# Padroes de hospedagem

## Modalidades

### Hospedagem compartilhada

Pode ser usada em projetos simples, institucionais ou sistemas pequenos, desde que as limitacoes sejam conhecidas.

Limitacoes comuns:

- acesso restrito a terminal;
- dificuldade para filas, workers e schedulers;
- restricao para comandos como artisan;
- menor controle de performance e seguranca;
- deploy mais manual.

### VPS

Recomendada quando o projeto exige maior controle de ambiente, workers, filas, configuracao de servidor, automacao de deploy e observabilidade.

### Cloud

Recomendada para projetos com escala, alta disponibilidade, automacao, multiplos ambientes, esteiras CI/CD e requisitos avancados de seguranca.

## Alternativas sem terminal/artisan

Quando nao houver acesso a terminal ou artisan, o projeto deve prever alternativas controladas para:

- execucao de migrations;
- limpeza de cache;
- filas e tarefas agendadas;
- deploy de dependencias;
- rotinas administrativas.

Essas alternativas devem ser documentadas e aprovadas antes do go-live.
