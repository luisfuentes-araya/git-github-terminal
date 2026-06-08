# 03 - Conectar proyecto local con GitHub

## Crear el remoto

Primero creas el repositorio en GitHub.

## Conectar el remoto

```bash
git remote add origin https://github.com/usuario/repositorio.git
```

Asocia tu proyecto local con el repositorio remoto.

## Ver remotos

```bash
git remote -v
```

Muestra las URLs conectadas.

## Subir por primera vez

```bash
git branch -M main
git push -u origin main
```

- `git branch -M main`: cambia la rama principal a `main`.
- `git push -u origin main`: sube la rama y deja el seguimiento configurado.
