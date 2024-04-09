#include <stdio.h>

int main()
{
    printf("Hello World");

    return 0;
}



numero_mes = int(input("Digite um número inteiro entre 1 e 12: "))

if 1 <= numero_mes <= 12:

   # Lista com os nomes dos meses

   meses = [

       "Janeiro", "Fevereiro", "Março", "Abril",

       "Maio", "Junho", "Julho", "Agosto",

       "Setembro", "Outubro", "Novembro", "Dezembro"

   ]

   # Obtém o nome do mês correspondente ao número digitado

   nome_mes = meses[numero_mes - 1]

print("O mês correspondente ao número", numero_mes, "é", nome_mes)

else:

   # Exibe uma mensagem de erro para números fora do intervalo

   print("Não existe mês com este número.")
