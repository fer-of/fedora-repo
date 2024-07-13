## Linux Commands

### Files and Navigation
- `ls` - listado de directorios.
- `ls -l` - listado de directorios en formato largo.
- `cd dir` - cambiar de directorio.
- `cd ../dir` - cambiar al directorio padre y luego al subdirectorio.
- `cd` - cambiar al directorio home.
- `pwd` - mostrar el directorio actual.
- `mkdir dir` - crear un nuevo directorio.
- `rm file` - eliminar un archivo.
- `rm -f dir` - eliminar un directorio de forma forzada.
- `rm -r dir` - eliminar un directorio y su contenido recursivamente.
- `cp file1 file2` - copiar un archivo.
- `mv file1 file2` - mover o renombrar un archivo.
- `touch file` - crear un archivo vacío o actualizar la fecha de modificación.
- `cat file` - mostrar el contenido de un archivo.
- `cat > file` - redirigir la entrada estándar a un archivo.
- `cat >> file` - agregar la entrada estándar al final de un archivo.
- `tail -f file` - mostrar las últimas líneas de un archivo y seguir actualizando en tiempo real.

### User and Group Management
- `passwd` - cambiar la contraseña de un usuario.
- `useradd` - añadir un nuevo usuario.
- `userdel` - eliminar un usuario.
- `usermod` - modificar un usuario.
- `groupadd` - añadir un nuevo grupo.
- `groupdel` - eliminar un grupo.
- `groups` - mostrar los grupos a los que pertenece un usuario.
- `id` - mostrar el ID de usuario y grupo.

### System Info
- `uptime` - mostrar el tiempo de actividad del sistema.
- `date` - mostrar o configurar la fecha y hora del sistema.
- `whoami` - mostrar el nombre de usuario actual.
- `w` - mostrar quién está conectado y qué están haciendo.
- `cat /proc/cpuinfo` - mostrar información de la CPU.
- `cat /proc/meminfo` - mostrar información de la memoria.
- `free` - mostrar la cantidad de memoria libre y usada.
- `du` - estimar el uso del espacio en disco.
- `du -sh` - mostrar el tamaño total de un directorio de forma legible.
- `df` - mostrar el uso del espacio en disco de los sistemas de archivos.
- `uname -a` - mostrar información del sistema.
- `lscpu` - mostrar información detallada de la CPU.
- `lshw` - mostrar un informe detallado del hardware.
- `lsblk` - listar la información de todos los dispositivos de bloques.

### Permissions
- `chmod octal file` - cambiar los permisos de un archivo.
  - 4 - readable (r)
  - 2 - writable (w)
  - 1 - executable (x)
  - Orden - owner/group/world
- `chmod 777 file` - rwx para todos.
- `chmod 755 file` - rw para el propietario, rx para el grupo y otros.

### Processes
- `ps` - mostrar los procesos en ejecución.
- `ps aux` - mostrar información detallada de los procesos.
- `kill pid` - matar un proceso por su ID.
- `killall proc` - matar todos los procesos con el mismo nombre.
- `top` - mostrar los procesos en ejecución en tiempo real.
- `htop` - una versión interactiva de `top`.
- `pstree` - mostrar los procesos en forma de árbol.

### Networking
- `whois domain` - obtener información sobre un dominio.
- `ping host` - enviar paquetes ICMP a un host para verificar la conectividad.
- `dig domain` - realizar consultas DNS.
- `dig -x host` - realizar consultas DNS inversas.
- `wget file` - descargar un archivo.
- `wget -c file` - continuar una descarga interrumpida.
- `ssh user@host` - conectarse a un host remoto vía SSH.
- `ssh -p port user@host` - conectarse a un host remoto vía SSH en un puerto específico.
- `ssh -D user@host` - crear un túnel SSH.
- `ifconfig` - mostrar o configurar interfaces de red.
- `ip` - mostrar o configurar interfaces de red y rutas.
- `netstat` - mostrar conexiones de red y estadísticas.
- `ss` - mostrar conexiones de red y estadísticas.
- `traceroute` - trazar la ruta hacia un host.
- `nc` - herramienta de red para leer y escribir datos a través de conexiones de red.

### Compressing
- `tar cf file.tar files` - crear un archivo tar.
- `tar xf file.tar` - extraer un archivo tar.
- `tar tf file.tar` - listar el contenido de un archivo tar.

### Package Management
- `dnf` - herramienta de gestión de paquetes para Fedora.
- `rpm` - gestor de paquetes de Red Hat.
- `snap` - sistema de paquetes universal.

### File Viewing and Editing
- `cat` - mostrar el contenido de un archivo.
- `less` - ver el contenido de un archivo con paginación.
- `more` - ver el contenido de un archivo con paginación.
- `nano` - editor de texto simple.
- `vim` - editor de texto avanzado.
- `gedit` - editor de texto gráfico.
