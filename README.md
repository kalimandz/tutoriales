# Tutoriales de Python en Español
## Listas

Una lista es una serie de valores separados por coma que van entre corchetes.
Estos valores pueden ser de cualquier tipo, int, float, str, etc.
Las listas incluso pueden contener otras listas.

Una lista es una colección de elementos en un orden en particular.

Ya que una lista usualmente contiene mas de un elemento, es buena idea hacer el nombre de tu lista en plural, como frutas, o animales.

En Python, los corchetes indican una lista, y los elementos individuales dentro de la lista están separados por comas. Aquí hay un ejemplo de una lista que contiene unos cuantos pokemon
```python
pokemons = ["pikachu", "togepi", "mew"]
```
Si le pides a Python que imprima una lista, Python devuelve su representación de la lista, incluyendo los corchetes:

```python
["pikachu", "togepi", "mew"]
```
Ya que este no es la salida que quieres que tus usuarios vean, vamos a aprender a acceder a los elementos individuales dentro de una lista.

```python

# Crear una lista
lista_pokemons = ["moltres", "zapdos", "articuno"]

print(lista_pokemons)

# Accediendo a Elementos dentro de una lista
print(lista_pokemons[0])

# Usando metodos de cadena
print(f"{lista_pokemons[0].upper()}")

# Posiciones de Indice
print(lista_pokemons[0])
print(lista_pokemons[1])
print(lista_pokemons[2])

# Indices Negativos
print(lista_pokemons[-1])
print(lista_pokemons[-2])
print(lista_pokemons[-3])

# Usando valores individuales
mensaje = f"{lista_pokemons[0].upper()} es un pokemon legendario"

print(mensaje)

```
