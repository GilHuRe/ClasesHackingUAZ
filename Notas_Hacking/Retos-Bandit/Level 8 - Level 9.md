## Objetivo
La contraseña para el siguiente nivel se almacena en el archivo data.txt y es la única línea de texto que aparece una sola vez.

## Datos de acceso al nivel
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

## Solucion
```shell
bandit8@bandit:~$ ls
data.txt
bandit8@bandit:~$ cat data.txt | sort | uniq -u
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
bandit8@bandit:~$
```
## Notas adicionales 
Nos damos cuenta que los pasword estan repetidos y revueltos, el comando *sort*, al pasarle una salida las ordena las lineas.
El comando *wc* nos cuenta las palabras.
El comando *uniq* reporta u omite lineas repetidas. 


## Referencias