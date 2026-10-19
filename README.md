# Ñande

*Ñande* es una palabra guaraní que significa **"nosotros"**, incluyéndote a vos. No "nosotros contra ellos": nosotros todos.

**Plataforma cívica abierta para que los latinoamericanos estemos más conectados con lo que pasa en nuestros países.**

No es de derecha ni de izquierda. No pertenece a ningún partido, gobierno ni empresa.
Es una herramienta para que el vecino participe, vote lo que su barrio necesita
y vea con datos públicos cómo se gasta realmente el dinero de su comuna.

> Leé la [Carta / MANIFIESTO](MANIFIESTO.md) para entender la idea y los [PRINCIPIOS](PRINCIPIOS.md) para ver cómo trabajamos.

## ¿Por qué existe?

- La participación local en Latinoamérica es baja, y en Chile está entre las más bajas de la región.
- Los datos de gasto público existen, pero casi nadie los cruza con lo que la gente pide.
- Cada territorio vive aislado: no sabemos qué pasa en el barrio, la ciudad o el país de al lado.

## ¿Cómo funciona? (visión del producto)

1. **Registro** con verificación de residencia.
2. **Propuesta**: el vecino publica qué necesita su barrio (con foto).
3. **Voto**: solo votan los residentes de esa comuna en su comuna.
4. **Sugerencia**: la propuesta más votada se presenta al municipio (consultiva, no vinculante).
5. **Transparencia**: un panel muestra lo que la gente pide vs. lo que se gasta.
6. **Conexión**: cualquier persona puede ver lo que pasa en otros territorios de Latinoamérica.

## Etapas

1. **Plataforma cívica** (propuestas, votos, transparencia): la que empezamos hoy.
2. **Información verificable** de cada región, con fuentes públicas.
3. **Mensajería latinoamericana abierta y cifrada** (visión a futuro, sobre protocolos abiertos como Matrix o Signal).

## Estado del proyecto

🌱 **Fase 0: cimientos.** Estamos armando las bases y buscando gente. Ver [ROADMAP.md](ROADMAP.md).

**Piloto:** San Bernardo (Región Metropolitana, Chile) → Puente Alto → otras comunas → otros países.

## Stack técnico (propuesto)

| Capa | Tecnología |
|------|------------|
| Backend | NestJS |
| Base de datos | PostgreSQL + PostGIS |
| Frontend | Next.js (PWA) |
| Datos públicos | ChileCompra y portales de transparencia |

Las decisiones técnicas se discuten abiertamente. Ver [docs/decisions](docs/decisions).

## Idiomas

Multiidioma desde el diseño: español (con todas sus variantes), portugués, lenguas
originarias e inglés. Ver [docs/IDIOMAS.md](docs/IDIOMAS.md).

## ¿Cómo puedo colaborar?

**No hace falta saber programar.** Se necesita gente de código, diseño, datos, traducción,
comunicación y trabajo en terreno. Empezá por [CONTRIBUTING.md](CONTRIBUTING.md)
y buscá los Issues con la etiqueta `good first issue`.

## Comunidad

- Canal de chat: pendiente (Discord o Telegram)
- Reunión abierta mensual: pendiente
- Contacto: info@nandenewen.example.org (correo de prueba)
- Reportes de seguridad: security@nandenewen.example.org

## Licencia

[AGPL-3.0](LICENSE). Todo lo que se construya aquí queda abierto para siempre.
