# Cuaderno 06 · Tres soluciones de referencia para el facilitador

**Correspondencia directa con el Micro-laboratorio 05: Fábrica de aplicaciones educativas inteligentes.** Estos son diseños y productos esperados; **no se afirma que se haya construido o probado realmente un prototipo**.

## Alternativa 1 · Cuento participativo animado
- **Selector:** Cuento participativo animado.
- **Edad:** 4 a 5 años. **Área:** Lenguaje y comunicación. **Duración:** 15 minutos.
- **Objetivo:** reconocer personajes y narrar acciones con palabra, gesto o señalamiento.
- **Contexto:** aula, proyector o tableta y acompañamiento docente.
- **Modalidad:** aplicación web HTML, CSS y JavaScript.
- **SKILL.md, nombre:** `parv-cuento-interactivo`.
- **Procedimiento que debe contener:** validar entradas; construir tres escenas; añadir dos elecciones seguras por escena; incluir narración opcional; crear controles comenzar, siguiente, anterior y reiniciar; ofrecer participación multimodal; comprobar seguridad y calidad.
- **Especificación:** inicio con título; tres escenas con personajes grandes; decisiones y respuestas respetuosas; cierre con recapitulación; controles accesibles.
- **Producto esperado:** cuento navegable en navegador, no simple historia en texto.
- **Pruebas:** los botones deben responder, las escenas no salirse de pantalla, no almacenar datos infantiles y permitir completar la actividad sin audio.

## Alternativa 2 · Ruleta de emociones
- **Selector:** Ruleta de emociones.
- **Edad:** 4 a 5 años. **Área:** Desarrollo socioemocional. **Duración:** 10 minutos.
- **Objetivo:** identificar y nombrar emociones por palabras, imágenes o movimientos voluntarios.
- **Contexto:** espacio de juego con pantalla táctil y docente.
- **Modalidad:** aplicación web HTML, CSS y JavaScript.
- **SKILL.md, nombre:** `parv-ruleta-interactivo`.
- **Procedimiento:** confirmar emociones a trabajar; programar giro con resultado visible; mostrar ejemplo no invasivo; ofrecer botón pasar turno; incorporar refuerzo sin puntuación punitiva; probar reinicio.
- **Especificación:** ruleta con alegría, tristeza, sorpresa y calma; giro; tarjeta explicativa; gesto opcional; nueva ronda.
- **Producto esperado:** ruleta funcional con controles grandes y participación voluntaria.
- **Pruebas:** evitar animaciones intensas; comprobar giro y restablecimiento; no solicitar relatos personales privados ni inferir estados psicológicos.

## Alternativa 3 · Juego de clasificación con integración MCP
- **Selector:** Juego de clasificación.
- **Edad:** 5 a 6 años. **Área:** Pensamiento lógico. **Duración:** 20 minutos.
- **Objetivo:** agrupar figuras grandes por forma y comunicar un criterio de clasificación.
- **Contexto:** aula con computadora y supervisión.
- **Modalidad:** componente visual integrado mediante servidor MCP.
- **SKILL.md, nombre:** `parv-clasificacion-interactivo`.
- **Procedimiento:** especificar objetivos y edad; diseñar panel de figuras con clic y alternativas a arrastrar; declarar estados del juego; definir herramientas MCP para iniciar partida, registrar una acción y reiniciar; diseñar recurso visual; comprobar permisos, estado y accesibilidad.
- **Especificación:** componente de clasificación en interfaz visual; herramientas disponibles para gestionar estado; servidor MCP alojado y configuración de integración con ChatGPT.
- **Producto esperado:** proyecto de servidor MCP y componente visual **por desarrollar**. El `SKILL.md` y la especificación no constituyen por sí mismos una integración funcional.
- **Pruebas pendientes de ejecución real:** llamadas a herramientas, comunicación interfaz-servidor, reinicio, validación de estado, accesibilidad y ausencia de datos personales.

## Rúbrica de revisión para las tres alternativas
| Criterio | Evidencia exigible |
|---|---|
| Coherencia didáctica | Objetivo observable y mecánica adecuados |
| Interactividad | Controles con comportamiento definido |
| Accesibilidad | Alternativas a arrastre/audio, textos e iconos claros |
| Seguridad | Contenido y materiales apropiados, sin datos identificables |
| Validación | Registro explícito de pruebas ejecutadas o pendientes |

**Uso interno del facilitador:** contrastar los artefactos de los participantes y diferenciar una especificación de un producto realmente ejecutable.

---
© Prof. Dr. Pablo José Guerrero. 2026 - https://guerrero-consultores.com/
