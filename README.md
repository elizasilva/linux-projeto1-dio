# Primeiro projeto Linux DIO
 
Infraestrutura como código (IaC):
Script de criação de estrutura de usuários, diretórios e permissões.

======================================================================

DIRETÓRIOS
/publico
/adm
/ven
/sec

GRUPOS      USUÁRIOS

            carlos
GRP_ADM     maria
            joao

            debora
GRP_VEN     sebastiana
            roberto

            josefina
GRP_ASEC    amanda
            rogerio

---------------------------

Definições

Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;
O dono de todos os diretórios criados será o usuário root;
Todos os usuários terão permissão total dentro do diretório publico;
Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem;
Subir arquivo de script criado para a sua conta no GitHub.



