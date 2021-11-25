# Python-Essentials-
Curso Python Essentials CEC EPN

# PARTE 1
print()

print("PARTE 1")
print()

print("Stephanie Chanalata")
# El tipo de dato de 875 es: INT
print("El tipo de dato de 875 es: INT")
print(type(875)) 
 # El tipo de dato de 4.89 es: FLOAT
print("El tipo de dato de 4.89 es: FLOAT")
print(type(4.89))
# El tipo de dato del texto: Now is better than never. es:STRING
print("El tipo de dato del texto: Now is better than never. es:STRING")
print(type("Now is better than never. es:")) 
# El tipo de dato de 1.32 es:FLOAT
print("# El tipo de dato de 1.32 es:FLOAT")
print(type(1.32)) 
# ¿El valor 5 + 8i corresponde a un valor entero? COMPLEX
print("¿El valor 5 + 8i corresponde a un valor entero? COMPLEX")
print(type(5 + 8j)) 
#¿El valor 8.2 corresponde a un valor entero? FLOAT
print("¿El valor 8.2 corresponde a un valor entero? FLOAT")
print(type(8.2)) 
# ¿El texto: Readability counts. corresponde a un string? STRING
print("¿El texto: Readability counts. corresponde a un string? STRING")
print(type("¿El texto: Readability counts. corresponde a un string?")) 
print()

# PARTE 2
print("PARTE 2")
print()

print("Programa que identifica el tipo de dato de un valor ingresado por el usuario, se realizarán cinco interacciones:")
 
numero = 1

while numero <= 5:
    numero = numero + 1
    print("Ingreso un valor cualquiera:")
    variable=input()
    print(type(variable))
print()
print ("¡YA NO SE HARÁN MÁS INTERACCIONES!")
