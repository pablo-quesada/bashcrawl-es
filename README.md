# ¡Hola!

Este es un juego para enseñarte los conceptos básicos de cómo usar una terminal POSIX (Linux, BSD, UNIX).

**Nota**: esta es una traducción al castellano del proyecto original, disponible en
[GitLab](https://gitlab.com/slackermedia/bashcrawl).


## Pruébalo en tu PC

Para comenzar a jugar, abre una terminal.

Escribe las letras "cd " (solo las letras, no las comillas) en la terminal...

Escribe un espacio (presiona la barra espaciadora)...

Arrastra y suelta el directorio ``entrada`` de esta carpeta en tu terminal...

Si tu terminal te pregunta qué quieres hacer con lo que acabas de arrastrar, selecciona "Pegar ubicación".
Si no pregunta nada, debería aparecer pegada la ruta de acceso a la carpeta que acabas de arrastrar.

Una vez tengas algo tal que:

```
$ cd /home/tu_usuario/Descargas/bashcrawl/entrada
```

en la ventana de tu terminal, presiona la tecla _Enter_.
La ruta exacta a la ``entrada`` varía según en lugar dónde hayas guardado el archivo.

Tu primer movimiento es muy importante.
Escribe esto en tu terminal:

```
cat pergamino
```

y presiona _Enter_.

Ahora estás jugando.
Que los dioses te salven.


## Notas para macOS

Al descargar el juego desde la web de GitHub, en lugar de usar la función `clone` de git, hay un problema al hacer
doble click en el ZIP para extraerlo. En concreto, puede que todos los ficheros de la carpeta extraída estén
configurados para ser ejecutables. Esto será muy confuso al jugar, ya que los ficheros de texto plano serán
indistinguible de los scripts ejecutables.

Este problema puede evitarse de la siguiente manera:

1. Abre tu terminal favorita (por ejemplo, `Terminal.app` o `iTerm2`).
2. Navega hasta el directorio en el que quieres descomprimir el archivo ZIP:
    ```
    cd /ruta/a/directorio
    ```
    Reemplaza `/ruta/a/directorio` por la ruta relativa (no empieza por `/`) o absoluta (empieza por `/`) a tu
    destino deseado.
3.  Escribe `unzip ` (es decir, 'unzip' seguido de uno o más *espacios* [pulsa la barra espaciadora una o más veces]).
4.  Desde `Finder`, arrastra bashcrawl-master.zip a la ventana de tu terminal. La ruta absoluta hasta el fichero
    descargado debería aparecer en tu terminal, tal que:
    ```
    unzip /Usuarios/${USUARIO}/Descargas/bashcrawl-master.zip
    ```
5.  Presiona `Enter` para extraer los contenidos del fichero ZIP al directorio actual.
6.  En la terminal, desplázate al directorio `bashcrawl-master/entrada`:
    ```
    cd bashcrawl-master/entrada
    ```

¡Ya puedes comenzar a jugar! ¡Diviértete!
