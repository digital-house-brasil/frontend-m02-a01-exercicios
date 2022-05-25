![](./hd-header.png)

## Front-End | Exercícios

<details>
  <summary>1. IF/ELSE</summary>

  - 1.1 Faça um programa para verificar se o número é par ou ímpar. O programa deve receber um número e imprimir o resultado `Par` ou `Impar`.
    > Numero par, são os números divisíveis por 2 que tem o resto 0.
  - 1.2 Faça um programa para verificar se o número é positivo ou negativo. O programa deve receber um número e imprimir o resultado `Positivo` ou `Negativo`.
    > Número positivo, são os números que são maiores que 0.
    > Número positivo, são os números que são maiores que 0.
  - 1.3 Faça um programa para verificar se o número é primo. O programa deve receber um número e imprimir o resultado `Primo` ou `Não primo`.
    > Número primo, são os números que são divisíveis por 1 e por ele mesmo.   
  - 1.4 Faça um programa programa para verificar se um triângulo é equilátero, isósceles ou escaleno. O programa deve ler os valores dos três lados e escrever o nome do tipo de triângulo correspondente.
    > Triângulo equilátero, são os triângulos que possuem todos os lados iguais.
    > Triângulo isósceles, são os triângulos que possuem dois lados iguais.
    > Triângulo escaleno, são os triângulos que possuem todos os lados diferentes. 
</details>

<details>

  <summary>2. Array + Objetos</summary>
  
  - 2.1 Faça um programa que receba um array de números e imprima o maior e o menor número. O programa deve receber um array de números e imprimir o maior e o menor número.
    > Exemplo:
    > Entrada: [1, 2, 3, 4, 5]
    > Saída:
    > Maior: 5
    > Menor: 1    
  - 2.2 Faça um programa que receba um array de números e ordene-o. O programa deve receber um array de números e ordená-lo.
    > Exemplo:
    > Entrada: [6, 2, 5, 100, 23, 1]
    > Saída:
    > [1, 2, 5, 6, 23, 100]
  - 2.3 Faça um programa que receba um array com nomes de alunos e verificar se o nome do aluno está na lista. 
    > Exemplo:
    > Entrada: ['João', 'Maria', 'José', 'Pedro']
    > Procurar por: 'Maria'
    > Saída:
    > Encontrado!
  - 2.4 Faça um programa que receba um array de objetos, contendo produtos de supermecado. Cada objeto deve ter as propriedades nome e preço. 
    > Exemplo:
    > Entrada: [{nome: 'Arroz', preço: 2.50}, {nome: 'Feijão', preço: 1.50}, {nome: 'Batata', preço: 0.50}]
    > Procurar por: 'Feijão'
    > Saída:
    > Encontrado!
  - 2.5 Com o array de objeto abaixo, faça o que se pede:
  ```js
  const listaDeCompras = [
    {nome:'Feijão', valor: 8.00},
    {nome:'Sabonete (pacote com 6)', valor: 14.00},
    {nome:'Arroz 5kg', valor: 22.50},
    {nome:'Farinha de trigo', valor: 6.99},
    {nome:'Chocolate', valor: 8.00},
  ];
  ```

  - 1 - Escreva um código que retorne somente os nomes dos itens da lista de compra como um array;
  - 2 - Escreva um código que retorne a soma de todos os valores da lista de compras;
  - 3 - Escreva um código que retone os nomes dos items como uma string separada por vírgulas;
  - 4 - Escreva um código que remova somente o último item da lista de compra;
  - 5 - Escreva um código que remova somente o primeiro da lista de compras;
  - 6 - Escreva um código que retorne somente os itens ordenados pelo nome de forma crescente;
  - 7 - Escreva um código que retorne somente os itens ordenados pelo valor de forma decrescente;
  - 8 - Escreva um código que adicione o objeto {nome:'Macarrão', valor: 5.50} na lista de compras;
  - 9 - Escreva um código que retone o item Feijão;
  - 10 - Escreva um código que retorne o valor dos itens da lista de compras adicionando R$;
 
</details>

<details>
  <summary>3. Funções</summary>
  
  - 3.1 Faça um função que receba um número e imprima o seu fatorial. O programa deve receber um número e imprimir o seu fatorial.
    > Exemplo:
    > Entrada: 5
    > Saída:
    > 5! = 120
  - 3.2 Faça um função que receba uma senha e verificar se a senha é segura. A senha é considerada segura se possuir pelo menos uma letra minúscula, uma letra maiúscula, um número e ter tamanho mínimo de 6 caracteres.   
    > Exemplo:
    > Entrada: abc123
    > Saída:
    > Senha segura  
  - 3.3 Faça um função que receba uma altura e peso de uma pessoa e calcule seu IMC. O programa deve receber uma altura e peso e imprimir o seu IMC e sua classificação. As classificações são:
    > - Abaixo do peso: Abaixo do peso (IMC abaixo de 18,5)
    > - Peso normal: Peso normal (IMC entre 18,5 e 24,9)
    > - Sobrepeso: Sobrepeso (IMC entre 25 e 29,9)
    > - Obesidade grau I: Obesidade grau I (IMC entre 30 e 34,9)
    > - Obesidade grau II: Obesidade grau II (IMC entre 35 e 39,9)
    > - Obesidade grau III: Obesidade grau III (IMC acima de 40)
    > Exemplo:
    > Entrada: 1.75 e 80
    > Saída:
    > Seu IMC é: 24.5
    > Você está com peso normal.
