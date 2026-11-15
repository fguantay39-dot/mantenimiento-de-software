# Mantenimiento de Software

Repositorio oficial para las actividades prácticas y laboratorios de la materia **Mantenimiento de Software**.

* **Estudiante:** Franco Guantay
* **Profesor:** Artaza
* **Año:** 2026

## Estructura del Repositorio

```text
mantenimiento-de-software/
├── README.md
└── linux/
    ├── tp-sistemas-de-archivos/
    │   ├── README.md
    │   └── assets/
    │       ├── 01_raiz_ls.png
    │       ├── 02_case_sensitivity.png
    │       ├── 03_archivos_ocultos.png
    │       ├── 04_creacion_directorio.png
    │       └── 05_proc_dev.png
    │
    ├── tp-comandos-basicos/
    │   ├── README.md
    │   └── assets/
    │       ├── 01_navegacion_archivos.png
    │       ├── 02_procesos_top.png
    │       ├── 03_info_sistema.png
    │       └── 04_red_espacio.png
    │
    ├── tp-usuarios-y-grupos/
    │   ├── README.md
    │   └── assets/
    │       ├── 01_creacion_grupo_usuario.png
    │       ├── 02_pertenencia_grupos.png
    │       ├── 03_modificacion_usuario.png
    │       ├── 04_ficheros_configuracion.png
    │       └── 05_eliminacion_usuario_grupo.png
    │
    └── tp-permisos-y-propiedad/
        ├── README.md
        └── assets/
            ├── 01_lectura_permisos_ls.png
            ├── 02_chmod_octal.png
            ├── 03_chmod_simbolico.png
            ├── 04_cambio_propietario_grupo.png
            └── 05_chmod_recursivo.png
```

## Trabajos Prácticos de Laboratorio

1. **[TP 1: Exploración del Sistema de Archivos en Linux](linux/tp-sistemas-de-archivos/README.md)**
   * Jerarquía de directorios raíz (`/etc`, `/home`, `/dev`, `/var`).
   * Sensibilidad a mayúsculas y minúsculas (*Case Sensitivity*).
   * Visualización y gestión de archivos ocultos (*dotfiles*).
   * Buenas prácticas en nombres de archivos en UNIX.
   * Exploración de dispositivos y procesos (`/dev` y `/proc`).

2. **[TP 2: Comandos Básicos, Procesos y Utilidades en Linux](linux/tp-comandos-basicos/README.md)**
   * Gestión de archivos, directorios y copias (`pwd`, `mkdir`, `cd`, `touch`, `cp`, `ls -al`).
   * Monitoreo y control de procesos (`ps`, monitor interactivo `top`, terminación con `kill pid`).
   * Información del sistema y del núcleo (`uname -a`, `arch`, `/proc/cpuinfo`, `free -h`).
   * Diagnóstico de red y espacio en disco (`df -h`, conectividad con `ping`).

3. **[TP 3: Administración de Usuarios y Grupos en Linux](linux/tp-usuarios-y-grupos/README.md)**
   * Creación de usuarios y grupos primarios con directorio personal (`groupadd`, `useradd -m`, `passwd`).
   * Gestión y pertenencia de grupos secundarios (`adduser`, `gpasswd`, `deluser`, `groups`).
   * Modificación de atributos de usuario preexistentes (`usermod -d`).
   * Inspección y análisis de ficheros de configuración (`/etc/passwd`, `/etc/group`, `/etc/shadow`).
   * Eliminación segura de cuentas y grupos (`userdel -r`, `groupdel`).

4. **[TP 4: Permisos de Archivos, Directorios y Propiedad en Linux](linux/tp-permisos-y-propiedad/README.md)**
   * Lectura e interpretación del formato largo (`ls -l`, tipos `-`, `d`, `l`, tríadas `rwx`).
   * Asignación de permisos en modo octal (`chmod 640`, `chmod 755`).
   * Asignación de permisos en modo simbólico (`chmod go-x`, `chmod a+w`).
   * Cambio de grupo y propietario (`chgrp`, `chown` con privilegios `sudo`).
   * Permisos recursivos sobre directorios (`chmod -R 700`) e importancia del bit de ejecución (`x`).
