# Pomodoro
https://peterargueta.github.io/pomodoro/

Temporizador Pomodoro animado.
Un solo archivo HTML, sin dependencias, funciona en GitHub Pages.

---

## Ver en vivo
https://TU-USUARIO.github.io/pomodoro/

---

## Subir a GitHub Pages (paso a paso)

### 1. Crear repositorio en GitHub
- Ir a https://github.com
- Clic en "New repository"
- Nombre: pomodoro
- Dejarlo publico
- Clic en "Create repository"

### 2. Subir el archivo
Desde la terminal, en la carpeta donde esta este index.html:

    git init
    git add index.html README.md
    git commit -m "Pomodoro"
    git branch -M main
    git remote add origin https://github.com/TU-USUARIO/pomodoro.git
    git push -u origin main

(Reemplazar TU-USUARIO con tu usuario de GitHub)

### 3. Activar GitHub Pages
- Ir al repositorio en GitHub
- Clic en Settings
- En el menu izquierdo: Pages
- En "Branch" seleccionar: main
- Clic en Save

### 4. Abrir en el navegador
Esperar 1-2 minutos y abrir:
    https://TU-USUARIO.github.io/pomodoro/
---

