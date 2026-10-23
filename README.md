# ekLibreELEC

EspaKodi para PC, Raspberry Pi y placas Amlogic. Por dentro es LibreELEC 12.2 con Kodi 21.3, ya configurado en español y con los addons y favoritos de EspaKodi listos desde el primer arranque. Se graba en un USB o en una tarjeta, se enciende el aparato y arranca directamente en Kodi.

Las imágenes se descargan desde [Releases](https://github.com/espakodi/ekLibreELEC/releases).

## Versiones

- [v0.0.2](https://github.com/espakodi/ekLibreELEC/releases/tag/v0.0.2), del 23 de octubre de 2026. Es la actual.

El nombre de cada archivo lleva la versión de LibreELEC (12.2), la de EspaKodi (0.0.2) y la fecha en que se construyó la imagen. Los enlaces de abajo son de la 0.0.2.

## Qué archivo descargar

Cada imagen vale solo para el aparato que indica su nombre. La de una Raspberry Pi 4 no arranca en una Pi 5, y la de una placa no sirve para otra.

### PC

| Para qué | Descarga |
|---|---|
| Probarlo en VirtualBox sin tocar tu ordenador | [EspaKodi-PC-VirtualBox.ova](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-PC-VirtualBox.ova) |
| Instalarlo en un PC | [EspaKodi-Generic.x86_64-12.2-0.0.2-20261022.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-Generic.x86_64-12.2-0.0.2-20261022.img.gz) |

Los dos llevan el mismo EspaKodi. Solo cambia la forma de arrancarlo.

### Raspberry Pi

| Placa | Descarga |
|---|---|
| Raspberry Pi 4 y Raspberry Pi 400 | [EspaKodi-RPi4.aarch64-12.2-0.0.2-20261017.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-RPi4.aarch64-12.2-0.0.2-20261017.img.gz) |
| Raspberry Pi 5 | [EspaKodi-RPi5.aarch64-12.2-0.0.2-20261021.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-RPi5.aarch64-12.2-0.0.2-20261021.img.gz) |

### TV box y placas Amlogic

Hay una imagen por placa. Busca la tuya en la tabla:

| Placa | Descarga |
|---|---|
| Banana Pi M2 Pro | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m2-pro.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m2-pro.img.gz) |
| Banana Pi M2S | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m2s.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m2s.img.gz) |
| Banana Pi M5 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m5.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-bananapi-m5.img.gz) |
| FriendlyElec NanoPi K2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-nanopi-k2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-nanopi-k2.img.gz) |
| Hardkernel Odroid C2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-c2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-c2.img.gz) |
| Hardkernel Odroid C4 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-c4.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-c4.img.gz) |
| Hardkernel Odroid HC4 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-hc4.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-hc4.img.gz) |
| Hardkernel Odroid N2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-n2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-odroid-n2.img.gz) |
| Khadas VIM | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim.img.gz) |
| Khadas VIM2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim2.img.gz) |
| Khadas VIM3 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim3.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim3.img.gz) |
| Khadas VIM3L | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim3l.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-khadas-vim3l.img.gz) |
| Libre Computer Alta (AML-A311D-CC) | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-alta.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-alta.img.gz) |
| Libre Computer La Frite (AML-S805X-AC) | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-lafrite.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-lafrite.img.gz) |
| Libre Computer Le Potato (AML-S905X-CC) | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-lepotato.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-lepotato.img.gz) |
| Libre Computer Solitude (AML-S905D3-CC) | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-solitude.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-solitude.img.gz) |
| Radxa Zero | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-radxa-zero.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-radxa-zero.img.gz) |
| Radxa Zero 2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-radxa-zero2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-radxa-zero2.img.gz) |
| WeTek Core 2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-wetek-core2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-wetek-core2.img.gz) |
| WeTek Play 2 | [EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-wetek-play2.img.gz](https://github.com/espakodi/ekLibreELEC/releases/download/v0.0.2/EspaKodi-AMLGX.aarch64-12.2-0.0.2-20261017-wetek-play2.img.gz) |

Si tienes uno de esos TV box genéricos que se venden con Android y no aparece en la tabla, ninguna de estas imágenes te vale. Para esos casos existe una imagen comodín, pero no se publica porque hay que adaptarla a mano al chip de cada caja y casi siempre hay que arrancarla pulsando el botón de recuperación con un palillo.

## Cómo se instala

### En VirtualBox

Abre VirtualBox, entra en Archivo > Importar servicio virtualizado, elige el `.ova` y pulsa Importar. Después arranca la máquina. No hace falta configurar nada más, porque ya trae su disco de 8 GB y la tarjeta gráfica que necesita.

### En un PC, una Raspberry Pi o una placa Amlogic

Para el PC necesitas un USB de 2 GB o más, y para las placas una microSD de 8 GB o más. Para grabarla vale cualquiera de estos dos programas, que abren el `.img.gz` tal cual, sin descomprimirlo:

- [balenaEtcher](https://etcher.balena.io/)
- [Raspberry Pi Imager](https://www.raspberrypi.com/software/). En «Sistema operativo» elige la última opción, «Usar personalizada», y busca el archivo.

Al grabar se borra todo lo que hubiera en el USB o en la tarjeta.

Cuando termine, puede que Windows diga que no puede leer la unidad y te ofrezca formatearla. Dile que no. Es normal, la unidad queda con un formato que Windows no entiende.

Luego, según el aparato:

- En un PC, arranca desde el USB. Aparece un menú que permite instalar EspaKodi en el disco del ordenador. Ten en cuenta que instalarlo borra lo que hubiera en ese disco.
- En una Raspberry Pi, mete la tarjeta y enchúfala.
- En una placa Amlogic, mete la tarjeta y enchúfala. Muchas tienen un interruptor o un botón para elegir que arranquen desde la tarjeta; si la tuya sigue encendiendo con su sistema de siempre, mira en su manual cómo se hace.

## El primer arranque

Tarda alrededor de un minuto, porque copia los addons y agranda la partición de datos. No lo apagues mientras tanto.

Primero sale la lista de Favoritos y, poco después, un asistente de bienvenida para poner la hora y conectarse a internet. Se pasa con Siguiente hasta el final y ya no vuelve a aparecer. A veces la primera vez se cierra solo, o no sale hasta el segundo arranque. No pasa nada; vuelve a salir y entonces se queda.

El SSH y el servidor web de Kodi vienen apagados, de modo que nadie de tu red puede entrar en el aparato. Si necesitas el SSH, el asistente lo pregunta en la página de compartir, y también se puede encender más tarde desde Configuración de EspaKodi.

## Actualizaciones

EspaKodi no busca versiones nuevas ni instala nada por su cuenta, así que no va a cambiar de un día para otro sin que tú hagas nada. Las versiones nuevas se publican aquí, en Releases.

No le grabes encima una actualización de LibreELEC descargada de su web. El sistema la acepta, porque solo comprueba que sea para el mismo tipo de aparato, pero borra todo lo de EspaKodi y te deja un LibreELEC normal en inglés. Tus addons, favoritos y ajustes se conservan; lo propio de EspaKodi se pierde.

## El registro de errores

Si usas Configuración de EspaKodi > Sistema > Enviar registro, el archivo se guarda en la carpeta compartida Downloads del propio aparato y no se manda a ningún sitio. Desde ahí lo puedes copiar por la red y pasárselo a quien quieras.

## Comprobar que la descarga está entera

Es opcional. Cada imagen tiene al lado, en Releases, un archivo `.sha256` con su huella, que sirve para saber si el archivo se ha cortado o estropeado al descargarlo.

En Windows, desde PowerShell:

```
Get-FileHash -Algorithm SHA256 <archivo>
```

El número que sale tiene que ser el mismo que el que hay dentro del `.sha256`.

En Linux, con los dos archivos en la misma carpeta:

```
sha256sum -c <archivo>.sha256
```

Si está bien, responde con un OK.

## Aviso legal

EspaKodi es una modificación no oficial de Kodi, el reproductor de la Fundación XBMC, montada sobre LibreELEC. No está desarrollada, afiliada, autorizada ni respaldada por la Fundación XBMC, ni por el equipo de Kodi, ni por el de LibreELEC. Kodi y LibreELEC son software libre bajo licencia GPL, y sus licencias van incluidas dentro de cada imagen.
