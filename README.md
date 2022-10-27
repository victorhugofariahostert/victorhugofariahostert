#include <iostream>
#include <time.h>
using namespace std;



    void facil( ){
system("cls");
        srand (time(NULL));
 cout<<"ffffffffffffffffffffffffffffffgfgfgfgfffffffffffffffffffff" <<endl;
 int numeror1 =0, numeror2=0, numeror3=0,c=0 ;
 int resposta1=0, respoesta2=0,resposta3=0 ;
cout << "dificuldade 1" << endl;

 numeror1=rand()%6+1;
 numeror2=rand()%6+1;
 numeror3=rand()%6+1;

    cout<<("digite 3 digitos para saber se esta certo, voce tem 8 tentativas")<<endl;



 cout << (numeror1) <<  endl;
 cout << (numeror2) <<  endl;



 int i;
 switch(i){
 case 1:
     do{
         numeror1=rand()%6+1;
         numeror2=rand()%6+1;
         numeror3=rand()%6+1;


     }while (numeror1==numeror2||numeror1==numeror3 ); {

     }

 }





 }

    void normal(){
 srand (time(NULL));
    int numeror;

        cout << "dificuldade 2" << endl;




    }



     void dificil( ){
 srand (time(NULL));
    int numeror;
 cout << "dificuldade 3" << endl;
}



int main()
{
    int imaco=0, retorno, dific, numeror ;
system("cls");


   cout <<"  ola, bem vindo ao Mastermind um jogo onde voce pode desafiar sua mente(com probabilidades) ou com a sorte, " << endl;
   cout <<"entao tente utilizar esse jogo para testar o seu potencial ao maximo. "<< endl;
   cout << "\n"<< endl;
   cout << "   jogar" << endl;
   cout << "   dificuldade"<< endl;
   cout << "   sobre"<< endl;
   cout << "   fim"<< endl;
   cin >>imaco ;
   cout << "\n"<< endl;



   if(imaco == 2 ){
     system("cls");
   }
   else{

   cout << "eu disse 1 nao essa tecla, parece que voce nao vai se dar bem nesse jogo,vamos la aperte qualquer" << endl;
   cout     << "coisa que eu vou deichar voce jogar, boa sorte voce vai precisar.    " <<endl;
   system("pause");

    }
system("cls");





   cout <<" entao vamos iniciar o jogo, insira o numero da dificuldade." << endl;
    cout << endl;
    cout <<"   1-facil"<<endl;
    cout <<"   2-normal"<<endl;
    cout <<"   3-dificil"<<endl;
    cin>> dific;
    switch (dific) {
    case 1:
         facil();
    break;

    case 2:
        normal();
   break;

   case 3:
       dificil();
    break;


    }







    return 0;
   ;
}
