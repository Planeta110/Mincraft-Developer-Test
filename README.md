# Minecraft Developer Test

Esta prueba ha sido creada para evaluar tus habilidades como desarrollador de Daynocraft.

Lee el siguiente documento.

**Puedes ver tutoriales o buscar información, pero evítalo si puedes.**

---

# Requisitos

1. Ordenador/PC/Laptop con Windows.
2. Java 17 instalado.

_¿No tienes Java 17 instalado?_ [Descárgalo aquí](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

---

## Preparación

1. Descarga la última release del repositorio de GitHub.  
   (IMAGEN AQUÍ)

2. Descomprime el archivo descargado si es necesario.

3. Ejecuta el archivo `start.bat`.

   ![Imagen start.bat](https://raw.githubusercontent.com/Planeta110/Mincraft-Developer-Test/main/imgs/startbat.png)

4. Acepta el EULA si aún no está aceptado.

5. Se generarán los archivos necesarios automáticamente al ejecutar `start.bat`.

6. Podrás acceder al servidor desde esta IP: `localhost:25565`.

**Los plugins a configurar ya vienen en la carpeta descargada.**

---

## ¿Qué hay que hacer?

Instala **Player** en el plugin PlaceholderAPI con el comando:  
`/papi ecloud download Player`

---

### 1. CommandPanels

1. Configura CommandPanels al idioma español.
2. Añade el tag o prefijo: `&b&lDaynocraft`
3. Crea un panel (no copies uno ya hecho) con el comando:  
   `/commandpanelgenerate <número de líneas de inventario>`
4. El panel debe parecerse a este:

   - **Título del panel**: Social and Rewards panel
   - La **cabeza del jugador** debe mostrar tu nombre de Minecraft.
   - El **corazón del mar** debe mostrar "DISCORD" y, al hacer clic, debe enviar un mensaje al usuario con información.
   - La **antorcha de redstone** debe mostrar "TIENDA" y también debe enviar un mensaje al usuario.
   - El **bloque de redstone** debe hacer lo mismo.
   - Los **cristales tintados** **no deben realizar ninguna función**.

   ![Imagen social](https://raw.githubusercontent.com/Planeta110/Mincraft-Developer-Test/main/imgs/social.png)

---

### 2. LuckPerms

1. Crea un rango:
   - **Nombre del rango**: REY
   - **Permisos**: `fly`, `near`
   - **Padre del grupo**: Default  
     Comando: `/lp group rey parent set default`
