
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

  * Algoritmo
        * Escribir "Ingresar número"
        * Leer número
        * Escribir "Mul número * 9"
        * mul<-num*9
        * Escribir "El resultado de la mul es: ",mul
  * FinAlgoritmo
  
  ![MULTIPLICA UN NUMERO POR 9](https://user-images.githubusercontent.com/101481300/160735826-37fa9c2b-6faf-4b4a-99bc-39bd67427652.png)

  
  
2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 

  * Algoritmo
  * Definir x Como Entero
	 * Definir n,suma Como Real
	      x = 1
	      suma = 0
	 * Mientras x <=10 Hacer
		* Escribir "Ingresa el número: ",x
		* Leer n
		     suma = suma + n
		     x = x + 1
	 * FinMientras
	 * Escribir "La suma de los 10 números es: ",suma
  * Fin
    
    ![SUMA 10 CANTIDADES](https://user-images.githubusercontent.com/101481300/160747693-fd5a871a-0399-4dd8-b873-b565f822ddfb.png)
 

3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

  * Algoritmo 
  * Definir a,b,c,d Como Entero
  * Definir e Como Real
  * Escribir "Ingresar nota 1 del alumno: "
  * Leer a
  * Escribir "Ingresar nota 2 del alumno: "
  * Leer b
  * Escribir "Ingresar nota 3 del alumno: "
  * Leer c
  * Escribir "Ingresar nota 4 del alumno: "
  * Leer d
	    e<-(a+b+c+d)/4
	 * Escribir "El promedio es: ",e;
	 * Si e>6 Entonces
	 * Escribir "FELICIDADES USTED APROBO"
     SiNo
  * Escribir "USTED REPROBO"
     Fin Si	
  * FinAlgoritmo

![CALIFICACIONES](https://user-images.githubusercontent.com/101481300/160946366-d24f983c-d134-4d90-b135-c21af2d355a6.png)




4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

 * Algoritmo sin_titulo
 * Escribir "Ingresar un número: "
 * Leer nun
 * Si num mod 2 = 0 Entonces
 * Escribir "El número: ", num, "Es par"
     SiNo
 * Escribir "El número: ", num, "Es impar"
	FinSi
 * FinAlgoritmo

![PAR IMPAR](https://user-images.githubusercontent.com/101481300/160944976-b51099a3-89e8-49dd-9cea-0910810d460e.png)


5. Un programa que pida una letra y detecte si es una vocal.
  * Algoritmo
  * Escribir "Ingresar letra como caracter"
	 * Escribir "Ingresar un caracter: "
	 * asignar(letra)
	   Si letra == "a" o letra == "e" o letra == "i" o letra == "o" o letra == "u" Entonces
		  Escribir "El caracter es una vocal" 
	 * SiNo
		   si letra == "A" o letra == "E" o letra == "I" o letra == "O" o letra == "U" Entonces
			 Escribir "El caracter es una vocal"
		* SiNo
			 Escribir "El caracter es una consonante"
		  FinSi
	  Fin Si
  * Fin
   
   ![DETECTA VOCAL](https://user-images.githubusercontent.com/101481300/160303421-f1dc7500-0f86-4acb-8f6e-adb60d503b33.png)



6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.

 * Algoritmo
 * Escribir "a,b,c como entero"
	* Escribir "Ingresar tres números"
 * Mostrar a,b,c
	* Si a>b Entonces
		  Si a>c Entonces
	* Escribir "El número: ",a, "Es el mayor de los tres"
	  	SiNo
	* Escribir "El número: ",c, "Es el mayor de los tres"
		  Fin Si
	   SiNo
		  Si b>c Entonces
	* Escribir "El número: ",b, "Es el mayor de los tres"
		  SiNo
	*	Escribir "El número: ",c, "Es el mayor de los tres"
	  	Fin Si
   	Fin Si
 * Fin
  
  ![PIDE 3 NUMEROS QUE SE MUESTREN DE MAYOR A MENOR](https://user-images.githubusercontent.com/101481300/160304950-04a100e8-3c12-48f2-8a14-d5caab80fdd3.png)



7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.

 * Algoritmo
 * Definir nombre Como Caracter
 * Definir c Como Entero
 * Escribir "Ingrese su nombre"
 * Leer nombre
     c<-1
 * Escribir "Ingresar número"
 * Leer número
 * Mientras c<=10 Hacer
 * Escribir c,".-",nombre;
      c<-c+1		
    FinMientras
 * FinAlgoritmo

![INGRESA NOMBRE](https://user-images.githubusercontent.com/101481300/160948546-56ceadca-2934-46b2-9bd1-7ece82a0e1c4.png)

8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
