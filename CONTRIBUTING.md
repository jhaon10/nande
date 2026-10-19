# Cómo colaborar

Gracias por querer sumar. Este proyecto es abierto y de todos.
**No necesitás saber programar:** también se necesita gente de diseño, traducción,
datos, comunicación y trabajo en terreno.

> **Regla de oro: primero se avisa, después se trabaja.**
> Así evitamos que dos personas hagan lo mismo sin saberlo.

## Cómo empezar en 3 pasos

1. Leé el [MANIFIESTO](MANIFIESTO.md) y el [Código de conducta](CODE_OF_CONDUCT.md).
2. Buscá un Issue con la etiqueta `good first issue` o `ayuda necesaria`.
3. Comentá "me lo asigno" y esperá a que un mantenedor te lo asigne.

## Flujo según el tamaño del cambio

| Tamaño | Ejemplos | Qué hacer |
|--------|----------|-----------|
| **Menor** | Typos, traducciones, documentación | Pull Request directo, sin Issue previo |
| **Mediano** | Una función nueva, un arreglo importante | Issue + esperar 48 horas de comentarios |
| **Grande** | Arquitectura, base de datos, sistema de votación | RFC (propuesta escrita en `docs/decisions`) + 7 días de discusión |

## Reglas para evitar trabajo duplicado

1. **Buscá antes de crear.** Revisá Issues, Pull Requests y Projects. Si alguien ya está
   en eso, sumate a su Issue.
2. **Reclamá el Issue.** Nadie más lo toca mientras lo tengas.
3. **Si te trabás, avisá.** Con más de una semana sin avance, comentalo para que otro
   pueda tomar el relevo. Trabarse es normal.

### Si dos personas quieren hacer lo mismo

- **Tareas distintas, mismo tema:** se hacen ambas y se integra lo mejor en la revisión.
- **La misma tarea exacta:** gana la mejor solución (no la primera). La otra queda como
  referencia y su autor/a se acredita igual.

**Nadie trabaja en vano: todo aporte se acredita en [CONTRIBUTORS.md](CONTRIBUTORS.md).**

## Ramas y Pull Requests

- Nunca trabajes sobre `main`. Usá ramas con nombre claro: `feat/votacion-comuna`,
  `fix/login`, `docs/readme-pt-br`, `i18n/quechua`.
- Un Pull Request = una tarea.
- Describí qué hiciste y cómo probarlo.
- Se necesita al menos 1 aprobación y que pasen los checks automáticos.

## Convención de commits

| Prefijo | Uso |
|---------|-----|
| `feat:` | nueva función |
| `fix:` | corrección |
| `docs:` | documentación |
| `chore:` | mantenimiento |
| `i18n:` | traducción |

Ejemplo: `feat: agregar voto restringido por comuna`

## Firma de commits (DCO)

Cada commit lleva `Signed-off-by` (usá `git commit -s`). Significa que tenés derecho a
aportar ese trabajo y aceptás que quede bajo la licencia del proyecto (AGPL-3.0).

## Áreas donde se necesita ayuda

- **Backend:** API, base de datos, verificación de residencia
- **Frontend:** PWA, feed, panel de transparencia
- **Datos:** integración con ChileCompra y portales de transparencia
- **UX/UI y accesibilidad**
- **Traducciones:** ver [docs/IDIOMAS.md](docs/IDIOMAS.md)
- **Comunicación y terreno:** juntas de vecinos, universidades, organizaciones locales

## Datos personales

Nunca subas al repositorio claves, archivos `.env`, ni datos reales de personas
(RUT, direcciones, fotos). Usá datos de prueba inventados.

## Idioma de trabajo

Cualquier idioma sirve en los Issues, siempre que se entienda. Si no, usá español o inglés.
