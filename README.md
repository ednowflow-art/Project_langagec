#include <stdio.h>
int main(){
    int x, i,nbrdiv;
    do{
        printf("saisir une valeur positif");
        scanf("%d",&x);
    }while(x<0);
    nbrdiv=0;
    for(i=1;i<=x;i++){
        if(x%i==0){
            nbrdiv++;
        }
    }
 //(nbrdiv==2) ? printf("%d est nombre premier",x) :  printf("%d n est pas nombre premier",x);
    if(nbrdiv==2){
        printf("%d est nombre premier",x);
    }
    else{
        printf("%d n est pas nombre premier",x);
    }

    return 0;
}

