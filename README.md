
# Projeto Task

<p align='center'>Gerenciador de Tarefas desenvolvido com <b> Spring Boot</b> no backend e <b> Angular</b> no frontend. O projeto é um CRUD completo para o gerenciamento de tarefas.</p>

<p align='center'>
 <a href="https://github.com/MikalROn/task-frontend">
    <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  </a>
  <a href="https://github.com/MikalROn/task-backend">
   <img alt="Spring" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white">
   </a>&nbsp;&nbsp;
</p>


---

## Tecnologias Utilizadas

- **Backend**: Java com Spring Boot e Thunder Client (para testes)
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

<p aling="center">Backend do sistema de tasks</p>

#### Requisitos

- Docker compose

#### Instalar
1. Clone o repositório do backend:
   ```bash
   git clone git@github.com:MikalROn/task-backend.git
   ```
2. Abra o projeto:

   ```bash
   cd task-backend
   ```
3. Inicie o banco de dados:
   ```bash
   docker-compose up -d
   ```
   
4. Compile e execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

#### Banco de dados

Você pode acessar o banco dedados atravez do phpmyadmin no link *http://localhost:8081/*

![myadmin](http://localhost:8081/)

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
