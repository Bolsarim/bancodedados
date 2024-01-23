# Banco de Dados
É um sistema que vai armazenar dados e possui ferramentas para a organização desses dados.
É um mine-mundo.

## SGBT
*Sistema gerenciador de* **Banco de dados**

-MySQL.

-PostgreSQL

-SQLite.

-MongoDB.

-Microsoft SQL Server.
## TABELAS OU ENTIDADE
Tabelas são as estruturas que vão armazenar os dados.

Relaciona informações
### *Colunas*: campos ou atributos
É uma parcela da informção, é parte de uma informação, exemplo: Nome, endereço, números.

### *Linha*: Tupla
É o Registro

## SQL
 Essencialmente, é uma linguagem que permite comunicar com banco de dados com o objetivo de manusear os dados que eles armazenam

 # TRABALHANDO COM SQL
 ## CONECTANDO: 
 mysql -h localhost -u root

 `-h=` computador/host conectado

 `-u=` usuario que está ultilizando

 `-p=` senha

` Show databases=` mostra os bancos de dados
 ;= finaliza um comando

 `DROP DATABASE` "bd_login";  apaga a palavra

`CREATE TABLE` ; : criar tabela

  `() `: criar campos 
   
`DESC JOGOS;` : mostra a estrutura da tabela

`\ ! cls;` : limpar a tela

# COMANDOS SQL
## DDL
`- create database`

`- show database`

`- create table nome_da_tabela
`
`- show tables`

`- desc nome_da_tabela`

## DML - MANIPULAÇÃO DE DADOS

`- select * from nome_da_tabela`

`- insert into nome_da_tabela(campo1, campo2 ...)values(valor1, valoe2...)
`

# EXERCICIOS

`1. O que é um Sistema Gerenciador de Banco de Dados?`
R: É o lugar onde o banco de dados é criado, como mysql,PostgreSQL e etc..

`2. O que é um Banco de dados relacional?`
 É um conjunto de informações que organiza dados em relações predefinidas, em que os dados são armazenados em uma ou mais tabelas (ou "relações") de colunas e linhas, facilitando a visualização e a compreensão de como as diferentes estruturas de dados se relacionam.

`3. O que é T-SQL?`  É uma linguagem com a finalidade de reunir os comandos que serão empregados para diferentes funções, como a geração e o controle de todos os objetos, bem como a inserção, alteração, exclusão e recuperação de todos os dados presentes no banco.

`4. O que é PL/SQL?`
É uma linguagem que possibilita o desenvolvimento de programas que são armazenados, compilados e executados dentro do servidor de banco de dados Oracle.

5. T-SQL e PL/SQL são iguais? Caso não sejam, cite 3 diferenças entre elas. 
Não são iguais, as 3 diferenças entre elas são a maneira de como elas lidam com váriaveis, procedimentos armazenados e funções integradas.

`6. O Que é:`

`A. DML:` Manipulação de dados.

`B. DDL:` Definição de dados.

`C. DCL:` Controle de dados.


