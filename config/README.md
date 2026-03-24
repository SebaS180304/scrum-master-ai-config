# scrum-master-ai-config

## File Format

YAML is used to define configuration files due to its simplicity and compatibility with multiple languages.

## Parameters

- **APP_NAME**: Application name.
- **PORT**: Port where the application runs.
- **ENVIRONMENT**: Environment (development, staging, production).
- **DB_HOST**: Database server address.
- **DB_PORT**: Database port.
- **DEBUG**: Enables logs and debugging.
- **FEATURE_FLAGS**: Enables specific features.

## Naming Conventions

- Use UPPERCASE for global parameters.
- File names: `<environment>.yaml`.
