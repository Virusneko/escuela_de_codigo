# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* I.Programa que pida un número y diga si es positivo o negativo
* 1.-Inicio
* 2.-Declarar (n)
* 3.Escribir "porfavor ingresa tu numero"
* 4.-Asignar (n)
* 5.-Si n>0 Entonces Escribir "tu número es positivo" sino entonces "tu numero es negativo"
* ![image](https://user-images.githubusercontent.com/99296446/167274193-0595f15d-8241-421c-9817-b4e6c90aac30.png)
![image](https://user-images.githubusercontent.com/99296446/167274196-13b27f68-f91c-4e5c-b1ee-8488b7f475b6.png)
* II.Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.
* 1.Inicio
* 2.Declarar (letra)char
* 3.Escribir "Ingresa una letra"
* 4.Asignar (letra)
* 5.Si letra=="s" o letra=="n" entonces 
* Escribir "correcto"
* Sino
* Escribir "Incorrecto" 
* 6.Fin
* ![image](https://user-images.githubusercontent.com/99296446/167274523-a240f740-a349-4f4f-aa92-16777f8bf449.png)
![image](https://user-images.githubusercontent.com/99296446/167274546-56e8a72b-38ba-4cf8-9f2d-5f0b8075082f.png)
* III.Un programa que pida una letra y detecte si es una vocal. 
* 1.Inicio
* 2.Declarar (vocal)
* 3.Escribir "Ingresa la letra que creas que es vocal"
* 4.Asignar (vocal)
* 5.Si vocal=="a" o vocal=="e" o vocal=="i" o vocal=="o" o vocal=="u" entonces
* Escribir "La letra si es vocal!"
* Sino
* Escribir "La letra no es vocal"
* 6.Fin
* ![image](https://user-images.githubusercontent.com/99296446/167274698-11fa9e89-d60f-4ab2-b7f4-ed9d86c4a9f1.png)
![image](https://user-images.githubusercontent.com/99296446/167274762-b4d20095-81bc-4840-8739-d879b5c5c22e.png)
* IV.Programa que pida 3 números y los muestre en pantalla de menor a mayor.  
* 1.-Inicio
* 2.-Declarar (n1, n2, n3)
* 3.-Escribir "Por favor ingresa 3 números de uno en uno"
* 4.-Asignar (n1, n2, n3)
* 5.-Si n1<n2 entonces
* Si n2<n3 entonces
* escribir "Tu secuencia de números es: ", n1, n2, n3
*		SiNo
*			Si n1<n3 Entonces
*				Escribir "Tu secuencia de números es: ", n1, n3, n2
*			SiNo
*				Escribir "Tu secuencia de números es: ", n3, n1, n2
*			Fin Si
*		Fin Si
*	SiNo
*		Si n1<n3 Entonces
*			Escribir "Tu secuencia de números es: " n2, n1, n3
*		SiNo
*			Si n2<n3 Entonces
*				Escribir "Tu secuencia de números es: " n2, n3, n1
*			SiNo
*				Escribir "Tu secuencia de números es: " n3, n2, n1
*			Fin Si
*		Fin Si
*	Fin Si
* 6.Fin
*![image](https://user-images.githubusercontent.com/99296446/167275326-f08bcbee-f0fd-417e-9e3c-1c25c707be5e.png)
![image](https://user-images.githubusercontent.com/99296446/167275334-48813220-dd50-4531-8ed5-f5023033d753.png)
* V.De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
* 1.Inicio
* 2.Declarar (mes)
* 3.Escribir "Porfavor ingresa un número del 1 al 12"
* 4.Asignar (mes)
* 5.Si mes = 1 entonces
escribir "El mes número 1 es enero"
sino entonces          
* 6.Si mes = 2 entonces
escribir "El mes número 2 es febrero"
* 7.Si mes = 3 entonces
escribir "El mes número 3 es marzo"
* 8.Si mes = 4 entonces
escribir "El mes número 4 es abril"
* 9.Si mes = 5 entonces
escribir "El mes número 5 es mayo"
* 10.Si mes =6
* 18.Fin
* ![image](https://user-images.githubusercontent.com/99296446/167315781-be0b9db1-e4fa-4f3f-8628-9ada3f2dd60f.png)
![image](https://user-images.githubusercontent.com/99296446/167315832-79f6156f-534d-4889-9d3c-0422e33d6793.png)
* ![image](https://user-images.githubusercontent.com/99296446/167315835-56fb6d1f-5dc4-4106-b46a-f34731ded347.png)
* VI.De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* 1.Inicio
* 2.Declarar (voto)
* 3.Escribir "Porfavor vota por: Rojo, verde, o azul"
* 4.Leer (voto)
* 5.Si voto <> "Rojo" o voto <> "Azúl" o voto <> "Verde" entonces               
Si voto == "Rojo" entonces
Escribir "Usted ha votado por el partido rojo"
Sino 
Si voto == "Azul" entonces
Escribir "Usted ha votado por el partido azul"
Sino
Escribir "Usted ha votado por el partido verde"
Sino escribir "Opción erronea"
* ![image](https://user-images.githubusercontent.com/99296446/167316318-6ea2ee9c-09f7-41df-b9e2-2489be747007.png)
![image](https://user-images.githubusercontent.com/99296446/167316291-6614c426-79fa-414a-8c0d-66eaba1b6361.png)
* VII.Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
* 1.Inicio
* 2.Declarar (e, c)
* 3.Escribir "Porfavor ingrese su email y luego su contraseña"
* 4.Asignar (e, c)
* 5.Si e=="virusneko" y c=="elmejorprogramador" entonces
escribir "Tu usuario y tu email son correctos, iniciando sesion"
sino
escribir "Tu usuario o ocntraseña son incorrectos, porfavor intenta de nuevo"
* 6.Fin
* ![image](https://user-images.githubusercontent.com/99296446/167317132-8b98eb0e-180b-43a1-8025-80cec89515a5.png)
![image](https://user-images.githubusercontent.com/99296446/167317145-b6aab016-db1d-4ab1-94ee-5c08d0132eca.png)
