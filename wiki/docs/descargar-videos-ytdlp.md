---
title: Descarga de vídeos con YT-DLP
author: Rosendo Camal
date: 2026-10-18
update: 2026-10-19
type: documentation
tags:
  - python
  - yt-dlp
  - videos
  - linux
---

# DESCARGA DE VÍDEOS CON YT-DLP

## Objetivo

Descargar vídeos de plataformas de internet utilizando la herramienta `yt-dlp`.

## Uso

Obtenga la URL del vídeo a descargar e ingrese a la terminal de su preferencia.

Posteriormente, ingresa el ulterior comando reemplazado el término `URL` por la URL correspondiente.

```bash
yt-dlp -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]" "URL"
```

## Resultado esperado

Se iniciará la descarga en la ubicación en la que se ejecutó el comando, una vez terminado la descarga de su vídeo puedo finalizar el comando con `CRTL + C` si empieza a descargar más vídeos (según la plataforma). 