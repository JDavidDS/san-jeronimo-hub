# Reglas obligatorias para agentes — San Jerónimo

Alcance: todos los agentes, herramientas y colaboradores que participen en el proyecto.

1. **Antes de actuar:** leer `AGENTS.md`, `CONTEXT.md`, `STATUS.md` y los ADR recientes pertinentes en `decisions/`. Consultar además los documentos del área y `RESOURCES.md`.
2. **Precedencia:** ante contradicciones, prevalece el contenido vigente de este repositorio frente al historial de chat. Contrastar afirmaciones especializadas con sus fuentes originales; no presentar este repositorio como sustituto de normas oficiales.
3. **Autoridad:** solo David aprueba decisiones institucionales. Los agentes proponen; no convierten propuestas en aprobaciones. Los ADR llevan estado **Propuesta / Aprobada / Rechazada / Reemplazada**, fecha y responsable de aprobación.
4. **Evidencia:** distinguir explícitamente **Hecho confirmado**, **Dato reportado pendiente de verificar**, **Supuesto** y **Propuesta**. No rellenar vacíos con inferencias presentadas como hechos.
5. **Colaboración:** después de esta carga inicial autorizada, trabajar mediante rama + pull request. Solo David integra cambios a `main`. Ningún agente hace merges ni cambios directos en `main` sin autorización expresa.
6. **Cierre:** actualizar `STATUS.md` al cerrar una sesión o tarea con cambios efectivos; si no se tiene acceso de escritura, entregar cambios propuestos y un handoff. Un estado parcial no se presenta como terminado.
7. **No duplicar:** cada hecho o documento tiene una fuente autoritativa. Enlazar en lugar de mantener copias editables divergentes. Drive almacena los archivos institucionales pesados; este repo guarda contexto, decisiones e índices.
8. **Privacidad:** cero datos sensibles en Git, Issues, PR, commits y handoffs. No publicar datos personales de estudiantes, identificaciones, secretos, tokens, contraseñas ni expedientes confidenciales. Un repo privado no sustituye controles de datos.
9. **Fuentes:** toda afirmación regulatoria, legal o financiera relevante debe indicar **fuente, enlace y fecha de consulta**; señalar vigencia, incertidumbre y necesidad de validación cuando corresponda.
10. **Trazabilidad:** los cambios de enfoque con consecuencias institucionales se documentan como ADR. Nunca borrar el historial: reemplazar decisiones mediante nuevos ADR y referencias cruzadas.
11. **Trabajo concurrente:** usar Issues y PR para evitar sobreescritura. `STATUS.md` refleja únicamente cambios consolidados en `main`.

## Handoff obligatorio para agentes sin acceso al repo

Al terminar una sesión sin acceso al repositorio, cerrar exactamente con esta estructura:

```text
HANDOFF [agente] [fecha]
Hecho: ...
Decisiones propuestas: ...
Pendiente / bloqueado: ...
Archivos nuevos (dónde están): ...
```

Este bloque no constituye aprobación automática de ninguna decisión.
