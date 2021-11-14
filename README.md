## Exercicio: Multiplicação Simples

O exercicio publicado é referente ao treinamento do BOOTCAMP - Desenvolvedor NodeJS - Introdução a Programação Com Java Script 
[https://digitalinnovation.one](https://digitalinnovation.one)


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


#### Update:
06-03-2021 - Utilizando variaveis constantes (const) e ajustado nomenclatura das constantes (Uso de conceitos CleanCode)


#### Javascript　

```javascript
//SOLUCAO 1
/* Utilizando variaveis constantes (const) 
e ajustado nomenclatura das constantes (Uso de conceitos CleanCode) */ 
const valorUm = gets();
const valorDois = gets();
const totalDaMultiplicacao = valorUm * valorDois;
console.log("PROD = " + totalDaMultiplicacao);

//SOLUCAO 2
var valor1 = gets();
var valor2 = gets();
console.log("PROD = " + (valor1 * valor2));


//SOLUCAO 3 - Resumido
var total = gets() * gets();
console.log("PROD = " + total);

//SOLUCAO 4 - Resumido 
/*Faz a leitura das duas entradas (gets()), calcula e mostra o total no console.*/
console.log("PROD = " + (gets() * gets()));
```

