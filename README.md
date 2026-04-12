# Curso de Continuos Integration em Go - API com Gin

[![Go](https://img.shields.io/badge/Go-1.15-blue.svg)](https://golang.org/)

### Descrição do Projeto
📚 O presente projeto é uma API construída com a linguagem Go e o framework Gin, visando ser uma referência prática em Continuos Integration.

### Funcionalidades Principais

* API em Go com Gin
* Integração com Banco de Dados Postgres
* Utilização de PGAdmin para administração do Banco
* Utilização de Docker para orquestração de containers

### Pré-requisitos
🔧 Antes de começar, você precisará:

* Ter o Go instalado na sua máquina
* Ter o Docker e o Docker Compose instalados

### Instruções de Instalação

#### Passo 1: Baixar o Repositório

```bash
git clone https://github.com/usuario/curso_ci_2.git
```

#### Passo 2: Criar um Ambiente de Desenvolvimento

```bash
cd curso_ci_2
docker-compose up -d
```

#### Passo 3: Instalar as Dependências

```bash
go mod download
```

### Instruções de Uso

1. Acessar a API: `http://localhost:8080`
2. Realizar requisição GET em `/users` para obter a lista de usuários
3. Realizar requisição POST em `/users` para criar um novo usuário

### Estrutura do Projeto

* `.github/`: Pastas relacionadas ao GitHub
* `assets/`: Arquivos estáticos
* `controllers/`: Camadas de lógica de negócio
* `database/`: Configurações do Banco de Dados
* `docker-compose.yml`: Arquivo de configuração do Docker Compose
* `go.mod`: Arquivo de dependências do Go
* `main.go`: Arquivo principal da aplicação
* `models/`: Definições das entidades do projeto
* `postgres-data/`: Armazenamento dos dados do Banco
* `routes/`: Definições das rotas da API
* `templates/`: Pastas de templates para resposta da API
* `teste.txt`: Arquivo de testes

### Licença

⚖️ Este projeto é distribuído sob a Licença MIT.