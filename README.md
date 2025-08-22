# MAOH_GithubRamas

Ejercicio semanal: Gitflow + algoritmo en PSeInt para mostrar números pares del 1 al 100.

## Archivos
- `Pares_1_a_100.psc`: algoritmo en PSeInt.

## Cómo ejecutar en PSeInt
1. Abre PSeInt → **Archivo > Abrir** → selecciona `Pares_1_a_100.psc`.
2. Presiona **F9** (o clic en **Ejecutar**) para ver la salida (2, 4, 6, ..., 100).

## Flujo Git (opción con CLI)
```bash
# 1) Clonar (o crear repo vacío en GitHub y conectarlo)
git clone <URL-de-tu-repo> MAOH_GithubRamas
cd bootcampES4

# 2) Crear rama develop
git checkout -b develop

# 3) Copiar el archivo .psc a la carpeta del repo (si no está ya)
#    (este README y el .psc ya están listos para subir)

# 4) Commit & push en develop
git add .
git commit -m "feat: algoritmo PSeInt pares 1..100"
git push -u origin develop

# 5) Crear Pull Request en GitHub: develop -> main y hacer merge
```

## Flujo Git (solo desde GitHub web)
1. Crea el repo en GitHub llamado **MAOH_GithubRamas**.
2. En la pestaña **Code**, cambia a la rama **develop** (Create branch: `develop`).
3. Sube `Pares_1_a_100.psc` y este `README.md` en la rama **develop**.
4. Ve a **Pull requests > New pull request**: `base: main` ← `compare: develop` y **Merge**.
