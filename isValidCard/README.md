Autora:	Tatiana Tudela Hern�ndez
Squad:	Gal�cticas

subproceso funci�n isValidCard
Hacer
	var singleNumber <- arreglo vacio; 
        var doubleNumber <- arreglo vacio; 
        var finalArray <- arreglo vacio; 
        var sum <- 0;
	Solicita valor de n�mero de su tarjeta;
	var cardNumber <- valor de n�mero de su tarjeta;
      	    Si cardNumber es distinto a a valor vacio
 		var array <- arreglo vacio; 
		Para i < 0 hasta cantidad de caracteres de cardNumber con paso 1 Hacer		
			Introduce el car�cter en el �ndice i de la cadena de texto obtenida en el arreglo vacio;
         		Invierte el orden del arreglo;
		Fin Para;
		
		Para i < hasta cantidad de caracteres de cardNumber con paso 1 Hacer	
                	Si (i%2 === 0) entonces
				Introduce los elementos de �ndice i obtenidos al arreglo singleNumber;
			Si no entonces                	
				Introduce los elementos de �ndice i obtenidos multiplicados por 2 al arreglo doubleNumber;
				y los convierte cadena de tipo string.
			Fin Si no;
		Fin Para;
		
		Unifica todos los elementos del arreglo doubleNumber en una cadena
		y divide esta cadena tipo String en un arreglo de cadenas mediante la separaci�n de esta cadena en subcadenas.

		finalArray <- Uni�n de los arreglos singleNumber y doubleNumber en un solo arreglo;

            	Para j < 0 hasta cantidad de caracteres de finalNumber con paso 1 Hacer		
			Suma los d�gitos impares y los nuevos d�gitos pares operados.
		Fin Para;
		
		Si el m�dulo del total de la suma por 10 es igual a 0
			Muestra: "Tarjeta v�lida";
              		Muestra el total de la suma;
		Fin si;
		
		Si no Muestra: "Tarjeta inv�lida");
	Si no Muestra: "Ingrese un n�mero v�lido por favor.";
            }
Mientras cardNumber sea distinto a valor vacio;
![Diagrama de flujo isValidCard](http://imageshack.com/a/img923/4944/lK5j7v.jpg)