# Finalmente Parte Chata Terminada

## Recomendado baixar o arquivo em zip para melhor funcionamento

## Tabela do Banco de Dados:

```sql
create database userdb;
use userdb;

create 	table users(
id CHAR(36) NOT NULL PRIMARY KEY,
username varchar(100) not null unique,
password varchar (100) not null,
role text auto_increment
);

select 	 * from users;

