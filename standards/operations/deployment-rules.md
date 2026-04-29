# Regras de deploy

## Checklist pre-deploy

- Versao identificada.
- Branch ou artefato validado.
- Variaveis de ambiente conferidas.
- Migrations revisadas quando houver.
- Dependencias instaladas ou empacotadas.
- Testes e validacoes criticas executados.
- Comunicacao de janela de deploy quando necessario.

## Backup

Alteracao critica exige backup antes do deploy, especialmente quando envolver banco de dados, arquivos de cliente, configuracoes ou migracoes irreversiveis.

## Pos-deploy

- Validar tela ou endpoint principal.
- Validar login/autenticacao quando aplicavel.
- Validar logs de erro.
- Validar integracoes externas relevantes.
- Registrar versao implantada.

## Rollback

Todo deploy relevante deve ter rollback planejado, incluindo criterio para acionamento, responsavel e procedimento minimo.
