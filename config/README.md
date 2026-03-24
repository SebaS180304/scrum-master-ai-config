# scrum-master-ai-config

## Formato de archivos

Se utiliza YAML para definir los archivos de configuración por su simplicidad y compatibilidad con múltiples lenguajes.

## Parámetros

- **APP_NAME**: Nombre de la aplicación.
- **PORT**: Puerto en el que se ejecuta la aplicación.
- **ENVIRONMENT**: Entorno (development, staging, production).
- **DB_HOST**: Dirección del servidor de base de datos.
- **DB_PORT**: Puerto de la base de datos.
- **DEBUG**: Activa logs y debugging.
- **FEATURE_FLAGS**: Activación de funcionalidades específicas.

## Convenciones de nomenclatura

- Uso de MAYÚSCULAS para parámetros globales.
- Nombres de archivos: `<environment>.yaml`.
