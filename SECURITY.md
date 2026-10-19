# Política de seguridad

## Contacto para reportes de vulnerabilidades

**No abras un Issue público.** Escribí a security@nandenewen.example.org con:

- Descripción del problema
- Pasos para reproducirlo
- Impacto estimado

Respondemos en un máximo de 72 horas.

## Datos sensibles

Este proyecto manejará datos personales. Reglas desde el día 1:

- Nunca subir claves, tokens ni archivos `.env`.
- Nunca subir datos reales de usuarios. Usar datos de prueba.
- Identificadores como el RUT no se guardan en texto plano (usar HMAC con clave secreta fuera de la base de datos).
- La identidad y el voto de una persona se guardan separados.
