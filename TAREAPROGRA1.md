Algoritmo sin_titulo
	Definir opc  como cadena
	Definir centi Como entero
	
	Escribir "Elige el tipo de conversion de centimetros que deseas hacer:" 

	Escribir "Seleccione 1 Para convertir a metros "

	Escribir "Seleccione 2 Para convertir a yardas"
	
	Escribir "Seleccione 3 Para convertir a varas "
	
	Escribir "Seleccione 4 Para convertir a pies "
	
	Escribir "Seleccione 5 Para convertir a pulgadas "
	
	leer opc
	
			
	Segun opc Hacer
	
		"1":Escribir "Seleccion� de centimetros a metros"
			Escribir "ingrese cantidad de centimetros"
				leer centi
				si centi<=0 Entonces
					Escribir "numero no valido"
				sino
						
					
				si centi>0 Entonces
					Escribir" los centimetros ingresados son : " , centi , " equivalen a : " , centi/100, " metros "
				FinSi	
				FinSi
			"2":Escribir "Seleccion� de centimetros a yardas"
				Escribir "ingrese cantidad de centimetros"
				leer centi
				si centi<=0 Entonces
					Escribir "numero no valido"
				SiNo
					
					si centi>0 Entonces
						Escribir " los centimetros ingresados son: " , centi , " equivalen a: " , centi/91.44 , " yardas "					
					FinSi
				FinSi
					
			"3":Escribir "Seleccion� de centimetros a varas"
				Escribir "ingrese cantidad de centimetros"
				leer centi
				si centi<=0 Entonces
					Escribir "numero no valido"
				SiNo
					
					si centi>0 Entonces
						Escribir " los centimetros ingresados son: " , centi , " equivalen a: " ,  centi /83.8235 , " varas "
					FinSi
					
				FinSi
			"4":Escribir "Seleccion� de centimetros a pies "
				Escribir "ingrese cantidad de centimetros"
				leer centi
				si centi<=0 Entonces
					Escribir "numero no valido"
				SiNo
					si centi>0 Entonces
						Escribir " los centimetros ingresados son: " , centi , " equivalen a: " ,  centi/30.48 , " pies "
					FinSi
				FinSi
			"5":Escribir "Seleccion� de centimetros a pulgadas"
				Escribir "ingrese cantidad de centimetros"
				leer centi
				si centi<=0 Entonces
					Escribir "numero no valido"
				SiNo
					si centi>0 Entonces
						Escribir "los centimetros ingresados son: " , centi  , " equivalen a: " ,  centi/2.54  , " pulgadas"
					FinSi
				FinSi	
				
				
				
				De Otro Modo:
					Escribir "ingrese una opcion valida por favor "
			Fin Segun


	
FinAlgoritmo
