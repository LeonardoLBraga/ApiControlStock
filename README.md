# 📦 ApiControlStock

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

API desenvolvida em Go para controle de estoque de produtos. O objetivo é fornecer endpoints que permitam cadastrar, listar, atualizar e excluir produtos de um estoque de forma eficiente e escalável.

## 🚀 Tecnologias Utilizadas

- [Go](https://golang.org/)
- `net/http` para rotas e requisições

## 📁 Estrutura do Projeto

```
ApiControlStock/
├── go.mod         # Arquivo de definição do módulo
├── go.sum         # Dependências do projeto
├── main.go        # Arquivo principal da aplicação
```

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/LeonardoLBraga/ApiControlStock.git
   cd ApiControlStock
   ```

2. Execute a aplicação:
   ```bash
   go run main.go
   ```

3. A API estará disponível em `http://localhost:8080` (ou porta configurada no código).

## 📌 Funcionalidades Esperadas (Controle de Estoque)

- ✅ Cadastro de produtos
- ✅ Listagem de todos os produtos
- ✅ Atualização de produtos
- ✅ Remoção de produtos
- 🚧 (Opcional) Consulta por ID, nome ou categoria

## 📈 Sugestões de Melhorias

- 🔒 **Adicionar autenticação JWT** para proteger endpoints
- 🗃️ **Persistência em banco de dados**, como PostgreSQL ou SQLite
- 📦 **Criação de camadas separadas** (controller, service, repository) para seguir boas práticas
- 🧪 **Implementar testes unitários e de integração**
- 📄 **Documentação com Swagger/OpenAPI**
- 🚀 **Deploy via Docker**

## 👨‍💻 Autor

Desenvolvido por [Leonardo Lourenço Braga](https://github.com/LeonardoLBraga)

---

> ⚠️ Projeto ainda em fase inicial.
