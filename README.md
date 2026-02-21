#include <stdio.h>
#include <stdlib.h>

int main()
{
    int choixdeMenu, prix;

    printf("Bienvenu a notre restaurant en ligne  \n");
    printf("=== ** Menu **======\n");
    printf("1. Royal chesse\n");
    printf("2. Mc Deluxe\n");
    printf("3. Mc Frits au poulet\n");
    printf("4. Shawarma\n");
    printf("5. Spaguetti avec viande\n");
    printf("6. Yaourt\n");
    do {
    printf("\n Votre choix ? : ");
    scanf("%d",&choixdeMenu);
    }while (choixdeMenu <0) ;

    switch (choixdeMenu){

    case 1: printf("vous avez choisir le royal chesse. Bon choix.\n prix : 2500f");
    break;

    case 2: printf("vous avez choisir le Mc Deluxe. Trop de Sauce, waouh! \n prix : 5000f");
    break;

    case 3: printf("vous avez choisir le Mc Frits au poulet. super! \n prix : 2500f");
    break;

    case 4: printf("vous avez choisir Shawarma. Bon appetit ! \n prix : 2000f");
    break;

    case 5: printf("vous avez choisir Spaguetti.  \n prix : 500f");
    break;

    case 6: printf("vous avez choisir le Yaourt. \n prix : 500f");
    break;


      default : printf( "vous n'avez pas rentrez un nombre correct.\n"
                       "vous ne mangerai rien du tout");
}
    return 0;
}

