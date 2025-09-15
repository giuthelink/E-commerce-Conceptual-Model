
# Projeto E-commerce

No projeto do E-commerce, aprendi os conceitos elementares sobre o modelo conceitual de Banco de Dados, assim como outros conceitos de refinamento que tornam o modelo mais otimizado, evitando conflitos ou erros inesperados.

Tomando como ponto de partida o modelo feito pela lecionante do curso, foram solicitadas três alterações para otimizar o Banco de Dados:

- Inclusão de Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

## Soluções Propostas

1) Criei as entidades Cliente_PJ e Cliente_PF, ambas vinculadas á entidade Cliente, coloquei então a sua Foreign Key nas entidades que dela derivam.

2) Criei a entidade Forma de Pagamento, sendo esta ligada ás entidades Pedido e Cliente, com cardinalidades 1-N e N-1, respectivamente. A tabela Pedido recebe a Foreign key de Forma de Pagamento, como é de se esperar, e esta última recebe a foreign key de Cliente.

3) Enfim, criei a tabela entrega, e a conectei com a tabela pedido com a cardinalidade 1-1, ou seja, apenas será feita uma entrega por pedido. Coloquei também atributos como o status da entrega e o código de rastreio.

### Conecte-se comigo 🤝🌐

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giuliano-ferreira-563823210/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/giuthelink)
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=007BFF)](mailto:giuliano.br.work@outlook.com)

# E-commerce Project

In the E-commerce project, I learned the fundamental concepts of the conceptual model of Databases, as well as other refinement concepts that make the model more optimized, avoiding conflicts or unexpected errors.

Starting from the model created by the course instructor, three changes were requested to optimize the Database:

- Inclusion of Individual and Corporate Clients – An account can be either PJ or PF, but it cannot have both pieces of information simultaneously;

- Payment – A client can have more than one payment method registered;

- Delivery – Contains status and tracking code.

## Proposed Solutions

1) I created the entities Client_PJ and Client_PF, both linked to the Client entity. I placed the foreign key of Client in both derived entities, thus ensuring that it will not be possible to use both entities simultaneously.

2) I created the Payment Method entity, linking it to the Order and Client entities, with cardinalities 1-N and N-1, respectively. The Order table receives the foreign key from Payment Method, as expected, and the latter receives the foreign key from Client.

3) Finally, I created the Delivery table and connected it to the Order table with a 1-1 cardinality, meaning that only one delivery will be made per order. I also added attributes such as delivery status and tracking code.

### Connect with me 🤝🌐

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giuliano-ferreira-563823210/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/giuthelink)
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=007BFF)](mailto:giuliano.br.work@outlook.com)