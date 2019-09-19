# PIMPROJET
#include <conio.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <locale.h>

int main(void)
{
char login[15]= "admin";
char login1[15];
char senha[15]= "admin";
char senha1[15];
int escolha;
int voltar = 0;

    printf("================================================================================\n");
    printf("<================================= SISTEMA ====================================>\n");
    printf("================================================================================\n");
    printf("________________________________________________________________________________\n");

      printf("  USUARIO: ");
      scanf("%s",login1);
      printf("   SENHA: ");
      scanf("%s",senha1);
        if(strcmp(login1,senha1)== 0)
         {
            printf("   CARREGANDO....");
            sleep(1);
            printf("\nACESSO AUTORIZADO ");
            sleep(1);
            system("cls");

              while(voltar== -7){

              printf("================================================================================\n");
              printf("<====================================MENU=======================================>\n");
              printf("================================================================================\n");
              printf("\n________________________________________________________________________________\n");
              printf("  ( 1 )                    GERENCIAMENTO DE CARDÁPIO\n");
              printf("  ( 2 )                    SISTEMA DE CONTROLE DO ESTOQUE\n");
              printf("  ( 3 )                    GESTÃO DE PEDIDOS\n");
              printf("  ( 4 )                    RELATORIO DIARIOS\n");
              printf("  ( 5 )                    SISTEMA DE SUGESTÃO\n");
              printf("  ( 6 )                    SISTEMA DE CONTROLE DE CLIENTES\n");
              printf("                                ( 0 ) VOLTAR                                    \n");
              scanf("%d",& escolha);
              system("cls");

            switch(escolha)
            {
                case 1:
                system("cls");
                printf("GERENCIAMENTO DE CARDÁPIO\n");
                break;

                case 2:
                system("cls");
                printf("SISTEMA DE CONTROLE DO ESTOQUE\n");
                break;

                case 3:
                system("cls");
                printf("GESTÃO DE PEDIDOS\n");
                break;

                case 4:
                system("cls");
                printf("RELATORIO DIARIOS\n");
                break;

                case 5:
                system("cls");
                printf("SISTEMA DE SUGESTÃO\n");
                break;

                case 6:
                system("cls");
                printf("SISTEMA DE CONTROLE DE CLIENTES\n");
                break;

            }

        }

        }

        else
         {
            printf("ACESSO NEGADO");
}
    return 0;
}
