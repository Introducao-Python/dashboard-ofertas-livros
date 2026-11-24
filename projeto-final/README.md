# Filtros e ordenação: tuplas, sets, list comprehension e lambda

## Evolução do projeto
- Tuplas: sequências imutáveis, que podem ser chave de dicionário
- Desempacotamento: `menor, maior = calcular_faixa_precos(livros)`, e o `for titulo, favorito in favoritos.items()`
- `st.slider` com duas pontas, que devolve uma tupla `(minimo, maximo)`
- Sets: `set()`, `.add`, `in`, sem repetição e sem índice
- Operações de conjunto: `|` (união), `&` (interseção) e `-` (diferença)
- `sorted` × `.sort()`: `sorted` funciona com qualquer coleção e devolve uma lista **nova**
- List comprehension: `[expressão for item in coleção if condição]`, e quando **não** usar
- `sorted(livros, key=lambda livro: livro["preco"], reverse=True)` para ordenar dicionários