## Objetivo
La contraseña para el siguiente nivel se almacena en el único archivo legible por humanos en el directorio inhere. Consejo: si su terminal está desordenada, intente con el comando "reset".

## Datos de acceso al nivel
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

## Solucion
bandit4@bandit:~/inhere$ ls
-file00  -file02  -file04  -file06  -file08
-file01  -file03  -file05  -file07  -file09
bandit4@bandit:~/inhere$ man file
bandit4@bandit:~/inhere$ bandit4@bandit:~/inhere$
bandit4@bandit:~/inhere$ file ./-file00
./-file00: data
bandit4@bandit:~/inhere$ file ./-file01
./-file01: data
bandit4@bandit:~/inhere$ file ./*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@bandit:~/inhere$ file ./-file07
./-file07: ASCII text
bandit4@bandit:~/inhere$ cat ./-file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
bandit4@bandit:~/inhere$

## Notas adicionales
Si la terminal se llena de basura tecleamos reset.
Recordemos que para leer archivo que comienzan con - hay que teclear ./ antes del nombre.
El * nos ayuda a listar todos los archivos.
El comando file nos determina el tipo de un archivo, el tipo ASCII es el que tiene la contraseña.

## Referencias