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
ejemplo
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
```git
(muestra estados de como estan trackeados)
```
```git

git add 
(pasa al area de preparacion)
```


nos muestra la bitacora

-------- 1.7 aprendiendo a escribir commits
git commit
ahora presionamos "I" para insertar
escribimos fuera del texto
ponemos ESQ
:wq

y entrer y se creo un commit



-------2.1
/*/*/agregar un archivo actualizado
git add <nombrearchivo>

/*/*/ agregar todo el archivo actual stage
git add .

/*/*/ agregar todo lo de stage a repositorio
git commit -m "el mensaje para agregar"


