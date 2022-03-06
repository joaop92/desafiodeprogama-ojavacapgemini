
Todos os códigos foram desenvolvidos com Java e Maven, dessa forma sendo possível utilizar os testes unitários para funções.

Foram executados como funções criadas com os exemplos passados ​​do desafio, sendo realizados através de testes unitários apresentados no arquivo: src/test/java/com/gIssamu/QuestionTest.java

Requisitos:
Java na sua versão 11 ou superiores.
Maven na versão 3.6.3
Questão 1
Código localizado na pasta:

src/main/java/com/gIssamu/question1

Para esta, deveríamos desenvolver um empreendimento que encontramos uma lista com números de primeira quantidade igual.

Foi criada uma turmaMedian contendo o código para realizar essa verificação.

E também uma classe Question1contendo uma classe main para ser possível rodar o ćodigo.

Inicialmente pede-se a quantidade de valores que vão estar presentes na lista que o usuário deve informar ao programa, informando um valor Integer e apertando enter para ir para a póxima parte. Logo em seguida irá pedir os valores da lista, que não precisa estar em ordem, para procurar a mediana.

E este programa apresentará como resposta o valor, dentre os que foram informados, qual será o valor da mediana.

Um exemplo:
Para a lista:

n = [9, 2, 1, 4, 6]
O resultado da execução do programa será:

4
Já que o número 4 é a mediana da lista nregistrada depois de ser realizada uma ordenação nos valores dessa lista.

Para rodar esta questão:
Para ver o código funcionando deve-se usar um terminal e na pasta raiz do projeto rodar:

$ mvn exec:java -Dexec.mainClass=com.gIssamu.question1.Question1
Em que dessa descida, o Maven irá como condições óbvias para rodar o projeto e logo logo em seguida para iniciar a execução do programa.

Questão 2
Código localizado na pasta:

src/main/java/com/gIssamu/question2

Para esta segunda questão, deveríamos desenvolver um conjunto de todo um conjunto de inteiros ne um conjunto qualquer encontrou xuma quantidade de elementos do que tem uma diferença igual ao valor x.

Foi criada uma classe Countercontendo o código para realizar essa contagem de pares.

E também uma classe Question2contendo uma classe main para ser possível rodar o ćodigo.

Inicialmente pede-se a quantidade de valores que vão estar presentes na lista que o usuário deve informar ao programa, informando um valor Integer e apertando enter para ir para a póxima parte. Logo em seguida irá pedir os valores do array. E depois o valor dessa diferença.

E este programa apresentará como responsável uma quantidade de pares inteiros no vetor com pessuem a diferença entre os valores escolhidos.

Exemplo:
Para a lista:

n = [1, 5, 3, 4, 2]
A diferença:

2
O resultado da execução do programa será:

3
Como resultado foram possíveis encontrar 3 pares de inteiros no vetor com uma diferença de 2: [5, 3], [4, 2] e [3, 1].

Para rodar esta questão:
Assim como na questão 1, rodar no terminal da pasta raiz do projeto:

$ mvn exec:java -Dexec.mainClass=com.gIssamu.question2.Question2
Em que dessa descida, o Maven irá como condições óbvias para rodar o projeto e logo logo em seguida para iniciar a execução do programa.

Questão 2
Código localizado na pasta:

src/main/java/com/gIssamu/question3

Para esta terceira questão, devemos desenvolver um que dê uma string realizando uma criptografia nessa string.

Essa encriptação foi realizada primeiro removendo possíveis espaços que podem existir na string, e logo após os caracteres escritos na forma de uma grade qual a quantidade de linhas são seguidas sem essa regra:

a raíz da quantidade de caracteres

E essa grade formada o resultado é obtido de acordo com a organização de caracteres cada coluna na coluna nessa grade se torne uma palavra.

Foi criada uma classe Encryptorcontendo o código para realizar essa criptografia.

E também uma classe Question3contendo uma classe main para ser possível rodar o ćodigo.

A execução do programa ele pedirá uma string que irá ser criptografada.

E apresentará como responsta uma string já criptografada.

Exemplo:
Uma linha:

s = ola mundo
Removendo o espaço presente nessa string, ela possui:8 caracteres

Dessa forma, sua grade ficará fixa com tamanho de 3 linhas e 3 colunas, já que a raiz de 8 está entre 2 e 3, na forma:

ola 
mun
do 
Em seguida, o programa combinará essa grade em apenas uma string, fazendo com que cada coluna dessa grade se torne uma palavra, apresentando dessa forma como resultado:

omd luo an
E está seria uma string criptografada.

Para rodar esta questão:
Da forma que as demais questões, rodar no terminal:

$ mvn exec:java -Dexec.mainClass=com.gIssamu.question3.Question3
Em que dessa descida, o Maven irá como condições óbvias para rodar o projeto e logo logo em seguida para iniciar a execução do programa.
