# Guía para Clonar el Repositorio y Crear una Rama en GitHub Desktop

Este documento explica cómo clonar el repositorio y crear una rama con tu nombre utilizando la aplicación **GitHub Desktop**.

---

## 🧩 Requisitos Previos

Asegúrate de tener instalada la aplicación [GitHub Desktop](https://desktop.github.com/) y haber iniciado sesión con tu cuenta de GitHub.

---

## 🔁 Paso 1: Clonar el Repositorio

1. Abre **GitHub Desktop**.
2. En la barra superior, haz clic en **"File"** → **"Clone repository..."**.
3. Selecciona la pestaña **"URL"**.
4. En el campo de URL, pega la siguiente dirección: https://github.com/Barghest01/Game.git

5. Elige la carpeta donde quieres guardar el repositorio.
6. Haz clic en **"Clone"**.

---

## 🌿 Paso 2: Crear una Nueva Rama

1. Asegúrate de que el repositorio `Game` esté abierto en GitHub Desktop.
2. En la parte superior, haz clic en el desplegable de ramas (probablemente dice `main`).
3. Selecciona **"New Branch"**.
4. Escribe tu nombre como nombre de la rama (por ejemplo: `juan-perez`).
5. Haz clic en **"Create Branch"**.
6. Comienza a trabajar en esa rama.

---

## ☁️ Paso 3: Subir tu Rama a GitHub

1. Una vez que hayas hecho cambios y *commits* en tu rama, verás un botón azul que dice **"Publish branch"**.
2. Haz clic en **"Publish branch"** para subir tu rama al repositorio remoto.

---

## 🔀 Paso 4: Fusionar tu Rama en `main` (Squash and Merge)

1. En GitHub Desktop, cambia a la rama `main` usando el desplegable de ramas.
2. Una vez estés en `main`, haz clic de nuevo en el desplegable de ramas y selecciona **"Choose a branch to merge into main..."**.
3. En la lista, selecciona tu rama.
4. Se mostrará un resumen de los cambios.
5. En la parte inferior, asegúrate de seleccionar la opción **"Squash and merge"**.
6. Haz clic en **"Merge into main"**.

---

## 🔄 Paso 5: Hacer Pull Después del Merge

1. Asegúrate de seguir en la rama `main`.
2. Haz clic en **"Fetch origin"** y luego en **"Pull origin"** para asegurarte de que tu repositorio local tenga la última versión de `main` después del merge.

---

## 🧠 Recomendación: Mantén tu Rama Actualizada

Para mantener tu rama al día con los últimos cambios en `main`:

1. Cambia a la rama `main`.
2. Haz clic en **"Fetch origin"** y luego en **"Pull origin"** si hay cambios nuevos.
3. Cambia nuevamente a tu rama personal.
4. Ve a **"Branch"** → **"Update from main"**.

Esto integrará los últimos cambios del repositorio principal en tu rama de trabajo.

---
