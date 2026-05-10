## ToDoList

ToDoList é uma aplicação web que permite criar, editar e remover tarefas. Cada tarefa possui um nome e uma breve descrição. O projeto foi desenvolvido como estudo de boas práticas com ReactJS, incluindo gerenciamento de estado global com Redux, roteamento protegido e consumo de API REST.

A aplicação consome a [JSONPlaceholder](https://jsonplaceholder.typicode.com/) como API fake para simular operações de CRUD.

**[Acesse a demo ao vivo](https://mystifying-newton-9c5a3b.netlify.app/task)**

<img src="https://user-images.githubusercontent.com/47945703/129308723-d3a4deb0-806c-4e9e-a743-622551c99e43.png" alt="Screenshot da aplicação ToDoList" width="900"/>

## Funcionalidades

- Autenticação com rota protegida (`PrivateRoute`)
- Listagem de tarefas
- Cadastro de nova tarefa (nome + descrição)
- Edição de tarefa existente
- Remoção de tarefa
- Página 404 para rotas inexistentes
- Tema global com Styled Components

## Tecnologias

| Tecnologia | Versão |
|---|---|
| React | 17.0.2 |
| React Router DOM | 5.2.0 |
| Redux | 4.1.0 |
| Redux Thunk | 2.3.0 |
| React Redux | 7.2.4 |
| Styled Components | 5.3.0 |
| Prop Types | 15.7.2 |

**Dev:** ESLint, Prettier, Testing Library

## Como Executar

**Pré-requisito:** Node.js >= 14

```bash
# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
```

A aplicação ficará disponível em `http://localhost:3000`.

### Outros scripts

| Comando | Descrição |
|---|---|
| `npm test` | Executa os testes |
| `npm run build` | Gera o build de produção |
