## Connect to psql
`sudo -i -u postgres`

then

`psql`

## Informations 

`\conninfo`

## Available users and databases

`\l`

## Create database

`CREATE DATABASE gregs_list;`


## Change to database

`\c gregs_list`

## Creating table `meus_contatos`

```sql
CREATE TABLE meus_contatos
(
sobre_nome VARCHAR(30),
primeiro_nome VARCHAR(20),
email VARCHAR(50),
aniversario DATE,
profissao VARCHAR(50),
local VARCHAR(50),
estado_civil VARCHAR(20),
interesses VARCHAR(100),
procura VARCHAR(100)
);

