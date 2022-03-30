# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
     * Iniciar
     * Declarar(num Como Entero)
     * Mostrar("Digite un número: ")
     * Asignar(número)
     * Si num > 0 Entonces
        Escribir "El número: ",num, "Es positivo"
     *  SiNo
        Si num < 0 Entonces
        Escribir "El número: ",num, "Es negativo"
     *  SiNo
        Escribir "El número: ",num, "Es neutro"
       Fin Si
      * Fin
      ![multiplica](https://user-images.githubusercontent.com/101481300/160302187-31bed57f-504d-46d4-a3a1-a9df0f8e22a5.png)

   
* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.
  * Iniciar
  * Mostrar("Ingresar x Como entero")
  * Mostrar("Ingresar l Como entero")
     x = 1
  * Mientras x <> 0 Hacer
  * Escribir "Ingresa una letra"
     Leer l
     Si l <> "s" y l <> "S" y l <> "n" y l <> "N" Entonces
      x = 0
     Fin Si
    Fin Mientras
  * Fin
  
  ![INTRODUCE S Y N](https://user-images.githubusercontent.com/101481300/160302316-039d85f2-6190-47ae-9681-183e3affeafc.png)


* Un programa que pida una letra y detecte si es una vocal. 
  * Inicia
  * mostrar("Ingresar letra como caracter")
	 * mostrar("Ingresar un caracter: ")
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


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.
  * Inicia
  * mostrar("a,b,c como entero")
	 * mostrar("Ingresar tres números")
 	* asignar(a,b,c)
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

  
* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
  * Inicio
  * Declarar(número Como Entero)
  * Mostrar("Ingresar número")
  * Asignar(número)
	segun número hacer
		1:
			Escribir "El numero 1 corresponde al mes de enero"
		2:
			Escribir "El numero 1 corresponde al mes de febrero"
		3:
			Escribir "El numero 1 corresponde al mes de marzo"
		4:
			Escribir "El numero 1 corresponde al mes de abril"
		5:
			Escribir "El numero 1 corresponde al mes de mayo"
		6:
			Escribir "El numero 1 corresponde al mes de junio"
		7:
			Escribir "El numero 1 corresponde al mes de julio"
		8:
			Escribir "El numero 1 corresponde al mes de agosto"
		9:
			Escribir "El numero 1 corresponde al mes de septiembre"
		10:
			Escribir "El numero 1 corresponde al mes de octubre"
		11:
			Escribir "El numero 1 corresponde al mes de noviembre"
		12:
			Escribir "El numero 1 corresponde al mes de diciembre"
		FinSegun	
  * Fin

![MES](https://user-images.githubusercontent.com/101481300/160730076-37df9d35-572a-4cf6-af17-75ccc852c063.png)


* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.



* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables..
