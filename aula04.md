## Comandos de Repetição: Para, Enquanto e Repita.

&nbsp;

### Comandos de Repetição:

* **Para...faça →**  O exemplo abaixo imprime números de 1 a 5, mas pode usar outros valores.
<br>**Exemplo:**  
```
   j : inteiro // Declarar variável controle do laço de repetição.

   para j de 1 até 10 faca
      escreva(j)
   fimpara
```

&nbsp;

* **Enquanto...faça  →**  O exemplo abaixo cria um laço que se repete até o usuário digitar 9.
<br>**Exemplo:**  
```
   opcao : inteiro // Declarar variável controle do laço de repetição.

   enquanto (opcao <> 9) faca
      leia(opcao)
   fimenquanto
```

&nbsp;

* **Repita...até  →**  Idem ao _Enquanto_. A diferença é que o teste para saber se a variável tem o valor 9 é no final do laço.
<br>**Exemplo:**  
```
   opcao : inteiro // Declarar variável controle do laço de repetição.

   repita
      leia(opcao)
   ate (opcao = 9)
```
