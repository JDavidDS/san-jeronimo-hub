# ADR-0005 — Aplicación de la línea de preapertura en piezas y botones

- **Fecha:** 2026-11-06
- **Estado:** **Aprobada**
- **Propuesto por:** Claude (marca), con los textos definidos por David
- **Aprobado/rechazado por:** **David**, en chat, el 2026-11-06
- **Fecha de aprobación/rechazo:** 2026-11-06

## Contexto

El [ADR 0003](0003-comunicacion-preapertura.md) fijó que cada landing y cada pieza lleva la línea corta: *"Programa en proceso de registro ante la Secretaría de Educación de Montería."* Quedaban dos dudas de aplicación:

- Qué texto va junto al botón de preinscripción.
- Qué hacer con las piezas que no nombran ningún programa (citas, aula, marca), porque la línea habla de "programa".

Claude propuso dos textos el 2026-11-06. David respondió en chat:

- **Hecho confirmado (decisión de David):** junto al botón va solo *"Preinscripción gratuita"*.
- **Dato reportado pendiente de soporte escrito:** ese texto ya está confirmado con los abogados.
- **Hecho confirmado (decisión de David):** las piezas que no mencionan programas no llevan ninguna línea.

## Alternativas consideradas

1. Microcopia larga: "Preinscripción gratuita. No es matrícula ni reserva de cupo." Más explícita; David la descartó.
2. Variante institucional para piezas sin programa ("En preapertura. Programas en proceso de registro…"). David la descartó.

## Decisión

- **Pieza o landing que nombra un programa:** lleva visible la línea del ADR 0003, con el texto exacto y sin cambios.
- **Junto a cada botón de preinscripción:** *"Preinscripción gratuita"*.
- **Pieza que no nombra ningún programa:** no lleva línea legal.
- Especificación visual (propuesta de Claude, a aplicar en el punto 4 del kit): Figtree 400; mínimo 24 px en piezas de 1080 px, 28 px en story, 14 px en web (16 recomendado), 8 pt en impreso; contraste mínimo 4,5:1; en web, en el primer pantallazo y junto a cada botón.

## Motivo

- Mantiene la protección del ADR 0003 donde se habla de un programa, sin cargar de texto legal las piezas institucionales.

## Consecuencias

- Las plantillas de programa del kit pasan de la línea completa (post-registro) a la línea corta mientras dure la preapertura. La línea completa se conserva para cuando cada programa tenga registro notificado.
- El manual debe corregir la fila "Programas sin registro: la pieza no sale", que quedó desactualizada con el ADR 0003.
- Guardar en la carpeta jurídica del Drive el soporte escrito de los abogados sobre "Preinscripción gratuita".
- El aviso completo (autorización de datos) del ADR 0003 no cambia.

## Referencias

- [ADR 0003](0003-comunicacion-preapertura.md).

## Historial

Precisa la aplicación del [ADR 0003](0003-comunicacion-preapertura.md); no lo reemplaza.
