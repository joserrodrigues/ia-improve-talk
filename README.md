# FIAP ML - Sistema de Gerenciamento de Livros

Sistema completo de gerenciamento de livros. O projeto permite coletar dados de livros, armazená-los em CSV e fornecer uma API para consulta e análise.


### Variáveis de Ambiente
Criar arquivo `.env` na raiz do projeto:

```env
DATABASE_PATH=mockdata/books.csv
PAGE_SIZE=10
```

### Pré-requisitos
- Python >= 3.12
- Poetry (gerenciador de dependências)
- Poe (task runner para pyproject - https://poethepoet.natn.io/index.html)

## 🚀 Instalação

### Instalação em Produção
```bash
poetry install
```

### Instalação em Desenvolvimento
```bash
poetry install -G dev
```

## 💻 Uso

### Iniciar em Desenvolvimento
```bash
poe servedev
```

### Executar Scraping
```bash
poe scrap
```

### Executar Aplicação
```bash
poe run
```

## 👥 Autores

- **Erick Muller** - erick@em.pro.br
- **José Rubens Rodrigues** - joserrodrigues@yahoo.com.br

## 🛠️ Tecnologias Utilizadas

- **FastAPI**: Framework web para API REST
- **DuckDB**: Banco de dados analítico
- **BeautifulSoup4**: Web scraping
- **Pandas**: Análise de dados
- **PyJWT**: Autenticação JWT
- **SQLAlchemy**: ORM
- **Poetry**: Gerenciamento de dependências
- **Python 3.12+**: Linguagem principal