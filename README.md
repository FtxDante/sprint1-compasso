# SPRINT 1 🏃

## :red_circle: HTTP: _o protocolo mais importante_.
HTTP é um protocolo de comunicação utilizado para sistemas de informação de hipermídia, distribuídos e colaborativos.

* **HTTP/1.1: HyperText Transfer Protocol** 

* **HTTPS: Camada adicional de segurança**

### Melhorias do HTTP2 ↗️

* Corpo da resposta comprimido pelo GZIP // Dados mais leves.
* Request e Response:
  * Foram convertidos em binário.
  * Foram comprimidos com HPACK
* Camadas de TLS (Segurança) agora é o padrão.

### URL: O caminho 🗺️

Um URL se refere ao endereço de rede no qual se encontra algum recurso informático, como por exemplo um arquivo de computador ou um dispositivo periférico.

Ex: https://compassouol.com/



## :green_heart: MongoDB: Um Banco de Dados NoSQL

MongoDB é um banco de dados orientado a documentos que armazena dados em documentos **JSON** com esquema dinâmico. Isso significa que você **pode armazenar** seus registros **sem se preocupar com a estrutura de dados**, como o número de campos ou tipos de campos para armazenar valores. **Os documentos do MongoDB são semelhantes** aos objetos **JSON**.

### COMO É UM ARQUIVO JSON:

```json
{“endereco”: [
   {
      “rua”: Leonor Viana,
      “cidade”: São Paulo,
      “estado”: SP
   }
]};
```

### Vantagens do MongoDB

- ✔️ Utilizando MongoDB **temos uma melhor performance**, visto que uma única consulta retorna tudo o que precisamos saber sobre o documento.
- ✔️ Os bancos de dados **NoSQL** vão apresentar sempre muitas vantagens sobre os outros quando o assunto for necessidade. Trará assim a **escalabilidade**, **flexibilidade** e também o** desempenho** e uma **facilidade para as consultas**.
- ✔️ **As consultas são simples de serem feitas**, porém quando não existirem as transações e também joins.



## :large_blue_circle: SQL e MySQL 

### SQL (Structured Query Language)

Essa **linguagem de programação** foi criada para que os programadores pudessem **acessar**, **consultar** e **modificar** os dados estruturais de uma empresa ou organização.

Uma programação baseada em SQL pode ser usada para realizar tarefas complexas, como por exemplo, **escrever queries** e fazer consulta ou **manipulações**. Também podem executar tarefas simples em tabelas:

- Insert (inserir);
- Delete (excluir);
- Update (atualizar);
- Search (pesquisar).

#### Tipos de comandos:

- DML – Data Manipulation Language: **comandos que alteram informações nas tabelas, seja para inserir ou excluir dados (ex: select, delete e insert);**

- DDL – Data Definition Language: são comandos que modificam o banco de dados (ex: drop – apaga algum objeto e create – permite a criação de novos objetos);

- DCL – Data Control Language: é o grupo responsável pelas permissões, restrições ou bloqueios (ex: grant – permite o acesso e/ou modificações no banco de dados);

- DTL – Linguagem de Transição de Dados: é responsável por salvar as alterações feitas pelos usuários (ex: commit – autoriza que as alterações sejam salvas).

### MySQL

MySQL é um sistema de gerenciamento de Banco de Dados

#### Similaridades entre bancos de dados SQL:

São elas: **tabelas** para armazenar dados, **referências a chaves primárias** e **externas**, assim como **múltiplos bancos de dados** dentro de um único ambiente ou servidor. 
