## SQL ou NoSQL, qual Banco de Dados devo usar?
Depende. Essa é resposta mais direta possível, e vou explicar o porquê.

Primeiramente, quem é o responsável pela estruturação e modelagem de dados? Estamos falando do Engenheiro de Dados, além de criar, ele deve garantir que os dados sejam armazenados, distribuídos e disponibilizados conforme o esperado e, isso envolve, definir qual será a arquitetura utilizada. Sabemos que existem dois tipos de base de dados amplamente utilizadas: SQL para banco relacionais e NoSQL para banco não-relacionais.
A escolha da arquitetura deve ser feita a partir do entendimento e da finalidade do próprio Banco de Dados. Quanto mais informações e clareza sobre o objetivo do Banco de Dados que será desenvolvido, mais fácil vai ser escolher a estrutura que melhor supre as necessidades do projeto.
Vamos ver alguns conceitos e diferenças entre SQL e NoSQL.

SQL é a linguagem de programação padrão utilizada para definir, consultar e manipular dados de uma estrutura de dados relacional. É uma opção em que os dados são guardados dentro de tabelas, e é muito utilizado por sua segurança e possibilidade de consultas complexas. Porém, devido ao seu esquema de dados previamente definidos e estruturados, pode se tornar menos flexível a mudanças. 
Dentre os bancos mais populares estão o Oracle, MySQL e PostgreSQL. 

Já o NoSQL ou Not Only SQL, como o nome já diz, não utiliza somente SQL e é uma estrutura de dados não-relacional. Isso implica em mais flexibilidade, reduz o nível de complexidade ao realizar *querys* . Essa estrutura foi criada a partir da necessidade de armazenamento de um volume maior de dados, utilizando um escalonamento horizontal, que permite manter uma alta performance na busca e retorno dos dados.
Ainda sobre o NoSQL, os dados podem ser armazenados de várias formas: documentos, colunas, grafos e chave-valor.
Exemplo de bases de dados NoSQL: MongoDB, Redis, Cassandra.

Cada base de dados tem suas especificidades que se encaixam melhor em cada cenário. Isso significa que SQL não é melhor que NoSQL ou vice-versa, ambos são úteis para o contexto para que foram designados. Então, antes de tudo, devemos conhecer principalmente a finalidade do projeto de dados e o propósito de cada base de dados, para que a escolha entre SQL e NoSQL faça sentido. E ainda há o modo híbrido, em que as duas bases de dados podem se complementar para atingir o objetivo de um projeto.
