# 05 - Ramas en Git
Ejemplo simple:

    Estás trabajando en tu proyecto.

    Quieres agregar login.

    Creas una rama llamada login.

    Haces todos los cambios ahí.

    Si funciona, la unes con main.

    Si sale mal, no rompiste el proyecto principal.

## Crear una rama

```bash
git branch nueva-rama
```

Crea una rama nueva.

## Cambiarse a una rama

```bash
git checkout nueva-rama
```

O también:

```bash
git switch nueva-rama
```

## Crear y cambiar al mismo tiempo

```bash
git checkout -b nueva-rama
```

## Ver ramas

```bash
git branch
```

## Fusionar ramas

```bash
git merge nueva-rama
```

Une los cambios de una rama con otra.
