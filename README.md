# ALGORITMOS
PROGRAMA CLASE 1
--------------------
--------------------

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include "stdlib.h"


using namespace std;

void main()
{
	float A,B,C,Area, Promedio, mayor;
	int op;
	do
	{
		cout<< "area de un cuadrado \n:";
		cout<< "promedio de tres numeros"<<endl;
		cout<< "mayor de dos numeros"<<endl;
		cout<< "salir"<<endl;
		cin>> op;
		switch (op){
		
		    case 1:  
			       cout<< "ingrese lado del cuadradro:";
			       cin>> A;
			
				   Area=A*A;
				   cout<< "el area del cuadrado es:"<< Area;
				   break;

			case 2:
				   cout<< "ingrese el primer numero:";
				   cin>> A;
				   cout<< "ingrese el segundo numero:";
				   cin>> B;
				   cout<< "ingrese el tercer numero.";
				   cin>> C;
				   Promedio= (A+B+C)/3;
				   cout<< "el promedio de los tres numeros es:"<< Promedio;
				   break;
			case 3:
				   cout<< "ingrese un numero:";
				   cin>> A;
				   cout<< "ingrese otro numero:";
				   cin >> B;
				   if (A>B)
					   cout<< A<<" es el mayor ";
				   else 
					   cout<< (B,"es el mayor ");
				   break;
			case 0:
				   cout<< "salir";
				   break;
			default: 
				   cout<< "error,opcion invalida";
				   break;
		}
		 getch();
		 system ("cls");
	}  while ( op !=0);
	   
	getch();

}
	 
