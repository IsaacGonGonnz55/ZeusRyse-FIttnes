# ZeusRyse Fitnnes

Aplicacion movil adaptada para sitios web, desarrollada con Spring Boot backend y Flutter como Frontend y base de datos PostgreSQL.

## Arquitectura 

-`backend/`: API REST desarrollada con Spring Boot
_`frontend`: Interfaz web y mobil desarrollada con Flutter
-`docs/`: Documentación Tecnica y Arquitectura

Los requisitos de Java, Spring Boot, Flutter y la base de datos se definirán segun las versiones seleccionadas para el proyecto

## Tecnologías previstas
- Java 21
- Spring Boot 4.1.1
- Maven Wrapper
- Flutter stable
- PostgreSQL
-Git

## Configuración

1. Clonar el repositorio
2. Configurar las variables de entorno
3. Iniciar el Backend
4. Instalar las dependencias del Frontend
5. Ejecutar Flutter en modo web

## Desarrollo local

Los procedimientos de instalación, configuración y ejecución se documentarán en `docs/` conforme se configure el proyecto.

## Seguridad
- No versionar archivos `env` reales.
- No guardar contraseñas ni claves privadas en Git.
- El acceso a PostgreSQL s realizará desde el backend.
- El FrontEnd consumira la API mediante HTTP durante el desarrollo local y HTTPS cuando corresponde en un entorno protegido.

