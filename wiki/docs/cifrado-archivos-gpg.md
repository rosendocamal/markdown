---
title: Cifrado de archivos con gpg
author: Rosendo Camal
date: 2025-12-11
update: 2026-10-19
type: documentation
tags:
  - linux
  - encryption
  - security
  - gpg
  - shred
---

### Cifrado, descifrado y eliminado de archivo sensible

Para cifrar un archivo con `gpg`:

```bash
gpg -c FILENAME # Cambiar FILENAME por el archivo a cifrar
```

> [!NOTE]
> El comando anterior conservará el archivo original y creará otro con extensión `.gpg`.

Dado que el comando anterior no elimina el nuevo ejecutamos:

```bash
shred -u FILENAME # Cambiar FILENAME por el archivo original
```

> [!IMPORTANT]
> El comando `shred` borrar el archivo original de forma segura para que no haya fugas ni exposición de este.

Para recuperar (descifrar) el archivo encriptado se recurre a:

```bash
gpg -d FILENAME.gpg > FILENAME
```