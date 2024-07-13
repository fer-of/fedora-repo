## Linux Commands

### Files and Navigation
- `ls` - list directories.
- `ls -l` - list directories in long format.
- `cd dir` - change directory.
- `cd ../dir` - change to parent directory and then to the subdirectory.
- `cd` - change to the home directory.
- `pwd` - display the current directory.
- `mkdir dir` - create a new directory.
- `rm file` - remove a file.
- `rm -f dir` - forcibly remove a directory.
- `rm -r dir` - remove a directory and its contents recursively.
- `cp file1 file2` - copy a file.
- `mv file1 file2` - move or rename a file.
- `touch file` - create an empty file or update the modification date.
- `cat file` - display the content of a file.
- `cat > file` - redirect standard input to a file.
- `cat >> file` - append standard input to the end of a file.
- `tail -f file` - display the last lines of a file and keep updating in real-time.

### User and Group Management
- `passwd` - change a user's password.
- `useradd` - add a new user.
- `userdel` - delete a user.
- `usermod` - modify a user.
- `groupadd` - add a new group.
- `groupdel` - delete a group.
- `groups` - display the groups a user belongs to.
- `id` - display user and group IDs.

### System Info
- `uptime` - display the system's uptime.
- `date` - display or set the system's date and time.
- `whoami` - display the current username.
- `w` - display who is logged in and what they are doing.
- `cat /proc/cpuinfo` - display CPU information.
- `cat /proc/meminfo` - display memory information.
- `free` - display the amount of free and used memory.
- `du` - estimate disk space usage.
- `du -sh` - display the total size of a directory in a human-readable format.
- `df` - display disk space usage of file systems.
- `uname -a` - display system information.
- `lscpu` - display detailed CPU information.
- `lshw` - display a detailed hardware report.
- `lsblk` - list information about all block devices.

### Permissions
- `chmod octal file` - change the permissions of a file.
  - 4 - readable (r)
  - 2 - writable (w)
  - 1 - executable (x)
  - Order - owner/group/world
- `chmod 777 file` - rwx for everyone.
- `chmod 755 file` - rw for owner, rx for group and others.

### Processes
- `ps` - display running processes.
- `ps aux` - display detailed information about running processes.
- `kill pid` - kill a process by its ID.
- `killall proc` - kill all processes with the same name.
- `top` - display running processes in real-time.
- `htop` - an interactive version of `top`.
- `pstree` - display processes in a tree format.

### Networking
- `whois domain` - get information about a domain.
- `ping host` - send ICMP packets to a host to check connectivity.
- `dig domain` - perform DNS queries.
- `dig -x host` - perform reverse DNS queries.
- `wget file` - download a file.
- `wget -c file` - continue an interrupted download.
- `ssh user@host` - connect to a remote host via SSH.
- `ssh -p port user@host` - connect to a remote host via SSH on a specific port.
- `ssh -D user@host` - create an SSH tunnel.
- `ifconfig` - display or configure network interfaces.
- `ip` - display or configure network interfaces and routes.
- `netstat` - display network connections and statistics.
- `ss` - display network connections and statistics.
- `traceroute` - trace the route to a host.
- `nc` - network tool to read and write data across network connections.

### Compressing
- `tar cf file.tar files` - create a tar archive.
- `tar xf file.tar` - extract a tar archive.
- `tar tf file.tar` - list the contents of a tar archive.

### Package Management
- `dnf` - package management tool for Fedora.
- `rpm` - Red Hat package manager.
- `snap` - universal package system.

### File Viewing and Editing
- `cat` - display the content of a file.
- `less` - view the content of a file with pagination.
- `more` - view the content of a file with pagination.
- `nano` - simple text editor.
- `vim` - advanced text editor.
- `gedit` - graphical text editor.
