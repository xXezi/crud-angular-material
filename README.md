## Cadastro de Clientes com Angular e Angular Material

Este projeto é um sistema de cadastro e consulta de clientes, desenvolvido com Angular e Angular Material. Os dados são armazenados no navegador via `localStorage`, e o sistema conta com integração à [BrasilAPI](https://brasilapi.com.br) para seleção dinâmica de estados e municípios.

---

### Conhecimentos adquiridos

- Criação de projetos com Angular CLI.
- Estrutura de componentes e rotas no Angular.
- Utilização de Angular Material para UI responsiva.
- Criação e estilização de formulários com validação.
- Aplicação de máscaras em campos de formulário.
- Feedback ao usuário com `MatSnackBar`.
- Armazenamento de dados no `localStorage`.
- Implementação de CRUD completo (Create, Read, Update, Delete).
- Consumo de APIs externas (BrasilAPI).
- Injeção de dependência e criação de serviços.
- Manipulação de parâmetros de rota para edição de registros.

---

### Tecnologias utilizadas

- Angular CLI - v19.0.2
- Angular Material
- Flex Layout
- UUID
- BrasilAPI
- TypeScript
- HTML / SCSS
- LocalStorage
- Postman
- VS Code

---

### Estrutura do Projeto

- `cadastro/cliente.ts`: Modelo de cliente com geração de ID único e atributos como nome, CPF, data de nascimento, e localização.
- `cadastro.component.ts/html`: Formulário de cadastro com campos dinâmicos, máscaras e integração com BrasilAPI.
- `consulta.component.ts/html`: Tabela de consulta com filtros, edição e exclusão de clientes.
- `cliente.service.ts`: Serviço responsável por salvar, atualizar, buscar e deletar clientes.
- `brasilapi.service.ts`: Serviço para consumir estados e municípios via BrasilAPI.
- `app.routes.ts`: Configuração de rotas para navegação entre componentes.
- `styles.scss`: Estilos globais reutilizáveis para espaçamentos e largura.

---

### Como executar o projeto

Siga os passos abaixo para rodar o projeto localmente.
```bash
# Clonar o repositório
git clone https://github.com/xXezi/crud-angular-material.git

# Acessar a pasta do projeto
cd crud-angular-material

# Instalar as dependências
npm install

# Executar o servidor
ng serve
```

Depois, abra o navegador e acesse: http://localhost:4200  
A aplicação será recarregada automaticamente sempre que você modificar os arquivos-fonte.

---

## Layout do projeto

### Tela inicial

![Home](https://github.com/xXezi/crud-angular-material/blob/main/src/assets/img/home.png)

### Formulário de cadastro

![Formulário](https://github.com/xXezi/crud-angular-material/blob/main/src/assets/img/cadastro1.png)
![Formulário](https://github.com/xXezi/crud-angular-material/blob/main/src/assets/img/cadastro2.png)
![Formulário](https://github.com/xXezi/crud-angular-material/blob/main/src/assets/img/cadastro3.png)

### Consulta de clientes

![Consulta](https://github.com/xXezi/crud-angular-material/blob/main/src/assets/img/consulta.png)

---

### Informações adicionais

[Documentação oficial do Angular](https://angular.dev/overview).
