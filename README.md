# ISAC20 - SCRIPTS DE INSTALACION DE ARCHLINUX

La instalación y configuración de archlinux nunca ha sido tan fácil!

Prerequisitos

    Conexion a Internet
    Usuario 'root'

Obteniendo Archivos
Con git
Seguir Estos Pasos:

    Aumentar la partición del cowspace: mount -o remount,size=2G /run/archiso/cowspace
    Obtenga una lista de paquetes e instálelos git: pacman -Sy git
    Obtener el Scripts: git clone git://github.com/jutamara90/ISAC20

Como Usar

    1 - instbase [Sistema Base]: cd ISAC20 ; ./instbase
    2 - instpost [Xorg, Escritorio, ETC.]: cd ISAC20 ; ./instpost


