# Minecraft Developer Test

Esta prueba ha sido creada para evaluar tus habilidades como desarrollador de Daynocraft.

Lea el siguiente documento.

**Puedes ver tutoriales o información pero evitalo si puedes**

# Requisitos

1. Ordenador/PC/Laptop con Windows
2. Java 17 Instalado

_¿No tienes Java 17 instalado?_ [Descargalo aquí]("https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html")

## Preparación

1. Descarga la ultima Release del repositorio de Github.

IMAGEN

2. Descomprime el archivo descargado si hace falta.

3. Ejecuta el archivo start.bat

![Imagen start.bat](https://raw.githubusercontent.com/Planeta110/Mincraft-Developer-Test/main/imgs/startbat.png)

4. Acepta el EULA si no esta aceptado

5. Se generaran los archivos necesarios automaticamente al ejecutar el start.bat

6. Podras acceder al servidor desde esta ip: localhost:25565

**Los plugins a configurar ya vienen en la carpeta descargada**

## ¿Que hay que hacer?

Instala Player en el plugin de PlaceHolderApi _/papi ecloud download Player_

1. CommandPanels

   1. Configura CommandPanels al idioma español.
   2. Añade el tag o prefijo `&b&lDaynocraft`.
   3. Crea un panel (no copies uno ya hecho) con el comando `/commandpanelgenerate <número de líneas de inventario>`.
   4. El panel debe parecerse a este:
      - Titulo del panel: Social and Rewards panel
      - La cabeza del jugador debe mostrar tu nombre de Minecraft.
      - El corazón del mar debe mostrar "DISCORD" y, al hacer clic, debe enviar un mensaje al usuario con información.
      - La antorcha de redstone debe mostrar "TIENDA" y también debe enviar un mensaje al usuario.
      - El bloque de redstone debe hacer lo mismo.
      - Los cristales tintados **no deben realizar ninguna función**.

      ![Imagen social](https://raw.githubusercontent.com/Planeta110/Mincraft-Developer-Test/main/imgs/social.png)

2. LuckPerms
    1. Crea un rango 
        - Nombre del rango: REY
        - Permisos: FLY, NEAR, 
        - Padre de: Default "/lp group rey parent set default"