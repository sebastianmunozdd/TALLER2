# TALLER2

TALLER DOS PROFE
Algoritmo mayor_de_4
	
	
	definir num1, num2, num3, num4, num5 Como Real
	
	imprimir  "escribe su primer digito" 
	
	leer num1
	
	imprimir  "escribe su segundo digito" 
	
	leer num2
	
	imprimir  "escribe su tercer digito" 
	
	leer num3
	
	imprimir  "escribe su cuarto digito" 
	
	leer num4
	
	
	si(num1 >num2) entonces
		
		si(num1 >num3) Entonces
			
			si(num1> num4) Entonces
				
				mayor= num1
			SiNo
				
				mayor=num4
				
			FinSi
			
				sino
				
				si( num3>num4) Entonces
					
					mayor=num3
					
				SiNo
					mayor=num4
					
				fin si
				
			  SiNo
				si(num2> num3)Entonces
					
					si(num2>num4) Entonces
						
						mayor=  num2
						
					SiNo
						
						mayor= num4
					
					FinSi
					
				sino
					
					
			
				FinSi
					
				
					
				
				
			
				
				
				
		
			
				
				
				
			FinSi
		FinSi
	FinSi
	
	
	
	
FinAlgoritmo

Algoritmo MayorNumero
	Definir num1, num2, Mayor como entero
	
	imprimir  "Ingrese el primer n�mero: "
	
	leer num1
	
	imprimir "Ingrese el segundo n�mero: " 
	
	leer num2
	
	Si num1 > num2 Entonces
	mayor = num1

	SiNo

	mayor = num2

	Si num1 > num2 Entonces
	      mayor = num1
	FinSi
	
	imprimir "El mayor entre ", num1, " y ", num2
	
	
	imprimir. " es ", mayor
	
FinAlgoritmo
Algoritmo notas
	
	definir nota Como Real
	
	Imprimir " escribe tu nota final"
	
	leer nota
	
	si ( nota < 3.0)Entonces
		imprimir "no pasas"
		
		
	SiNo
		
		
		si(nota <=3.5) Entonces
			
			imprimir "regular"
		SiNo
			
			si( nota <=4.0)
				
				Imprimir "bien"
				
			SiNo
				
				si ( nota <5.0)
					
					imprimir "muy bien"
				SiNo
					si( nota = 5.0)
						
						imprimir "exelente"
					FinSi
				
				
				
				
				
			FinSi
			

			
		FinSi
		
		
	FinSi
	
	fin si

FinAlgoritmo

Algoritmo Par_o_Impar
	Definir num1 como Entero
	
	Imprimir "Ingrese un n�mero: "
	
	leer num1
	
	
	Si( num1 % 2 == 0) Entonces
	
	imprimir( "Es par" )
	

	SiNo
	

	imprimir( "Es impar" )
	
	FinSi
	
FinAlgoritmo

Algoritmo rango
	
	definir num1 Como Real
	
	imprimir " ingrese un numero"
	
	leer num1
	
	
	si (num1 > 3.5 y x <= 7.8) Entonces
		
		imprimir "esta en el rango"
		
	SiNo
		imprimir " no esta en el rango"
	FinSi
	
FinAlgoritmo

Algoritmo rangos
	
	definir num1 como real
	
	imprimir "ingrese un numero"
	
	leer num1
	
	si ( num1 > 3.5 y num1 <=7.8 o  num1>= 9.3 y num1 < 4.5  o num1 >= 23.4 y num1 <= 45.3 )  Entonces
		
		imprimir "esta en el rango"
		
		sino 
		
			imprimir "no esta en el rango"
			
	FinSi
	
		
FinAlgoritmo

Algoritmo  felicitacioness
	
	definir  notadefi Como Real
	
	imprimir "ingresas la nota definitiva"
	
	leer notadefi
	
	imprimir "su definitiva es" notadefi
	
	si (notadefi >= 4.0)
		
		imprimir "felicitacioness"
		
		FinSI
		
 FinAlgoritmo

Algoritmo android_o_ios
	
	
	definir eleccion Como Caracter
	
	Imprimir " elige caracter A,I o el que quieras"
	
	leer eleccion
	
	imprimir "su opcion es"
	
	si( eleccion = "a" o eleccion = "A") Entonces
		
		Imprimir "ANDROID"
		
	SiNo
		
		si( eleccion = "i" o eleccion = "I") Entonces
			
			Imprimir  "IOS"
			
			
		SiNo
			
			Imprimir "no valido"
		FinSi
		
		
		
	FinSi
	
	
	
	
	
FinAlgoritmo

Algoritmo MayoriaEdad
	
	definir nombre, mensajedad COMO CADENA
	
	definir edadn Como Entero
	
	imprimir "Ingrese su nombre:" 
	
	leer nombre
	
	imprimir "Ingrese su edad:"
	
	leer edad 

	Si( edad >= 18 ) Entonces

	mensajeEdad = "Mayor de edad"
	
	SiNo
	
	mensajeEdad = "Menor de edad"


	FinSi

	
	imprimir "fin de operacion ", nombre
	imprimir " usted es", mensajeEdad
	
FinAlgoritmo

