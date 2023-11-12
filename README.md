# TUPLAS: SON INMUTABLES
''' tupla = (100, 'Hola', [1,2,3], -50) '''
''' print(tupla) '''


#Indice de las tuplas

''' print(tupla[0])
print(tupla[-1])
print(tupla[2:])
print(tupla[2][-1]) '''


''' len(tupla) '''


#Metodo Index : Sirve para buscar un elemento y saber su posicion

''' print(tupla.index(800)) '''


# Metodo Count:  Sirve para saber cuantas  veces aparece un elemento:
''' print(tupla.count('Chau'))
 '''


''' print(tupla.append(10))
nos va a devolver error''' 



# Conjuntos O SET

''' conjunto = set()

print(conjunto) '''

''' conjunto = {1, 2, 3}
print(conjunto)


conjunto.add(4)
conjunto.add(0)

print(conjunto)

conjunto.add('A')
conjunto.add('D')
conjunto.add('Z')
conjunto.add('B')

print(conjunto) '''


""" grupo = {'Hector', 'Juan', 'Mario'} """


#Sintaxis in / not in
""" print('Hector' in grupo)



print('Hecto' not in grupo) """



# Los conjuntos no pueden tener el mismo elemento mas de una vez, por lo que se va a borrar automaticamente los que esten duplicados
""" test = {'Hector', 'Jorge', 'Hector'}
print(test) """


""" lista = [1,2,3,1,2,3]
print(lista)


conjunto = set(lista)
lista = list(conjunto)

print(lista)

lista = list(set(lista))
print(lista)

cadena = 'Al pan pan y al vino vino'
print(set(cadena)) """


#DICT 
#Para cada elemento se define la estructura clave:valor

""" vacio = {}
print(vacio)

print(type(vacio)) """


colores = {'amarillo': 'yellow', 'azul':'blue'}

""" print(colores)

print(colores['amarillo'])

 """
colores['verde'] = 'green'
""" print(colores) """

colores['amarillo'] = 'white'

""" print(colores) """


#DEL elimina 
""" del(colores['amarillo'])

print(colores)
 """

""" numeros = {10:'diez', 20: 'veinte'}
print(numeros[10])
 """


""" edades = {'Hector': 27, 'Juan': 45, 'Maria': 34}
edades['Hector']+=1
"" print(edades) ""

print(edades['Juan'] + edades ['Maria'])
 """

""" edades = {'Hector': 27, 'Juan': 45, 'Maria': 34} """
""" 
for edad in edades:
    print(edades[edad])

 """
 
#Agregamos con .append variables DICCIONARIO a la lista vacia.
""" personajes = []

gandalf = {'Nombre': 'Gandalf', 'Clase':'Mago', 'Especie': 'Humano'}
legoles = {'Nombre': 'Legolas', 'Clase':'Arquero', 'Especie': 'Elfo'}
gimli = {'Nombre': 'Gimli', 'Clase':'Guerrero', 'Especie': 'Enano'}

personajes.append(gandalf)
personajes.append(legoles)
personajes.append(gimli)

print(personajes)

 """
 
 
#PILAS: LIFO (Last in First Out) / El ultimo elemento en entrar es el primero en salir.

""" pila = [3,4,5]
pila.append(6)
pila.append(7)
print(pila) """

""" 
pila= [1,2,3]
print(pila.pop())
print(pila)

numero = pila.pop()
print(numero)

pila.pop()
pila.pop()
 """

#COLAS: FIFO (First In First Out)

cola = ['Hector', 'Maria', 'Juan']
print(cola)

