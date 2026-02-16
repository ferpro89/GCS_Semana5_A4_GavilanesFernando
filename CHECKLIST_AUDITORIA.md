# Checklist de Control de Integridad

## Reglas aplicadas en el proyecto

- Todo cambio debe iniciar desde un Issue.
- Toda modificación debe realizarse en una rama distinta a main.
- Todo commit debe referenciar el Issue correspondiente.
- Todo cambio debe pasar por Pull Request.
- El Pull Request debe ser revisado antes de hacer merge.
- No se permiten archivos sensibles (.env).
- Las versiones deben seguir Semantic Versioning (vMAJOR.MINOR.PATCH).
- Todo release debe incluir notas de cambios y evidencia.

## Validación realizada

Se comprobó que:

- Issue → Rama → Commit → PR → Merge → Release
- No existen archivos sensibles.
- Versionado aplicado correctamente (v1.1.0, v1.2.0).
