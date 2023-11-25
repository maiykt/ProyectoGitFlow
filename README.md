# ProyectoGitFlow

# Proyecto de Ejemplo con Git Flow

Este repositorio es un proyecto de ejemplo que demuestra el uso de Git Flow para organizar y gestionar el desarrollo de software.

## Ramas Principales

- **main**: Rama principal que refleja la versión en producción del proyecto.
- **develop**: Rama de desarrollo continua donde se integran las características.

## Ramas de Funcionalidades

- **feature/exportar-reporte-drive**: Rama que contiene la implementación de la funcionalidad de exportar reporte a Google Drive.
- **feature/login-con-facebook**: Rama que contiene la implementación de la funcionalidad de inicio de sesión con Facebook.

## Ramas de Mantenimiento

- **hotfix/login-linkedin**: Rama de corrección de errores críticos, en este caso, solucionando un problema relacionado con el inicio de sesión con LinkedIn.

## Ramas de Lanzamiento

- **release/v1.2.0**: Rama dedicada a preparar la versión 1.2.0 para su lanzamiento. Aquí se realizan las últimas pruebas y ajustes antes de fusionar en la rama principal.

## Instrucciones para Desarrolladores

### Clonar el Repositorio



# Cambiar a la rama de desarrollo
git checkout develop

# Crear nueva rama para una funcionalidad
git flow feature start nombre-de-la-funcionalidad

# Realizar cambios y commits en la rama de la funcionalidad

# Finalizar la funcionalidad
git flow feature finish nombre-de-la-funcionalidad

# Crear nueva rama para un hotfix
git flow hotfix start nombre-del-hotfix

# Realizar cambios y commits en la rama del hotfix

# Finalizar el hotfix
git flow hotfix finish nombre-del-hotfix

# Crear nueva rama para el lanzamiento
git flow release start v1.2.0

# Realizar pruebas y ajustes finales

# Finalizar el lanzamiento
git flow release finish v1.2.0
