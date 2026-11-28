# Práctica Git: 0 a 100 en micro-retos

¿Cómo usar esta lista? Marca cada tarea realizada ✔️. Si alguna te parece trivial, explícasela a un compañero.

¡Gana confianza paso a paso!

**Criterio:** HECHO incluye ejercicios equivalentes con otros nombres de ramas, archivos o carpetas. Las tareas sin confirmación suficiente quedan sin marcar.

## 🟢 Fundamentos y primeros comandos

1. [x] Instala Git en tu sistema operativo y verifica con `git --version`. — **HECHO** (Git ya instalado y utilizado).
2. [x] Configura tu usuario y correo con `git config --global user.name "Tu Nombre"` y `git config --global user.email "tu@email.com"`.
3. [x] Crea una carpeta `git-lab` y entra en ella. — **HECHO** (carpeta de prácticas equivalente).
4. [x] Inicializa un repositorio: `git init`. — **HECHO**.
5. [x] Añade un archivo `README.md` con tu nombre. — **HECHO** (README creado; contenido exacto no confirmado).
6. [x] Consulta el estado con `git status`. — **HECHO**.
7. [x] Añade el archivo al staging con `git add README.md`. — **HECHO**.
8. [x] Haz tu primer commit: `git commit -m "Primer commit"`. — **HECHO**.
9. [x] Modifica el `README.md` y observa los cambios con `git diff`.
10. [x] Haz otro commit con un mensaje diferente. — **HECHO**.
11. [x] Mira el historial de commits: `git log --oneline`.

## 🟡 Ramas y trabajo paralelo

12. [x] Crea una rama llamada `dev`: `git branch dev`. — **HECHO** (rama equivalente `experimentos`).
13. [x] Cámbiate a la rama `dev`: `git checkout dev`. — **HECHO** (rama equivalente).
14. [x] Edita el `README.md` y haz un commit en `dev`. — **HECHO** (práctica equivalente con otros archivos).
15. [x] Vuelve a `main` y comprueba que los cambios no están. — **HECHO** (práctica con `master`).
16. [x] Fusiona la rama `dev` con `main`: `git merge dev`. — **HECHO** (fusión de `experimentos` con `master`).
17. [x] Borra la rama `dev`: `git branch -d dev`.
18. [x] Prueba a crear una rama `experimento` y haz commits solo en esa rama. — **HECHO** (rama `experimentos`).

## 🟠 Conflictos y resolución

19. [x] Crea dos ramas nuevas: `a` y `b`. Modifica la misma línea en un archivo diferente en cada rama. (Se intentó una práctica equivalente; para provocar un conflicto de contenido debe modificarse la misma línea del mismo archivo en ambas ramas).
20. [x] Intenta fusionar `a` en `b` y provoca un conflicto.
21. [x] Abre el archivo en conflicto, resuelve las marcas `<<<<<<<`, `=======`, `>>>>>>>`.
22. [x] Finaliza el conflicto con `git add` y `git commit`.
23. [x] Consulta el historial con `git log --graph --all --oneline`.

## 🔵 Repositorios remotos y GitHub

24. [x] Crea una cuenta en GitHub si no la tienes. — **HECHO**.
25. [x] Crea un repositorio nuevo en GitHub llamado `proyecto-git`. — **HECHO** (repositorio de práctica equivalente).
26. [x] Conecta tu repo local con GitHub usando `git remote add origin https://github.com/TU-USUARIO/proyecto-git.git`. — **HECHO**.
27. [x] Sube tu código con `git push -u origin main`. — **HECHO**.
28. [x] Edita un archivo desde la web y luego actualiza localmente con `git pull`. — **HECHO**.
29. [x] Crea una rama `mejora`, haz commits y sube solo esa rama: `git push -u origin mejora`. — **HECHO**.
30. [x] Abre un Pull Request en GitHub para fusionar `mejora` en `main`. — **HECHO** (incluida la fusión desde GitHub).

## 🟣 Avanzado y bonus

31. [x] Clona un repositorio existente de GitHub: `git clone URL`.
32. [x] Crea y usa un `.gitignore` para excluir archivos temporales.
33. [x] Busca y elimina ramas locales y remotas.
34. [x] Recupera un archivo borrado usando `git checkout` o `git restore`.
35. [ ] Busca el commit en que se hizo un cambio usando `git log -p`.
36. [ ] Investiga qué es `git stash` y úsalo para guardar cambios temporales.
37. [ ] Haz un pequeño proyecto colaborativo con un compañero (pull, push, merge, conflictos reales).
38. [ ] Configura autenticación SSH y realiza un push seguro.
