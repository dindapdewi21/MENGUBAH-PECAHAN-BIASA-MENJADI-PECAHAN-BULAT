# MENGUBAH-PECAHAN-BIASA-MENJADI-PECAHAN-BULAT


## CODINGAN LENGKAP
    #include<stdio.h>
    using namespace std;

    void pecahan();
    main(){
    pecahan();
    }

    void pecahan (){
    int a,b,l,t;
    printf("============================DINDA PUSPITA DEWI=======================");
    printf("========================MENGUBAH BILANGAN PECAHAN MENJADI BILANGAN BULAT===================");
    printf("Masukkan pembilang :");
    scanf("%d",&a);
    printf("Masukkan penyebut :");
    scanf("%d",&b);
    t =a/b;
    l =a%b;
    if (a%b ==0)
    printf("Bilangan (%d/%d) \ndisederhanakan menjadi %d",a,b,t);
    else if(a%b !=0)
        printf("Bilangan (%d/%d) \ndisederhanakan menjadi(%d/%d)",a,b,t,l,b);
    }

## HASIL PROGRAM
![img](https://github.com/dindapuspitadewi/MENGUBAH-PECAHAN-BIASA-MENJADI-PECAHAN-BULAT/blob/master/mengubah%20pecahan%20ke%20bulat.png?raw=true)
