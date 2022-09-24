# Diferença-de-SQL-e-noSQL-
Desafio de Projeto da Dio. Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos.  
Pré-requisitos:  Conhecimento Avançados(SQL, NoSQL);  Computador com SO de sua preferência(Windows, Linux, Mac OS);

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Diferença entre SQL e noSQL na Engenharia de Dados: 

SQL - Banco de Dados Relacional:  

É a linguagem utilizada para executar comandos em Banco de Dados Relacionais, isto é, baseado em tabelas e que as informações possuem relacionamento entre si. Por meio dela é possível criar databases, tabelas, colunas, índices, garantir e revogar privilégios a usuários e consultar os dados armazenados no banco de dados. Possui Escalabilidade vertical e é mais utilizado quando se conhece o esquema antes de se modelar. 

SQL é uma linguagem declarativa dividida em conjuntos de comandos que são: 

DDL ou Linguagem de Definição de Dados - Responsável pelos comandos de criação e alteração no banco de dados. Os principais comandos são: CREATE, ALTER e DROP. 

DML ou Linguagem de Manipulação de Dados - São comandos utilizados para a recuperação, inclusão, remoção e modificação de informações em bancos de dados. Os principais comandos são: INSERT, UPDATE, DELECT. 

NoSQL – Banco de dados não relacional:  

O grande diferencial dessa tecnologia em relação ao SQL é a capacidade de escalabilidade horizontal, que proporciona para as empresas uma operacionalidade de uma forma mais simples e econômica. Também proporciona uma performance melhor para o gerenciamento de dados, pois não há necessidade de agrupar os dados em um esquema de tabelas para usar as informações. Gerando assim uma maior flexibilidade por não ter uma estrutura de dados rígida. 

É dividida pela forma em que são armazenadas que são:  

Documentos – Armazena dados e documentos autocontidos e auto descritivos, permite redundância e inconsistência. Livre de esquemas podendo utilizar JSON, XML entre outros. Principal Banco de Dados e o MongoDB. 

Chave-valor – armazena um conjunto de dados identificados por um identificador exclusivo. Gerando assim um bom desempenho em aplicações na nuvem, porém possui uma menor capacidade de busca. Usado principalmente para cache, sessão de usuário e carrinhos de compra. Principal Banco de Dados é o Redis. 

Coluna/família de colunas – Armazena as informações nas colunas de forma independente entre elas. Uso principal é para ser consultado pela chave primária. Principal Banco de dados é o Cassandra. 

Grafos – É baseado entre nós (dados) e vértices (relacionamentos), utilizado principalmente para detecção de fraudes, mecanismos de recomendação, sistemas de arquivos, redes sociais, games e etc. Principal banco de dados é o Neo4j. 
