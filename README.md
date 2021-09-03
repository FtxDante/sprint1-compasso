# SPRINT 1 :calendar:

## :small_blue_diamond: SCRUM: Método Ágil

### Metáfora SCRUM: :thought_balloon:

A ideia do SCRUM foi inspirado no jogo americano Rugby, na qual uma partida só pode ser ganha com a colaboração do time.

#### Sprint :running_woman:

É um período curto de tempo (geralmente de 1 à 2 semanas), SPRINT  é um tipo de corrida de velocidade em que o atleta percorre uma distância curta num período de tempo mais curto ainda.

##### Duração de uma Sprint :clock1:

- Inicio do projeto = sprints mais curtas
- Muita demanda = sprints mais longas
- Pouco conhecimento = sprints mais longas
- Pessoas mais jovens =sprints mais curtas

### Etapas da Sprint

- **Planning (planejamento)**
  - Participantes = Time completo
  - Tempo = 5% do tempo total da Sprint
  - Product Owner deve ter feito o *grooming*, ou refinamento, do topo do Product Backlog
  - Analisar o Product Backlog e decidir o Sprint Backlog
  - Sprint Backlog = tarefas + histórias
  - Criar meta (frase que exprime valor incremental da sprint)
- **Desenvolvimento**
- **Daily Scrum**
  - Uma reunião diária com duração de até 15 minutos
  - Mesmo horário e local
  - Três perguntas principais devem ser respondidas: O que fez? O que fará? Quais problemas enfrentou?
  - Participantes = Time completo
- **Review Meeting (reunião de revisão)**
  - Tempo = até 2,5% do tempo total da sprint
  - cliente e o time de desenvolvimento se reúnem para mostrar os incrementos feitos na Sprint
  - Novas demandas = novo cartão no Product Backlog
  - Conceito de Pronto
-  ***Retrospective* (retrospectiva): melhoria contínua**
  - Participantes = Time completo
  - Melhoria contínua

### Papéis no Scrum

- **Scrum Master:** focar no processo e se assegurar que o time esteja tirando o maior proveito possível dele.
- **Product** **Owner** **(P.O.):** dono do *Product* *Backlog*.
- **Desenvolvedor:** atuar como time, decidir abordagem técnica, estimar histórias, realizar tarefas.
- **Time todo:** melhoria contínua.



## :yellow_heart: Git e Github

Git é um sistema de controle de versão, serve para facilitar e melhorar a relação entre o desenvolvedor e o código.

**O git pode : :point_down:**

- Manter um histórico de alterações.
- Controlar cada alteração no código.
- Separar alterações, uma alteração de determinada pessoa não influencie na alteração realizada por outra.

### Definições :mag_right:

- Branches: possibilita seguir com versões diferentes de um mesmo código sem que um interfira na outra.
- Merge: une branches.
- É possível transitar entre branches.
- Git checkout: desfaz uma alteração que ainda não foi adicionada ao index ou stage, ou seja, antes do git add. 
- Desfazer pós commit: git reset HEAD <arquivos> e depois podemos desfazê-las com git checkout -- <arquivos>
- Git revert = reverte alterações, gerando novo commit.
- Git stash = guarda um trabalho sem commitar.
- Git diff = mostra alterações feitas em cada arquivo.
- Com ele é possível comparar duas branches ou dois commits.
- Git tag = salva marcos da aplicação. Geram Releases no GitHub.
- 

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

MySQL é um sistema de gerenciamento de Banco de Dados (SGBD)

**Similaridades entre bancos de dados SQL:**

Os bancos de dados relacionais se parecem, eles tem: **Tabelas** para armazenar dados, **referências a chaves primárias** e **externas**, assim como **múltiplos bancos de dados** dentro de um único ambiente ou servidor. 



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





