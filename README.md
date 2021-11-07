# Entorno laravel con docker

Éste repositorio incluye los archivos .yml, dockerfile y .conf para ejecutar un proyecto laravel en contenedores docker.

## Instalación

1. Clonar proyecto `git clone git@github.com:Emulator-Dnl/laravelEnvDocker.git` y cambiarse a directorio `cd laravelEnvDocker`
2. Crear directorios `mkdir src` y `mkdir mysql`
3. En línea de comandos ejecutar `docker-compose build` seguido por `docker-compose up -d`

Ahora sólo queda añadir el proyecto laravel a `src`, ya sea al crearlo mediante `composer create-proyect laravel/laravel .` o clonando el repositorio de un proyecto en desarrollo.