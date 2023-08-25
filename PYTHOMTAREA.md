print("Conversor de centímetros")
print("Seleccione 1 para convertir a metros")
print("Seleccione 2 para convertir a yardas")
print("Seleccione 3 para convertir a varas")
print("Seleccione 4 para convertir a pies")
print("Seleccione 5 para convertir a pulgadas")
opc = int(input())

if opc == 1:
    print("Seleccionó de centímetros a metros")
    centi = float(input("Ingrese la cantidad de centímetros: "))
    if centi <= 0:
        print("Número no válido")
    else:
        print(f"Los centímetros ingresados son {centi} equivalen a {centi / 100} metros")
elif opc == 2:
    print("Seleccionó de centímetros a yardas")
    centi = float(input("Ingrese la cantidad de centímetros: "))
    if centi <= 0:
        print("Número no válido")
    else:
        print(f"Los centímetros ingresados son {centi} equivalen a {centi / 91.44} yardas")
elif opc == 3:
    print("Seleccionó de centímetros a varas")
    centi = float(input("Ingrese la cantidad de centímetros: "))
    if centi <= 0:
        print("Número no válido")
    else:
        print(f"Los centímetros ingresados son {centi} equivalen a {centi / 83.8235} varas")
elif opc == 4:
    print("Seleccionó de centímetros a pies")
    centi = float(input("Ingrese la cantidad de centímetros: "))
    if centi <= 0:
        print("Número no válido")
    else:
        print(f"Los centímetros ingresados son {centi} equivalen a {centi / 30.48} pies")
elif opc == 5:
    print("Seleccionó de centímetros a pulgadas")
    centi = float(input("Ingrese la cantidad de centímetros: "))
    if centi <= 0:
        print("Número no válido")
    else:
        print(f"Los centímetros ingresados son {centi} equivalen a {centi / 2.54} pulgadas")
else:
    print("Ingrese una opción válida, por favor.")
