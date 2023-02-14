# Python
simbolo=input("Teclear “k” si quieres convertir kilos en libras o teclear “l” si quieres convertir libras en kilos")

if simbolo=="k":
k=float(input("ingresa los kilogramos"))
print(f"su resultado en kg es "){k*2.2046}

elif simbolo=="l":
l=float(input("ingresa las libras"))
print(f"su resultado en lb es "{l/2.2046})
else:

    print("ingresa una letra valida")
