# Que hay !!

Si llegaste a este repositorio, es porque Z0SO estara encantado de que entres al servidor de Minecraft y es por eso que te va a explicar como hacerlo.

- ***IP del server***

```ip
<<<<<<< HEAD
decision-cop.gl.joinmc.link
=======
y-proportion.gl.joinmc.link
>>>>>>> 597dbb033a3d9d72a4dc29b6d2bbb50968c116e8
```


> **Nota**: Si tienes linux te recomiendo que clones este reposiotorio y borres todo el contenido de tu carpeta mods/ de .minecraft y crees un enlace simbolico apuntando a la carpeta mods/ de este repositorio.

Parate en este directorio y ejecuta los siguientes comandos:

```sh
sudo rm ~/.minecraft/mods/*
ln -s mods/ ~/.minecraft/mods
```

Esto creara un enlace simbolico en tu carpeta mods/ de .minecraft que apunta a la carpeta mods/ de este repositorio. Esto es util para que si hay cambios de mods en este repositorio, no tengas que estar copiando los mods a tu carpeta mods/ de .minecraft.

Simplemente descargas el .zip o haces un git pull y ya tienes los mods actualizados.


> **Nota**: Si tienes windows, simplemente copia los mods a tu carpeta mods/ de .minecraft.


## Requisitos
- **Minecraft Java Edition** (versión **1.20.1**)

# Pasos

### Descarga
Para facilitarte las cosas, he subido todos los archivos necesarios a Google Drive. Solo tienes que descargar un archivo zip que contiene el instalador de Forge y los mods necesarios.

> [Link de Descarga](https://drive.google.com/drive/folders/1ZZxfsMmwi2Hvgp9xwn98E5pwd0YvQRGp?usp=sharing "https://drive.google.com/drive/folders/1ZZxfsMmwi2Hvgp9xwn98E5pwd0YvQRGp?usp=sharing")

### Contenidos del zip
1. **Forge** (archivo `.jar`)
2. **Carpeta con los mods**

## Instalación

### Usuarios de Windows

1. **Extrae el zip** que descargaste.
2. **Doble clic en `Forge.jar`**: Se abrirá una ventana de instalación. Solo necesitas hacer clic en "Instalar".

3. **Crea la carpeta `mods`**:
    - Presiona la tecla `Windows` y escribe `%appdata%` en el campo de búsqueda.
    - Abre la carpeta `.minecraft`.
    - Dentro de `.minecraft`, crea una carpeta llamada `mods`.

4. **Copia los mods**: Pega todos los mods que estaban en el zip dentro de la carpeta `mods`.

### Usuarios de Linux

1. **Descomprime el zip** que descargaste.
2. **Abre una terminal** en el directorio donde está `forge.jar`.
3. **Ejecuta el siguiente comando** para instalar Forge:

    ```sh
    java -jar forge.jar
    ```

4. **Crea la carpeta `mods`**:
    - Navega hasta tu carpeta de usuario (`/home/usuario`) y abre la carpeta `.minecraft`.
    - Dentro de `.minecraft`, crea una carpeta llamada `mods`.

5. **Copia los mods**: Pega todos los mods que estaban en el zip dentro de la carpeta `mods`.

## ¡Listo!

Finalmente, abre el launcher de Minecraft de tu preferencia, selecciona el perfil de Forge.

> Nota: No olvides copiar la ip del server que esta en el Discord.

¡Nos vemos en el juego, si es que estoy viciando xD! 🎮✨
