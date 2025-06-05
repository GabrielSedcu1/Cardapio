✍️ Sobre o Projeto
Desenvolvimento de uma aplicação fullstack composta por Java Spring Boot no backend e React no frontend. Esta primeira etapa contempla exclusivamente a criação do backend, com foco na construção de uma API RESTful completa, organizada e preparada para integração com o frontend.

⚙️ Tecnologias Utilizadas
Java 17 — linguagem principal para desenvolvimento backend.

Spring Boot — framework para simplificação da configuração e estruturação da aplicação.

Spring Data JPA — abstração da camada de persistência, facilitando o CRUD.

MySQL — banco de dados relacional.

Maven — gerenciamento de dependências e build.

Postman — ferramenta para testes de API.

🗂️ Estrutura do Backend
A estrutura do backend foi organizada seguindo as melhores práticas, utilizando as seguintes camadas:

Entidade Produto: com atributos id, nome, descricao e preco.

Repositório: interface com Spring Data JPA, permitindo operações CRUD automáticas.

Serviço: camada intermediária para centralização da lógica de negócios.

Controller: responsável por expor os endpoints REST, com as seguintes rotas:

GET /produtos → Listagem de todos os produtos

POST /produtos → Cadastro de novos produtos

PUT /produtos/{id} → Atualização de produtos

DELETE /produtos/{id} → Exclusão de produtos

🗄️ Banco de Dados: MySQL
Utilização do banco de dados MySQL para garantir persistência e escalabilidade.

O banco foi criado previamente, e a estrutura das tabelas foi gerenciada automaticamente pelo Hibernate com base nas entidades definidas no projeto.

✅ Funcionalidades Implementadas
Cadastro de produtos

Listagem completa de produtos

Atualização de dados de produtos

Remoção de produtos

Validação de dados nas requisições

Todos os endpoints foram testados com Postman para garantir o correto funcionamento e integridade dos dados.

📌 Principais Resultados
Estrutura backend organizada e seguindo o padrão Model → Repository → Service → Controller.

Conexão estável e eficiente com banco de dados MySQL.

API RESTful funcional, com todas as operações CRUD implementadas e testadas.

