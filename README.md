#NOTA: El repositorio se encontrara en constante modificación hasta el día de entrega.

# Lista-Comandos
Lista de Comandos (Ubuntu, Manjaro, Docker, etc.) por VirtualBox 6

| Comando  | Descripción | Sintaxis |
| ------------- | ------------- | ------------- |
| `sudo` | Permite ejecutar cualquier programa como administrador  | `sudo su` y `sudo -i` para pasar a modo administrativo/root, `sudo <comando>` para darle permisos de ejecucion a un comando o programa.  |
| `ls`  | Muestra la lista de archivos y carpetas del directorio actual, imprime en pantalla las lista de las carpetas y archivos de la carpeta actual |  `ls -l` imprime los archivos en un formato de lista, `ls -a` imprime los archivos tanto visibles como ocultos  |
| `/` | "Madre de carpetas", dentro de lash estan dentros todas las carpetas del sistema operativo |  La ruta de todos los directorios empiezan con `/`  |
| `pwd` | Muestra la ruta de un archivo, carpeta, o donde uno esta posicionado  |  `pwd <opciones: -L o -P>` para encontrar la ruta en el dicrectorio que uno se encuentra actualmente.  |
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
| `man` | Manual de usuario de cualquier comando o utilidad que pueda ejecutar en Terminal |  `man <opciones> <número sección> <nombre comando>` para visualizar informacion de el comando que necesite usar |
| `whoami` | Muestra cual usuario esta en control del equipo  |  Solo se necesita ejecutar `whoami` sin ningun comando o condicion para ver el usuario que ha iniciado sesión actualmente  |
| `exit` / `quit` | Salir de un usuario, del shell, o modo sudo | Solo se necesita ejecutar `exit` o `quit` salir de modo sudo, salir del shell o un usuario.  |
| `more` | Imprime en pantalla el contenido del archivo. Se utiliza para visualizar archivos largos  |  `more <nombre archivo.txt` para ver los contenidos de un documento largo  |
| `tail` | Imprime en pantalla una el final de cierta cantidad de lineas de documentos largos. Solo funcionan con archivos de texto. |  `tail -n <numero> <ruta>` para visualizar las primeras lineas de un documento de acuerdo al numero ingresado  |
| `head` | Imprime en pantalla una el principio de cierta cantidad de lineas de documentos largos.  Solo funcionan con archivos de texto.  |  `head -n <numero> <ruta>` para visualizar las ultimas lineas de un documento de acuerdo al numero ingresado |
| `cp` | Copiar un archivo  |  `cp <nombre archivo original> <nombre archivo copia>` para hacer copias de un documento, `cp <nombre archivo> <ruta>` para hacer una copia en una ubicacion especifica |
| `mv` | Mover un archivo a una carpeta  |  `mv <nombre archivo> <ruta>` para mover a un archivo o carpeta de un lugar a otro.  |
| `adduser`  `useradd` | Crear un usuario  |  `sudo adduser/useradd <opciones> <nombre usuario>` para crear un nuevo usuario, debe tener privilegios `sudo`  |
| `passwd` | Cambiar la contraseña de un usuario |  `sudo passwd <nombre usuario>` para cambiar la contraseña de un usuario en especifico, debe tener privilegios `sudo` |
| `history` | Muestra el historial de todos los comandos ejecutados desde el principio | Solo se necesita ejecutar `history <opciones>` para visualizar los comandos ejecutados desde el inicio  |
| `grep` | Buscar un palabra entre el texto de un archivo especifico  |  `grep <palabra a buscar> <archivo de texto>` para buscar un palabra especifica en un archivo fijo |
| `reboot` | Reinicia el equipo |  Solo se necesita ejecutar `reboot` sin ningun comando o condicion para reiniciar el equipo  |
| `find` | Encontrar y filtrar archivos  |  `find <ruta directorio> <parametro a buscar>` para buscar un elemento siguiendo la ruta indicada  |
| `echo` | Imprime lineas de texto en la terminal  |  `echo <opciones> <palabras>` para imprimir lineas de texto en la terminal |
| `>` | Se utiliza para convertir un comando a otro.  |  `ls > archivo.txt` es una ejemplo para que lo que imprime `ls` se guarde un archivo de texto. Tiene multiples usos y se puede combinar con otros comandos.  |
| `tar` | Archiva varios archivos en un archivo TAR, un formato común de Linux similar a ZIP  |  `tar <opciones> <archivo_archivo> <archivo o directorio a archivar>` para archivar en formato TAR  |
| `wget` | Descargar archivos de Internet  |  `wget <opciones> <URL>` para descargar un paquete o archivo de Internet |
| `locate` | Buscar un archivo en un sistema de base de datos  |  `locate -i <palabra>` para buscar una palabra en especifico sin hacer distincion entre miniscula o mayuscula. Para buscar dos palabras a la vez, cada palabra se separa por un asterico (*)  |
| `zip` | Comprime archivos en un archivo ZIP |  `zip <opciones> <nombre archivo ZIP>.zip <archivo(s)>` para comprimir un archivo o directorio |
| `unzip` | Extrae los archivos comprimidos de un archivo ZIP |  `unzip <opciones> <nombre archivo ZIP>.zip` para descomprimir un archivo o directorio |
| `apt-get` / `apt` | Herramienta de línea de comandos para manejar las bibliotecas de Advanced Package Tool (APT)  |  `apt-get <opciones> <comando>` para descargar, administrar, actualizar, y eliminar algun software o aplicacion  |
| `uname` | Imprime información detallada sobre el sistema y hardware |  `uname <opciones>` para ver la informacion del sistema y hardware, `uname -a` para que imprima **toda** la informacion del sistema y hardward |
| `rmdir` | Eliminar permanentement directorios vacios  |  `rmdir <nombre directorio>` para eliminar un directorio en especifico, necesita tener los privilegios `sudo` para poder ejecutarse  |
| `touch` | Crear un documento vacio o generar o modificar una marca de tiempo en una linea de comando |  `touch <comando>` para ejecutar un comando que va a guardar en un documento, `touch <ruta archivo>` para cambiar la marca de tiempo de un archivo  |
| `df` | Informa sobre el uso del espacio en disco del sistema  |  `df -h` para visualizar el uso del espacio en disco del sistema del directorio actual en un formato legible por humanos |
| `du` | Verificar cuánto espacio ocupa un archivo o un directorio |  `du <ruta>` para verificar el espacio que ocupa un archivo o directorio  |
| `chmod` | Modifica los permisos de lectura, escritura y ejecución de un archivo o directorio. Tomar en cuenta las tres clases de usuarios: propietario , miembro del grupo y otros. |  `chmod <opciones> <permiso> <nombre_archivo>` para cambiar los permisos de un archivo o directorio segun los permisos de lectura, escritura, y ejecucion asignados.  |
| `chown` | Permite cambiar la propiedad de un archivo o directorio a un nombre de usuario específico  |  `chown <opciones> <propietario> <archivo o directorio>` para cambiar los permisos de ese archivo a un usuario especifico |
| `su` | Ejecutar un programa como un usuario diferente  |  `su <opciones> <nombre de usuario>` para cambiar de un usuario a otro sin tener que salir de session |
| `ping` | Comprobar si se puede acceder a una red o un servidor  |  `ping <opciones> <hostname or IP address>` para verificar la conexion a internet o un servidor  |
| `alias` | Crear un acceso directo o 'alias' con la misma funcionalidad que un comando o archivo de texto  |  `alias <palabra>=<comando>` para asignarle un alias a un comando, en vez de ejecutar con su nombre pretederminado, `unalias <nombre alias>` para remover el alias a ese comando o archivo de texto  |
| `diff` | Compara dos contenidos de un archivo línea por línea  |  `diff <nombre archivo 1> <nombre archivo 2>` para comparar los contenidos de dos archivos en especifico  |
| `git clone` | Línea de comandos de Git que se utiliza para apuntar a un repositorio existente y crear un clon o una copia del repositorio de destino  |  `git clone <opciones> <URL de Git>` para descargar repositorios que se encuenten en Github  |
| `curl` | Línea de comandos para transferir datos hacia o desde un servidor, utilizando cualquiera de los protocolos admitidos (HTTP, FTP, IMAP, POP3, SCP, SFTP, SMTP, TFTP, TELNET, LDAP o FILE)  |  `curl <opciones> <URL>` para intercambiar informacion de equipo a un servidor  |
| `wc` | calcula el recuento de palabras, líneas, caracteres o bytes de un archivo  |  `wc <opciones> <nombre archivo` para calcular el recuento de elementos en un archivo  |
| `pwsh` | Iniciar un instancia de Powershell, abrir la terminal de Powershell y ejecutar scripts con el formato .ps1  |  Solo se necesita ejecutar `pwsh` para ingresar a Powershell, `pwsh <nombre script>.ps1` para ejecutar un script de Powershell en la terminal  | 
| `updatedb` | Crea o actualiza una base de datos utilizada por mlocate. Si la base de datos ya existe, sus datos se reutilizan para evitar volver a leer directorios que no han cambiado. Cron suele ejecutar dailyb para actualizar la base de datos predeterminada.  |  `updatedb <opciones>` para crear, revisar o actualizar datos, sin volver a tener que leer datos que ya estan cargados y no han sido modificados  |
| `scp` | Línea de comandos que le permite copiar archivos y directorios de forma segura entre dos ubicaciones  |  `scp <opciones> <nombre achivo> <usuario@IP:/ruta/del/directorio>` para copiar documentos de manera remota a otro escritorio |
| `bash` | Conocido como Linux Bash Scripting es un shell de Unix que es un intérprete de lenguaje de comandos compatible con sh  |  `bash <nombre script>.sh` para ejecutar comandos en formato .sh en la terminal  |
| `zenity` | Herramienta que muestra cuadros de diálogo en el terminal de Linux utilizando scripts de shell  |  `zenity <opciones>` para crear calendarios, notificacion, cajas de texto, etc.  |
| `docker` | Plataforma de creación de contenedores que empaqueta su aplicación y todas sus dependencias en forma de un contenedor  |  `docker <opciones>` para crear, modificar, eliminar contenedors en Docker  |
| `systemctl` | Línea de comandos de Linux que se utiliza para controlar y administrar systemd y servicios.  |  `systemctl <opciones> <comandos>` para revisar y controlar el systemd |
| `ifconfig` | Se utiliza en el momento del arranque para configurar interfaces  |  `ifconfig <opciones> <nombre interfaz>` para modificar la interfaz de algun network |
| `netstat` | Proporciona cifras estadísticas sobre diferentes interfaces que incluyen sockets abiertos, tablas de enrutamiento e información de conexión.   |  `netstat -p` para visualizar programas asociados al socket, `netstat -s` para obtener detalles de todos los puertos  |
| `vim` | Crear un archivo nuevo, editar un archivo existente o simplemente leer un archivo.  | Comando para su instalacion: `apt install vim` El comando `vim <argumentos> <opciones> <nombre archivo>` es para crear o editar archivos que ejecutan un accion dentro del sistema  |
| `less` | Muestra el contenido de un archivo una pantalla a la vez  | `less <opciones> <ruta archivo>` para visualizar el contenido de un documento largo en hojas |
| `dpkg` | Es una herramienta para instalar, compilar, eliminar y administrar paquetes de Debian  |  `dpkg <opciones> <nombre paquete .deb>` para interactuar con paquetes que contiene o se descargaron en el sistema  |
| `fdisk` | Crear y manipular la tabla de particiones del disco  |  `fdisk <opciones> <dispositivo>` o `fdisk -l <dispositivo>` para visualizar las particiones del disco del sistema |
| `ln` | Crear enlaces duros o suaves/blandos de archivos o directorios  |  `ln <ruta archivo/directorio> <nombre enlace duro>` para crear enlaces duros de un archivo o directorio, `ln -s <ruta archivo/directorio> <nombre enlace duro>` para crear enlaces suaves/blandos de un archivo o directorio  |
| `apcalc` | Programa que nos permite realizar operaciones matemáticas desde una ventana de terminal  |  Comando para su instalacion: `sudo apt install calc`  El comando `calc <operacion>` es para que el programa resuelva la operacion introducida  |
| `nmap` | Línea de comandos de Linux para la exploración de redes y la auditoría de seguridad  |  Comando para su instalacion: `sudo apt-get install nmap`. `nmap <URL>` o `<IP>` para obtener informacion detallada de la red, puertos abiertos, IPs activadas, etc.  |
| `nslookup` | Utilizado para consultas relacionadas con el Domain Name System (DNS)  |  `nslookup <nombre dominio>` para buscar relaciones con un servidor DNS  |
| `dd` | Convertir y copiar archivos |  `dd <opciones>` para hacer copias de seguridad para archivos importantes del sistema operativo  |
| `ffmpeg` |  Procesar archivos multimedia |  Comando para su instalacion: `sudo add-apt-repository universe` y `sudo apt install ffmpeg`. El comando `ffmpeg <opciones>` es para realizar muchas tareas de procesamiento de una manera simple |
| `fdupes` | Encontrar y eliminar archivos duplicados  |  Comando para su instalacion: `sudo apt install fdupes`, `sudo dnf install fdupes`. El comando `fdupes <opciones> <ruta directorio>` para buscar archivos repetidos |
| `shutdown` | Apagar o parar el sistema operativo  | `shutdown <opciones: --halt o --poweroff>` para que el sistema se detenga o se apague  |


