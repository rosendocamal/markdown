---
title: Primeros pasos con Fedora
author: Rosendo Camal
date: 2025-12-11
update: 2026-10-19
type: documentation
tags:
  - linux
  - fedora
  - installation
---

# MIS PRIMEROS PASOS CON FEDORA

## Actualización de Fedora

Antes de configurar Fedora actualizamos todo:

```bash
sudo dnf upgrade --refresh -y
```

Esto evitará conflictos de paquetes y errores al instalar software.

> [!NOTE]
> El comando `dnf upgrade` ya hace el trabajo de `update` y `clean all` no es estrictamente necesario al inicio.

## Instalación de programas

Una vez hecho lo anterior paso a instalar programas con el comando `sudo dnf install [program] -y`.

Ejemplo de programas a instalar son `ranger`, `neovim`, `git`, `chromium` y `tmux`.

```bash
sudo dnf install ranger neovim git chromium tmux -y
```

> [!TIP]
> En la tabla siguiente se muestran algunos programas que podrían ser útiles, se debe consultar primero como realizar la instalación de cada uno. Recuerde instalar las aplicaciones que solo vayas a usar.

| Aplicación         | Descripción                                                               |
| ------------------ | ------------------------------------------------------------------------- |
| Visual Studio Code | Editor de código desarrollado por Microsoft.                              |
| Neovim             | Editor de código basado en terminal.                                      |
| Fresh              | Editor de código de terminal con atajos de VSC.                           |
| Warp               | Emulador de terminal.                                                     |
| Bitwarden          | Gestor de contraseñas.                                                    |
| btop++             | Administrador de tareas con visualización mejorada respecto a htop y top. |
| Oracle VirtualBox  | Virtualizador de sistemas operativos.                                     |
| MySQL              | Bases de datos.                                                           |
| Docker             | Contenedores.                                                             |
| Opencode           | Agente para desarrollo con IA.                                            |
| Hermes             | Harness para desarrollo con IA.                                           |
| LaTeX              | Procesador de textos para artículos científicos y documentos académicos.  |
| Python             | Lenguaje de programación versátil.                                        |
| Obsidian           | Notas en formato markdown.                                                |
| OBS Studio         | Grabación y generación de vídeo.                                          |
| Blender            | Generación de renderizado 3D y más.                                       |
| Krita              | Dibujo 2D.                                                                |
| Inkscape           | Dibujo vectorial.                                                         |