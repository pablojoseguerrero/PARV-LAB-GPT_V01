# Cuaderno 01 · Solución integral: LLM, tokens y contexto

## Actividad 1 · Comparación controlada de instrucciones
**Prompt A:** «Crea una actividad infantil».

**Respuesta ilustrativa A:** «Realiza un juego de palabras con los niños y pregúntales qué aprendieron». Es una sugerencia inespecífica: omite edad, duración, objetivo observable, materiales y evaluación. **No se presenta como una respuesta realmente obtenida de ChatGPT.**

**Prompt B:** «Diseña una experiencia lúdica de 20 minutos para niños de 4 a 5 años orientada a ampliar vocabulario de animales de su entorno, usando tarjetas grandes, sin piezas pequeñas, en un aula de 20 niños. Indica apertura, desarrollo, cierre, mediación docente, adaptaciones inclusivas y tres indicadores observables».

**Respuesta de referencia B:**
- **Título:** Animales que hablan.
- **Objetivo:** nombrar al menos tres animales conocidos y describir oralmente una característica, con apoyos según necesidad.
- **Apertura (4 min):** explorar imágenes y escuchar sonidos imitativos.
- **Desarrollo (12 min):** por turnos, elegir tarjetas, decir nombres y atributos; ofrecer señalamiento o pictogramas para quienes lo requieran.
- **Cierre (4 min):** ronda de palabras favoritas y retroalimentación respetuosa.
- **Materiales:** tarjetas grandes de bordes seguros; supervisión docente.
- **Observación:** participación, denominación de animales, expresión de atributos.

| Criterio | Prompt A | Prompt B |
|---|---|---|
| Edad y contexto | No definidos | 4–5 años; 20 niños |
| Objetivo | Genérico | Observable |
| Secuencia | No detallada | Apertura, desarrollo y cierre |
| Seguridad e inclusión | No especificadas | Explicitadas |
| Evaluación formativa | Ausente | Tres indicadores |

**Tres mejoras documentadas:** contextualización etaria, concreción didáctica y evaluación observable.

## Actividad 2 · Tokenización
Texto: «Aprendemos jugando con palabras».
Separación **por espacios**: [Aprendemos] [jugando] [con] [palabras], cuatro palabras. **Esto no constituye el conteo real de tokens.** Un tokenizador puede subdividir palabras y manejar espacios de forma distinta. Para obtener el conteo exacto debe elegirse un modelo y usar su tokenizador; no se inventan IDs ni números de tokens.

## Reflexión resuelta
Un contexto bien delimitado acota las alternativas de respuesta y facilita verificar pertinencia. No garantiza precisión: el modelo puede elaborar contenidos incorrectos, inventar referencias o ignorar restricciones. Por eso la revisión profesional es indispensable.

## Evidencia de cierre
Matriz comparativa anterior, prompts A/B y revisión de tres mejoras. **Criterio de aprobación:** diferenciar palabra y token, reconocer límites y justificar el efecto del contexto.

---
© Prof. Dr. Pablo José Guerrero. 2026 - https://guerrero-consultores.com/
