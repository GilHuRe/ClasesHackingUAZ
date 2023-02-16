## Objetivo
La contraseña para el siguiente nivel se almacena en un archivo llamado - ubicado en el directorio de inicio.

## Datos de acceso al nivel
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

## Solucion
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat -
hola
hola
^C
bandit1@bandit:~$ cat ./-
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit1@bandit:~$ pwd
/home/bandit1
bandit1@bandit:~$ cat /home/bandit1/-
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit1@bandit:~$

## Notas adicionales 
Cuando cat ve la cadena - como un nombre de archivo, la trata como un sinónimo de stdin. Para evitar esto, debe modificar la cadena que ve el gato de tal manera que todavía se refiera a un archivo llamado -. La forma habitual de hacer esto es prefijar el nombre del archivo con una ruta - ./-, o /home/Tim/-.

## Referencias

[Google Search for “dashed filename”](https://www.google.com/search?q=dashed+filename)
[Advanced Bash-scripting Guide - Chapter 3 - Special Characters](http://tldp.org/LDP/abs/html/special-chars.html)
