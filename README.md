
# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

Atividade desenvolvido como atividade de desafio de projeto do Bootcamp Database Expericence da [DIO](https://web.dio.me), com objetivo de compreender o papel dos Bancos de Dados Relacionais(SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados.

## Autores

- [@ericscunha](https://www.github.com/ericscunha)


## O que é SQL e NoSQL

### SQL

SQL é a sigla para Structured Query Language, refere-se a linguange utilizada nos Bancos de dados relacionais, que são um conjunto de informações modelados em tabelas que possuem relacionamento entre si, obedecendo um esquema pré-estabelecido, rígido que apresenta consistência.

* Características dos BD's Relacionais

- Os bancos de dados consistem em várias entridades
- A linguagem SQL é a interface padrão
- Altamente estruturado e representado usando um equema (lógico e físico)
- Reduz a redundância de dados

* Propriedades ACID

Quatro propriedades cruciais definem transações de bancos de dados relacionais: Atomicidade, Consistência, Isolamento e Durabilidade,

- A Atomicidade define todos os elementos que compõem uma transação completa do banco de dados.
- A Consistência define as regras para manter os pontos de dados em um estado correto após uma transação.
- O Isolamento matém o efeito de uma transação invisível para outras pessoas até ser confirmada, para evitar confusão.
- A Durabilidade garante que as alterações de dados se tornem permanentes quando a transação for confirmada.

* Exemplos de Bancos de Dados Relacionais

- OracleDB
- SQL Server
- MySQL
- PostgreSQL

### NoSQL

NoSQL ou Not Only SQL é o termo utilizado para bancos de dados não relacionais de alto desempennho, onde geralmente não é utilizado o SQL como linguagem de consulta. Surgiu da necessidade crescente de tratamento de grande volumes de dados e dados não estruturados em diversos formatos.

* Tipos de não relacionais

- Key value, coleção de pares de chave-valor em um objeto.
- Document, utiliza uma string para denominar uma base de dados no formato JSON. Flexível, Os documentos não precisam manter estrutura idêntica.
- Wide-column, armazena seus dados em colunas flexíveis que podem ser compartilhadas em múltiplos servidores e bancos de dados.
- Graph, projetado para armazenar de forma eficiente as relações entre as entidades.

* Exemplos de Bancos de Dados Não Relacionais

- Redis (Key-value)
- MongoDB (Document)
- Cassandra
- Neo4J

### Comparações SQl e NoSQL

* Escalabidiade

- SQL: Vertical
- NoSQL: Grande facilidade em escalar Horizontalmente

* Estrutura de dados

- SQl: Dados Estruturados
- NoSQL: Melhores para manipular dados não estruturados. Permitem doferentes estruturas para a mesma informação.

* Flexibilidade

- SQL: Mais rígidos.
- NoSQL: Por não precisar seguir uma estrutura pré-definida, são mais flexíveis às mudanças.

* Performance

- SQL: Depende do sistema de disco.
- NoSQL: Depende do tamanho do cluster e latência da rede.

* Consistência dos dados

- SQL: Maior consistência e organização.
- NoSQL: Menor garantia de consistência.


O NoSQL veio para atender o que o SQL não resolvia, não tendo como objetivo substituí-lo. O NoSQL vem para resolver situações que precisam de flexibilidade, sem esquemas rígidos, maior performance e suporte a um maior volume de dados variados.


No NoSQL, embora temnha flexibilidaded e diversidade de dados, é preciso dimensionar o banco para garantir performance nas consultas através das chaves. Não é porque se está usando um Não Relacional que se deixará de modelar o banco de dados.

## Conhecer um SGBD de cada tipo é suficiente para iniciar na carreira de dados?

Não é preciso conhecer todos ou se especializar em todos. É importante conhecer o contexto, os conceitos para reconhcer as situações aplicáveis e buscar o conhecimento específico quando necessário.

É preciso analisar o cenário dos dados que será trabalhado, o problema a ser resolvido, os tipos de dados (estruturados ou não estruturados), definir os critérios técnicos para  definir a arquitetura e escolher a ferramenta adequada para aplicar na resolução do problema, analisando, também, o custo x benefício.

## Data Lake

Data lake é um repositório centralizado de informações que permite armazenar dados estruturados e não estrurados em qualquer escala.

### 5 capacidade básicas

1- Ingestão
2- Armazenamento
3- Processamento
4- Disponibilidade da informação / Consumo
5- Segurança e governança

É preciso cuidados de governança para não tornar o data lake em um pantâno de dados (data swamp).


## Engenheiro de Dados x Cientistas de dados

São perfis complementares. O Engnheiro de dados está ligado a preparação dos dados. Deve ter o perfil voltado para a coleta, preparo e amarzenamento dos dados, deixando a informação disponível para o cientista de dados utilizar. O Cientisda de dados, por sua vez, está mais ligado a construção de modelos de Machine Learning e IA com o objetivo de utilizar os dados para extrair insgihts. Enfim, aplicar processamento nos dados disponibilizados pelos Engenheiros de Dados.


## Dicas

- Conhecimento amplo do ecossistema de dados
- Curiosidade
- Olhar crítico na escolha das tecnologias necessárias para o negócio
- Desenvolvimento de técnicas de ETL
- Conhecimento de algumas ferramentas como Spark, Apache Nifi, Power Center, Cloud's (GCP, AWS, Azure)


 
