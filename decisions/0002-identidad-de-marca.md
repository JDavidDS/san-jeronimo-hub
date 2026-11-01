# ADR-0002 — Identidad de marca v1.0

- **Fecha:** 2026-11-01
- **Estado:** Propuesta
- **Propuesto por:** Claude (proyecto San Jeronimo en claude.ai), a partir de las elecciones que David expresó en chat entre el 13 y el 30 de octubre de 2026
- **Aprobado/rechazado por:** Pendiente (solo David)
- **Fecha de aprobación/rechazo:** Pendiente

## Contexto

San Jerónimo necesita una identidad cerrada antes de construir la página web, la app y las redes. El trabajo de marca ya produjo un sistema completo, pero ninguna decisión de marca está registrada como ADR. Por eso, según [AGENTS.md](../AGENTS.md), ninguna elección de marca cuenta todavía como aprobada.

**Elecciones expresadas por David en chat, pendientes de este ADR:**

- 13/10: nombre de trabajo, Instituto San Jerónimo.
- Punto de partida: el territorio "V2" que propuso Design Colibrí, con paleta vino y crema y monograma ISJ.
- 29/10: escudo C1 con el monograma y tipografía Playfair Display SC.
- 30/10: sistema en dos niveles, ceremonial y diario.
- 30/10: marca diaria D1 (monograma libre), con la placa D2 para íconos.
- 30/10: innovación entendida como A + B. A es pedagogía: aprender haciendo, con portafolio. B es tecnología e IA en clase, con revisión docente.

**Hechos confirmados:**

- Los logos están construidos en vectores.
- Las tipografías tienen licencia OFL (uso comercial libre).
- Los pares de color del sistema digital cumplen WCAG AA, verificado por cálculo.
- Los entregables listados en Referencias existen.

**Supuestos no validados:**

- Que el público prioritario, bachilleres de menores recursos y sus familias, lea la marca como confiable y no como cara o elitista.
- Que la marca no tenga conflicto ante la SIC, porque hay homónimos registrados.
- Que el proyecto pueda usar la propuesta original de Colibrí.

## Alternativas consideradas

1. **Adoptar el sistema en dos niveles (recomendada).**
   - Qué es: la marca diaria D1 con la placa D2 para todo lo cotidiano, y el escudo C1 solo para lo ceremonial.
   - Ventajas:
     - El escudo guarda la aspiración de largo plazo.
     - La marca diaria se ve contemporánea y funciona en pantallas pequeñas.
     - El sistema ya está completo y la web puede empezar ya.
   - Riesgos: gestionar dos niveles exige disciplina de uso. Lo mitiga el manual.
2. **Una sola marca, D1 en todo y sin escudo.**
   - Ventajas: más simple y más barata de mantener.
   - Riesgos: pierde el registro solemne que necesitan certificados y grados, y el puente visual hacia la etapa universitaria.
3. **Seguir explorando** (rutas B portal, D3 u otras).
   - Ventajas: podría mejorar el símbolo.
   - Riesgos: retrasa la web y las redes. Además, ya no hay un problema de marca sin resolver que lo justifique: lo que falta por saber se resuelve validando con el público, no diseñando más.

## Decisión (propuesta)

Adoptar la **Identidad de marca v1.0** y congelarla. A partir de la aprobación, todo cambio de logo, color o tipografía requiere un ADR nuevo.

| Elemento | Definición |
| --- | --- |
| Nombre | **San Jerónimo**. "Instituto" es el descriptor de la etapa y solo cambia con un reconocimiento legal nuevo |
| Marca diaria | D1: monograma ISJ libre + "INSTITUTO" (Figtree) + "San Jerónimo" (Playfair Display SC). Va en web, app, redes, WhatsApp, avisos, publicidad y uniformes |
| Placa | D2: el monograma calado en una placa redondeada. Va en el ícono de app, el favicon, las fotos de perfil y todo lo menor de 32 px |
| Escudo ceremonial | C1. Va solo en certificados, actas, sellos, actos de grado, la placa institucional y la papelería oficial. Nunca junto a la marca diaria |
| Color | Vino #7A0000 · vino profundo #31050F · crema #F6F3E4 · arena #C5B29E · petróleo #1F4E5A como único acento. Proporción 60/30/10 |
| Tipografía | Playfair Display para titulares (desde 24 px) y Figtree para todo lo demás. Playfair Display SC solo en el logo y en lo ceremonial |
| Recurso gráfico | La S del monograma ampliada y cortada por un borde, una vez por pieza |
| Voz | Exigente, cercana, clara y actual. Tuteo, datos antes que adjetivos, costo total siempre visible, sin urgencia falsa |
| Límites | No decir "universidad", "alta calidad", "acreditados", "empleo garantizado", ni "título" o "carrera" para un programa ETDH. No mostrar convenios sin firmar, programas sin registro ni símbolos religiosos |

