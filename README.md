# BruteForceSearchAlgorithm
## Autores: Luís Filipe Loureiro e Murilo Lima

O algoritmo de força exaustiva é baseado na ideia de geração de todas as subsequências possíveis a partir das entradas SeqA e SeqB.

As substrings são então armazenadas em uma lista. Em seguida, é realizado a comparação e o cálculo do score entre apenas **as subsequências de mesmo tamanho**.

Assim, tendo todas as comparações e os respectivos *scores*, seleciona-se o *score* máximo e suas respectivas entradas. Ou seja, aquelas com maior grau de similaridade.

Importante ressaltar que, seguindo a rubrica e a proposta de criação do algoritmo, uma segunda possibilidade seria também realizar o cálculo do score para aquelas sequências de tamanho diferentes. Para tanto, bastaria utilizar o algoritmo Smith Waterman. Entretanto, foi escolhido outro caminho, pois tal proposta aumentaria consideravelmente o tempo de execução do algoritmo. 

Por fim, o alinhamento foi baseado os seguintes valores para comparação:

 | Comparação  |Resultado |
| ------------- | ------------- |
| iguais  | 2 |
| diferentes  | -1  |
