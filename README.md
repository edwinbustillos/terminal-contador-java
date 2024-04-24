# DesafioControleFluxo
Este projeto é um simples contador que aceita dois parâmetros via terminal e imprime todos os números entre eles.

## Como usar
1. Compile o arquivo `Contador.java` com o comando `javac Contador.java`.
2. Execute o programa com o comando `java Contador`.

O programa irá solicitar que você insira dois números. O primeiro número deve ser menor que o segundo. Se o primeiro número for maior, o programa lançará uma exceção `ParametrosInvalidosException` e terminará.

## Exemplo
Se você inserir os números 12 e 30, o programa imprimirá todos os números de 12 a 30.

## Exceções
Se o primeiro número for maior que o segundo, o programa lançará uma exceção `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro".
