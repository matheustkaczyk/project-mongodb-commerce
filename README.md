Projeto desenvolvido durante o curso de desenvolvimento de software na Trybe. O objetivo foi práticar métodos e operadores SQL mais complexos.

Data de entrega: 20/10/2021

# Habilidades
  * Utilizar o método `updateOne()` e `updateMany()`
  * Utilizar os operadores `$set`, `$mul`, `$inc`, `$min`, `$max` e `$currentDate`
  * Renomear campos e remover campos
  * Incorporar dados aos documentos através de arrays
  * Utilizar os operadores `$pop`, `$pull` e `$push`
  * Utilizar o operador `$addToSet`
  * Utilizar os operadores `$each`, `$slice` e `$sort`
  * Utilizar o operador `$all` para filtrar documentos
  * Utilizar o operador `$elemMatch` para filtrar documentos
  * Utilizar o operador `$size` para filtrar documentos pelo tamanho de arrays
  * Utilizar o operador `$expr` para criar expressões de agregação
  * Utilizar expressões regulares e o operador `$regex` para buscar documentos
  * Utilizar o índice textual e o operador `$text`
  * Utilizar o operador `$mod`

# Lista de requisitos

### 1 - Inclua o campo `criadoPor` em todos os documentos, colocando `"Ronald McDonald"` no valor desse campo.

### 2 - Inclua o campo `valorUnitario` em todos os documentos em que esse campo não existe e atribua a ele o valor `"0.00"`, com o tipo `NumberDecimal`.

### 3 - Adicione o campo `avaliacao` em todos os documentos da coleção e efetue alterações nesse campo.

### 4 - Atribua a data corrente ao campo `ultimaModificacao` no sanduíche `Big Mac`.

### 5 - Adicione `ketchup` aos `ingredientes` para todos os sanduíches menos o `McChicken`, garantindo que não haja duplicidade nos `ingredientes`.

### 6 - Inclua `bacon` no final da lista de `ingredientes` dos sanduíches `Big Mac` e `Quarteirão com Queijo`.

### 7 - Remova o item `cebola` de todos os sanduíches.

### 8 - Remova o **primeiro** `ingrediente` do sanduíche `Quarteirão com Queijo`.

### 9 - Remova o **último** `ingrediente` do sanduíche `Cheddar McMelt`.

### 10 - Adicione a quantidade de vendas dos sanduíches por dia da semana.

### 11 - Insira os elementos `combo` e `tasty` no _array_ `tags` de todos os sanduíches e aproveite para deixar os elementos em ordem alfabética ascendente.

### 12 - Ordene em todos os documentos os elementos do _array_ `valoresNutricionais` pelo campo `percentual` de forma descendente.

### 13 - Adicione o elemento `muito sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior ou igual a `40`.

### 14 - Adicione o elemento `contém sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior do que `20` e menor do que `40`.

### 15 - Conte quantos produtos contêm `Mc` no nome, sem considerar letras maiúsculas ou minúsculas.

### 16 - Conte quantos produtos têm `4` ingredientes.

### 17 - Conte quantos documentos contêm as palavras `frango` ou `hamburguer` utilizando o operador `$text`.

### 18 - Conte quantos documentos contêm a **expressão** `feito com` utilizando o operador `$text`.

### 19 - Renomeie o campo `descricao` para `descricaoSite` em todos os documentos.

### 20 - Remova o campo `curtidas` do item `Big Mac`.

### 21 - Retorne o `nome` dos sanduíches em que o número de `curtidas` é maior que o número de sanduíches `vendidos`.

### 22 - Retorne o `nome` e a quantidade de vendas (`vendidos`) dos sanduíches em que o número de vendas é múltiplo de `5`.
