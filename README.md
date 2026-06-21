<div align="center">

# Comandos Esenciales de Ubuntu

### Kit de supervivencia para diagnosticar, administrar y mantener sistemas Linux desde terminal.

![Platform](https://img.shields.io/badge/Platform-Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?logo=gnubash&logoColor=white)
![Level](https://img.shields.io/badge/Level-Essential-blue)
![Use](https://img.shields.io/badge/Use-Administration-yellow)
![Topic](https://img.shields.io/badge/Topic-Linux%20Commands-purple)

</div>

---

## Descripcion

Este repositorio contiene una guia rapida de comandos esenciales para trabajar con Ubuntu/Linux. Esta pensado como una hoja de referencia practica para administracion basica, diagnostico del sistema, monitoreo, redes, paquetes, permisos, servicios y tareas frecuentes desde consola.

El archivo principal es:

```text
COMANDOS ESENCIALES
```

## Contenido principal

| Area | Que cubre |
| --- | --- |
| Diagnostico | Informacion del sistema, memoria, disco y procesos |
| Red | Puertos abiertos, conectividad, interfaces e IPs |
| Paquetes | Instalacion, actualizacion y eliminacion con APT |
| Archivos | Navegacion, permisos, busqueda y manipulacion |
| Servicios | Revision y control con systemctl |
| Seguridad | Comandos utiles para revisar el estado del sistema |

## How-To: usar esta guia

1. Abre el archivo `COMANDOS ESENCIALES`.
2. Busca la categoria que necesitas.
3. Copia el comando correspondiente.
4. Ejecutalo en una terminal de Ubuntu.
5. Si el comando modifica el sistema, revisalo antes de usarlo con `sudo`.

## Requisitos

- Ubuntu Server o Desktop.
- Acceso a terminal.
- Permisos de administrador para comandos con `sudo`.
- Conocimiento basico de rutas, usuarios y servicios Linux.

## Ejemplos de uso

```bash
uname -a
free -h
df -h
top
sudo systemctl status ssh
```

## Buenas practicas

- Ejecuta primero comandos de lectura antes de hacer cambios.
- No uses `sudo` si no es necesario.
- Documenta los cambios importantes que realices.
- Verifica siempre la salida del comando antes de continuar.

## Autor

Repositorio academico y practico para consulta rapida de comandos Linux.
