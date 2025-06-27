# 📚 Plano de Aula – Projeto API RESTful de ToDo List com Spring Boot e JavaScript

## 🎯 Tema da Aula
Desenvolvimento de uma API RESTful utilizando Spring Boot (Java) no backend e HTML, CSS, JavaScript com `fetch` no frontend, aplicando boas práticas de desenvolvimento.

---

## ⏱️ Duração Estimada
2 a 3 aulas de 1h30 cada (adaptável conforme a carga horária)

---

## 🧠 Objetivos de Aprendizagem

- Compreender os princípios de uma API RESTful
- Criar endpoints REST com Spring Boot
- Aplicar boas práticas de arquitetura (camadas: Model, Repository, Service, Controller)
- Testar a API com Postman
- Criar frontend que consome a API usando JavaScript e `fetch`
- Praticar validação de dados e estruturação de projetos

---

## 🛠️ Tecnologias Utilizadas

- **Backend:** Java, Spring Boot, Spring Web, Spring Data JPA, H2 (ou MySQL)
- **Frontend:** HTML, CSS, Bootstrap, JavaScript (fetch API)
- **Ferramentas:** Postman, Git, GitHub, IDE (IntelliJ ou VS Code)

---

## 📚 Conteúdo Programático

### Aula 1 – Introdução e Criação da API

- Conceitos de API RESTful
- Métodos HTTP: `GET`, `POST`, `PUT`, `DELETE`
- Estrutura do projeto Spring Boot
- Criação da entidade `Tarefa` (`id`, `titulo`, `descricao`, `concluida`)
- Configuração do banco H2
- Testes iniciais com Postman

> **Atividade prática:** Implementar os métodos `GET`, `POST` e `DELETE` no controller de tarefas.

---

### Aula 2 – Finalização da API e Consumo no Frontend

- Implementar método `PUT` (edição de tarefas)
- Criar layout com HTML + Bootstrap
- Usar `fetch()` para consumir a API no frontend
- Listar tarefas dinamicamente
- Criar formulário para adicionar tarefas

> **Atividade prática:** Criar página funcional que consome a API e exibe/adiciona tarefas.

---

### Aula 3 – Boas Práticas e Refino

- Configurar CORS no backend
- Validar dados com `@Valid` e `@NotBlank`
- Criar DTOs para desacoplar as camadas
- Utilizar status HTTP corretos e mensagens de erro
- Refatoração: separação de responsabilidades, tratamento de exceções
- Discussão: como evoluir esse projeto?

> **Atividade prática:** Adicionar botão "Concluir tarefa" e feedback visual no frontend.

---

## 🗂️ Estrutura de Pastas Sugerida

```

todo-api/
├── model/
├── repository/
├── service/
├── controller/
└── dto/ (opcional)

todo-frontend/
├── index.html
├── script.js
└── style.css

```

---

## 🧪 Avaliação

- Participação nas atividades práticas
- Código funcional entregue em dupla ou individual
- Apresentação final explicando o funcionamento da API e do frontend

---

## 💡 Recursos Didáticos

- Slides teóricos (REST, camadas, HTTP)
- Quadro para fluxogramas ou mapa mental
- Repositório base ou projeto inicial
- Postman para testes

---

> Este projeto foi desenvolvido com fins pedagógicos para o ensino de desenvolvimento de APIs RESTful com boas práticas utilizando Java, Spring Boot e JavaScript.

