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
