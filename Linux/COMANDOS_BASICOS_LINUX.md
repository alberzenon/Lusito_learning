# Comandos Básicos de Linux para Ubuntu

Este `README.md` proporciona una referencia rápida a los comandos básicos de Linux más utilizados en la distribución Ubuntu.

## Tabla de Contenidos

- [Navegación](#navegacion)
- [Gestión de Archivos y Directorios](#gestion-de-archivos-y-directorios)
- [Permisos](#permisos)
- [Gestión de Paquetes](#gestion-de-paquetes)
- [Información del Sistema](#informacion-del-sistema)
- [Otros Comandos Útiles](#otros-comandos-utiles)

## Navegación

| Comando | Descripción | Ejemplo |
|---|---|---|
| `pwd` | Imprime el directorio de trabajo actual. | `pwd` |
| `ls` | Lista los archivos y directorios en el directorio actual. | `ls -lha` (lista detallada, incluye archivos ocultos, tamaños legibles) [1] |
| `cd` | Cambia el directorio actual. | `cd /home/usuario/Documentos` |
| `cd ..` |  Mueve un directorio hacia arriba. | `cd ..` [1]|
| `cd ~` |  Va al directorio personal del usuario actual. | `cd ~` |
| `cd -` |  Vas al directorio anterior en el que estabas. | `cd -` [4]|

## Gestión de Archivos y Directorios

| Comando | Descripción | Ejemplo |
|---|---|---|
| `mkdir` | Crea un nuevo directorio. | `mkdir NuevoDirectorio` [4] |
| `rmdir` | Elimina un directorio vacío. | `rmdir DirectorioVacio` [4] |
| `touch` | Crea un archivo vacío. | `touch nuevo_archivo.txt` [1][2] |
| `cp` | Copia archivos o directorios. | `cp archivo.txt copia_archivo.txt` [3][5] |
| `mv` | Mueve o renombra archivos o directorios. | `mv archivo.txt nuevo_nombre.txt` [2][3] |
| `rm` | Elimina archivos o directorios. | `rm archivo.txt` (elimina un archivo) [3] `rm -r Directorio` (elimina un directorio y su contenido)|
| `file` | Determina el tipo de archivo. | `file archivo.txt` [1]|
| `cat` | Muestra el contenido de un archivo. | `cat archivo.txt` [2][3]|

## Permisos

| Comando | Descripción | Ejemplo |
|---|---|---|
| `chmod` | Modifica los permisos de archivos y directorios. | `chmod +x script.sh` (agrega permiso de ejecución) [5] |
| `chown` | Cambia el propietario de un archivo o directorio. | `chown usuario:grupo archivo.txt` [5] |

## Gestión de Paquetes

| Comando | Descripción | Ejemplo |
|---|---|---|
| `sudo apt update` | Actualiza la lista de paquetes disponibles. | `sudo apt update` |
| `sudo apt upgrade` | Actualiza los paquetes instalados a la última versión. | `sudo apt upgrade` |
| `sudo apt install` | Instala un nuevo paquete. | `sudo apt install nombre_del_paquete` |
| `sudo apt remove` | Remueve un paquete instalado. | `sudo apt remove nombre_del_paquete` |

## Información del Sistema

| Comando | Descripción | Ejemplo |
|---|---|---|
| `df` | Muestra el uso del espacio en disco. | `df -h` [3]|
| `dmesg` | Imprime el buffer del kernel. | `dmesg` [3]|
| `lspci` | Lista todos los dispositivos PCI. | `lspci` [3]|
| `lsusb` | Lista todos los dispositivos USB. | `lsusb` [3]|
| `lsmod` | Muestra los módulos del kernel cargados. | `lsmod` [3]|

## Otros Comandos Útiles

| Comando | Descripción | Ejemplo |
|---|---|---|
| `sudo` | Ejecuta un comando con privilegios de superusuario. | `sudo apt update` [1][3][6]|
| `grep` | Busca patrones de texto dentro de archivos. | `grep "texto_a_buscar" archivo.txt` [3]|
| `man` | Muestra el manual de un comando. | `man ls` |
| `help` | Muestra la ayuda de un comando. | `comando -help` [1]|

---

**Nota:**  Este es un resumen básico. Para obtener información más detallada sobre cada comando, se recomienda consultar el manual (`man comando`) o utilizar la opción de ayuda (`comando --help`).
