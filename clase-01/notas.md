<!-- TOC ignore:true -->
# Clase 1 - 12/05/2021
<!-- TOC -->

- [Clase 1 - 12/05/2021](#clase-1---12052021)
- [Presentaciones](#presentaciones)
- [Historia Unix](#historia-unix)
- [Hypervisor](#hypervisor)
- [Centos 7](#centos-7)
- [Particionado](#particionado)
- [Comandos](#comandos)

<!-- /TOC -->


# Presentaciones

# Historia Unix

# Hypervisor
En Windows usando [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
y su [extensión](https://download.virtualbox.org/virtualbox/6.1.22/Oracle_VM_VirtualBox_Extension_Pack-6.1.22.vbox-extpack) 

En linux usar KVM

# Centos 7
Se crea eligiendo redhat, 2gb de ram, crear disco nuevo, VDI, 8GB

1. Ir a configuración
2. Red modo puente placa fisica
3. Almacenamiento seleccionar el iso
4. Iniciar

# Particionado
VolumeGroup partir en asignaciones lógicas (Logical Volume)

LVM

/ 4G -> create new volume group -> volgroup00 | name: lv_root | fileSystem xfs


swap 1G lv_swap

/boot 300M 

/home 3G lv_home

# Comandos
uname -a

shutdown -h now

id
