## Objetivo
La contraseña para el siguiente nivel se almacena en el archivo data.txt junto a la palabra millonésima.

## Datos de acceso al nivel
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

## Solucion
```bash
bandit7@bandit:~$ man grep
bandit7@bandit:~$
bandit7@bandit:~$ cat data.txt | grep millionth
millionth       TESKZC0XvTetK0S9xNwm25STk5iWrBvP
bandit7@bandit:~$
bandit7@bandit:~$ gerp milliont data.txt
Command 'gerp' not found, did you mean:
  command 'grep' from deb grep (3.7-1build1)
Try: apt install <deb name>
bandit7@bandit:~$ grep milliont data.txt
millionth       TESKZC0XvTetK0S9xNwm25STk5iWrBvP
bandit7@bandit:~$
```
## Notas adicionales  
El comando grep nos ayuda a filtrar datos.

## Referencias
