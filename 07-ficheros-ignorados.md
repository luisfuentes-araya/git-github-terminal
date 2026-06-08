# 07 - .gitignore

Ejemplos típicos:

    node_modules/

    dist/

    .env

    *.log

¿Por qué es importante?

Porque no todo lo que existe en tu proyecto debe ir a GitHub.
Git solo debería guardar lo útil para reconstruir el proyecto, no basura generada automáticamente.

## ¿Qué es?

Es un archivo que le dice a Git qué archivos no debe seguir.

## Ejemplo

```txt
node_modules/
dist/
.env
*.log
```

## Para qué sirve

Evita subir archivos pesados, temporales o sensibles.
