# <h1 align="center">  📑 Challenge Forum Hub 📑 </h1>
Challenge de construção de uma API Restful de um fórum, que inclui persistências e acessos de usuários, tópicos e respostas, implementado com Spring Boot e MySQL.<br>
Proposto pela Oracle Next Education, na formação de Back-end Java, em parceria com a Alura.


## 🔧 Sobre o projeto
- Uma API Rest simples e robusta, estruturada utilizando as melhores práticas de programação, arquitetada com a ideia do "Clean Architecture" e "MVC", os quais permitem a organização do código por camadas como: domain, infra e controller.
- O objetivo da API é realizar a persistência de tópicos e suas respectivas respostas, além de cadastro de usuários com autenticação de tokens, e permitir o acesso desses dados em formato JSON, para manipulação no front-end.
- A API fornece endpoints para interação, e cada endpoint tem sua função (persistência ou busca) implementadas também com os verbos HTTP respectivos, além de nível de acesso para endpoints que realizam funções mais sensíveis.


<br>
<div align="center">
  <img alt="Badge conclusão do challenge ONE" src="C:\Users\Jp.Fagundes\OneDrive\Desktop\Projetos\IntelliJ\ForumHub\api\Badge-Spring.png" width="10" height="10">
</div>
<br>


## ✨ Funcionalidades

- 👤 **Criar usuário**:  
  Cria um novo usuário na base de dados. Os dados necessários devem incluir informações como nome, e-mail e senha.

- 🔐 **Realizar login**:  
  Autentica o usuário e gera um token de acesso. O token será usado para acessar endpoints protegidos.

- 📝 **Registrar tópico**:  
  Permite criar um novo tópico no sistema, enviando informações como título e conteúdo.

- 🔍 **Listar tópico específico**:  
  Retorna os detalhes de um único tópico com base no identificador fornecido (ID).

- 📋 **Listar todos os tópicos**:  
  Retorna uma lista completa de todos os tópicos disponíveis no sistema.

- ✏️ **Atualizar tópico**:  
  Permite editar as informações de um tópico existente, como o título ou o conteúdo, enviando o ID do tópico.

- 🗑️ **Excluir tópico**:  
  Remove um tópico da base de dados com base no seu identificador (ID).




## 📋 Como funciona?
- Todos os endpoints necessitam de autenticação por tokens no padrão JWT.
- Apenas o endpoint "POST /usuarios" é livre de autenticação e disponível para acesso geral, justamente por ser o endpoint que realiza o login do usuário e retorna um token JWT válido para uso em outras requisições.
> O formato padrão de retorno dos dados serializados é o formato JSON (JavaScript Object Notation).

## 💻 Tecnologias e ferramentas utilizadas
- Java (JDK 17)
- Spring Boot e JPA Hibernate
- Spring Security e Spring Doc
- Bean Validation, Lombok e Flyway
- Auth0 para tokens JWT
- IntelliJ e Git
- MySQL
## Autor

- [@jpfagundes](https://www.github.com/jpfagundes)

## Contato

- [Email] jpsafagundes@hotmail.com

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jpfagundes/)