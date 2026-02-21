# iue-prog-web2

## 📌 Descripción del Proyecto

Repositorio correspondiente a la asignatura **Programación Web II (IF2003)**.

El objetivo de este proyecto es aplicar los conceptos de control de versiones utilizando Git y la plataforma GitHub como repositorio remoto, simulando un entorno real de desarrollo colaborativo.

Durante el laboratorio se implementaron buenas prácticas como el uso de ramas para el desarrollo de funcionalidades, integración de cambios mediante merge, resolución de conflictos y recuperación de versiones anteriores del proyecto.

---

## 👥 Integrantes

- Danilo Ramírez Pérez  
- Esteban Páez Castrillón  
- Luis David Correa Riofrío  

---

## 🛠️ Tecnologías Utilizadas

- HTML5  
- Git  
- GitHub  

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

git clone https://github.com/Danilo062603/iue-prog-web2.git

2. Ingresar a la carpeta del proyecto:

cd iue-prog-web2

3. Abrir el archivo `index.html` en el navegador.

---

## 🌿 Ramas creadas

- main  
- feat-header  
- feat-footer  

---

## 🔄 Flujo de trabajo utilizado

- Inicialización del repositorio con `git init`.
- Creación de ramas para nuevas funcionalidades.
- Desarrollo en ramas independientes.
- Integración de ramas a `main` mediante `git merge`.
- Resolución manual de conflictos.
- Uso de `git revert` y `git restore`.
- Sincronización con el repositorio remoto usando `git push` y `git pull`.

---

## ⚠️ Evidencia de conflicto resuelto

Se presentó un conflicto al modificar la misma línea del archivo `index.html` en distintas ramas.

Git marcó el conflicto de la siguiente forma:

<<<<<<< HEAD
Contenido rama actual
=======
Contenido otra rama
>>>>>>> nombre-rama

El conflicto fue resuelto manualmente eliminando las marcas y dejando el contenido correcto. Luego se realizó el commit correspondiente para registrar la solución.

---

## 🔁 Recuperación de versiones

Durante el laboratorio se aplicaron:

- `git restore index.html` para recuperar cambios no confirmados.
- `git revert HASH` para deshacer un commit sin eliminar el historial.

---

## 📜 Comandos fundamentales utilizados

- git init  
- git status  
- git add  
- git commit  
- git branch  
- git checkout -b  
- git merge  
- git pull  
- git push  
- git revert  
- git restore  

---

## ✅ Entregable Final

El repositorio contiene:

✔ Mínimo tres ramas creadas  
✔ Ramas integradas correctamente en `main`  
✔ Evidencia de resolución de conflicto  
✔ Uso de revert o restore  
✔ Historial con commits descriptivos  
✔ README estructurado profesionalmente  

docs: mejorar estructura del README
