## Objetivo
La contraseña para el siguiente nivel se almacena en algún lugar del servidor y tiene todas las siguientes propiedades:

	Propiedad del usuario bandit7
	Propiedad del grupo bandit6
	33 bytes de tamaño

## Datos de acceso al nivel
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

## Solucion
```bash

bandit6@bandit:~$ man find
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
bandit6@bandit:~$
```

## Notas adicionales 

## Referencias
