# Cheatsheet GIT


------------------------------
## Ayuda en git
```git
sarasa --help
```


------------------------------
## crear repositorio 
```git
git init
```


(muestra estados de como estan trackeados)

```git

git add 
```
(pasa al area de preparacion)

------------------------------
## Estados en git
```git
git status 
```


nos muestra la bitacora

Mostrar el log de datos del git
```git
git log
```

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


```git
git commit -m "el mensaje para agregar"
```
------------------------------
## Agregando archivos que se van a enviar
```git
git add <nombrearchivo>
```

### agregar todo el archivo actual stage

```git
git add .
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

------------------------------
## Configuración para GITHUB

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

### creando keygen (en linux)
```git
Ssh-keygen -t rsa -b 4096 -C FRASEUNICA
```
Buscamos donde esta creada la ssh
```git
Cd ~/.ssh!
```

probamos si está todo ok la ssh:
```git
eval"$(ssh-agent -s)"
```

```git
ssh-add ~/.ssh/id_rsa
```

instalaremos xclip (linux)
```git
sudo apt install xclip
```
Edutaremos el archivo y agregaremos la SSH y GPG key antes creada:
```git
xclip -selection clipboard < ~/.ssh/id_rsa.pub
```

