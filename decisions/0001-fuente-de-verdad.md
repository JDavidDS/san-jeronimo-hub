# ADR-0001 — Fuente de verdad y repositorios

- **Fecha:** 2026-10-31
- **Estado:** **Aprobada**
- **Propuesto por:** Agentes colaboradores (propuesta de arquitectura)
- **Aprobado por:** **David**, según aprobación expresamente comunicada para esta inicialización el 2026-10-31.
- **Fecha de aprobación:** 2026-10-31

## Contexto

San Jerónimo tendrá desarrollo institucional, web, plataforma y app, con colaboración de personas y varios agentes de IA. Se requiere un contexto central auditable, portable y con trazabilidad histórica.

## Alternativas consideradas

1. GitHub como fuente central y Drive para documentos.
2. Notion como fuente central.
3. GitHub + Drive, Notion opcional como tablero.

## Decisión

- Repositorio privado **`JDavidDS/san-jeronimo-hub`** como **fuente de verdad operativa** para contexto, estado, reglas y decisiones.
- **Repositorios separados por producto**, vinculados desde el hub; primer producto previsto: `san-jeronimo-web`, a crear posteriormente.
- **Google Drive institucional** como origen de archivos institucionales pesados y documentos de trabajo; enlazar originales desde el hub, sin duplicarlos.
- **Notion opcional en el futuro**, solo como vista/tablero; no introducir segunda fuente autoritativa.
- ADR individuales con estados Propuesta / Aprobada / Rechazada / Reemplazada; **solo David aprueba**.

## Motivo

Versionado y colaboración reproducible entre agentes y plataformas, separación de productos, preservación documental y menor fragmentación del conocimiento.

## Consecuencias

- Requiere disciplina para actualizar documentos y enlazar fuentes.
- Acceso de cada agente a GitHub/Drive debe configurarse por separado.
- Los productos mantienen sus repos propios, con enlaces a este hub.
- Tras la inicialización, los cambios se proponen en rama y PR; solo David integra a `main`.

## Referencias

- Aprobación y especificación comunicadas en la conversación del proyecto, **2026-10-31** (fuente interna; sin enlace público).
- [AGENTS.md](../AGENTS.md)
- [RESOURCES.md](../RESOURCES.md)
