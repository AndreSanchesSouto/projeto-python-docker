# FastAPI Hello API

Esta é uma API simples feita com [FastAPI](https://fastapi.tiangolo.com/) que responde com `"hello"` quando acessada via navegador ou requisição HTTP.

## 🚀 O que a aplicação faz?

A API possui uma única rota:

- `GET /` → retorna um JSON com `{"message": "hello"}`.

É ideal para fins de estudo ou como base para projetos maiores.

---

## 💻 Rodando localmente com ambiente virtual (recomendado)

### 1. Clone o repositório

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

### 2. Crie um ambiente virtual
python3 -m venv venv
source venv/bin/activate

### 3. Instale as dependencia
pip install fastapi uvicorn

### 4. Inicie a aplicação
uvicorn main:app --reload

### 5. Acesse a API
Abra no navegador: http://localhost:8000
Você verá uma resposta como:

{
  "message": "hello"
}
