# Cuaderno 03 · Solución integral: asistentes, agentes, RAG y Skills

## Clasificación de casos
| Situación | Solución principal | Justificación |
|---|---|---|
| a. Responder una consulta didáctica | Asistente | Conversación e instrucciones |
| b. Consultar un currículo aportado | RAG o recuperación documental | Fundamentar respuesta en el documento y comprobar citas |
| c. Ejecutar varios pasos con herramientas | Agente | Planificación, uso de herramientas autorizadas y verificación |
| d. Aplicar una pauta recurrente de planificación | Skill | Procedimiento reutilizable, estructurado y comprobable |

Las categorías son complementarias: un agente puede invocar un Skill y apoyarse en recuperación documental.

## Caso 1 · Adecuación de experiencias al currículo
**Necesidad:** crear una secuencia sobre clasificación de objetos alineada con una guía curricular que entrega el docente. **Diseño:** recuperación del documento para identificar resultados y criterios; asistente para dialogar; Skill para aplicar la plantilla de secuencia. **Flujo:** recibir guía → localizar objetivos → comprobar contexto → diseñar experiencia → citar ubicación relevante → revisión docente. **Control:** si el texto curricular no contiene un objetivo, no inventarlo.

## Caso 2 · Revisión repetible de planificaciones
**Necesidad:** analizar planificaciones de diferentes grupos. **Solución principal:** Skill REVISOR-PARV.
- Entradas: plan sin datos personales, edad, contexto, criterios institucionales.
- Procedimiento: verificar propósito, secuencia, recursos seguros, inclusión, indicadores.
- Salida: matriz criterio | evidencia | estado | observación | corrección.
- Límites: no calificar desarrollo individual de un niño ni atribuir diagnósticos.

## Pregunta crítica resuelta
RAG no es una garantía de veracidad: la fuente puede ser errónea o estar desactualizada. Un Skill tampoco verifica automáticamente información externa; necesita herramientas y revisión humana.

## Evidencia
Mapa de selección de tecnologías y dos diseños con flujo de trabajo, riesgos y controles.

---
© Prof. Dr. Pablo José Guerrero. 2026 - https://guerrero-consultores.com/
