## Comando de Seleção - Escolha.

&nbsp;

### Comando de Seleção:

* **Escolha →**  O comando escolha permite várias opções e uma "default", caso não se enquadre nas demais.
<br>**Exemplo:**  
```
Algoritmo "Escolha"
// Disciplina   : [Lógica de Programação]
// Professor   : Arthur Antunes Ferreira
// Descrição   : Exemplo do comando Escolha.
// Data atual  : 17/12/2020
Var
   // Seção de Declarações das variáveis
   letra : caractere
Inicio

   escreval("Escolha uma letra: ")
   leia(letra)

   escolha letra
   caso "A"
      escreval("Letra A")
   caso "B"
      escreval("Letra B")
   outrocaso
      escreval("Nem A, nem B, Outra letra")
   fimescolha

Fimalgoritmo
```

&nbsp;
