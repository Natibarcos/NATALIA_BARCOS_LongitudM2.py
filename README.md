def verificar_longitud_palabra(palabra):
    
    ##Verifica la longitud de una palabra ingresada y muestra un mensaje apropiado.
    
    longitud = len(palabra)
    
    if 4 <= longitud <= 8:
        print("La palabra es correcta.")
    elif longitud < 4:
        print(f"Hacen falta letras. Solo tiene {longitud} letras.")
    else:
        print(f"Sobran letras. Tiene {longitud} letras.")
        
# Ingresa palabra

palabra_ingresada = input("Ingresa una palabra: ")

verificar_longitud_palabra(palabra_ingresada)
