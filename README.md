# Ejercicio 1

Crear repo local:

En Shell ejecutar:

```
$ git init .
```


Ejecutar git status:

```
$ git status
```

Agregar archivo a git:

```
$ git add README.md
```

Configurar identificacion del desarrollador:

```

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

Hacer el primer commit

```
git commit -m "feat: agrega archivo README"
```

Después ejecutar git status

```
$ git status
```

Agregar archivo .gitignore con este contenido:

```
venv
```

O cualquier otra cosa que quieran ignorar

```
git commit -a -m "actualizar repo con .gitignore y README"
```

Nota: `git commit -a` es como hacer un add y un commit al mismo tiempo

# Ejercicio 2

Sincronizando repos

Actualizar el archivo README.md directamente en GitHub.

Luego hacer `git pull` en replit:
```
$ git pull origin master
```








