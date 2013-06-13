dump_sh_mysql
=============

## Descrição:

Shell script para backup de banco de dados

## Preparação:

Alterar o arquivo get_dumps com os dados do banco a ser salvo.

## Execução:

> ./get_dumps

## Inclusão do processo na cron:

> 0 3 * * * sh /path/do/script/get_dumps
