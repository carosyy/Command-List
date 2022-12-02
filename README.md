#NOTA: El repositorio se encontrara en constante modificación hasta el día de entrega.

# Command-List
Command List for Linux (Ubuntu, Manjaro, Docker, etc.) through VirtualBox 6

| Commando  | Descripción | Sintaxis | 
| ------------- | ------------- | ------------- |
| `sudo` | Permite ejecutar cualquier programa como administrador  | `sudo su` y `sudo -i` para pasar a modo administrativo/root, `sudo <comando>` para darle permisos de ejecucion a un comando o programa.  |
| `ls`  | Muestra la lista de archivos y carpetas del directorio actual, imprime en pantalla las lista de las carpetas y archivos de la carpeta actual |  `ls -l` imprime los archivos en un formato de lista, `ls -a` imprime los archivos tanto visibles como ocultos  |
| `/` | "Madre de carpetas", dentro de lash estan dentros todas las carpetas del sistema operativo |  Content Cell  |
| `pwd` | Muestra la ruta de un archivo, carpeta, o donde uno esta posicionado  |  Content Cell  |
| `clear`  | Limpia la terminal, se elimina todo el contenido de la pantalla  |  Content Cell  |
| `cd` | Change direction/cambiar directorio  |   `cd <ruta>` se usa para cambiar de un directorio a otro, mientras que `cd ..` es para devolverse |
| `nano` | Crea documentos, editor de texto en consola |  `nano <nombre archivo>.txt` es para crear o editar achivos de texto. Este comando se puede usar para crear archivos de otros formatos (ej. *.sh, *.ps1)  |
| `cat` | Imprime el contenido del archivo, se utiliza para visualizar el contenido de un archivo  |  `cat <nombre archivo>.txt` se usa para imprimir en terminal el contenido de un archivo de texto  |
| `mkdir` | Crea carpetas/directorios nuevas |  `mkdir <nombre carpeta/directorio>` se usa para crear un directorio/carpeta en la ubicacion donde se encuentra, `mkdir <nombre carpeta/directorio> <ruta>` se usa para crear un carpeta/directorio en una ubicacion especifica |
| `rm` | Eliminar archivos y carpetas/directorios | `rm <nombre archivo>.txt` se usa para eliminar un archivo. Nota: hay que escribir el formato al final para eliminar el correcto. `rm <nombre archivo>.* -R` se utiliza para eliminar de manera recursiva  |
| `top` | Ver el administrador de procesos en una terminal interactiva. Para salir del administrador de procesos: ctrl + c  |  Content Cell  |
| `htop` | Comando para su instalacion: `sudo apt install htop`. Ver administrador de procesos con colores en una terminal interactiva. Para salir del administrador de procesos: ctrl + c |  Content Cell  |
| `ps -aux` | Imprime en pantalla el estado de los procesos en el momento actual |  `ps -a`  |
| `pstree` | Muestra los procesos como arbol |  Content Cell  |
| `kill` | Mata/Para procesos dentro del sistema operativo. Para quitar una app:s e busca el PID (process ID) y en la Terminal se escribe: `kill -9 (PID de la app a quitar)`  |  Content Cell  |
| `ip a` / `ip addr` | Muestra las direcciones IP que tienen el equipo |  Content Cell  |
| `&&` | Se utiliza para ejecutar dos o más comandos uno tras otro  |  Content Cell  |
| `man` | Manual de los comandos |  Content Cell  |
| `whoiam` | Muestra cual usuario esta en control del equipo  |  Content Cell  |
| `exit` | Sale de un usuario a otro |  Content Cell  |
| `more` | Imprime en pantalla el contenido del archivo. Se utiliza para visualizar archivos largos  |  `more <nombre archivo.txt` para ver los contenidos de un documento largo  |
| `tail` | Imprime en pantalla una el final de cierta cantidad de lineas de documentos largos. Solo funcionan con archivos de texto. |  `tail -n <numero> <ruta>` para visualizar las primeras lineas de un documento de acuerdo al numero ingresado  |
| `head` | Imprime en pantalla una el principio de cierta cantidad de lineas de documentos largos.  Solo funcionan con archivos de texto.  |  `head -n <numero> <ruta>` para visualizar las ultimas lineas de un documento de acuerdo al numero ingresado |
| `cp` | Copiar un archivo  |  `cp <nombre archivo original> <nombre archivo copia>` para hacer copias de un documento, `cp <nombre archivo> <ruta>` para hacer una copia en una ubicacion especifica |
| `mv` | Mover un archivo a una carpeta  |  `mv <nombre archivo> <ruta>` para mover a un archivo o carpeta de un lugar a otro.  |
| `adduser`  `useradd` | Crear un usuario  |  `adduser/useradd <nombre usuario>` para crear un nuevo usuario  |
| `passwd` | Cambiar la contraseña de un usuario |  ` sudo passwd <nombre usuario>` para cambiar la contraseña de un usuario en especifico  |
| `history` | Muestra el historial de todos los comandos ejecutados desde el principio | Content Cell  |
| `grep` | Content Cell  |  Content Cell  |
| `reboot` | Reinicia el equipo |  Content Cell  |
| `sudo apt install` | Content Cell  |  Content Cell  |
| `find` | Content Cell  |  Content Cell  |
| `echo` | Content Cell  |  Content Cell  |
| `>` | Content Cell  |  Content Cell  |
| `scp` | Content Cell  |  Content Cell  |
| `bash` | Content Cell  |  Content Cell  |
| `zenity` | Content Cell  |  Content Cell  |
| `docker` | Content Cell  |  Content Cell  |
| `systemctl` | Content Cell  |  Content Cell  |
| `tar` | Content Cell  |  Content Cell  |
| `git clone` | Content Cell  |  Content Cell  |
| `wget` | Content Cell  |  Content Cell  |
| `locate` | Content Cell  |  Content Cell  |
| `zip` | Content Cell  |  Content Cell  |
| `unzip` | Content Cell  |  Content Cell  |
| `curl` | Content Cell  |  Content Cell  |
| `wc` | Content Cell  |  Content Cell  |
| `apt-get` | Content Cell  |  Content Cell  |
| `pwsh` | Content Cell  |  Content Cell  |
| `quit` | Content Cell  |  Content Cell  |
| `updatedb` | Content Cell  |  Content Cell  |
| `uname` | Content Cell  |  Content Cell  |
| `ifconfig` | Content Cell  |  Content Cell  |
| `network` | Content Cell  |  Content Cell  |
| `vim` | Content Cell  |  Content Cell  |
| `rmdir` | Content Cell  |  Content Cell  |
| `touch` | Content Cell  |  Content Cell  |
| `df` | Content Cell  |  Content Cell  |
| `du` | Content Cell  |  Content Cell  |
| `chmod` | Content Cell  |  Content Cell  |
| `chown` | Content Cell  |  Content Cell  |
| `su` | Content Cell  |  Content Cell  |
| `less` | Content Cell  |  Content Cell  |
| `dpkg` | Content Cell  |  Content Cell  |
| `ping` | Content Cell  |  Content Cell  |
| `nmap` | Content Cell  |  Content Cell  |
| `nslookup` | Content Cell  |  Content Cell  |
| `netstat` | Content Cell  |  Content Cell  |
| `fdisk` | Content Cell  |  Content Cell  |
| `ln` | Content Cell  |  Content Cell  |
| `apcalc` | Content Cell  |  Content Cell  |
| `alias` | Content Cell  |  Content Cell  |
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
| Content Cell | Content Cell  |  Content Cell  |




















