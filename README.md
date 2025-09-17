`markdown
# CRUD Usuários (Docker + Node + Postgres)

## 📖 Descrição
Este projeto implementa um sistema **CRUD de usuários**.  
Ele permite **criar, listar, editar e remover** usuários, utilizando a seguinte stack tecnológica:

- **Frontend**: HTML + JavaScript
- **Backend**: Node.js + Express
- **Banco de Dados**: PostgreSQL
- **Orquestração**: Docker Compose

---

## ⚙️ Pré-requisitos
Antes de começar, certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (>= 14.x)
- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)  
- [Git](https://git-scm.com/) (para clonar o repositório)

---

## 🚀 Como executar o projeto

### 1. Clonar o repositório
bash
git clone https://github.com/Guilh3rme/projeto_web_aula_27.git
cd projeto_web_aula_27
`

### 2. Subir os containers com Docker

bash
docker-compose up --build


### 3. Acessar a aplicação

* **Frontend**: [http://localhost:3000](http://localhost:3000)
* **API**: [http://localhost:3000/api](http://localhost:3000/api)

---

## 🗂 Estrutura do Projeto


projeto_web_aula_27/
│── docker-compose.yml        # Configuração dos containers
│
├── backend/                  # API Node.js
│   ├── index.js              # Ponto de entrada da API
│   ├── package.json          # Dependências do backend
│   └── db/                   # Scripts de inicialização do banco
│
├── frontend/                 # Interface do usuário
│   ├── index.html            # Página principal
│   └── app.js                # Lógica de consumo da API
│
└── README.md                 # Documentação do projeto


---

## 📝 Observações

* O projeto segue arquitetura simples (**Frontend + API + Banco de Dados**).
* O uso de **Docker** facilita a execução sem necessidade de configuração manual do PostgreSQL.
* Possíveis melhorias identificadas:

  * Melhorar mensagens de log do servidor.
  * Organizar o backend separando rotas e controladores.
  * Adicionar validação de dados no frontend.



---
