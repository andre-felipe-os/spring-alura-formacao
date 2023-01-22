# java-banco-de-dados-alura
Atividades desenvolvidas na formação Banco de Dados com Java da Alura.

## Módulo I - Java e JDBC
### Curso I - Java e JDBC: trabalhando com um banco de dados
Nesse curso criei um CRUD de produtos, armazendo-os em um banco de dados MariaDB. Todo o CRUD foi organizado sob o padrão DAO (*Data Access Objects*);

Cada produto contém um nome, uma descrição, um identificador e uma categoria. Desses atributos, somente a categoria foi armazenada em uma tabela externa, sendo acessada por uma chave estrangeira.

Não implementei dois assuntos vistos no curso por não serem úteis em uma aplicação tão simples: o *pool* de conexões e o controle de transações usando *commit* e *rollback*.

## Módulo II - ORM com JPA
### Curso II - Persistência com JPA: Hibernate
Nesse curso aprendi o básico de JPA utilizando o Hibernate.
- Aprendi sobre as configurações que podem ser feitas no arquivo *persistence.xml*.
- Criei mapeamentos simples para entidades e seus relacionamentos.
- Utilizei as transações da JPA para executar operações sobre as entidades.
- Usei os métodos *persist*, *remove* e *merge* para alterar os estados das entidades nos seus ciclos de vida da JPA.
- E por fim, fiz algumas consultas utilizando JPQL.

### Curso III - Java e JPA: consultas avançadas, performance e modelos complexos
Nesse curso formas mais avançadas de utilizar a JPA com Hibernate.
- Criei mapeamentos mais complexos, como *many-to-many* bidirecional.
- Fiz consultas utilizando *named queries*, *select new*, funções de agregação e a Criteria API.
- Vi que há diferença entre os carregamentos de consultas *lazy* e *eager*.
