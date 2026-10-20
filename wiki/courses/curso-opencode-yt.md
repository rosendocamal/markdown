---
title: Curso de Opencode con Brais Mouredev
type: notes
author: Rosendo Camal
school: YouTube
start: 2026-08-27
end: 2026-08-29
update: 2026-10-19
tags:
  - ai
  - tui
  - opencode
  - coding
  - programming
  - vibe-coding
  - course
---

# Curso de Opencode con Brais Mouredev

**El agente de codificación IA de código abierto.**

## Instalación de Opencode

Instalación mediante el script de instalación:

```bash
curl -fsSL https://opencode.ai/install | bash
```

Hay otras maneras de instalación, se puede consultar el sitio y la documentación oficial de **Opencode**.

## Guía de uso de Opencode

### Ingresar y salir de la TUI

Para ingresar a la TUI:

```bash
opencode
```

Para salir de la TUI, ingresamos en el prompt `/exit`.

En bash, podemos verificar la versión de la herramienta de la siguiente manera.

```bash
opencode -v
```

Para abrir una nueva sesión de la TUI, ingresamos en el prompt `/new`.

Dentro de la sesión de la TUI, podemos ingresar `/help` y se desplegará un menú indicando que debemos pulsar `Ctrl` más `p`. Si presionamos `Esc`, _escape_, para quitar el menú actual y pulsamos la combinación de teclas, nos abre una pestaña con una lista de atajos útiles para aprovechar las funcionalidades de **Opencode** mediante la rapidez de los atajos.

### Sesiones

Si queremos copiar la conversación, ingresamos `/copy`. En cambio, si queremos exportar la conversación utilizaremos `/export` y se desplegará un menú para personalizar la exportación de la conversación. También tenemos la opción de compartir la sesión de la TUI mediante `/share`.

Al salir de una sesión con `/exit`, en la terminal nos aparecerá una vista similar:

```bash
                                   ▄     
  █▀▀█ █▀▀█ █▀▀█ █▀▀▄ █▀▀▀ █▀▀█ █▀▀█ █▀▀█
  █  █ █  █ █▀▀▀ █  █ █    █  █ █  █ █▀▀▀
  ▀▀▀▀ █▀▀▀ ▀▀▀▀ ▀▀▀▀ ▀▀▀▀ ▀▀▀▀ ▀▀▀▀ ▀▀▀▀

  Session   Hola greeting
  Continue  opencode -s ses_faf95c95effeLsrCEcEIBXsVzo

```

Si en la terminal utilizamos el comando indicado nos devolverá a la sesión del que salimos.

```bash
opencoe -s ses_faf95c95effeLsrCEcEIBXsVzo
```

Otra manera de recuperar la sesión, dentro de la TUI, es ingresando en el prompt `/sessions` y nos abrirá un menú en el que podemos elegir la sesión de las sesiones guardadas.

> [!IMPORTANT]
> Las sesiones se pueden recuperar, con `/sessions`, siempre y cuando se inicie la TUI en la ruta, el directorio, en donde se inicializó la TUI con la sesión por primera vez.

Para ver estadísticas o métricas relacionadas con la cantidad de sesiones, uso de herramientas y tokens podemos usar:

```bash
opencode stats
```

### Modelos de inteligencia artificial

Para conectar un proveedor de modelo de inteligencia artificial en el prompt se debe ingresar `/connect`. Mientras que para usar un modelo se ingresa `/models` y se selecciona el deseado. De igual forma, podemos emplear el atajo de `Ctrl` + `x` y `m` para cambiar o seleccionar un modelo de IA.

En algunos modelos se puede cambiar la potencia del modelo usando el comando `/variants`, no está disponible en todos ya que depende del modelo.


Al usar un modelo de IA, utilizando el prompt, podemos ocultar y mostrar el razonamiento mediante el comando `/thinking`.

Podemos emplear `\timestamp` para obtener información de cuándo enviamos un prompt, en qué momento se ejecutó y poder tener más información del contexto de la sesión y el trabajo realizado.

Podemos emplear un arroba, `@`, y la dirección a un directorio o fichero en donde inicializamos la TUI y el proyecto y con ello indicarle mediante al modelo de IA alguna instrucción respecto a tal directorio o fichero.

### Agentes

Podemos cambiar los agentes con la tecla `tab` o con el comando `/agents`.

### Shell

En el prompt ingresamos `!` e inmediatamente veremos que tendremos habilitado el ingreso de comandos de terminal para poder ejecutarlos.

### Historial de cambios y apoyo de Git

Si en nuestra ubicación o proyecto tenemos Git podemos hacer uso de `/diff` para ver las diferencias implementadas.

De igual manera, tenemos `/review` para hacerle una revisión al proyecto y que nos comente al respecto un reporte.

Tenemos `/undo` para revertir un cambio realizado por el modelo de IA, pero tomando en cuenta el prompt anterior al actual y así sucesivamente cada vez que usemos `/undo`. Es decir, realizamos un regreso al mensaje, prompt, y al estado anterior cada vez que usamos este comando. Y para recuperar el cambio, es decir, regresar al cambio siguiente al actual, haremos uso de `/redo`.

Lo anterior se puede hacer de forma más controlada y específica usando `/timeline`. Este comando nos permite ir a un mensaje, prompt, específico y revertirlo, copiarlo o hacer _fork_ en una nueva sesión.

## Recursos adicionales

- [Sitio oficial de Opencode](https://opencode.ai/)
- [Documentación oficial de Opencode](https://opencode.ai/docs)
- [MCP Directory](https://mcp.directory/)
- [Context7](https://context7.com/)
- [The Agent Skills Directory](https://www.skills.sh/)
