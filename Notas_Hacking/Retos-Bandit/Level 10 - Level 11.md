## Objetivo
La contraseña para el siguiente nivel se almacena en el archivo *data.txt*, que contiene datos codificados en base64.

## Datos de acceso al nivel
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

## Solucion
``` shell
bandit10@bandit:~$ ls
data.txt
bandit10@bandit:~$ cat data.txt
VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg==
bandit10@bandit:~$
bandit10@bandit:~$ man base64
bandit10@bandit:~$ 
bandit10@bandit:~$ cat data.txt | base64 -d
The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

bandit10@bandit:~$ base64 -d data.txt
The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
```
## Notas adicionales 
Base64 es un sistema de numeración posicional que usa 64 como base. Es la mayor potencia que puede ser representada usando únicamente los caracteres imprimibles de ASCII. Esto ha propiciado su uso para codificación de correos electrónicos, PGP y otras aplicaciones.

El comando base64 codifica en base 64, con el -d nos ayuda a decodificar.

## Referencias