Algoritmo "SalárioReajuste"

var
   n1, multi: real
   
inicio
   //Entrada de dados
   escreva("Digite seu salário: ")
   leia(n1)
   
   //Saída de dados
   se (n1 <= 300) entao
      multi <- n1 * 1.5
      escreva("SALARIO COM REAJUSTE = " , multi)
   senao
      multi <- n1 * 1.3
      escreva("SALARIO COM REAJUSTE = " , multi)
   fimse
fimalgoritmo
