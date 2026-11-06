# ADR-0004 — Identidad de marca v1.1: afinado de dibujo del logo

- **Fecha:** 2026-11-06
- **Estado:** Propuesta
- **Propuesto por:** Claude (marca)
- **Aprobado/rechazado por:** Pendiente (solo David). El 2026-11-06 David escribió en chat "Me gusta la v1.1"; falta su confirmación expresa para marcarla Aprobada.
- **Fecha de aprobación/rechazo:** Pendiente

## Contexto

El [ADR 0002](0002-identidad-de-marca.md) aprobó y congeló la identidad v1.0 el 2026-11-01: cualquier cambio de logo, color o tipografía requiere un ADR nuevo.

Al preparar el Kit Maestro para la imprenta y el diseñador se revisó el logo a tamaño grande y pequeño. **Hechos observados** en los archivos v1.0:

- En el monograma, el fuste de la J queda casi oculto detrás del remate de la S: deja una astilla delgada y un muñón junto al remate, que se empastan al imprimir.
- Los cortes entre letras (4,2 % del alto de la mayúscula) se cierran por debajo de unos 32 px.
- "INSTITUTO" va al 34 % del alto de "San Jerónimo" con un espaciado de casi una letra, y se pierde en tamaños pequeños.
- A 16 px (favicon) la S y la J se funden.

## Alternativas consideradas

1. **Dejar la v1.0.** Sin costo de cambio; los defectos se notan en impresión grande y en celular.
2. **Afinado de dibujo, sin cambio de concepto (propuesta).** Mismo monograma, letras, colores y proporción.
3. **Rediseño.** Descartado: la identidad está aprobada y los socios ya la conocen.

## Decisión (propuesta)

Adoptar la **identidad v1.1** con cuatro ajustes:

1. La J se desplaza 8 unidades a la derecha para salir de detrás del remate de la S.
2. Los cortes pasan de 4,2 % a 5,5 % del alto de la mayúscula.
3. "INSTITUTO" sube de 34 % a 40 % del alto de "San Jerónimo", con espaciado de 0,30 em.
4. Se crea la versión **monograma-micro** (cortes de 10 %) solo para tamaños de 24 px o menos (favicon, avisos diminutos).

El escudo ceremonial usa el monograma afinado. No cambian el concepto, Playfair Display SC Bold y Figtree, la proporción monograma/nombre, el escudo ni ningún color.

## Motivo

- Mejora la legibilidad en celular y la reproducción en imprenta sin costo de reconocimiento.
- Se hace antes de mandar a producir papelería, avisos y uniformes, cuando el cambio aún es barato.

## Consecuencias

- Con la aprobación, el kit pasa a `ISJ_Kit-de-Marca_v1.1` en el Drive (07 › 02 Kit de marca) y la carpeta `ISJ-marca-v2` se mueve a 99 Archivo histórico.
- El diseñador produce los masters `.ai`, CMYK y Pantone con la guía técnica del kit (`09_Para-el-disenador`).
- El manual, el Design System, el lienzo de marca y las plantillas se actualizan al logo v1.1 en el punto 4 (diagramación del manual y plantillas en Adobe).
- Mientras no se apruebe, la versión vigente sigue siendo la v1.0.

## Referencias

- [ADR 0002](0002-identidad-de-marca.md).
- Lámina antes/después y kit v1.1: entregados a David en chat el 2026-11-06; se enlazan desde el Drive al aprobar.

## Historial

Modifica el [ADR 0002](0002-identidad-de-marca.md) solo en el dibujo del logo. El resto del ADR 0002 sigue vigente.
