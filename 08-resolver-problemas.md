# 08 - Problemas comunes

## Repositorio remoto ya existe

```bash
git remote remove origin
git remote add origin URL
```

## Quedó un commit mal escrito

```bash
git commit --amend -m "nuevo mensaje"
```


En palabras simples:

    Modified = cambió, pero aún no lo has preparado.

    Staged = ya está listo para guardarse en el commit.

    Committed = ya quedó guardado como versión.


    Staging
es una zona intermedia antes del commit.


## Quiero deshacer staging

```bash
git restore --staged archivo.txt
```

## Quiero ver historial

```bash
git log
```
