## Objetivo
La contraseña para el siguiente nivel se almacena en el archivo data.txt en una de las pocas cadenas legibles por humanos, precedida por varios caracteres '='.

## Datos de acceso al nivel
EN632PlfYiZbn3PhVK3XOGSlNInNE00t

## Solucion
```shell 
bandit9@bandit:~$ cat data.txt | strings | grep ==
c========== the
h;========== password
========== isT
n.E========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
```
## Notas adicionales 
El comando *strings* nos ayuda a imprimir cadenas de un archivo binario.

## Referencias