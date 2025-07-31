# 📡 Projeto Java - Consumo de APIs Públicas

## 🔖 Sobre o projeto  
Este projeto foi desenvolvido como exercício de prática com **consumo de APIs REST** em Java. Ele simula um sistema de busca que se conecta a diferentes APIs públicas para consultar:

- 📚 Informações sobre livros via [Google Books API](https://developers.google.com/books)
- 🥘 Receitas culinárias via [TheMealDB API](https://www.themealdb.com/)
- 💰 Preços de criptomoedas via [CoinGecko API](https://www.coingecko.com/)

A aplicação foi construída com foco em lógica de programação, manipulação de strings, tratamento de requisições HTTP e integração com APIs externas usando Java moderno.

---

## 🎯 Funcionalidades

✔️ Permite ao usuário:
- Buscar **livros** por nome/título e retornar resultados da Google Books API.  
- Buscar **receitas** por nome e visualizar os dados da TheMealDB API.  
- Consultar o **preço atual de criptomoedas** com base na CoinGecko API.

---

## 🧠 Técnicas e conceitos utilizados

✅ Manipulação de APIs REST com `java.net.http.HttpClient`  
✅ Requisições GET com `HttpRequest` e `HttpResponse`  
✅ Leitura de entrada do usuário com `Scanner`  
✅ Manipulação de strings e URIs  
✅ Estrutura de projeto modular com pacotes: `BookApi`, `ReceitaAPI`, `CriptoAPI`  
✅ Leitura e exibição direta de dados em formato JSON

---

## 🚀 Tecnologias e ferramentas

- Java 17+
- IntelliJ IDEA
- Git e GitHub
- APIs REST públicas (Google Books, CoinGecko, TheMealDB)

---

## 📂 Organização do Projeto

```
src/
├── BookApi/
│   └── BuscaLivros.java
├── ReceitaAPI/
│   └── BuscaReceita.java
└── CriptoAPI/
    └── BuscaCripto.java
```

# 🔐 Observações sobre chaves de API

A Google Books API pode exigir uma chave (`key=SUACHAVE`).  
Certifique-se de armazenar essa chave com segurança e **nunca versioná-la em repositórios públicos no GitHub**.

Para isso, utilize um `.gitignore` adequado e **variáveis de ambiente** ou arquivos `.env` no futuro.

---

✍️ **Autor**  
Vinícius Alves Dias

Projeto desenvolvido com fins educacionais para a Alura.
