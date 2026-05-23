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
- **Principales Hallazgos: 1. Inconsistencia Crítica en CTAs: Los botones para "Votar" están etiquetados como "PEDIR AHORA", generando bloqueo cognitivo.
2. Accesibilidad Deficiente: Graves problemas de contraste (textos rojos sobre fondos negros) y tipografía minúscula.
3. Jerarquía Visual Confusa: Textos importantes ("VOTA") camuflados gráficamente sobre las texturas de las hamburguesas.
- **Resultado Global**: Aunque el diseño es fiel a la identidad de marca (dark), sacrifica principios vitales de usabilidad y accesibilidad, penalizando la experiencia del usuario.


## 2. Metodología y Reclutamiento

- **Perfil de los participantes**: Muestra de 4 usuarios con perfiles variados. Edad media de 22 años. Nivel de competencia digital mixta (desde baja hasta alta). Destacan perfiles que requieren inmediatez (abogada con poco tiempo) y detalle analítico (estudiante detallista).
- **Escenario de la prueba**: Se asignó a los usuarios la tarea de acceder a la pantalla "Votaciones del mes", analizar los ingredientes de las tres opciones propuestas y emitir un voto efectivo por su favorita.
- **Herramientas**: Evaluación heurística (Checklist P1), Cuestionario SUS, herramientas de revisión de contraste WCAG, y simulación de GazeRecorder para el seguimiento ocular.

## 3. Resultados del Cuestionario SUS (Datos Cuantitativos)

[Aquí se muestran datos del análisis multivariable de SUS] 

- **Comparativa A vs. B:** Un gráfico de barras comparando la puntuación final de ambos diseños.
- **Desglose por ítems:** Identifica qué preguntas del SUS tuvieron peor puntuación (por ejemplo, si la pregunta 2 sobre "complejidad" fue muy alta en el Diseño B).

Valoración numérica del SUS - 


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



