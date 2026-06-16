# Personagens Bíblicos por Livro

Este repositorio contem um arquivo JSON com uma lista de personagens biblicos organizados por livro da Biblia.

O objetivo e facilitar consultas, estudos, filtros, buscas e uso em projetos como sites, aplicativos, APIs, estudos biblicos, jogos, quizzes ou ferramentas de referencia.

## Arquivo

- `personagens_biblicos_por_livro.json`

## Estrutura

O JSON possui dois blocos principais:

- `meta`: informacoes sobre idioma, escopo, observacoes e fontes consultadas.
- `livros`: objeto onde cada chave representa um livro da Biblia e o valor e uma lista de nomes mencionados nesse livro.

Exemplo simplificado:

```json
{
  "livros": {
    "Genesis": [
      "Adao",
      "Eva",
      "Caim",
      "Abel"
    ],
    "Mateus": [
      "Jesus",
      "Maria",
      "Jose",
      "Pedro"
    ]
  }
}
```

## Criterio

Cada personagem aparece dentro do livro em que e mencionado. Quando um personagem aparece em mais de um livro, ele tambem e repetido em cada um desses livros.

Por exemplo, um personagem citado em Mateus e Marcos aparece nas duas listas.

A lista prioriza pessoas e personagens biblicos. Nao foram incluidos lugares, rios, objetos, povos ou regioes como personagens.

## Observacoes

Os nomes biblicos podem variar conforme a traducao, tradicao religiosa e transliteracao adotada. Por isso, alguns nomes podem aparecer de forma diferente em outras versoes da Biblia.

Este arquivo foi preparado como uma base ampla e pratica para uso em projetos digitais, mas pode ser ajustado conforme a traducao biblica ou o canon desejado.

## Canon

A estrutura segue a Biblia canonica protestante com 66 livros.

## Possiveis usos

- Consulta de personagens por livro
- Estudos biblicos
- Geracao de quizzes
- Aplicativos devocionais
- APIs de dados biblicos
- Sistemas de busca e categorizacao

## Licenca

Use, adapte e distribua livremente conforme a necessidade do seu projeto.
