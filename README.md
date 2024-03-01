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
```

## 

| Nome da coluna | Descrição | Exemplo | Melhor opção de Tipos de Dados |
| --- | --- | --- | --- |
| preco | O custo de um item à venda | 5678.39 | DEC(5,2) |
| cep |  |  | |  |
| peso_atomico | Peso atômico de um objeto com seis casas decimais | |  |
| comentarios | Bloco de texto grande de 255 caracteres | Joe. estou na reuniao... |  |
| quantidade | A quantidade deste item disponível no estoque | | |
| percentual_de_imposto | | 3.755 | |
