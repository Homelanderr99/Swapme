# SwapMe

Proyecto inicial para gestionar "SwapMe": documentación, versionado, servicio y página.

## Objetivo
Dejar todo detallado en español: estructura del proyecto, flujo de trabajo con Git/GitHub, registro de cambios, versiones (SemVer) y lineamientos de contribución.

## Estructura (propuesta)
- `frontend/`: código de la página (por definir).
- `backend/`: servicio/API (por definir).
- `docs/`: documentación adicional (opcional).
- `CHANGELOG.md`: registro de cambios.
- `CONTRIBUTING.md`: guía de contribución.

## Flujo de trabajo con Git
- Rama principal: `main`.
- Ramas de características: `feature/nombre-clarito`.
- Ramas de corrección: `fix/descripcion-corta`.
- Pull Requests con descripción clara y checklist.
- Revisiones antes de merge a `main`.

## Versionado (SemVer)
Usaremos `MAJOR.MINOR.PATCH`.
- `MAJOR`: cambios incompatibles.
- `MINOR`: nuevas funciones compatibles.
- `PATCH`: correcciones y mejoras menores.

Ejemplos: `0.1.0` inicial, `0.2.0` nueva sección de página, `0.2.1` fix.

## Registro de cambios
El archivo `CHANGELOG.md` sigue el estilo "Keep a Changelog" adaptado al español.

## Entrega y despliegue
Por definir según hosting/servicio elegido. Se añadirán instrucciones aquí cuando se configure el pipeline.

## Cómo empezar
1. Clonar el repo: `git clone <URL-del-repo>`
2. Crear una rama para tu cambio: `git checkout -b feature/tu-cambio`
3. Enviar PR a `main`.

## Contribución
Consulta `CONTRIBUTING.md` para convenciones de commits, estilo y proceso de revisión.