# 📦 API RESTful para Gerenciamento de Produtos

Este projeto é uma API construída com foco em um desafio técnico de back-end. Utilizando **Node.js**, **Express** e **MongoDB**, ela oferece um CRUD completo para cadastro e gerenciamento de produtos. Ideal para projetos de aprendizado, testes ou integração com front-ends.

---

## ✨ O que você pode fazer com essa API

- 🔄 Obter a lista de todos os produtos  
- 🔎 Consultar produto por **ID**  
- 🧭 Procurar produto por **nome**  
- ➕ Adicionar novos produtos  
- 🛠️ Atualizar dados de um produto existente  
- 🗑️ Deletar produtos por ID  

---

## 🧰 Stack e Ferramentas

- **JavaScript (Node.js)** — linguagem principal  
- **Express** — framework para construção da API  
- **MongoDB Atlas** — banco de dados NoSQL na nuvem  
- **Mongoose** — ODM para integração com o MongoDB  
- **Swagger UI** — documentação interativa dos endpoints  
- **Render** — opção de deploy automático (não obrigatório)  

---

## 📑 Exemplos de Requisição

```json
{
  "nome": "Camisa Dry Fit",
  "descricao": "Camisa confeccionada com malha Dry",
  "cor": "Preta",
  "peso": 0.5,
  "tipo": "Vestimenta",
  "preco": 86.99,
  "dataCadastro": "2025-06-16T18:00:00Z"
}
```

---

## 🌍 Endereço Base da API

- Produção: `https://apiprodutos-ubhc.onrender.com`

---

## 🧪 Como rodar localmente

1. Clone o repositório:
```bash
git clone https://github.com/LeonardoFSousa/api_produtos.git
cd api_produtos
```

2. Instale as dependências:
```bash
npm install
```

3. Configure o ambiente:
Crie um arquivo `.env` com o seguinte conteúdo:
```
MONGODB_URI=mongodb://localhost:27017/produtos
PORT=3000
```

4. Inicie a aplicação:
```bash
npm run dev
```

5. Acesse a documentação:
```
https://apiprodutos-ubhc.onrender.com/api-dcos
```
