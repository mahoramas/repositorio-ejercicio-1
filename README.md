# Repositorio ejercicio 1

Este repositorio contiene los pasos básicos para trabajar con Git y GitHub.
---
# Paso 3

Clona el repositorio que acabas de crear a tu máquina local utilizando Git.
```
bae2@jpexposito-VirtualBox:~$ git clone https://github.com/mahoramas/repositorio-ejercicio-1
Clonando en 'repositorio-ejercicio-1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.
```
---
# Paso 4

Abre el archivo README.md en un editor de texto o desde la terminal, también puedes utilizar vscode y realiza los siguientes cambios:
```
bae2@jpexposito-VirtualBox:~$ cd repositorio-ejercicio-1/
bae2@jpexposito-VirtualBox:~/repositorio-ejercicio-1$ code
```
Guardo los cambios usando este comando:
```code
bae2@jpexposito-VirtualBox:~/repositorio-ejercicio-1$ git add README.md
git commit -m "Añadir título y descripción al README"
git push origin main
[main 4eb55f3] Añadir título y descripción al README
1 file changed, 20 insertions(+), 1 deletion(-)
rewrite README.md (100%)
Username for 'https://github.com': mahoramas
Password for 'https://mahoramas@github.com':
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 624 bytes | 624.00 KiB/s, listo.
Total 3 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/mahoramas/repositorio-ejercicio-1.git
  4651f81..4eb55f3  main -> main
```
