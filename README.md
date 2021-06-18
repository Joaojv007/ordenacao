## Ordenação

### bubble_sort --> Algoritmo de ordenação bolha
   O algoritmo de ordenação bolha (bubble sort) compara pares adjacentes de valores e "flutua" o maior valor (ou menor se for descrescente) para a posição correta (última). 
   O laço interno garante que todos os valores serão comparados e o maior valor da vez será selecionado. Enquanto o laço externo garante que o laço interno se repetirá e selecionará o valor (primeiro maior, segundo maior, terceiro maior, etc...) conforme quantidade de vezes necessária. 
   Obs: Após ser colocado na posição correta, o valor não precisa mais ser comparado. Mas mesmo que as comparações sigam de forma redundante nas próximas "passadas" pelo laço interno, o algoritmo conseguirá ordenar o vetor da mesma forma, embora execute passos desnecessários.

### insertion_sort --> Algoritmo de ordenação por inserção
   O algoritmo de ordenação por inserção (insertion sort) compara determinado valor (a partir da segunda posição) com todos os valores anteriores e troca se algum valor anterior for maior que o valor da posição comparada.
   O laço interno garante que todos os valores anteriores a posição definida (2 - n) serão comparados. Enquanto o laço externo garante que o laço interno se repetirá a quantidade de vezes necessárias para que todos os valores tomem suas respectivas posições.

### selection_sort --> Algoritmo de ordenação por seleção
   O algoritmo de ordenação por seleção (selection sort) percorre o vetor em busca do menor valor. Em seguida transfere-o para a posição esperada.
   O laço interno busca o menor valor, o laço externo posiciona-o conforme esperado e garante qu eo laço externo se repita a quantidade de vezes necessárias para buscar o próximo menor valor até que todos estejam ordenados.  

### quick_sort --> Algoritmo de ordenação por divisão e conquista 
   No metodo quick sort, um valor 'pivô' é escolhido como valor inicial para a ordenação (geralmente é escolhido o primeiro ou ultimo valor). A partir dele, os elementos são comparados entre si e irão trocar de lugar até 'alcançarem' o pivô, onde serão organizados acima (maior) ou abaixo (menor) do que ele. Após a primeira execução, vão existir duas  partições - os valores menores e os valores maiores do que o pivô (que estará na sua posição correta). Recursivamente, serão escolhidos novos pivôs em ambos os lados até que todos os valores estejam ordenados.
   
### Heapsort 
   É um método de ordenação cujo princípio de funcionamento é o mesmo utilizado para a ordenação por seleção. O heapsort utiliza uma estrutura de dados chamada heap binário para ordenar os elementos à medida que os insere na estrutura. Assim, ao final das inserções, os elementos podem ser sucessivamente removidos da raiz da heap, na ordem desejada.
   A heap pode ser representada como uma árvore (uma árvore binária com propriedades especiais) ou como um vetor. Para uma ordenação decrescente, deve ser construída uma heap mínima (o menor elemento fica na raiz). Para uma ordenação crescente, deve ser construído uma heap máxima (o maior elemento fica na raiz).
