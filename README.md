# git practica 2
Taller GIT. Práctica 2.
Guarda los comandos realizados, así como los resultados(capturas), integrarlo dentro del mismo repositorio

# Preguntas y Respuestas Git

## ¿Qué sucede cuando hacemos un git add?

El comando git add agrega los archivos modificados al área de preparación (stage), dejándolos listos para ser confirmados con un commit.

---

## ¿Qué sucede cuando hacemos un git commit? ¿Dónde está ese commit?

El comando git commit guarda una versión de los cambios realizados en el repositorio local. El commit se almacena en el historial del repositorio Git dentro de nuestra computadora.

---

## ¿Por qué al hacer git commit todavía no está disponible ese commit en el repositorio remoto?

Porque el commit solamente se guarda en el repositorio local y aún no se ha enviado al servidor remoto.

---

## ¿Qué hay que hacer para que veamos este commit en nuestro repositorio remoto de github?

Debemos utilizar el comando git push para enviar los cambios al repositorio remoto de GitHub.

---

## ¿Qué diferencia hay entre hacer un fork o crear una nueva rama?

Un fork crea una copia completa de un repositorio en otra cuenta de GitHub, mientras que una rama crea una línea de trabajo separada dentro del mismo repositorio.

---

## ¿Qué comando se utiliza para crear una nueva rama sin cambiarte a ella?

```bash
git branch nombre-rama
```

---

## ¿Cuál es la diferencia entre los comandos git switch y git checkout al trabajar con ramas?

git switch se utiliza específicamente para cambiar entre ramas, mientras que git checkout también puede usarse para restaurar archivos y otras funciones.

---

## ¿Qué es una rama por defecto (como main o master) y por qué es importante?

Es la rama principal del proyecto donde normalmente se encuentra la versión estable del código.

---

## ¿Qué comando te permite ver la lista de todas las ramas locales de tu repositorio?

```bash
git branch
```

---

## En el contexto de Git, explica con tus propias palabras qué es una rama (branch) y cuál es su beneficio principal al trabajar en un proyecto de software

Una rama es una copia independiente del proyecto que permite trabajar en nuevas funciones o cambios sin afectar la versión principal.

---

## ¿Qué ha pasado con el contenido de la carpeta practica-taller-git? ¿Por qué no la podemos ver en nuestro repositorio remoto de github?

No aparece porque ese proyecto local no fue conectado ni subido al repositorio remoto donde trabajamos el fork.
