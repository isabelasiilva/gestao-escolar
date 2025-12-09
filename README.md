# Gestão Escolar 

Projeto desenvolvido para o gerenciamento de alunos, composto por uma API RESTful em .NET e um Frontend moderno em Angular.

<img width="600" alt="home" src="https://github.com/user-attachments/assets/0efedbc4-14a8-44f3-91c8-14d8870ffc34" />


## 🚀 Tecnologias Utilizadas

### Backend
- **.NET 8**: Framework principal para construção da API.
- **Entity Framework Core**: ORM para acesso e manipulação do banco de dados.
- **SQL Server**: Banco de dados relacional.
- **Swagger**: Para documentação e teste dos endpoints da API.

### Frontend
- **Angular 18**: Framework para construção da interface de usuário.
- **PrimeNG**: Biblioteca de componentes visuais ricos.
- **PrimeFlex**: Sistema de grid e utilitários CSS flexíveis.
- **Ngx-Mask**: Biblioteca para máscaras de input (ex: CPF).

## Funcionalidades
* **Comunicação API**: Integração completa entre o frontend e o backend.

*   **Cadastro de Alunos**: Interface amigável para registrar novos alunos com validação de dados.
<img width="700" alt="cadastro-alunos" src="https://github.com/user-attachments/assets/3d0d0ef2-1713-43db-bdcd-719a78fb4ddb" />
<img width="700" alt="cadastro-alunos-sucesso" src="https://github.com/user-attachments/assets/09a6fadc-5b47-47e1-9661-5cff66cb0372" />

*   **Listagem de Alunos**: Visualização em tabela dos alunos cadastrados na base de dados.


<img width="700" alt="alunos-cadastrados" src="https://github.com/user-attachments/assets/1d86b344-4e85-47db-ac1c-b0006e06f12d" />

*   **Edição**: Atualização dos dados cadastrais.

  <img width="700" alt="alunos-cadastrados-editar" src="https://github.com/user-attachments/assets/1c8b5bea-4119-46e2-a7e0-2cc91e69b871" />
<img width="700" alt="alunos-cadastrados-editar-sucesso" src="https://github.com/user-attachments/assets/9c665cdb-ce9c-43ac-9bb1-21536db10797" />

*   **Exclusão**: Remoção de registros de alunos.
<img width="700" alt="alunos-cadastrados-deletar" src="https://github.com/user-attachments/assets/66ef8e3e-497d-4440-8168-20752aef49e8" />

  
*   **Integração API**: Comunicação completa (CRUD) com o backend.

## 🔧 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- SQL Server (LocalDB ou instância dedicada)

### 1. Configuração do Backend (`gestao-escolar-api`)

1. Navegue até a pasta da API:
   ```bash
   cd gestao-escolar-api
   ```

2. Verifique a string de conexão no arquivo `appsettings.json`. O padrão geralmente aponta para o servidor local.

3. Atualize o banco de dados (EF Core):
   ```bash
   dotnet ef database update
   ```

4. Inicie a aplicação:
   ```bash
   dotnet run
   ```
   A API estará disponível em `https://localhost:7060` (Swagger em `https://localhost:7060/swagger`).

### 2. Configuração do Frontend (`gestao-escolar-frontend`)

1. Abra um novo terminal e navegue até a pasta do Frontend:
   ```bash
   cd gestao-escolar-frontend
   ```

2. Instale as dependências do projeto:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```
   Ou:
   ```bash
   ng serve -o
   ```

4. Acesse a aplicação no navegador:
   `http://localhost:4200`

---

## 📂 Estrutura de Pastas

*   `gestao-escolar-api/`: Contém todo o código do backend (.NET).
*   `gestao-escolar-frontend/`: Contém todo o código do frontend (Angular).

---
Desenvolvido por Isabela Silva.
