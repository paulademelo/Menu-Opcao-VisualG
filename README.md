# visualg
Criando comandos de verificação no VisualG (par/impar, positivo/negativo ou calcular a raiz quadrada)
Algoritmo "Verificação Caso2"

Var
   op, n1, numero : inteiro
   n2, raiz :real

Inicio
   escreval("Escolha as opções:")
   escreval("1 - Par / Impar")
   escreval("2 - Positivo / Negativo")
   escreval("3 - Raiz Quadrada")
   escreval("4 - Sair")
   leia(op)

   escolha op
   caso 1
      escreval("Par / Impar")
      escreval("Digite o número")
      leia(n1)

      se(n1 mod 2 = 0) entao
         escreval("Número par")
      senao
         escreval("Número ímpar")
      fimse

   caso 2
      escreval("Positivo / Negativo")
      escreval("Digite o número")
      leia(n2)

      se(n2 < 0) entao
         escreval("Número negativo")
      senao
         escreval("Número positivo")
      fimse

   caso 3
      escreval("Raíz Quadrada")
      escreval("Digite o número")
      leia(numero)
      raiz := raizq(numero)
      escreval("Resultado da raíz = ", raiz)

   caso 4
        escreval("Obrigado por usar nosso app! :)")
   fimescolha



Fimalgoritmo
