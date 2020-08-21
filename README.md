![alt text](https://github.com/GenesisGonzalezM/Bitacora-Sistemas-Operativos/blob/master/Linux.png)

# Bitácora Sistemas Operativos
Sistemas Operativos ULACIT

Génesis González Marín

# --------------------- Comandos Linux ---------------------
La siguiente es una bitácora con los principales comandos de Linux vistos en el curso Sistemas Operativos.
  - sudo: da permisos de administrador a los comandos

### Instalación
  - apt: paquete que permite instalar el software
  - dpkg -l instalador: instalar un programa
  - sudo apt install paquete: instalar un paquete de software
  - sudo apt purge paquete: eliminar los instaladores
  - sudo apt remove paquete: desinstalar paquete
  - sudo apt update: verificar si hay alguna actualización
  - sudo apt upgrade: actualizar todos los paquetes
  - wget URL: descargar archivo

### Manejo de archivos
  - cat archivo: ver el contenido de un archivo
  - cd nombredir: cambiar de directorio
  - cd .. : regresar al directorio anterior
  - cp nombre destino: copiar el contenido a otra ubicación
  - du -h comprimido.tar: ver tamaño del archivo
  - find -name archivo: encontrar un archivo por nombre
  - head -n #: ver el comienzo de un archivo
  - ls: mostrar los directorios
  - ls -a/-l: listar los archivos
  - mkdir: crear una carpeta
  - mv archivo.txt NuevoNombre.txt: cambiar nombre
  - mv nuevoNombre /ruta: mover ubicación
  - nano: editar un archivo
  - pwd: ver la ruta actual
  - stat archivo: mostrar la fecha en que se creó un archivo
  - touch: crear un archivo
  - tail -n #: mostrar el final de un archivo
  - tar -xvf comprimido.tar: descomprimir
  - tar -tvf comprimido.tar: ver los archivos adentro

### Usuarios
  - useradd: crear un usuario
  - sudo su: loguearse desde el root
  - sudo chown user root archivo.ext: dar permisos
  - sudo chmod 777 (permiso) archivo.txt: dar permisos
  - whoami: ver el usuario en sesión

### Discos 
  - cd /mnt/ram_disk: entrar a la unidad
  - df-h: mostrar todos los discos 
  - gnome-disk-utility: ver información del disco
  - gparted: administrar particiones
  - mount: montar particiones nuevas
  - sudo mkdir /mnt/ram_disk: montar el disco en esta ubicación

### Procesos
  - kill -9 PID: matar el proceso
  - ps -aux: ver procesos corriendo
  - ps -aux | grep Firefox: buscar un proceso en especifico 
  - pstree: mostrar los procesos jerárquicamente

### Utilidades
- alias nombre ="sudo apt update && sudo apt upgrade": crear un comando
&&: unir comandos
- bash script.sh: ejecutar un script de bash
- clear: limpiar la consola
- df -h: mostrar detalles de los sistemas de archivos como el espacio total/usado
- free: ver información del uso de memoria usada/no usada
- history: ver el historial de todos los comandos
- ip addr: mostrar la dirección IP
- lsb_release -1: mostrar la versión de 
- man ls: ver función/información de un comando
- ping: comprobar conectividad con un servidor
- shutdown -c: apagar
- top: ver información acerca de los recursos y procesos en tiempo real.
- uname -a: ver versión del Kernel
- uptime: mostrar cuanto tiempo ha estado corriendo la máquina

### Docker
- docker ps: ver los contenedores que están activos
- sudo apt install docker-ce: instalar docker 
- sudo systenctl start docker: iniciar el contenedor
- sudo docker images: mostrar las imágenes descargadas
- sudo docker pull imagen: descargar una imagen 


![alt text](https://github.com/GenesisGonzalezM/Bitacora-Sistemas-Operativos/blob/master/Docker.png)
