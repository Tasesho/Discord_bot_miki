# Discord Bot Miki

Este es un bot de Discord llamado **Miki**, creado para interactuar en servidores de Discord. Miki tiene varias funciones, incluyendo la capacidad de saludar, repetir mensajes y mostrar estadísticas de palabras repetidas en el canal.

## Requisitos

Para ejecutar este bot, necesitarás tener instalado Python 3.x y las siguientes dependencias:

```bash
pip install -r requirements.txt
```

También necesitarás un token de Discord, el cual debe ser configurado en el archivo .env  En la carpeta raiz de tu proyecto crea un archivo llamado ".env" que contenga el token de tu bot.

```bash
DISCORD_TOKEN=TU_TOKEN
```
importante, en el espacio de TU_TOKEN debe ir sin espacios ni al principio ni al final.

Cuando tengas tu Virtual enviorment listo (.env) ejecuta el bot en la consola de tu editor de codigo y escribe lo siguiente:

```bash
cd /d UBICACION_DE_TUPROYECTO
```
Esto te llevara a la carpeta raiz de tu proyecto en la consola.

Luego inicia el Vitual enviorment.
```bash
call venv\Scripts\activate
```
Luego inicia el bot.
```bash
python NOMBRE_DE_TU_ARCHIVO_BOT.py
```
Hasta aca iniciaria tu bot.
Recomiendo Utilizar un archivo .bat en tu escritorio que contenga lo mismo pero añadiendo una linea mas.
```bash
pause
```
Esta ultima linea hara que no se cierre automaticamente cuando encuentre un error, asi te permitira visualizar mejor los registros de la Terminal


## Comandos

Miki posee los siguientes comandos (Usando el prefijo "!")
- !historial: Muestra las 10 palabras más repetidas en los últimos 100 mensajes.
- !say: Repite el mensaje que le envíes.
- !gravity: Muestra un GIF de una canasta de bastekball.
- !presentarse: El bot se presenta a sí mismo.
- !talk: El bot te saluda con un mensaje aleatorio.
- !ayuda: Muestra los comandos disponibles.


## Disclaimer

Este es el Primer bot que hago, me ayude de plantillas ya existentes, algunos comandos los copie de bots ya existentes. Pero tambien tiene mi propio esfuerzo y hacia donde quiero guiar este bot, La idiea es que interactue con los usuarios por eso tiene tantos Triggers de texto y comando para hablar y mostrar GIF.
