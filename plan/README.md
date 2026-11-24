# Plan editorial mensual

El contenido se aprueba **una vez al mes**, con el plan completo:

1. Hacia el día 18 de cada mes, una tarea programada prepara el plan del mes siguiente en `plan/AAAA-MM.md`, lo sube en una rama y abre una pull request. Avisa con un resumen que empieza por «PLAN DE [MES] PENDIENTE DE APROBACIÓN».
2. Se revisa el plan en la pull request. Para pedir cambios, se comentan en la PR o se piden a Claude en la sesión de esa ejecución.
3. **Aprobar = mergear la PR en `main`.** Desde ese momento el plan queda aceptado.
4. La tarea de publicaciones (martes y jueves) lee `plan/AAAA-MM.md` de `main` y publica la entrada del día sin pedir más aprobaciones.

Reglas de la tarea de publicaciones:

- Si hay una entrada con la fecha de hoy, publica **esa** entrada: tema, pilar, formato, mensajes y palabra del CTA.
- Si la entrada dice `NO PUBLICAR`, no publica y lo indica en el resumen.
- Si no hay plan aprobado o no hay entrada para hoy, elige tema con la rotación de la skill, respetando los pilares y el historial, y lo avisa en el resumen.

## Formato de cada entrada

```
## AAAA-MM-DD (día)
- Pilar: Problemas | Precios | Comparativas | Casos y proceso | Tecnología aplicada | Mercado y datos
- Formato: tipo de carrusel (checklist, pasos, comparativa, mito vs realidad, caso, datos)
- Tema: titular de trabajo
- Mensajes clave: 3-5 ideas que debe contener
- Datos permitidos: cifras con su fuente (solo estas)
- CTA: palabra para comentar y qué se ofrece
- LinkedIn: enfoque del texto para la página de empresa
```

## Reglas comunes

- Público: pymes de 10 a 50 empleados que crecen (servicios B2B, salud con varias sedes, comercio e industria, turismo, formación).
- Voz: socio tecnológico solvente que explica con claridad. De tú, registro profesional, sin jerga vacía ni coloquialismos.
- Hablar como empresa («nuestro equipo», «nuestros ingenieros»); nunca «somos dos».
- No publicar precios propios de Corexia hasta que se apruebe el documento de precios. Se pueden dar rangos de mercado con fuente y explicar de qué depende el precio.
- Redes: Instagram y Google Business se programan en Metricool (plan Free, máximo 20 publicaciones al mes). LinkedIn se entrega como PDF y texto para subirlo a mano a la página de empresa. Facebook queda fuera mientras el plan Free no dé para más.
