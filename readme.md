# Cheatsheet GIT


------------------------------
## Ayuda en git
```git
sarasa --help
```

------------------------------
## Configuración

```git
git config --global
```
ejemplo:

```
git config --global user.name "fabian gonzalez"
git config --global user.email "fabiansato@gmail.com"

git config -l
```
### podemos setear por repositorio 
ejemplo:
```git

git config --local
```
------------------------------
## crear repositorio 
```git
git init
```

------------------------------
## Estados en git
```git
git status 
```

(muestra estados de como estan trackeados)
```
```git

git add 
```
(pasa al area de preparacion)



nos muestra la bitacora

------------------------------
## escribiendo commits
```git
git commit
```
ahora presionamos "I" para insertar
escribimos fuera del texto
ponemos ESQ
para salir:
```
:wq
```
y entrer para salver y se creo el escrito para el commit!


------------------------------
## Agregando archivos que se van a enviar
```git
git add <nombrearchivo>
```

### agregar todo el archivo actual stage

```git
git add .
```

### agregar todo lo de stage a repositorio

```git
git commit -m "el mensaje para agregar"
```
------------------------------
## Subiendo archivos al repositorio
```git
git push
```

para subir todo el master:
```git
git push --set-upstream origin master
```

