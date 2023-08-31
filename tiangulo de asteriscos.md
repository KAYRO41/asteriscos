`console.long('Medidas en python')`

```python
print ('figuras con asteriscos')
def S(a,):
    return a 
def M(a,):
    return a 
def D(a,):
    return a 
def R(a,):
    return a 
def N(a,):
    return a
while True:
    print("***Menu principal ***")
    print("1. figura 1")
    print("2 figura 2")
    print("3 figura 3")
    print("4 figura 4")
    opc = input("ingrese una opcion")
    n1 = 0
    if opc=="1":
        for i in range(5):
         print((i + 1) * "*")
    elif opc=="2":
        for i in range(5, -1, -1):
         print((i + 1) * "*")
    elif opc=="3":
        for i in range(9, -1, -1):
         print(f'{(i + 1) * "*" : >5}')

    elif opc=="4":
        for i in range(5):
         print(f'{(i + 1) * "*" : >5}')
    else:
        print("ingrese una opcion valida")
```

`console.long('Medidas en c++')`

```cpp
#include <iostream>
#include <cstdlib>
#include <cstdio>

using namespace std;
int main(int argc, char const *argv[]){
	
	//algoritmo para calcular mediada que sean seleccionadas por el usuario
	int a,x;
    
printf ("tomar en cuenta que es en centimetros, ")
cout << "escribe el numero";
	cin >> a
	x = 0;
	while x < > 5
	    cout <<"ingrese una opcion:";
	    cout <<"1 = figura:1 ";
	    cout <<"2 = figura:2 ";
	    cout <<"3 = figura:3";
	    cout <<"4 = figura:4";
		cout <<"5 = salir: ";
	     cin >> x 

        switch (x)
        {
        case   cout <<"la figura es = " :
            #include <stdio.h>
int main(void)
{
    int i, j;
    int vet[10] = { [0 ... 9] = '*' };
    for(i=9; i>=0; i--)
    {
        for(j=i; j>=0; j--)
        {
            printf("%c", vet[j]);
        }
        printf("\n");
    }
    return 0;
}
            break;
         case   cout <<"la figura es = " :
            #include <stdio.h>
int main(void)
{
    int i, j;
    int vet[10] = { [0 ... 9] = '*' };
    for(i=9; i>=0; i--)
    {
        for(j=i; j>=0; j--)
        {
            printf("%c", vet[j]);
        }
        printf("\n");
    }
    return 0;
}
            break;
         case   cout <<"la figura es = " :
           #include <stdio.h>
int main(void)
{
    int i, j;
    int vet[10] = { [0 ... 9] = '*' };
    for(i=9; i>=0; i--)
    {
        for(j=i; j>=0; j--)
        {
            printf("%c", vet[j]);
        }
        printf("\n");
    }
    return 0;
}
            break;
        case   cout <<"la figura es = " :
            #include <stdio.h>
int main(void)
{
    int i, j;
    int vet[10] = { [0 ... 9] = '*' };
    for(i=9; i>=0; i--)
    {
        for(j=i; j>=0; j--)
        {
            printf("%c", vet[j]);
        }
        printf("\n");
    }
    return 0;
}
            break;
        default:
            cout << "un curso de lenguaje "
            break;
        }
        
        return 0;
}
```
`console.long('Medidas en pseudocodigo')`

```psc
Algoritmo Medidas

	Definir a,x,b,c,fila,col,i,j,n Como entero
	n = 5
	fila = 0
	i = 5
	x = 0
	Mientras x <> 5 Hacer
	     EScribir "ingrese una opcion"
	     Escribir "1 = abjo derecha"
	     Escribir "2 = abajo izquierda"
	     Escribir "3 = arriba derecha"
	     Escribir "4 = abajo izquierda"
		 Escribir "5 = salir"
	     leer x 
	
		Segun x 
		1:
			Para a = 1 Hasta  n Con Paso 1 Hacer
				Para b = 1 Hasta a Con Paso 1 Hacer
					escribir Sin Saltar "*";
				Fin Para
				Escribir  ""
			Fin Para;
		2:
			Mientras fila < 6 Hacer
				col= 0
				Mientras col < 6 Hacer
					si col = i Entonces
						
						i = i -1
					SiNo
						si col > i Entonces
							Escribir  "*" Sin Saltar
						SiNo
							Escribir " " Sin Saltar
						FinSi
					FinSi
					
					col = col+1
				Fin Mientras
				Escribir ""
				fila = fila + 1 
			FinMientras
		3:
			Mientras fila < 6 Hacer
				col= 0
				Mientras col < 6 Hacer
					si col = i Entonces
						
						i = i -1
					SiNo
						si col > i Entonces
							Escribir  "" Sin Saltar
						SiNo
							Escribir "*" Sin Saltar
						FinSi
					FinSi
					
					col = col+1
				Fin Mientras
				Escribir ""
				fila = fila + 1 
			FinMientras
		4:
			para i <- n Con Paso -1 Hasta  1 Hacer
				para  j <- 0  Con Paso 1 Hasta ( n - i -1 ) Hacer
					escribir " " Sin Saltar;
				FinPara
				para  j <- 1  Con Paso 1 Hasta  i  Hacer
					escribir "*" Sin Saltar;
				FinPara
				escribir "";
			FinPara
			
		De Otro Modo:
			X = 5
	Fin Segun
FinMientras
FinAlgoritmo
```