Lista de Ejemplos de Comandos
| Commando  | Ejemplo |
| ------------- | ------------- |
| **sudo** | `sudo su`, `sudo ./VBoxLinuxAdditions.run`,  |
| **apt/apt-get** | `apt install neofetch`, `sudo apt update`,`sudo apt install snapd`,`sudo snap install`, `sudo add-apt-repository ppa:numix/ppa -y`,`sudo apt install numix-icon-theme-circle`,`sudo apt install numix-gtk-theme`,`apt install locate`,`sudo apt-get install ocrfeeder tesseract-ocr tesseract-ocr-spa tesseract-ocr-eng gocr cuneiform ocropusocrad`,`sudo apt -y install flameshot`  |  
| **less** | `less /etc/updatedb.conf`,`less welcome.txt` |  
| **mv** | `mv HolaSemanal.txt Documents`  |  
| **rm** | `rm random.txt`  | 
| **more** | `ls -l / -R `|` more`  |  
| **mkdir** | `mkdir diruno`,`mkdir PComandos/tmp/Sistemas/Operativos/Semana/3`  |  
| **grep** | `grep -r "ulacit"`,`grep -r "mydomain.com" /etc/apache2/`,`grep -r "apache" /`,`grep -r "mydomain.com" /etc/apache2/` |  
| **alias** | `alias update='sudo yum update'`  |  
| **scp** | `scp archivo.pdf mortasoft@192.168.1.184:/home/mortasoft/Documentos/archivo.pdf`,`scp pruebaU.txt cmoraj577@192.168.100.195:/home/cmoraj577/Desktop/` | 
| **curl** | `curl -X GET -L https://script.google.com/macros/s/AKfycby61tcPuNY3dw_3IYqNGFnR6Ei55MrLFPe_PHup_VMnGP07HeoRyIy5W8xlrheMB7vJ/exec?data=$nombre`  | 
| **nano** | `nano archivo1.txt`,`nano /svr/html/index.html`,`nano apache`  |  
| **cd** | `cd U/dirdos` |  
| **ls** | `ls /bin`, `ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3.txt`  |  
| **cat** | `cat archivo1.txt`,`cat /proc/cpuinfo`  |  
| **>** | `ls -la /bin > archivo1.txt`  |  
| **cp** | `cp -rv /etc/a* $HOME/U/dir004 1> $HOME/U/dir003/dircuatro/archivo2.txt`,`cp /etc/profile $HOME/dir003/dircuatro/`  |  
| **find** | `find pcolor`,`find /home/mortasoft/ -name index.html`,`find / -name foo 2>/dev/null`  |  
| **kill** | `pkill colord`  |  
| **echo** | `echo "Hola Mundo"`,`echo /tmp/Sistemas/Operativos/Semana/3 /opt/datos/ubuntu`  |  
| **systemctl** | `sudo systemctl restart httpd`,`sudo systemctl start docker`,`sudo systemctl enable docker`,`sudo systemctl status docker`  |  
| **chown** | `chown -R 700 nicit /home/cmoraj577/U/dir003`  |  
| **wget** | `wget https://wordpress.org/latest.zip`, `wget -qO- https://git.io/papirus-icon-theme-install`  |  
| **wc** | `wc /var/log/syslog`,`wc /var/log/syslog -l`,`wc /var/log/syslog -w`,`wc /var/log/syslog -m`  |  
| **head** | `head /var/log/syslog -n 3`  |  
| **tail** | `tail /var/log/syslog -n 3`,`tail archivo.txt -f` |  
| **locate** | `locate index.html`,`locate syslog`  | 
| **nmap** | `nmap 192.168.1.170`  |  
| **nslookup** | `nslookup ulacit.ac.cr`,`nslookup apt install dnsutils`  | 
| **netstat** | `netstat -ltp`,`netstat -tulpn`  |  
| **ping** | `ping apt install iputils`  |  
| **df** | `df -h`  |  
| **fdisk** | `sudo fdisk -l`  |  
| **tar** | `tar -cvf myarchive.tar /home/mortasoft/Semana_09/` (Comprimir),`tar -xvf myarchive.tar -C /tmp/` (Descomprimir), `tar -xvf file.tar.gz`,`tar -xzvf projects.tar.gz -C /tmp/`  |  
| **dd** | `dd if=/home/mortasoft/imagen.dd of=/dev/sde conv=notrunc &` (Hacer una imagen de disco),`sudo dd if=/dev/sdb1 of=/home/tecmint/Documents/Linux_Mint_19_XFCE.iso`,`sudo dd if=artful-desktop-amd64.iso of=/dev/sdd bs=1M status=progress`  |  
| **ln** | `ln -s file link`  |  
| **zip** | `zip comprimido.zip archivo.txt`  |  
| **unzip** | `unzip comprimido.zip`  |  
| **pacman** (gestor de paquetes Manjaro) | `sudo pacman -Syuu`,`sudo pacman -S unrar zip unzip p7zip gzip bzip2`,`sudo pacman -S yay`,`sudo yay -S --needed base-devel`,`sudo pacman -S apache`,`sudo pacman -S cronie`, `sudo pacman -S neofetch`  |  
| **yay** | `yay -S google-chrome`  |  
| **uname** | `uname -a`  |  
| **adduser / useradd** | `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario`  |  
| **ps** | `ps -aux`, `ps -a`  |  
| **crontab** | `crontab -e`  | 
| **chmod** | `chmod ugo+x HolaSemanal.sh`  |  
| **dpkg** | `sudo dpkg -i code_1.71.2-1663191218_amd64.deb`  |  
| **docker**   | `sudo docker run -it ubuntu`,`docker ps -a`,`docker start mi_ubuntu`,`sudo docker start mi_ubuntu`,`sudo docker attach mi_ubuntu`,`sudo docker pull portainer/portainer-ce:latest`,`sudo docker volume create portainer_data`,`docker search ubuntu`,`docker pull ubuntu`,`docker images`,`docker rm 9e6947a138c2`,`docker network ls`,`docker rmi 4b`  |  
| **man** | `man find`  |  
| **mount** | `sudo mount -t ext4 /dev/md/RAID5\:raid5 /media/RAID5`,`sudo mount -t ext4 /dev/md/RAID5\:raid5 /media/`  |
| **zenity** | `zenity --entry --title "Name request" --text "Please enter your name:"`  |  
| **bash** | `bash Bash3.sh`  |  
| **apcalc** | `calc 8+2`  |
| **top** | `sudo top -u cmoraj577`  |  
| **vim** | `vim Dockerfile`  |  
| **ifconfig** | `ifconfig -s`,`ifconfig docker0`  |
| **rmdir** | `rmdir dir003`  |  


FORMATO TABLA

TRES
| Content Cell | Content Cell  |  Content Cell  |

DOS
| Content Cell | Content Cell  |
