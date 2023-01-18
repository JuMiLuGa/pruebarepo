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

1. Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.
2. Crear un repositorio nuevo con el nombre libro y mostrar su contenido.
3. Comprobar el estado del repositorio.
4. Crear un fichero indice.txt con el siguiente contenido:

>Capítulo 1: Introducción a Git
>Capítulo 2: Flujo de trabajo básico
>Capítulo 3: Repositorios remotos

5. Comprobar de nuevo el estado del repositorio.
6. Añadir el fichero a la zona de intercambio temporal.
7. Volver a comprobar una vez más el estado del repositorio.
8. Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro.” y ver el estado del repositorio.
9. Cambiar el fichero indice.txt para que contenga lo siguiente:

>Capítulo 1: Introducción a Git
>Capítulo 2: Flujo de trabajo básico
>Capítulo 3: Gestión de ramas
>Capítulo 4: Repositorios remotos

10. Mostrar los cambios con respecto a la última versión guardada en el repositorio.
11. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.
12. Mostrar los cambios de la última versión del repositorio con respecto a la anterior.
13. Cambiar el mensaje del último commit por “Añadido capítulo 3 sobre gestión de ramas al índice.”
14. Volver a mostrar los últimos cambios del repositorio.

