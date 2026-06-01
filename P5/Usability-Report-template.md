# Usability Report



<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF017nhV-TFmNER2OM8UbXtdN6xwAKBYrv0i6onNfKu6Yn0BV0RK6aiOroeXl73LSY-B0&usqp=CAU" alt="usability Download png" style="height:150px" />

### Evaluación de usabilidad del proyecto  [NOMBRE PROYECTO]

23 de mayo de 2026

[img Proyecto]

[\[Enlace a GITHUB del proyecto\]](https://github.com/Practicas-DIU3-RESCUE/UX_CaseStudy/)

### Realizado por:  

Informe realizado por Equipo DIU3.ADE, creadores de BOLD BURGER.



## 1 RESUMEN EJECUTIVO  (Executive Summary)

- **Objetivo**: Evaluar la usabilidad, accesibilidad y carga cognitiva del prototipo de fidelización "GoikoMes" (Caso B) frente a nuestra propuesta "Bold Burger" (Caso A), identificando puntos de fricción reales en el flujo de interacción.
- **Metodología**: Se ha empleado un enfoque mixto: Task-based testing simulado, medición de satisfacción mediante Cuestionario SUS, evaluación heurística (WCAG) y simulación de análisis biométrico visual (Eye Tracking).
- **Principales Hallazgos**: 1. Inconsistencia Crítica en CTAs: Los botones para "Votar" están etiquetados como "PEDIR AHORA", generando bloqueo cognitivo.
2. Accesibilidad Deficiente: Graves problemas de contraste (textos rojos sobre fondos negros) y tipografía minúscula.
3. Jerarquía Visual Confusa: Textos importantes ("VOTA") camuflados gráficamente sobre las texturas de las hamburguesas.
- **Resultado Global**: Aunque el diseño es fiel a la identidad de marca (dark), sacrifica principios vitales de usabilidad y accesibilidad, penalizando la experiencia del usuario.


## 2. Metodología y Reclutamiento

- **Perfil de los participantes**: Muestra de 4 usuarios con perfiles variados. Edad media de 22 años. Nivel de competencia digital mixta (desde baja hasta alta). Destacan perfiles que requieren inmediatez (abogada con poco tiempo) y detalle analítico (estudiante detallista).
- **Escenario de la prueba**: Se asignó a los usuarios la tarea de acceder a la pantalla "Votaciones del mes", analizar los ingredientes de las tres opciones propuestas y emitir un voto efectivo por su favorita.
- **Herramientas**: Evaluación heurística (Checklist P1), Cuestionario SUS, herramientas de revisión de contraste WCAG, y simulación de GazeRecorder para el seguimiento ocular.

## 3. Resultados del Cuestionario SUS (Datos Cuantitativos)

Para la evaluación del A/B Testing, se ha utilizado el **cuestionario Tally proporcionado por el profesor** con un total de **3 usuarios para cada caso** (Caso A: Bold Burger y Caso B: GoikoMes). Este cuestionario permite recopilar datos cuantitativos y cualitativos sobre la experiencia de usuario en ambos diseños.

Tras enfrentar ambos diseños en el A/B Testing con las tareas asignadas, extraemos las siguientes conclusiones sobre la usabilidad de las alternativas:

Las respuestas al caso A generan una puntuación media aproximada de 85 (Excelente), reflejando que la interfaz de filtros es clara, predecible y no requiere ayuda.

Las respuestas al caso B generan una puntuación media de 55'8. Reflejan que, aunque el sistema no requiere un "técnico" para usarse, los usuarios se frustraron por la inconsistencia (botones de "Pedir" que en realidad son para "Votar") y lo engorroso que resulta leer la pantalla.

Al analizar las respuestas individuales, el Caso A (Bold Burger) ha mantenido una gran consistencia positiva en todas las métricas. Sin embargo, en el Caso B (GoikoMes), se han identificado tres áreas concretas que han hundido su puntuación general. Las preguntas con peor valoración (donde los usuarios marcaron mayor nivel de penalización) fueron:
- Pregunta 6 ("Pensé que había demasiada inconsistencia en este sistema"): Fue la peor valorada. Los usuarios penalizaron fuertemente la interfaz al encontrar botones de votación etiquetados como "PEDIR AHORA", rompiendo sus expectativas y la coherencia del sistema.
- Pregunta 8 ("Encontré el sistema muy engorroso de usar"): La lectura de textos pequeños en color rojo sobre fondo negro, sumada a la dificultad de interpretar los textos incrustados en las propias fotos de la comida, generó una alta percepción de pesadez visual.
- Pregunta 2 ("Encontré el sistema innecesariamente complejo"): Los perfiles con menor competencia digital o que buscaban inmediatez sintieron que el proceso para simplemente visualizar y votar una hamburguesa estaba sobrecargado de elementos visuales que distraían del objetivo principal.

El Caso A (Bold Burger) resulta notablemente más usable. Su enfoque centrado en la tarea principal (filtrar alérgenos) evita la confusión. Por el contrario, el Caso B falla en principios heurísticos básicos: la falta de correspondencia entre el sistema y el mundo real (botones que indican una acción distinta a la esperada) y problemas de legibilidad penalizan fuertemente la experiencia de usuario.

![Comparativa SUS AB](P5/ComparativaSUS-AB.png) 


## 4. Análisis de Eye Tracking (Datos Biométricos)

[Presenta la evidencia visual del comportamiento del usuario]

- **Heatmaps (Mapas de calor):** Los mapas de calor simulados muestran una fortísima concentración de fijaciones en las imágenes centrales de las hamburguesas. Sin embargo, el área de los CTAs muestra un patrón errático, indicando que el usuario mira el botón pero duda si hacer clic.
- **Zonas de Silencio:** Las listas de hamburguesas debajo del carrusel principal y los textos de información legal apenas registran fijaciones debido a la falta de contraste lumínico.
- **Hallazgo clave:** Ejemplo: El 100% de los usuarios sufrió confusión al leer "PEDIR AHORA" en la zona donde esperaban la acción de votar. Además, el gran texto "VOTA" impreso directamente sobre los panes de las hamburguesas pasó completamente desapercibido como texto legible..

## 5. Auditoría de Accesibilidad

Sintetiza el cumplimiento técnico y normativo.

- **Puntuación Automática:** (Lighthouse/WAVE).
- **Principales barreras:** Lista los errores críticos (contraste, falta de etiquetas, etc.) y cómo afectan a los usuarios con discapacidad.

## 6. Conclusiones y Recomendaciones (Actionable Insights)

No te limites a decir qué está mal; di cómo arreglarlo. Clasifica las recomendaciones por prioridad:

| **Prioridad**      | **Hallazgo**                                                 | **Recomendación de Mejora**                                  |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Alta (Crítica)** | Ej. El SUS indica alta complejidad y el Eye Tracking muestra confusión en el menú. | Simplificar la arquitectura de información y aumentar el tamaño de las fuentes. |
| **Media**          | Ej. Los usuarios no ven el botón de registro rápidamente.        | Cambiar el color del CTA a uno de mayor contraste según WCAG. |
| **Baja**           | Ej. El logo no redirige a la home.                               | Añadir el enlace estándar al logotipo en la cabecera.        |



