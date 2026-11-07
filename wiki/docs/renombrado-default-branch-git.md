---
title: Configuración de Git cuando se renombra la rama pretedeterminada en GitHub
author: Rosendo Camal
date: 2025-11-06
update: 2026-11-06
type: documentation
tags:
  - git
  - github
  - branch
  - fetch
  - renamed-default-branch
  - default-branch
  - remote
---
# Configuración de Git cuando se renombra rama principal en GitHub

Se emplea los siguientes comandos cuando se renombra la rama principal del repositorio. En la copial local, para actualizar se requiere correr:

```bash
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```