**Condiciones de la aprobación.** La versión 1.0 se puede usar desde ya en todo lo digital, donde cambiar es barato. Antes de producir piezas físicas costosas (aviso de fachada, uniformes, papelería impresa en volumen) o de radicar el registro, deben cumplirse tres condiciones:

1. **Validación con público:** probar la marca con 10 a 15 bachilleres y familias de Montería. Se pregunta qué tipo de institución creen que es, cuánto creen que cuesta y si la ven religiosa. Si la mayoría percibe un precio muy por encima del real, se ajustan primero el tono y la fotografía, y no el logo.
2. **SIC:** búsqueda de antecedentes en la clase 41 y decisión sobre el registro de la marca mixta.
3. **Colibrí:** confirmación escrita de que el proyecto puede usar y modificar la propuesta original.

## Motivo

- **Ambición:** el sistema en dos niveles responde a la meta de David. Se ve serio hoy como instituto y puede crecer hacia una institución de educación superior sin rediseño.
- **Diferenciación:** según la auditoría competitiva del 29/10, ningún instituto técnico de Montería usa el vino ni una identidad sobria. La competencia promete sueños, rapidez o precio, y San Jerónimo ocupa el espacio libre: aprendizaje demostrable, costo total y acompañamiento.
- **Costo:** continuar la exploración cuesta tiempo de calendario de preapertura. La duda que queda es de percepción del público, y se resuelve con la validación de la condición 1.

## Consecuencias

- **Web y app:** se construyen desde el Design System. El repositorio de la web enlaza este ADR.
- **Redes:** se producen desde las plantillas del lienzo, sección 10, pasadas a Canva.
- **Drive:** el kit ISJ-marca-v2 debe quedar en la carpeta de marca del Drive institucional y enlazarse en [RESOURCES.md](../RESOURCES.md).
- **Publicidad de programas:** toda pieza lleva el número del acto de registro, el tipo de certificado, la modalidad y la secretaría que vigila, según el [Ministerio de Educación, preguntas frecuentes sobre ETDH, pregunta 1.7](https://www.mineducacion.gov.co/portal/micrositios-superior/Educacion-para-elTrabajo-y-el-Desarrollo-Humano/Conceptos-y-aclaraciones/411770:Preguntas-frecuentes), consultadas el 2026-10-30. Hasta tener registro no se publican piezas de programas.
- **Riesgo residual:** que la validación o la SIC obliguen a cambiar el nombre o el símbolo. En ese caso, este ADR se reemplaza y no se borra.

## Referencias

Los artefactos están en claude.ai, en la cuenta de David, y son privados hasta que se compartan:

- Manual de marca v1.0 (Docs): https://claude.ai/artifact/2UCsKB42jNKSeANYTkFc9p
- Design System: https://claude.ai/artifact/MoZhyRERxDVD4SLyebqiE6
- Lienzo de marca, con la evolución del logo y las plantillas de redes: https://claude.ai/artifact/YNNXKZMz2RUP6NqmVRbgyq
- Plataforma de marca v0.1: https://claude.ai/artifact/TWux7u18XAiDVTN5huLoba
- Auditoría competitiva visual: https://claude.ai/artifact/W7oJStBKQSjaKLbZZjC3Sd
- Kit ISJ-marca-v2.zip: entregado en el chat del proyecto el 2026-10-30. Pendiente de subir al Drive.
- Ley 30 de 1992, arts. 20, 24 y 98, consultada el 2026-10-30: https://cancilleria.gov.co/sites/default/files/Normograma/docs/ley_0030_1992.htm

## Historial

Sin reemplazos.
