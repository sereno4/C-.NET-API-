# C-.NET-API-
Esta API foi criada para treinamento e demonstração de conceitos de: - **RESTful API** com .NET 10 - **CRUD completo** de produtos - **Gestão de vendas** com validação de estoque - **Swagger/OpenAPI** para documentação interativa - **Docker** para containerização

Set-Content -Path "C:\Users\seren\OneDrive\Documentos\Novo projeto DIO\MinhaApi\README.md" -Value '# 🚀 API de Produtos e Vendas

API RESTful desenvolvida em .NET 10 para gerenciamento de produtos e vendas.

## 📋 Descrição

Esta API foi criada para treinamento e demonstração de conceitos de:
- **RESTful API** com .NET 10
- **CRUD completo** de produtos
- **Gestão de vendas** com validação de estoque
- **Swagger/OpenAPI** para documentação interativa
- **Docker** para containerização

## ✨ Funcionalidades

### Produtos
- ✅ Listar todos os produtos
- ✅ Buscar produto por ID
- ✅ Criar novo produto
- ✅ Atualizar produto existente
- ✅ Deletar produto (soft delete)

### Vendas
- ✅ Listar todas as vendas
- ✅ Buscar venda por ID
- ✅ Criar nova venda com múltiplos itens
- ✅ Validação automática de estoque
- ✅ Atualização automática de estoque após venda

## 🛠️ Tecnologias Utilizadas

- **.NET 10** - Framework principal
- **C#** - Linguagem de programação
- **Swagger/OpenAPI** - Documentação interativa
- **Docker** - Containerização

## 📦 Pré-requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Docker Desktop](https://www.docker.com/products/docker-desktop) (opcional)

## 🚀 Como Executar

### Opção 1: Local (sem Docker)

```bash
# Navegar até a pasta do projeto
cd "C:\Users\seren\OneDrive\Documentos\Novo projeto DIO\MinhaApi"

# Restaurar dependências
dotnet restore

# Executar a API


dotnet run

