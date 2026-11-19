---
title: Keyboard shortcuts for Linux Terminal
author: Rosendo Camal
date: 2026-11-19
type: documentation
tags:
  - linux
  - keyboard
  - shortcuts
  - terminal
  - bash
---
# Keyboard shortcuts for Linux Terminal

## Navegación y movimiento del cursor

| Atajo o Tecla | Descripción |
| :--- | :--- |
| `Ctrl` + `A`; o `Inicio` | Mueve el cursor al inicio de la línea. |
| `Ctrl` + `E`; o `Fin` | Mueve el cursor al final de la línea. |
| `Ctrl` + `F` | Avanza un carácter. |
| `Ctrl` + `B` | Retrocede un carácter. |
| `Alt` + `F` | Avanza una palabra hacia adelante. |
| `Alt` + `B` | Retrocede una palabra hacia atrás. |

## Edición y borrado de texto

| Atajo o Tecla | Descripción |
| :--- | :--- |
| `Ctrl` + `D` | Elimina un carácter hacia adelante. |
| `Ctrl` + `H` | Elimina un carácter hacia atrás. |
| `Ctrl` + `T` | Intercambia la posición de dos letras. |
| `Alt` + `T` | Intercambia la posición de dos palabras. |
| `Ctrl` + `U` | Borra todo desde la posición actual del cursor hacia el inicio de la línea. |
| `Ctrl` + `K` | Borra todo desde la posición actual del cursor hacia el final de la línea. |
| `Ctrl` + `W` | Borra la palabra anterior al cursor. |
| `Alt` + `D` | Borra la palabra siguiente al cursor. |
| `Ctrl` + `Y` | Pega el último texto que borraste con los comandos anteriores. |
| `Ctrl` + `_` | Deshace el último cambio. |

## Historial y búsqueda de comandos

| Atajo o Comando | Descripción |
| :--- | :--- |
| `Tab` | Autocompletado. |
| `Ctrl` + `P` | Cambia al comando anterior. |
| `Ctrl` + `N` | Cambia al comando siguiente. |
| `↑` o `↓` | Navega por los comandos ejecutados anteriormente. |
| `!!` | Ejecuta el último comando. |
| `Ctrl` + `R` | Abre la búsqueda inversa. Empieza a escribir y la terminal buscará en el historial el comando que coincide. |
| `Ctrl` + `G` | Sale del modo de búsqueda inversa. |
| `Ctrl` + `O`; o `Enter` | Ejecuta un comando. |

## Control de pantalla y procesos

| Atajo o Comando | Descripción |
| :--- | :--- |
| `Ctrl` + `L` | Limpia la pantalla. |
| `Ctrl` + `S` | Detiene la salida de pantalla (congelar pantalla). |
| `Ctrl` + `Q` | Reanuda la salida en pantalla (descongelar). |
| `Ctrl` + `C` | Detiene y cancela el comando que se está ejecutando de forma inmediata. |
| `Ctrl` + `Z` | Pausa el proceso actual y lo manda al fondo (suspender). |
| `fg` | Reanuda el proceso del anterior comando (primer plano). |
| `bg` | Manda el programa al segundo plano. |
| `Ctrl` + `D` | Cierra la terminal *(cuando la línea está vacía)*. |

## Manual de comandos

* `tldr` o `man` $\rightarrow$ *Ayuda rápida o manual de comandos.*