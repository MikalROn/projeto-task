
# Projeto Task

Gerenciador de Tarefas desenvolvido com **Spring Boot** no backend e **Angular** no frontend. O projeto é um CRUD completo para o gerenciamento de tarefas.

---

## Tecnologias Utilizadas

- **Backend**: Java com Spring Boot, Thunder Client (para testes)
- **Frontend**: Angular, Bootstrap, Angular Material
- **Banco de Dados**: MySQL 
- **Gerenciamento de Dependências**: Maven (backend) e NPM (frontend)
---

## Estrutura do Projeto

O projeto está dividido em dois repositórios:

### 1. [Frontend](https://github.com/MikalROn/task-frontend)
Desenvolvido com Angular. Fornece a interface de usuário para a aplicação.

### 2. [Backend](https://github.com/MikalROn/task-backend)
API REST desenvolvida em Spring Boot, que gerencia os dados e a lógica do sistema.

---

## Funcionalidades

- **Listagem de Tarefas**: Visualize todas as tarefas cadastradas.
- **Criação de Tarefas**: Adicione novas tarefas com título e descrição.
- **Edição de Tarefas**: Atualize os detalhes de uma tarefa existente.
- **Exclusão de Tarefas**: Remova tarefas que não são mais necessárias.
- **Concluir tarefas**: Atualiza tarefa como concluida 
- **Desfazer Conclusão de Tarefas**: Permite valtar atras na conclusão da tarefa
---

## Instalação

### Backend
1. Clone o repositório do backend:
   ```bash
   git clone git@github.com:MikalROn/task-backend.git
   ```
2. Configure o arquivo `application.properties` com os detalhes do banco de dados.
3. Compile e execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

### Frontend
1. Clone o repositório do frontend:
   ```bash
   git clone git@github.com:MikalROn/task-frontend.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Execute o projeto:

> Use npm start para que rode as configurações de proxy.

   ```bash
   npm run start
   ```
4. Acesse a interface no navegador: [http://localhost:4200](http://localhost:4200)

---

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## Contato

- **Autor**: [MikalROn](https://github.com/MikalROn)
