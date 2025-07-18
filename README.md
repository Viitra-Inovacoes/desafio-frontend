# Desafio Técnico Presencial – Desenvolvedor(a) Frontend (Estágio)

## Objetivo

Desenvolver uma aplicação React que consuma a [Fake Store API](https://fakestoreapi.com/) e exiba um catálogo de produtos com a funcionalidade de adicionar ao carrinho.

Este desafio tem como objetivo avaliar seu domínio dos fundamentos do React, organização de projeto, escrita de código, consumo de APIs REST e construção de interface com foco funcional.

---

## Requisitos

### Funcionalidades obrigatórias

* Listar produtos da API em cards com as seguintes informações:

  * Imagem do produto
  * Nome
  * Preço
  * Botão para adicionar ao carrinho
* Exibir o número de itens no carrinho e o total de valor no cabeçalho
* O estado do carrinho deve ser mantido na aplicação enquanto ela estiver aberta

### Funcionalidades bônus (não obrigatórias)

Cada funcionalidade bônus implementada aumenta a nota final em:

* **Remover itens do carrinho** → +1 ponto
* **Exibir detalhes do produto em um modal** → +1 ponto
* **Persistência do carrinho no localStorage** → +3 pontos

---

## Avaliação

Os candidatos serão avaliados com base nos seguintes critérios:

| Critério                                    | Peso | Descrição                                                                            |
| ------------------------------------------- | ---- | ------------------------------------------------------------------------------------ |
| **Projeto funcional**                       | 4    | A aplicação funciona corretamente, sem erros, e cobre o fluxo proposto               |
| **Legibilidade e escrita de código**        | 4    | Código limpo, organizado, sem duplicações, com nomes claros e coerentes              |
| **Uso correto dos hooks**                   | 3    | Uso adequado de `useState`, `useEffect`, `useMemo` e outros hooks básicos            |
| **Arquitetura do projeto**                  | 3    | Organização das pastas, separação de responsabilidades, componentes bem estruturados |
| **Tratamento de erros e feedbacks visuais** | 2    | Lida com estados de erro, loading e estados vazios de forma clara                    |
| **Responsividade e design**                 | 1    | Layout visual simples, responsivo e funcional                                        |

Além disso, funcionalidades bônus adicionam até **5 pontos extras** à nota final.

---

## API

Você deverá utilizar a [Fake Store API](https://fakestoreapi.com/products) para obter a lista de produtos.

### Exemplo de requisição

```
GET https://fakestoreapi.com/products
```

### Exemplo de resposta

```json
[
  {
    "id": 1,
    "title": "Fjallraven - Foldsack No. 1 Backpack",
    "price": 109.95,
    "description": "Your perfect pack for everyday use and walks in the forest...",
    "category": "men's clothing",
    "image": "https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg"
  }
]
```

---

## Instruções finais

* Você deve clonar o seguinte repositório antes de começar o desenvolvimento:
  [https://github.com/Viitra-Inovacoes/desafio-frontend](https://github.com/Viitra-Inovacoes/desafio-frontend)
* Ao final do desafio, você deverá abrir um **Pull Request (PR)** com sua solução para esse repositório.
* A demonstração do projeto será feita localmente (não é necessário fazer deploy).
* Durante o desafio, será permitido fazer perguntas e pedir esclarecimentos.
* Você é **livre para pesquisar e utilizar a internet**, incluindo documentação oficial e fóruns de desenvolvedores.
