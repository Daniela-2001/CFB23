O 1° método é o BinarySearch – tem o retorno inteiro e vai me retornar a posição do elemento procurado. 
Chamo ele direto da classe array. 
Preciso passar o array de pesquisa e o valor que estou pesquisando. 
Ele me retorna um inteiro que é relacionado à posição desse elemento. Caso o valor que estou procurando não esteja no nosso array, ele vai retornar -1. 
Retorno -1 indica que o elemento não está no nosso array.
O 2° método, o método Copy, faz a cópia dos elementos de uma array para outro. 
Ele é chamado também a partir da classe array e o retorno dele é void. Eu preciso passar o array de origem, o array de destino e a quantidade de elementos que eu quero copiar. 
Usei o foreach para poder imprimir os elementos copiados. 
O CopyTo não é a partir da classe array, é a partir do vetor. 
Ele é um método que será chamado a partir do vetor de origem e eu preciso passar como parâmetro vetor de destino e a partir de qual posição eu quero realizar a cópia, ou seja, todos os elementos do vetor 1 serão copiados no vetor 3.
O 3° método é o GetLowerBound, vai me retornar o menor índice desse array ou matriz. 
O dimensão vai influenciar se é uma matriz ou uma array. 
Se for uma array é só dimensão então sempre vai ser dimensão 0(zero). 
Se for uma matriz eu vou indicar qual dimensão eu quero obter o menor índice. 
O 4° método é o GetUpperBound que me retorna o maior índice. 
O 5° método é o GetValue, vai me retornar o valor a partir de um índice. 
O 6° método é o IndexOf, que irá me retornar o índice do valor que eu indicar no segundo parâmetro. Irá me retornar a posição do primeiro valor encontrado. 
O 7° método, LastIndexOf, retornará a posição do último numeral 5 que ele encontrar.
O 8° método, Reverse, inverte a ordem dos elementos. Por exemplo, 12345 vai ficar 54321.
O 9° método, SetValue, permite a gente setar, ou seja, definir o valor em uma posição do nosso vetor. 
O 10° método e último método é o Sort, vamos utilizar sempre que quisermos ordernar em ordem crescente os elementos do nosso array. 
Ele é chamado a partir da classe array e ele recebe o array que ele quer ordenar como parâmetro. 

