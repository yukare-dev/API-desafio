# API Livros Doados VnW

Essa é uma API simples feita com Flask e Sqlite para fins de estudo na escola Vai na Web, ela permite cadastrar e listar os livros doados.

## Como rodar o projeto?

1. Faça o clone do repositório:

```bash
git clone <LINK_DO_REPOSITÓRIO>
cd nome_do_projeto
```

2. Criar um ambiente virtual (Obrigatório):

**Windows**

```bash
python -m venv venv
source venv/Scripts/activate
```

**Linux/Mac**

```bash
python3 -m venv venv
source venv/bin/activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Inicie o servidor:

```bash
python app.py
```

> A API estará disponível em http://127.0.0.1:5000/

## Endpoints

### POST /doar

Endpoint para o cadastro das informações do livro doado.

**Envio (JSON)**

```json
{
  "titulo": "A hora da estrela",
  "categoria": "Romance",
  "autor": "Clarice Lispector",
  "image_url": "https://m.media-amazon.com/images/I/61TaHURu27L._AC_UF1000,1000_QL80_.jpg"
}
```
