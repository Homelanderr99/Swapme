# Guía de Contribución

Gracias por querer contribuir a SwapMe. Esta guía resume el proceso para mantener el proyecto ordenado y trazable.

## Flujo de trabajo
1. Crea una rama descriptiva: `feature/...` o `fix/...`.
2. Haz commits pequeños y frecuentes.
3. Abre un Pull Request hacia `main` con descripción clara.
4. Solicita revisión y atiende comentarios.

## Convenciones de commits
Usa mensajes en español, claros y en modo imperativo.
Opcionalmente, puedes seguir "Conventional Commits":
- `feat: descripción` para nuevas funciones.
- `fix: descripción` para correcciones.
- `docs: descripción` para documentación.
- `chore: descripción` para tareas varias.

Incluye contexto si aplica (p.ej. módulo/carpeta afectada).

## Estilo de código
- Mantén el estilo consistente del proyecto.
- Incluye pruebas/unitarias si hay.
- Actualiza documentación cuando cambie el comportamiento.

## Versionado y changelog
- Usa SemVer.
- Actualiza `CHANGELOG.md` en cada PR con las secciones correspondientes.

## Revisión y merge
- Al menos una aprobación antes de merge.
- Rebase o squash según convenga para mantener historial limpio.