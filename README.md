# particionamento_MySQL-MariaDB
Script de particionamento do banco de Dados MySQL/MariaDB

Link de apoio do material: http://everaldoscabral.blogspot.com/2020/01/sobre-o-zabbix-particionamento-do-banco.html

```
yum install git dos2unix

git clone https://github.com/everaldoscabral/particionamento_MySQL-MariaDB.git

cd particionamento_MySQL-MariaDB/

chmod +x zbx_db_partitiong.sql

dos2unix zbx_db_partitiong.sql

```

# Expurgando logs antigos do banco
crontab -e
00 07 * * 1 sudo /database/script_expurgar_logs_antigos.sh

Schedulando para executar 1 vez na semana às 7hrs da manhã.
