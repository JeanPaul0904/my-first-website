# Git y Github

## Comprobar de que Git este instalado

```
git -v
git version 2.38.1.windows.1
```

## Congifuracion global

```
git config --global user.name "jhon doe"
git config --global user.email "example@example.com"
```

## Crear un repositorio Github

## Inicializar git

```
git init
```

## Enlazar nuestro repositorio remoto

```
git remote add origin "https://github.com/JeanPaul0904/my-first-website"
```

## Definir la rama principal

```
git branch -M main
```

## Subir los cambios

```
git add --all
git commit -m "my first commit"
git push origin main
```