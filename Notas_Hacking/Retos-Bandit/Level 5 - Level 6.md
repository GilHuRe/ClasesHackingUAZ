## Objetivo
La contraseña para el siguiente nivel se almacena en un archivo en algún lugar del directorio inhere y tiene todas las siguientes propiedades:

	legible por humanos
	1033 bytes de tamaño
	no ejecutable

## Datos de acceso al nivel
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

## Solucion
bandit5@bandit:~$ ls
inhere
bandit5@bandit:~$ cd inhere
bandit5@bandit:~/inhere$ ls
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17
maybehere02  maybehere06  maybehere10  maybehere14  maybehere18
maybehere03  maybehere07  maybehere11  maybehere15  maybehere19
bandit5@bandit:~/inhere$ man ls
bandit5@bandit:~/inhere$ ls -l
total 80
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere00
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere01
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere02
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere03
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere04
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere05
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere06
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere07
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere08
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere09
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere10
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere11
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere12
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere13
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere14
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere15
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere16
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere17
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere18
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere19
bandit5@bandit:~/inhere$ man ls
bandit5@bandit:~/inhere$ ls -R
.:
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17
maybehere02  maybehere06  maybehere10  maybehere14  maybehere18
maybehere03  maybehere07  maybehere11  maybehere15  maybehere19

./maybehere00:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere01:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere02:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere03:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere04:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere05:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere06:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere07:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere08:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere09:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere10:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere11:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere12:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere13:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere14:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere15:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere16:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere17:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere18:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3

./maybehere19:
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3
bandit5@bandit:~/inhere$ ls -R -l
.:
total 80
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere00
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere01
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere02
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere03
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere04
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere05
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere06
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere07
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere08
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere09
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere10
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere11
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere12
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere13
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere14
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere15
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere16
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere17
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere18
drwxr-x--- 2 root bandit5 4096 Jan 11 19:19 maybehere19

./maybehere00:
total 44
-rwxr-x--- 1 root bandit5 1039 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 9388 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 7378 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 6118 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 6850 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 1915 Jan 11 19:19 spaces file3

./maybehere01:
total 52
-rwxr-x--- 1 root bandit5 6028 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5  288 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 9641 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 4139 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 4543 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 8834 Jan 11 19:19 spaces file3

./maybehere02:
total 40
-rwxr-x--- 1 root bandit5 3801 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 3511 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 4932 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 6746 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 8488 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 2275 Jan 11 19:19 spaces file3

./maybehere03:
total 44
-rwxr-x--- 1 root bandit5  315 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 6595 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 8275 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 2190 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 3385 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 9234 Jan 11 19:19 spaces file3

./maybehere04:
total 36
-rwxr-x--- 1 root bandit5 4410 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 2619 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 2117 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 5532 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 2491 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 6002 Jan 11 19:19 spaces file3

./maybehere05:
total 36
-rwxr-x--- 1 root bandit5 2346 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 5959 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 2572 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5  880 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 2420 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 8585 Jan 11 19:19 spaces file3

./maybehere06:
total 36
-rwxr-x--- 1 root bandit5 5731 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 1076 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 3443 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 4073 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 4251 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 8065 Jan 11 19:19 spaces file3

./maybehere07:
total 36
-rwxr-x--- 1 root bandit5 3663 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 2488 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 3362 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 4130 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 9064 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 1022 Jan 11 19:19 spaces file3

./maybehere08:
total 32
-rwxr-x--- 1 root bandit5 1077 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 3825 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 2650 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5  215 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 3693 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 9138 Jan 11 19:19 spaces file3

./maybehere09:
total 44
-rwxr-x--- 1 root bandit5 3628 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5  774 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 7961 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 5301 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 8716 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 7569 Jan 11 19:19 spaces file3

./maybehere10:
total 32
-rwxr-x--- 1 root bandit5 1052 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 1991 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 1237 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 8269 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 3570 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 2155 Jan 11 19:19 spaces file3

./maybehere11:
total 44
-rwxr-x--- 1 root bandit5 1211 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 4559 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 8854 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 3147 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5  503 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 8845 Jan 11 19:19 spaces file3

./maybehere12:
total 40
-rwxr-x--- 1 root bandit5 9678 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5  251 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 9076 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 2157 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 2460 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 1639 Jan 11 19:19 spaces file3

./maybehere13:
total 28
-rwxr-x--- 1 root bandit5 1359 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 1423 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 3014 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 3952 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5  952 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 4389 Jan 11 19:19 spaces file3

./maybehere14:
total 36
-rwxr-x--- 1 root bandit5 4282 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 8351 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 3756 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 1382 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5  871 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5  376 Jan 11 19:19 spaces file3

./maybehere15:
total 44
-rwxr-x--- 1 root bandit5 8794 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 9499 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 6299 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 1623 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5   51 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 1637 Jan 11 19:19 spaces file3

./maybehere16:
total 48
-rwxr-x--- 1 root bandit5 4277 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 5301 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 8085 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 9773 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 3146 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 7509 Jan 11 19:19 spaces file3

./maybehere17:
total 40
-rwxr-x--- 1 root bandit5 1133 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 1791 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 4422 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 8361 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 3387 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 6381 Jan 11 19:19 spaces file3

./maybehere18:
total 44
-rwxr-x--- 1 root bandit5 9697 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5   77 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 2306 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 7334 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 6348 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 7040 Jan 11 19:19 spaces file3

./maybehere19:
total 48
-rwxr-x--- 1 root bandit5 6302 Jan 11 19:19 -file1
-rw-r----- 1 root bandit5 5594 Jan 11 19:19 -file2
-rwxr-x--- 1 root bandit5 7965 Jan 11 19:19 -file3
-rwxr-x--- 1 root bandit5 7186 Jan 11 19:19 spaces file1
-rw-r----- 1 root bandit5 8785 Jan 11 19:19 spaces file2
-rwxr-x--- 1 root bandit5 2307 Jan 11 19:19 spaces file3
bandit5@bandit:~/inhere$ man find
bandit5@bandit:~/inhere$ bandit5@bandit:~/inhere$
bandit5@bandit:~/inhere$ find . -size 1033c -type f
./maybehere07/.file2
bandit5@bandit:~/inhere$ cat ./maybehere07/.file2
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

## Notas adicionales 
Para buscar dentro de la ayuda ponemos / avanzamos para atras con "n" y con "N" Avanzamos para atras.
*ls -l* nos da una lista larga con algnos detalles como tamaño y permisos y la fecha de creación.
*ls -R* Nos da un listado recursivo, es decir carpetas con subcarpetas y sus archivos.
*ls -R -l* nos muestra carpetas, sub carpetas y archivos junto con sus detalles.
*find* nos ayuda a hacer una busqueda más detallada.
*find -type* nos muestra el tipo de archivo que buscamos
*find -size (tamaño en bytes)c* nos muestra los archivos que contengan el tamaño mencionado.
*find . -size 1033c -type f* nos da el tamaño en caracteres(c) y el tipo (f) que es normal.

## Referencias