# Prácticas Git

## Práctica 1: Creación e conexión de repositorios git

### Comandos empregados

```bash
git init
```
> Sirve para inicializar un repo local

```bash
git config --global user.name "Nome de usuario"
```
> Sirve para engadir o nome do usuario ao repositorio.

```bash
git config --global user.email correo
```
> Sirve para engadir o correo do usuario ao repositorio.

```bash
git add .
```
> Sirve para engadir todos os arquivos dun directorio ao repositorio local.

```bash
git commit -m "Mensaxe"
```
> Sirve para facer un commit dos arquivos ao repositorio local.

```bash
git branch -M main
```
> Sirve para cambiar a rama do repositorio a main.

```bash
git remote add origin https://github.com/fersp95/proba-repo
```
> Sirve para conectar o repositorio local e o repositorio en liña.

```bash
git push -u origin main
```
> Sirve para subir o contido do repositorio local ao repositorio en liña.

```bash
git pull --all
```
> Sirve para baixar o contido do repositorio en liña ao repositorio local.

### Pasos a seguir na práctica

1. Inicializar repo local co comando `git init`.
2. Establecemos o nome de usuario co comando `git config --global user.name "Nome de usuario"`
3. Establecemos o correo do usuario co comando `git config --global user.email correo`
4. Crear arquivos index.html e index2.html e engadilos ao repositorio local co comando `git add .`
5. Facemos o primero commit co comando `git commit -m "Creación do proxecto"`
6. Modificamos a rama á rama main do repositorio co comando `git branch -M main`
7. Unimos o repositorio local co repositorio en liña co comando `git remote add origin https://github.com/fersp95/proba-repo`
8. Subimos o contido do repositorio local ao repositorio en liña co comando `git push -u origin main`
9. Creamos o arquivo README.md
10. Baixamos os arquivos do repositorio en liña ao local co comando `git pull --all`

## Práctica 2: creación y actualización de repositorios

```bash
git diff
```
> Sirve para mostrar as diferencias entre commits

```bash
git show
```
> Sirve para mostrar visualmente as diferencias entre commits

```bash
git commit --amend -m "mensaje"
```
> Sirve para cambiar a mensaxe dun commit

```bash
git config --global color.ui auto
```
> Sirve para cambiar o color da interfaz

## Pasos a seguir na práctica

1. Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.
2. Crear un repositorio nuevo con el nombre libro y mostrar su contenido.
3. Comprobar el estado del repositorio.
4. Crear un fichero indice.txt con el siguiente contenido:

Capítulo 1: Introducción a Git

Capítulo 2: Flujo de trabajo básico

Capítulo 3: Repositorios remotos

5. Comprobar de nuevo el estado del repositorio.
6. Añadir el fichero a la zona de intercambio temporal.
7. Volver a comprobar una vez más el estado del repositorio.
8. Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro.” y ver el estado del repositorio.
9. Cambiar el fichero indice.txt para que contenga lo siguiente:

Capítulo 1: Introducción a Git

Capítulo 2: Flujo de trabajo básico

Capítulo 3: Gestión de ramas

Capítulo 4: Repositorios remotos

10. Mostrar los cambios con respecto a la última versión guardada en el repositorio.
11. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.
12. Mostrar los cambios de la última versión del repositorio con respecto a la anterior.
13. Cambiar el mensaje del último commit por “Añadido capítulo 3 sobre gestión de ramas al índice.”
14. Volver a mostrar los últimos cambios del repositorio.


## Práctica 3: Historial de cambios

```bash
git reset --hard
```
> Sirve para eliminar todos los cambios no guardados en el directorio de trabajo y el área de preparación, y hace que la rama actual apunte al commit especificado.

```bash
git log
```
> Sirve para mostrar un registro de todos los cambios realizados en un repositorio.

```bash
git annotate
```
> Sirve para mostrar la línea de código específica y el autor que la modificó en cada línea del archivo especificado.

## Pasos a seguir na práctica

1. Mostrar el historial de cambios del repositorio.
2. Crear la carpeta capitulos y crear dentro de ella el fichero capitulo1.txt con el siguiente texto:
  Git es un sistema de control de versiones ideado por Linus Torvalds.

3. Añadir los cambios a la zona de intercambio temporal.
4. Hacer un commit de los cambios con el mensaje “Añadido capítulo 1.”
5. Volver a mostrar el historial de cambios del repositorio.
6. Crear el fichero capitulo2.txt en la carpeta capitulos con el siguiente texto.
  El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en el repositorio. 2- Añadir los cambios a la zona de      intercambio temporal. 3- Hacer un commit de los cambios.

7. Añadir los cambios a la zona de intercambio temporal.
8. Hacer un commit de los cambios con el mensaje “Añadido capítulo 2.”
9. Mostrar las diferencias entre la última versión y dos versiones anteriores.
10. Crear el fichero capitulo3.txt en la carpeta capitulos con el siguiente texto.
  Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera           simultanea en ellas.

11. Añadir los cambios a la zona de intercambio temporal.
12. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3.”
13. Mostrar las diferencias entre la primera y la última versión del repositorio.
14. Añadir al final del fichero indice.txt la siguiente línea:
  Capítulo 5: Conceptos avanzados

15. Añadir los cambios a la zona de intercambio temporal.
16. Hacer un commit de los cambios con el mensaje “Añadido capítulo 5 al índice.”.
17. Mostrar quién ha hecho cambios sobre el fichero indice.txt.

## Práctica 3: Deshacer Cambios

### Comandos empregados

```bash
git checkout
```
> Sirve para desplazarte entre las ramas creadas por git branch

```bash
git clean
```
> Sirve para eliminar los archivos sin seguimiento en un directorio de trabajo del repositorio.

## Pasos a seguir na práctica

1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Comprobar el estado del repositorio.
3. Deshacer los cambios realizados en el fichero indice.txt para volver a     la versión anterior del fichero.
4. Volver a comprobar el estado del repositorio.
5. Eliminar la última línea del fichero indice.txt y guardarlo.
6. Añadir los cambios a la zona de intercambio temporal.
7. Comprobar de nuevo el estado del repositorio.
8. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos    en el directorio de trabajo.
9. Comprobar de nuevo el estado del repositorio.
10. Deshacer los cambios realizados en el fichero indice.txt para volver a     la versión anterior del fichero.
11. Volver a comprobar el estado del repositorio.
12. Eliminar la última línea del fichero indice.txt y guardarlo.
13. Eliminar el fichero capitulos/capitulo3.txt.
14. Añadir un fichero nuevo captitulos/capitulo4.txt vacío.
15. Añadir los cambios a la zona de intercambio temporal.
16. Comprobar de nuevo el estado del repositorio.
17. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos     en el directorio de trabajo.
18. Comprobar de nuevo el estado del repositorio.
19. Deshacer los cambios realizados para volver a la versión del               repositorio.
20. Volver a comprobar el estado del repositorio.
21. Eliminar la última línea del fichero indice.txt y guardarlo.
22. Eliminar el fichero capitulos/capitulo3.txt.
23. Añadir los cambios a la zona de intercambio temporal y hacer un commit     con el mensaje “Borrado accidental.”
24. Comprobar el historial del repositorio.
25. Deshacer el último commit pero mantener los cambios anteriores en el 26. directorio de trabajo y la zona de intercambio temporal.
27. Comprobar el historial y el estado del repositorio.
28. Volver a hacer el commit con el mismo mensaje de antes.
29. Deshacer el último commit y los cambios anteriores del directorio de       trabajo volviendo a la versión anterior del repositorio.
30. Comprobar de nuevo el historial y el estado del repositorio.
