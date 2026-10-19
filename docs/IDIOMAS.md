# Idiomas y culturas

Este proyecto nace en Chile pero es de toda Latinoamérica. Ningún pueblo debe quedar
afuera por su idioma.

## Idiomas planificados

- **Español:** lengua principal, con respeto por cada variante (chilena, argentina,
  mexicana, colombiana, peruana, caribeña, etc.)
- **Portugués (Brasil)**
- **Lenguas originarias:** quechua, aimara, guaraní, mapudungun, náhuatl y las que la
  comunidad quiera sumar
- **Inglés:** para que el proyecto sea visible fuera de la región

## Principios

1. Traducir no es solo texto: es tono, humor y referencias culturales.
2. Cada país puede tener su propio archivo, sin pisar a los demás.
3. Las variantes locales se respetan. No hay un "español neutro" que mande.
4. Toda traducción se acredita en [CONTRIBUTORS.md](../CONTRIBUTORS.md).
5. Las lenguas originarias se trabajan con revisión de hablantes nativos, idealmente
   junto a organizaciones de esos pueblos.

## Organización

```
/locales
  /es      español general
  /es-cl   español de Chile
  /pt-br   portugués de Brasil
  /qu      quechua
  /gn      guaraní
  /en      inglés
```

**Cadena de respaldo:** si falta una frase en `es-cl`, se muestra la de `es`; si falta
ahí, la de `en`. Nunca se muestra un error al usuario.

## Meta cultural

Que un vecino de San Bernardo pueda leer lo que publica uno de Recife, de Cusco o de
Oaxaca, y entenderlo.

## Sobre el nombre

*Ñande* viene del guaraní. Pedimos a hablantes nativos que revisen y corrijan el uso
del nombre y su significado en cualquier texto del proyecto. Para direcciones web y
nombres de repositorio usamos la forma sin tilde: `nande`.
