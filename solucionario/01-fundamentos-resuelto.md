# Cuaderno 01 · Solucionario del facilitador

**Tema:** LLM, tokens y contexto

**Correspondencia:** `cuadernos/01-fundamentos.md` y actividad del portal interactivo. Tres alternativas resueltas, para uso del facilitador. Son ejemplos ilustrativos, no resultados reales de ejecuciones de GPT.

## Alternativa 1 · Vocabulario de animales

**Desarrollo 1.** Prompt simple: «Crea una actividad infantil». Prompt mejorado: «Diseña una actividad de 15 min para niños de 4–5 años sobre vocabulario de animales de su entorno, con tarjetas grandes, apertura/desarrollo/cierre, apoyos inclusivos y tres indicadores».

**Producto o respuesta 2.** Respuesta esperada: exploración de tarjetas (3 min), imitación y descripción de animales (9 min), recapitulación (3 min); indicadores: nombra/señala, describe, participa.

**Verificación 3.** Frase para tokenizar: «Aprendemos jugando con palabras». Por espacios hay cuatro palabras; tokens reales dependen del tokenizador del modelo, por lo que no se afirma un número.

**Reflexión o prueba 4.** Reflexión: el contexto reduce ambigüedad, pero no garantiza verdad ni seguridad.

## Alternativa 2 · Reconocimiento de emociones

**Desarrollo 1.** Prompt simple: «Haz un cuento». Mejorado: «Crea un cuento participativo de 10 min para 4–5 años que favorezca nombrar alegría, tristeza y enojo, usando voz y movimientos; incorpora preguntas abiertas e inclusión».

**Producto o respuesta 2.** Producto esperado: relato de tres escenas, gestos opcionales, pregunta «¿Qué podría sentir el personaje?» y observación no diagnóstica.

**Verificación 3.** Tokenización de «Las emociones nos ayudan»: distinguir cuatro palabras separadas por espacios de tokens del modelo, sin inventar conteos.

**Reflexión o prueba 4.** Reflexión: edad, propósito y recursos mejoran adecuación; hay que comprobar sentido pedagógico.

## Alternativa 3 · Clasificación por formas

**Desarrollo 1.** Prompt simple: «Inventa un juego». Mejorado: «Planifica 20 min de clasificación de formas para 5–6 años con figuras grandes de cartón, variantes accesibles, consignas y registro observacional».

**Producto o respuesta 2.** Producto esperado: explorar formas (4 min), agrupar por criterios (12 min), explicar elecciones (4 min); indicadores: identifica, agrupa y justifica.

**Verificación 3.** Tokenización de «Clasificamos formas jugando»: tres palabras por espacios; no asumir tres tokens.

**Reflexión o prueba 4.** Reflexión: más información permite especificar el producto, no elimina la necesidad de revisión.

## Pauta común de revisión

Verificar: correspondencia entre entrada y producto; claridad de instrucciones; pertinencia del grupo etario; seguridad de materiales; accesibilidad; evaluación observacional sin diagnósticos; tratamiento responsable de datos infantiles.

**Alcance de la herramienta:** los analizadores del portal aplican reglas locales y producen modelos estructurados. No sustituyen validación humana, no consultan fuentes de forma automática y no prueban el Skill en GPT.

---
© Prof. Dr. Pablo José Guerrero. 2026 - https://guerrero-consultores.com/
