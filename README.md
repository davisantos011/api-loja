# API Loja

## API desenvolvida para gerenciamento de empreendimento lojistico. 

### 🛠️ Como executar: 

```bash
git clone https://github.com/seu-usuario/api-loja.git

cd api-loja

npm install

npm run dev
```

### ↪️ Endpoints: 

| Método | URL | Descrição |
|--------|-----|-----------|
| GET | /produtos | Lista todos os produtos |
| GET | /produtos/:id | Busca um produto pelo ID |
| POST | /produtos | Cadastra um novo produto |
| PUT | /produtos/:id | Atualiza um produto |
| DELETE | /produtos/:id | Remove um produto |
| GET | /produtos/cadastrar | Exibe o formulário de cadastro |

### 🤖 Tecnologias usadas:

- TypeScript
- Express
- EJS
- HTML
- CSS
- JSON
- ts-node-dev

### 📁Estrutura de pastas:

```bash
src/
 ├── controllers/
 ├── routes/
 ├── models/
 ├── views/
 ├── public/
 │    ├── css/
 │    ├── js/
 │    └── img/
 ├── dados/
 ├── app.ts
 └── server.ts
```

### ✍🏼 Autor: 
- Nome: Davi Silva
- Turma: 2°A 
- Instituição: Senac 
- Curso: Técnico em TI
