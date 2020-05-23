##
<h1 align="center">ISAC20 - SCRIPTS DE INSTALACION DE ARCHLINUX</h1>
    
<h4 align="center">La instalación y configuración de archlinux nunca ha sido tan fácil!</h4>

## PREREQUISITOS

    *Conexion a Internet
    *Usuario 'root'

## OBTENIENDO ARCHIVOS CON GIT
## SEGUIR ESTOS PASOS:
    *Aumentar la partición del cowspace: mount -o remount,size=2G /run/archiso/cowspace
    *Obtenga una lista de paquetes e instálelos git: pacman -Sy git
    *Obtener el Scripts: git clone git://github.com/jutamara90/ISAC20
    *Si al momento de ejecutar el archivo sale error de permisos puedes ejecutar el siguiente comando "chmod 777 archivo". 

## COMO USAR
    1 - instbase [Sistema Base]: cd ISAC20 ; ./installbase
    2 - instpost [Xorg, Escritorio, ETC.]: cd ISAC20 ; ./instpost


