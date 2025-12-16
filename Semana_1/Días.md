# Día 1
## Que es Linux?

Linux se encuentra desarrolla en cierta base de UNIX que a su vez esta en lenguaje ```C```.
Proyecto GNU - fue un proyecto basado tambien en UNIX pero queria ser libre y modificable para la comunidad siendo compatible, pero se volvió caro y privativo.

### Linus Torvalds
Se volvió el padre del SO Linux, creador del sistema que ahora tiene muchas distros y es ligero, modificable y desarrollado por y para la comunidad.

### Kernel
Que es? Es la parte central de un sistema operativo repsonsable de la gestión directa del hardware y los recursos del sistema.

Este controla el uso del:
* CPU
* Memoria
* Dispositivos E/S (Entrada / Salida)
* Ejecución de programas 

Esto fue tood un ecosistema un SO completo (programas, archivos y carpetas).  
Debajo de todo esta el Kernel, motor de la pc.  
Ejm: Doble click en un programa, indica al kernel como usar el procesador y la memoria para ejecutar el programa.  

Para crear un SO se usaba el kernel de Linux y las utilidades del GNU para tener un SO funcional llamados GNU/Linux y esto da al:
### Nacimiento de las Distribuciones.
* Uso General
* Juego
* Servidores

Android esta basada en Linux brindando ```Estabilidad y seguridad```

## File System
* Firmas únicas
* Estructuras únicas  

Almacena y gestiona los datos en discos de almacenamiento.  
Permitiendo:
- Crear
- Buscar
- Eliminar  

Directorio Raiz (Root) => `/..` (parte mas alta en la gerarquía)  

`/bin` Linea de comandos | correcto funcionamiento del sistema.
* `ls`
* `cp`
* `mv`
* `cat`  

`/sbin` Utilidad de sistemas especialisados usados por root.  
`*lib` Bibliotecas 
* Lectura de archivos
* Gestiona entradas y salidas
- Dependiendo del sistema se puede ver
    * `/lib31`
    * `/lib64`  
    Ambos bibliotecas de 31 y 64 bits, respectivamente.  

`/usr` (unit systems resources)
* Aplicaciones
* Bibliotecas
* Espacio de usuario
    * `/usr/bin`
    * `/usr/lib`
    * `/usr/sbin`

`/dev` Archivos de dispositivos como interfaces del hardware.  
`/boot` Directorio de arranque
* kernel
* memoria RAM
* initrd
* initramfs
* grub  

`/etc` Archivos de configuracion 