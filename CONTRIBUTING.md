# Guía de contribución

## Política de commits
Conventional Commits en español, imperativo, con referencia a Taiga:

    tipo(ámbito): descripción breve TG-<nº>

Tipos: feat, fix, docs, test, refactor, style, chore.

Ejemplos:
- feat(csv): añadir carga de ficheros TG-12
- fix(storage): evitar error al cargar modelo vacío TG-41

Reglas:
- Primera línea de máximo 72 caracteres.
- Un commit = un cambio lógico.
- Commits pequeños y frecuentes.

## Ramas
- main: versión estable (lo que se entrega)
- develop: integración
- feature/TG-<nº>-descripcion: una rama por tarea

## Pull Requests
- Todo cambio llega a develop mediante PR.
- Mínimo 1 revisión de otro miembro antes del merge.
- Sin push directo a main ni a develop.

## Estilo de código
- PEP 8, formateo con black y linting con flake8.

## Definition of Done
Pendiente de acordar en la reunión de estimación del backlog.