</details>


<details>
  <summary>4. Maratona de programação</summary>

  ### Derrapagem na frenagem
  > O Tesla Model X é um carro autônomo que consegue dirigir sozinho. Para evitar acidentes, o carro deve ser capaz de calcular qual a distância que ele percorrerá, ao iniciar o processo de frenagem, até parar.

  >Você acabou de ser contratado(a) como desenvolver(a) de software na Tesla. Sua primeira tarefa é fazer um programa capaz de calcular essa distância. A fórmula para o cálculo é a seguinte:

  > $$distancia = \frac{- velocidade^2}{2*aceleracao}$$

  > Seu programa sempre receberá como entrada a a velocidade e a aceleração e deverá imprimir na tela a distância percorrida pelo carro até parar.

  > Você acabou de ser contratado(a) como desenvolver(a) de software na Tesla. Sua primeira tarefa é fazer um programa capaz de calcular essa distância. A fórmula para o cálculo é a seguinte:

  > Seu programa sempre receberá como entrada a a velocidade e a aceleração e deverá imprimir na tela a distância percorrida pelo carro até parar.

  > `input`
  > A entrada será sempre composta por dois números inteiros:  a velocidade e a aceleração.

  > output
  > A saída deverá ser sempre um número representando a distância percorrida pelo carro ao longo da frenagem.

  > Exemplo de entrada:
  > Sample Input 

  ```20 -2```

  > Sample Output 

  ```100.0```
  ### Caçadores de Bugs
  > Você foi convidado por um amigo a resolver um problema de um programa que ele não consegue entender o que está dando errado. Esse programa calcula a distancia entre dois pontos num plano e exibe uma classificação. Encontre os problemas para que o programa volte a funcionar, exibindo a resposta correta.

  > input
  > Dois pontos no plano (x1, y1), (x2, y2)

  > output
  > `Longe` ou `Perto`

  > Exemplo de entrada:
  > Sample Input 
  
  ```1 1 2 3```

  > Sample Output 

  ```Perto```
  ### Cálculo da Parcela
  > Um novo banco abriu em seu estado e liberou a fórmula que ele utiliza para calcular o valor da parcela de um tipo de empréstimo.

  > A fórmula precisa de 3 dados, o valor do empréstimo, seu score no Serasa e em quantos meses a pessoa pretende pagar.

  > $$ parcela = \frac{valorEmprestimo + (valorEmprestimo * juros)}{mesesParaPagar} $$

  > Existem 3 faixas de juros que as pessoas se encaixam dependendo de seu score no Serasa:
  > - 1ª faixa (Score menor que 300), juros = 3%;<br/>
  > - 2ª faixa (Score menor que 700), juros = 9%;<br/>
  > - 3ª faixa (Score maior ou igual a 700), juros = 15%;<br/>

  > Um amigo seu viu isso como uma forma de empreender e decidiu criar um aplicativo que calcula o valor da parcela. Para fazer isso ele pediu a sua ajuda.

  > Seu programa receberá sempre como entrada os ganhos da pessoa, seu score no Serasa e em quantos meses a pessoa pagará e deverá imprimir na tela o valor da parcela.

  > input A entrada será sempre três números: 
  > - os ganhos da pessoa
  > - seu score no Serasa
  > - em quantos meses a pessoa pagará.

  > output
  > A saída deverá ser sempre um número representando o valor da parcela.

  > Exemplo de entrada:
  > Sample Input 

  ```5000 80 10```

  > Sample Output 

  ```515.0```
  ### Calculadora Simples
  > Você deverá construir uma calculadora simples, que ao receber dois números e um operador, exibe o resultado da operação.
  > Dica: para converter uma `String` para `double`, utilize `double.parse()`.

  > input:
  > Duas variáveis `double` e um operador `String`

  > constraints:
  > 1. Operadores possíveis: `+`, `-`, `*`, `/`, onde o operador `+` é o `default`.
  > 2. Não exibir `0`s desnecessários, por exemplo, se o resultado da operação for `2`, não exibir `2.00000`, mas sim `2`.

  > output:
  > Um número com no máximo 5 casas decimais. 

  > Exemplo de entrada:
  > Sample Input 

  ```2.2 + 4.6```

  > Sample Output 

  ```6.8```
</details>

###### tags: `Frontend` `nodeJS` `JavaScript` `variaveis` `condicional` `operadores` `loop`