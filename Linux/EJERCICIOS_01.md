# Ejercicios Prácticos de Linux (Ubuntu)

Este documento contiene 15 ejercicios prácticos para ayudarte a familiarizarte con los comandos básicos de Linux, especialmente en la distribución Ubuntu.

## Ejercicios

### 1. Navegación
- Crea una estructura de directorios:

mkdir -p mi_proyecto/modulo1/submodulo1

- Navega al directorio `submodulo1`.
- Regresa al directorio raíz usando `cd`.
- Regresa al directorio anterior usando `cd -`.

### 2. Gestión de Archivos
- Crea un archivo vacío llamado `lista_tareas.txt` dentro de `mi_proyecto`.
- Copia `lista_tareas.txt` a `lista_tareas_backup.txt` dentro del mismo directorio.
- Mueve `lista_tareas_backup.txt` al directorio `submodulo1` y renómbralo a `tareas_respaldo.txt`.
- Elimina `lista_tareas.txt`.

### 3. Contenido de Archivos
- Crea un archivo llamado `informacion.txt` y escribe algunas líneas de texto en él usando un editor de texto (nano, vim, etc.).
- Muestra el contenido de `informacion.txt` usando `cat`.

### 4. Búsqueda de Texto
- Dentro del archivo `informacion.txt`, busca la palabra "Ubuntu" (si existe) usando `grep`.

### 5. Permisos
- Crea un script ejecutable llamado `mi_script.sh`.
- Dale permisos de ejecución al script usando:

chmod +x mi_script.sh

- Verifica los permisos del script usando:

ls -l


### 6. Gestión de Paquetes
- Actualiza la lista de paquetes disponibles en tu sistema usando:

sudo apt update

- Instala un paquete básico, como `nano`, usando:

sudo apt install nano

- Remueve el paquete `nano` usando:

sudo apt remove nano


### 7. Información del Sistema
- Muestra el uso del espacio en disco usando:

df -h

- Lista todos los dispositivos USB conectados usando:

lsusb


### 8. Creación y manipulación de archivos
- Crea 3 archivos de texto (`archivo1.txt`, `archivo2.txt`, `archivo3.txt`).
- Escribe contenido diferente en cada archivo.
- Concatena los contenidos de los 3 archivos en un nuevo archivo llamado "archivo_final.txt".

### 9. Uso de comandos de búsqueda
- Crea varios archivos en diferentes directorios.
- Utiliza el comando `find` para buscar todos los archivos con la extensión ".txt".
- Utiliza el comando `grep` para buscar una palabra específica en todos los archivos .txt.

### 10. Manipulación de permisos
- Crea un script en bash llamado "script_ejemplo.sh".
- Asigna permisos de ejecución solo al propietario.
- Intenta ejecutar el script como otro usuario para verificar los permisos.

### 11. Redireccionamiento de entrada/salida
- Ejecuta un comando (por ejemplo, `ls -l`) y redirige la salida a un archivo llamado "listado.txt".
- Utiliza el comando `cat` para mostrar el contenido de "listado.txt".

### 12. Uso de variables de entorno
- Muestra el valor de la variable de entorno `HOME`.
- Crea una nueva variable de entorno llamada `MI_VARIABLE` y asigna un valor.
- Muestra el valor de la variable `MI_VARIABLE`.

### 13. Uso de tuberías (pipes)
- Utiliza el comando `ls -l` para listar los archivos en un directorio.
- Utiliza una tubería para pasar la salida del comando `ls -l` al comando `grep` y filtrar los archivos que contengan la palabra "texto".

### 14. Gestión de usuarios y grupos
- Crea un nuevo usuario en el sistema.
- Crea un nuevo grupo.
- Agrega el nuevo usuario al nuevo grupo.

### 15. Monitorización del sistema
- Utiliza el comando `top` para ver los procesos que consumen más recursos.
- Utiliza el comando `free -m` para mostrar el uso de la memoria RAM.

---

**Consejos Adicionales:**
* Utiliza `man comando` para obtener información detallada sobre cada comando.
* Experimenta con diferentes opciones y parámetros de los comandos.
* Busca tutoriales y ejemplos en línea para profundizar tus conocimientos.
* Practica regularmente para afianzar lo aprendido.

¡Buena suerte con tu práctica!

