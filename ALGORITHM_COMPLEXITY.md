Como analisar a complexidade de um algoritmo?

- Tipos de casos
  - Melhor caso: cenário onde o dado buscado é encontrado no inicio da iteração.
  - Pior caso: cenário onde o dado buscado é encontrado no final da iteração.
  - Médio caso: cenário onde o dado buscado é encontrado no meio da iteração.

Para analisar um algoritmo, o foco tem que ser em base do pior cenário possivel, pois ali saberemos o que precisamos para otimizar o pior caso.

[10, 5, 3, 6, 7, 9, 23, 15, 21]

- Melhor caso: 10
- Pior caso: 21
- Caso medio: 9

<br>
Big O (O Annotation):
Forma de representar a complexidade do algoritmo.

Alguns tempos de complexidade:

O(n):
Cenário de uso comum: Acesso a um elemento específico em uma array ou em um hash table.
<br>
O(log n):
Cenário de uso comum: Busca binária em uma árvore binária de busca.
<br>
O(n log n):
Cenário de uso comum: Algoritmos de ordenação eficientes, como o Merge Sort e o Quick Sort.
<br>
O(n²):
Cenário de uso comum: Algoritmos simples de ordenação, como o Bubble Sort ou o Selection Sort.
<br>
O(n³):
Cenário de uso comum: Algoritmos simples de multiplicação de matrizes.
<br>
O(2^n):
Cenário de uso comum: Cenários em que são testadas todas as possibilidades de combinações de elementos.
<br>
O(n!):
Cenário de uso comum: Cenários em que são testadas todas as permutações de elementos.