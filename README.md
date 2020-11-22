## Treinamento Digital Innovation One - Exercicio - Multiplicação Simples

O exercicio publicado é referente ao treinamento do BOOTCAMP - Desenvolvedor NodeJS - Introdução a Programação Com Java Script 
(https://digitalinnovation.one)

#### Descrição do Desafio:

Você receberá dois valores inteiros. Faça a leitura e em seguida calcule o produto entre estes dois valores. Atribua esta operação à variável PROD, mostrando esta de acordo com a mensagem de saída esperada (exemplo abaixo).


#### Entrada: 

A entrada contém 2 valores inteiros.


#### Saída: 

Exiba a variável PROD conforme exemplo abaixo, tendo obrigatoriamente um espaço em branco antes e depois da igualdade.

Exemplos de Entrada  | Exemplos de Saída
------------- | -------------
3 | PROD = 27
9 | 

Exemplos de Entrada  | Exemplos de Saída
------------- | -------------
-30 | PROD = -300
10 | 

Exemplos de Entrada  | Exemplos de Saída
------------- | -------------
0  | PROD = 0
9  |  



#### Javascript　

```javascript
//Solução 1
var valor1 = gets(); //leitura da primeira entrada e armazena na variavel
var valor2 = gets(); //leitura da segunda entrada entrada e armazena na variavel
var total = valor1 * valor2; //realiza o calculo e armazena na variavel
console.log("PROD = " + total); //mostra o total no console

//Solução 2 - Resumido
var total = gets() * gets(); //faz a leitura das duas entradas, calcula e armazena na variavel
console.log("PROD = " + total); //mostra o total no console

//Solução 3 - Resumido 
console.log("PROD = " + (gets() * gets())); //faz a leitura das duas entradas, calcula e mostra o total no console
```

