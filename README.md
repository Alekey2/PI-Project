# 🎸 MusicShop — Plataforma de E-commerce de Instrumentos Musicais

> Projeto desenvolvido para a disciplina de **Projeto Integrador** do 4º Semestre do curso de **Análise e Desenvolvimento de Sistemas**.

---

## 📋 Sobre o Projeto

O **MusicShop** é uma plataforma de e-commerce completa voltada para a **venda de instrumentos musicais de todos os tipos**. O sistema foi desenvolvido com uma arquitetura full-stack moderna, separando o back-end e o front-end em módulos independentes que se comunicam via API REST.

---

## 🚀 Tecnologias Utilizadas

### Back-end
| Tecnologia | Descrição |
|---|---|
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) **Java** | Linguagem principal do servidor |
| ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white) **Spring Boot** | Framework para criação da API REST |
| **Spring Data JPA** | Camada de persistência e acesso ao banco de dados |
| **Maven** | Gerenciamento de dependências |

### Front-end
| Tecnologia | Descrição |
|---|---|
| ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) **React.js** | Biblioteca para construção da interface |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) **JavaScript** | Linguagem principal do front-end |
| ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white) **SCSS** | Estilização avançada e responsiva |
| **HTML5 / CSS3** | Estrutura e estilo base das páginas |

---

## 🗂️ Estrutura do Projeto

```
PI-Project/
├── Back-end/          # API REST com Spring Boot (Java)
│   ├── src/
│   │   └── main/
│   │       ├── java/         # Controllers, Services, Repositories, Models
│   │       └── resources/    # application.properties
│   └── pom.xml
│
├── Front-end/         # Interface React + SCSS
│   ├── src/
│   │   ├── components/       # Componentes reutilizáveis
│   │   ├── pages/            # Páginas da aplicação
│   │   └── styles/           # Arquivos SCSS
│   └── package.json
│
└── README.md
```

---

## ⚙️ Funcionalidades

- 📦 **CRUD completo** de produtos (instrumentos musicais)
- 🛒 Catálogo de produtos com listagem e detalhes
- 🔍 Busca e filtragem de instrumentos por categoria
- 🖥️ Interface responsiva e moderna com React
- 🔗 API REST consumida pelo front-end via HTTP

---

## 🏁 Como Executar o Projeto

### Pré-requisitos

- [Java 17+](https://www.oracle.com/java/technologies/downloads/)
- [Node.js 18+](https://nodejs.org/)
- [Maven](https://maven.apache.org/)
- Banco de dados (MySQL ou H2 para testes)

---

### 🔧 Back-end (Spring Boot)

```bash
# 1. Acesse a pasta do back-end
cd Back-end

# 2. Configure o banco de dados em:
# src/main/resources/application.properties

# 3. Execute a aplicação
./mvnw spring-boot:run
```

A API ficará disponível em: `http://localhost:8080`

---

### 🎨 Front-end (React)

```bash
# 1. Acesse a pasta do front-end
cd Front-end

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm start
```

A aplicação ficará disponível em: `http://localhost:3000`

---

## 🔌 Endpoints da API

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| `GET` | `/produtos` | Lista todos os produtos |
| `GET` | `/produtos/{id}` | Busca produto por ID |
| `POST` | `/produtos` | Cadastra novo produto |
| `PUT` | `/produtos/{id}` | Atualiza produto existente |
| `DELETE` | `/produtos/{id}` | Remove um produto |

---

## 👤 Autor

Desenvolvido por **Alekey2**

---

## 📄 Licença

Este projeto é de uso acadêmico — desenvolvido para fins educacionais no curso de Análise e Desenvolvimento de Sistemas.


