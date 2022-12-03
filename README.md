#NOTA: El repositorio se encontrara en constante modificación hasta el día de entrega.

# Command-List
Command List for Linux (Ubuntu, Manjaro, Docker, etc.) through VirtualBox 6

| Commando  | Descripción | Sintaxis |
| ------------- | ------------- | ------------- |
| `sudo` | Permite ejecutar cualquier programa como administrador  | `sudo su` y `sudo -i` para pasar a modo administrativo/root, `sudo <comando>` para darle permisos de ejecucion a un comando o programa.  |
| `ls`  | Muestra la lista de archivos y carpetas del directorio actual, imprime en pantalla las lista de las carpetas y archivos de la carpeta actual |  `ls -l` imprime los archivos en un formato de lista, `ls -a` imprime los archivos tanto visibles como ocultos  |
| `/` | "Madre de carpetas", dentro de lash estan dentros todas las carpetas del sistema operativo |  La ruta de todos los directorios empiezan con `/`  |
| `pwd` | Muestra la ruta de un archivo, carpeta, o donde uno esta posicionado  |  `pwd <opcion: -L o -P>` para encontrar la ruta en el dicrectorio que uno se encuentra actualmente.  |
| `clear`  | Limpia la terminal, se elimina todo el contenido de la pantalla  |  Solo se necesita ejecutar `clear` sin ningun comando o condicion para limpiar la terminal  |
| `cd` | Change direction/cambiar directorio  |   `cd <ruta>` se usa para cambiar de un directorio a otro, mientras que `cd ..` es para devolverse |
| `nano` | Crea documentos, editor de texto en consola |  `nano <nombre archivo>.txt` es para crear o editar achivos de texto. Este comando se puede usar para crear archivos de otros formatos (ej. *.sh, *.ps1)  |
| `cat` | Imprime el contenido del archivo, se utiliza para visualizar el contenido de un archivo  |  `cat <nombre archivo>.txt` se usa para imprimir en terminal el contenido de un archivo de texto  |
| `mkdir` | Crea carpetas/directorios nuevas |  `mkdir <nombre carpeta/directorio>` se usa para crear un directorio/carpeta en la ubicacion donde se encuentra, `mkdir <nombre carpeta/directorio> <ruta>` se usa para crear un carpeta/directorio en una ubicacion especifica |
| `rm` | Eliminar archivos dentro de un directorio | `rm <nombre archivo>.txt` se usa para eliminar un archivo. Nota: hay que escribir el formato al final para eliminar el correcto. `rm <nombre archivo>.* -R` se utiliza para eliminar de manera recursiva  |
| `top` | Ver el administrador de procesos en una terminal interactiva. |  Solo se necesita ejecutar `top` para visualizar los procesos. Para salir del administrador de procesos: *Ctrl + C*   |
| `htop` | Ver administrador de procesos con colores en una terminal interactiva.  |  Comando para su instalacion: `sudo apt install htop`. Ejecutar `htop <opciones>` para visualizar los procesos. Para salir del administrador de procesos: *Ctrl + C* |
| `ps` | Imprime en pantalla el estado de los procesos en el momento actual | `ps -aux` para visualizar todas los atributos de los procesos en ejecucacion |
| `pstree` | Muestra los procesos como arbol |  `pstree` para visualizar los procesos en ejecucion en formato arbol  |
| `kill` | Mata/Para procesos dentro del sistema operativo.  |  Para quitar una app: se busca el PID (process ID) y en la Terminal se escribe: `kill -9 <PID de la app a matar>`  |
| `ip a` / `ip addr` | Muestra las direcciones IP que tienen el equipo | `ip a` y `ip addr` para visualizar la direccion IP  |
| `&&` | Se utiliza para ejecutar dos o más comandos uno tras otro  |  `&&` para permitir que el siguiente comando solo se ejecute si el anterior es exitoso  |
| `man` | Manual de usuario de cualquier comando o utilidad que pueda ejecutar en Terminal |  `man <opción> <número sección> <nombre comando>` para visualizar informacion de el comando que necesite usar |
| `whoami` | Muestra cual usuario esta en control del equipo  |  Solo se necesita ejecutar `whoami` sin ningun comando o condicion para ver el usuario que ha iniciado sesión actualmente  |
| `exit` / `quit` | Salir de un usuario, del shell, o modo sudo | Solo se necesita ejecutar `exit` o `quit` salir de modo sudo, salir del shell o un usuario.  |
| `more` | Imprime en pantalla el contenido del archivo. Se utiliza para visualizar archivos largos  |  `more <nombre archivo.txt` para ver los contenidos de un documento largo  |
| `tail` | Imprime en pantalla una el final de cierta cantidad de lineas de documentos largos. Solo funcionan con archivos de texto. |  `tail -n <numero> <ruta>` para visualizar las primeras lineas de un documento de acuerdo al numero ingresado  |
| `head` | Imprime en pantalla una el principio de cierta cantidad de lineas de documentos largos.  Solo funcionan con archivos de texto.  |  `head -n <numero> <ruta>` para visualizar las ultimas lineas de un documento de acuerdo al numero ingresado |
| `cp` | Copiar un archivo  |  `cp <nombre archivo original> <nombre archivo copia>` para hacer copias de un documento, `cp <nombre archivo> <ruta>` para hacer una copia en una ubicacion especifica |
| `mv` | Mover un archivo a una carpeta  |  `mv <nombre archivo> <ruta>` para mover a un archivo o carpeta de un lugar a otro.  |
| `adduser`  `useradd` | Crear un usuario  |  `sudo adduser/useradd <opcion> <nombre usuario>` para crear un nuevo usuario, debe tener privilegios `sudo`  |
| `passwd` | Cambiar la contraseña de un usuario |  `sudo passwd <nombre usuario>` para cambiar la contraseña de un usuario en especifico, debe tener privilegios `sudo` |
| `history` | Muestra el historial de todos los comandos ejecutados desde el principio | Solo se necesita ejecutar `history <opcion>` para visualizar los comandos ejecutados desde el inicio  |
| `grep` | Buscar un palabra entre el texto de un archivo especifico  |  `grep <palabra a buscar> <archivo de texto>` para buscar un palabra especifica en un archivo fijo |
| `reboot` | Reinicia el equipo |  Solo se necesita ejecutar `reboot` sin ningun comando o condicion para reiniciar el equipo  |
| `apt install` | Content Cell  |  Content Cell  |
| `find` | Content Cell  |  Content Cell  |
| `echo` | Imprime lineas de texto en la terminal  |  `echo <opción> <cadena>` para imprimir lineas de texto en la terminal |
| `>` | Se utiliza para convertir un comando a otro.  |  `ls > archivo.txt` es una ejemplo para que lo que imprime `ls` se guarde un archivo de texto. Tiene multiples usos y se puede combinar con otros comandos.  |
| `scp` | Content Cell  |  Content Cell  |
| `bash` | Content Cell  |  Content Cell  |
| `zenity` | Content Cell  |  Content Cell  |
| `docker` | Content Cell  |  Content Cell  |
| `systemctl` | Content Cell  |  Content Cell  |
| `tar` | Archiva varios archivos en un archivo TAR, un formato común de Linux similar a ZIP  |  `tar <opciones> <archivo_archivo> <archivo o directorio a archivar>` para archivar en formato TAR  |
| `git clone` | Content Cell  |  Content Cell  |
| `wget` | Descargar archivos de Internet  |  `wget <opción> <URL>` para descargar un paquete o archivo de Internet |
| `locate` | Buscar un archivo en un sistema de base de datos  |  `locate -i <palabra>` para buscar una palabra en especifico sin hacer distincion entre miniscula o mayuscula. Para buscar dos palabras a la vez, cada palabra se separa por un asterico (*)  |
| `zip` | Comprime archivos en un archivo ZIP |  `zip <opciones> <nombre archivo ZIP>.zip <archivo(s)>` para comprimir un archivo o directorio |
| `unzip` | Extrae los archivos comprimidos de un archivo ZIP |  `unzip <option> <nombre archivo ZIP>.zip` para descomprimir un archivo o directorio |
| `curl` | Content Cell  |  Content Cell  |
| `wc` | Content Cell  |  Content Cell  |
| `apt-get` | Herramienta de línea de comandos para manejar las bibliotecas de Advanced Package Tool (APT)  |  `apt-get <opciones> <comando>` para descargar, administrar, actualizar, y eliminar algun software o aplicacion  |
| `pwsh` | Content Cell  |  Content Cell  |
| `updatedb` | Content Cell  |  Content Cell  |
| `uname` | Imprime información detallada sobre el sistema y hardware |  `uname <opción>` para ver la informacion del sistema y hardware, `uname -a` para que imprima **toda** la informacion del sistema y hardward |
| `ifconfig` | Content Cell  |  Content Cell  |
| `network` | Content Cell  |  Content Cell  |
| `vim` | Content Cell  |  Content Cell  |
| `rmdir` | Eliminar permanentement directorios vacios  |  `rmdir <nombre directorio>` para eliminar un directorio en especifico, necesita tener los privilegios `sudo` para poder ejecutarse  |
| `touch` | Crear un documento vacio o generar o modificar una marca de tiempo en una linea de comando |  `touch <comando>` para ejecutar un comando que va a guardar en un documento, `touch <ruta archivo>` para cambiar la marca de tiempo de un archivo  |
| `df` | Informa sobre el uso del espacio en disco del sistema  |  `df-h` para visualizar el uso del espacio en disco del sistema del directorio actual en un formato legible por humanos |
| `du` | Verificar cuánto espacio ocupa un archivo o un directorio |  `du <ruta>` para verificar el espacio que ocupa un archivo o directorio  |
| `chmod` | Modifica los permisos de lectura, escritura y ejecución de un archivo o directorio. Tomar en cuenta las tres clases de usuarios: propietario , miembro del grupo y otros. |  `chmod <opción> <permiso> <nombre_archivo>` para cambiar los permisos de un archivo o directorio segun los permisos de lectura, escritura, y ejecucion asignados.  |
| `chown` | Permite cambiar la propiedad de un archivo o directorio a un nombre de usuario específico  |  `chown <opción> <propietario> <archivo o directorio>` para cambiar los permisos de ese archivo a un usuario especifico |
| `su` | Ejecutar un programa como un usuario diferente  |  `su <opcion> <nombre de usuario>` para cambiar de un usuario a otro sin tener que salir de session |
| `less` | Content Cell  |  Content Cell  |
| `dpkg` | Content Cell  |  Content Cell  |
| `ping` | Comprobar si se puede acceder a una red o un servidor  |  `ping <opción> <hostname or IP address>` para verificar la conexion a internet o un servidor  |
| `nmap` | Content Cell  |  Content Cell  |
| `nslookup` | Content Cell  |  Content Cell  |
| `netstat` | Content Cell  |  Content Cell  |
| `fdisk` | Content Cell  |  Content Cell  |
| `ln` | Content Cell  |  Content Cell  |
| `apcalc` | Content Cell  |  Content Cell  |
| `alias` | Crear un acceso directo o 'alias' con la misma funcionalidad que un comando o archivo de texto  |  `alias <palabra>=<comando>` para asignarle un alias a un comando, en vez de ejecutar con su nombre pretederminado, `unalias <nombre alias>` para remover el alias a ese comando o archivo de texto  |
| `diff` | Compara dos contenidos de un archivo línea por línea  |  `diff <nombre archivo 1> <nombre archivo 2>` para comparar los contenidos de dos archivos en especifico  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |
| Content Cell | Content Cell  |  Content Cell  |




















