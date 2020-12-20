## Condicionais, Operadores Relacionais e Operadores Lógicos.

&nbsp;

### Operadores relacionais:

* **Igual →** Testa a igualdade entre valores. 
<br>**Exemplo:**  (a `=` b)

* **Diferente →** Testa a diferença entre valores. 
<br>**Exemplo:**  (a `<>` b)

* **Maior →** Testa se valor **a** é maior que valor **b**. 
<br>**Exemplo:**  (a `>` b)

* **Menor →** Testa se valor **a** é menor que valor **b**. 
<br>**Exemplo:**  (a `<` b)

* **Maior ou Igual →** Testa se valor **a** é maior ou igual ao valor **b**. 
<br>**Exemplo:**  (a `>=` b)

* **Menor ou Igual →** Testa se valor **a** é menor ou igual ao valor **b**. 
<br>**Exemplo:**  (a `<=` b)

&nbsp;

### Operadores lógicos:

* **E →** Auxilia nas condicionais exigindo que os dois lados da expressão sejam verdadeiros. 
<br>**Exemplo:**  (nota > 7 `e` faltas < 10)

* **OU →** Auxilia nas condicionais exigindo que somente um dos lados da expressão seja verdadeiro.
<br>**Exemplo:**  (nota > 7 `ou` faltas < 10)

* **Não →** Testa se o valor é **_não_** **a**. 
<br>**Exemplo:**  (`não` a)

&nbsp;

### Condicionais:

* **Se, Se Senão, Se Senão Se  →** Estruturas Condicionais. 
<br>**Exemplo:**  
```
Algoritmo "Condicionais"
// Disciplina   : [Lógica de Programação]
// Professor   : Arthur Antunes Ferreira
// Descrição   : Três exemplos de estruturas condicionais
// Data atual  : 17/12/2020
Var
   // Seção de Declarações das variáveis
   notaUm : real
   notaDois : real
   media : real
   faltas : inteiro

Inicio
   // Seção de Comandos, procedimento, funções, operadores, etc...
   notaUm := 5
   notaDois := 3
   media := 0
   faltas := 2

   media := (notaUm + notaDois) / 2

   // Média >= 7 e faltas <= 10
   se (media >= 7) e (faltas <= 10 ) então
      escreval("Aprovado!")
   fimse


   // Média >= 7 e faltas <= 10 Aprovado
   se (media >= 7) e (faltas <= 10 ) então
      escreval("Aprovado!")
   senão
      escreval("Reprovado!")
   fimse


   // Média >= 7 e faltas <= 10 Aprovado
   // Média >= 5 e faltas <= 10 Em recuperação.
   se (media >= 7) e (faltas <= 10 ) então
      escreval("Aprovado!")
   senão
      se (media >= 5) e (faltas <= 10 )  entao
         escreval("Em recuperação!")
      senão
         escreval("Reprovado!")
      fimse
   fimse

Fimalgoritmo
```
