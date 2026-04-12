# DIU26
Prácticas Diseño Interfaces de Usuario (Tema: .... ) 

* [Guiones de prácticas](GuionesPracticas/)
* [Guía para crea tu Case Study](Guia_CaseStudy.md)
* Sala de la Fama [DIU Hall of fame](https://github.com/mgea/DIU/tree/master/hall_of_fame) donde se pueden encontrar Case Study destacados de otros años.
* [Recursos/plantillas en figma](https://www.figma.com/design/BN2IR0q2clOSplfMmalh9K/DIU_Toolkit_Framework--2026-)




Actualizado: 14/01/2026




## Paso 0 My UX-Case Study
![Método UX](img/caseStudy.png) 
-----

Grupo: DIU3_ADE.  Curso: 2025/26 Grado: Ingeniería Informática + ADE

Nombre del Proyecto: Bold Burger

Descripción: La web muestra al usuario únicamente los productos aptos para su consumo, indicados previamente mediante un filtro.s

Logotipo: 

>>> Si diseña un logotipo para su producto en la práctica 3 pongalo aqui, a un tamaño adecuado. Si diseña un slogan añadalo aquí (rellenar más adelante)

Miembros y nombre del equipo:
Nombre del equipo: DI3.ADE
 * :bust_in_silhouette:  Florín Emanuel Todor Gliga     :octocat:     : https://github.com/FlorinTodor
 * :bust_in_silhouette:  Laura Zafra Alarcos     :octocat:            : https://github.com/LauraZafra



----- 

<br>

# Proceso de Diseño 





<br>

## Paso 1. UX User & Desk Research & Analisis 




### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

## 1. Project Background (Contexto y Justificación)
El mercado del *fast-food* premium en Granada combina un alto volumen de usuarios universitarios que exigen inmediatez digital con profesionales que buscan experiencias en local. La hipótesis central de esta investigación es que la web de Goiko prioriza el impacto visual (*food porn*) sobre la propia usabilidad de la aplicación. Esta sobrecarga estética y la dependencia de plataformas externas para completar pedidos (*delivery*) generan fricción cognitiva y abandono en el embudo de conversión, afectando directamente a las ventas online.

## 2. Research Goals & KPIs (Objetivos y Métricas)

| Objetivos de Investigación | KPIs (Indicadores Clave de Rendimiento) |
| :--- | :--- |
| **Evaluar la fricción en el embudo de conversión del pedido a domicilio (Delivery).** | - Tasa de abandono en la pantalla de selección de extras.<br>- Número de clics necesarios para llegar al *checkout*. |
| **Analizar la usabilidad del sistema de reservas de mesas.** | - Tiempo promedio para completar una reserva de mesa para un grupo.<br>- Tasa de éxito en el primer intento sin errores del sistema. |
| **Medir la accesibilidad de la información nutricional crítica.** | - Tiempo requerido para localizar la tabla de alérgenos.<br>- Número de pasos para identificar opciones sin gluten. |

## 3. Research Methods (Metodología)
* **Cualitativa (Contextual Inquiry):** Observación directa de usuarios intentando realizar un pedido real desde su *smartphone* en un entorno ruidoso o con distracciones, para identificar la fatiga visual y los bloqueos ante ventanas modales (promociones).
* **Cuantitativa (Usability Test / Heuristic Review):** Aplicación de una lista de verificación de usabilidad (basada en heurísticas de Nielsen) para puntuar la severidad de los errores de interfaz en la navegación móvil y de escritorio.

## 4. Research Questions (Preguntas de Investigación)
1. ¿Qué elementos visuales o modales interrumpen al usuario antes de poder ver el precio final de su pedido?
2. ¿Con qué facilidad puede un usuario con restricciones alimentarias asegurar que su pedido es seguro para su consumo?
3. ¿La derivación de tráfico hacia plataformas de terceros (como Glovo o UberEats) rompe la confianza o el flujo de la experiencia del usuario?

## 5. Experience in this field (Perspectivas)
* **My personal experience:** El diseño orientado al *marketing* agresivo a menudo destruye la operabilidad. La retención de usuarios en restauración depende más de pedir en 3 clics que de ver imágenes en ultra alta resolución que ralentizan la carga en dispositivos móviles.
* **As a designer:** Observo que la arquitectura de la información es inconsistente; elementos críticos como los alérgenos están enterrados en menús secundarios en lugar de integrados en la ficha contextual del producto.
* **As an observer:** Los usuarios frecuentemente se frustran al intentar cerrar *banners* de suscripción a *newsletters* que tapan los botones de llamada a la acción (CTA) principales en pantallas pequeñas.
* **People say (User voice):** *"Solo quería pedir una Kevin Bacon rápida, pero la web me obligó a saltar a otra aplicación y perdí el hilo de lo que estaba haciendo"*.

## 6. Participant Recruitment (Reclutamiento)
* **Perfil 1: El Impaciente Digital.** Estudiantes universitarios (18-26 años) que buscan realizar un pedido a domicilio desde el móvil con la máxima velocidad y el mínimo esfuerzo cognitivo.
* **Perfil 2: El Planificador Restringido.** Profesionales (30-45 años) encargados de reservar para un grupo presencial, incluyendo la necesidad de verificar información de alérgenos de forma estricta.


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----
Para este análisis competitivo, contrastamos el modelo corporativo de Goiko con dos competidores locales consolidados en Granada: **Mumama Burger** y **Mostaza Green**. Esta comparativa expone cómo la usabilidad se resiente tanto por la sobresaturación de elementos en grandes cadenas como por la falta de madurez digital en negocios locales.

**Tabla Resumen de Competencia:**

### 3. [DESK RESEARCH: COMPETITOR ANALYSIS]

Para este análisis competitivo, contrastamos el modelo corporativo de Goiko con dos competidores locales consolidados en Granada: **Mumama Burger** y **Mostaza Green**. 

**Tabla Resumen de Competencia:**

| Funcionalidad / UX | [Goiko (Caso de Estudio)](https://www.goiko.com/es/) | [Mumama Burger](https://www.mumama.es/) | [Mostaza Green Burger](https://mostazagreen.com/) |
| :--- | :--- | :--- | :--- |
| **Arquitectura de la Información** | Sobrecargada. Alta densidad de *pop-ups* y opciones. <br><br> <img src="./P1/img/delivery_takeaway_goiko.png" width="150px"> | Básica e informativa. Actúa como un escaparate digital estático. | Narrativa visual, pero con interrupciones críticas (pop-ups de fidelización). <br><br> <img src="./P1/img/popup_mostaza.png" width="150px"> |
| **Flujo de Conversión (Delivery)** | Híbrido con fricción. Retiene al usuario en su sistema propio pero genera pasos extra. | Deficiente. Delegación total de la conversión. | Externalizado. Deriva directamente a Glovo. <br><br> <img src="./P1/img/delivery_mostaza.png" width="150px"> |
| **Accesibilidad (Alérgenos)** | Aislada. Obliga al usuario a abandonar el menú principal para consultar otra sección. <br><br> <img src="./P1/img/alergenos_aislados_goiko.png" width="150px"> | Nula a nivel digital. El usuario debe llamar al local o consultar in situ. | Carga cognitiva alta. Te obliga a descargar o abrir un PDF externo. <br><br> <img src="./P1/img/alergenos_mostaza_pdf.png" width="150px"> |
| **Sistema de Reservas** | Fricción en grupos. El flujo digital se rompe a partir de 7 personas, derivando a WhatsApp. <br><br> [🎥 Ver evidencia en vídeo](https://drive.google.com/file/d/1zAYtOdyyOtWYvLSiPs0dvJJ-7O3Mhk-i/view?usp=sharing) | Limitado. Ante aforos completos, exige llamar por teléfono. | Informativo. No disponen de un motor de reservas digital claro. |

<br>

**Valoración y Justificación de la Competencia:**

El análisis competitivo, respaldado por evidencias visuales de las plataformas, revela que tanto el exceso como la carencia de desarrollo digital destruyen el embudo de conversión. Goiko, nuestro caso de estudio, presenta una interfaz hiper-saturada donde la accesibilidad nutricional está aislada y las reservas grupales obligan a salir de la web hacia WhatsApp. 

Sin embargo, competidores locales como **Mostaza Green** demuestran que la alternativa no es necesariamente mejor, interrumpiendo la navegación con *pop-ups* invasivos, gestionando los alérgenos mediante PDFs poco accesibles desde móvil y externalizando el *delivery* a plataformas de terceros. En conclusión, mientras los actores locales fallan por omisión y falta de madurez digital, Goiko falla por sobrecarga cognitiva, ofreciendo una oportunidad clara para proponer un rediseño que equilibre estética y conversión sin fricciones.

### 1.c Personas

![Persona Marcos](./P1/Personas/Persona_1.png) 
**Marcos (El Impaciente Digital):** Representa la urgencia del sector universitario. Busca pedir comida rápido desde el móvil sin fricción ni distracciones.

![Persona Elena](./P1/Personas/Persona_2.png) 
**Elena (La Planificadora Rigurosa):** Perfil analítico corporativo. Evalúa la reserva online y la claridad de la información nutricional ante intolerancias.

-----


### 1.d User Journey Map

![Journey Map Marcos](./P1/Personas/Journey_p1.png) 
-----
**Justificación Journey Marcos (Delivery Rápido):** Hemos planteado el caso de Marcos porque refleja lo que nos pasa a todos un viernes por la noche: queremos la comida ya y tenemos cero paciencia. Lo más habitual cuando intentas pedir desde el móvil en estas webs es que te frían a *pop-ups* o te obliguen a crearte una cuenta. Al final, la fricción es tan alta que el usuario se cansa, cierra la pestaña y se va a pedir lo mismo por Glovo simplemente porque ahí ya tiene la tarjeta guardada y paga en un clic.

![Journey Map Elena](./P1/Personas/Journey_p2.png) 
-----
**Justificación Journey Elena (Reservas y Alérgenos):** El caso de Elena representa el típico dolor de cabeza al organizar una cena de empresa o de amigos. Es frustrante, y muy común, intentar reservar para un grupo grande y que la web colapse o te obligue a llamar por teléfono, rompiendo toda la utilidad de hacerlo online. Además, cuando tienes a alguien celíaco en el grupo, esconder los alérgenos en otra página en lugar de ponerlos claros al lado del plato genera mucha desconfianza. Es un fallo crítico que te hace descartar el restaurante.


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----
Enlace al documento:  https://github.com/DIU3-ADE/UX_CaseStudy/blob/master/P1/Usability-review-template_goiko.xls
URL y Valoración numérica obtenida: 81
Comentario sobre la revisión de Goiko:  
 Como puntos fuertes:
 - La web destaca por una estética moderna y coherente. El uso de fotografía de alta calidad no solo refuerza la marca, sino que actúa como un motor de conversión directo al hacer el producto altamente deseable.
 - Los flujos principales (pedir a domicilio y llamar al local) son extremadamente directos.
 - Se evita la sobrecarga cognitiva con un menú muy limpio y una arquitectura de información que facilita que el usuario encuentre lo que busca en pocos clics.
 - La experiencia está muy bien resuelta, manteniendo la velocidad de carga y la facilidad de interacción a pesar del peso visual de las imágenes.
 Como puntos débiles:
 - Se han detectado carencias en la gestión de estados de error en formularios complejos.
 - Falta ayuda contextual (ejemplos) dentro de los campos de entrada de datos para guiar al usuario en tiempo real.


### 1.f Briefing
![Método UX](img/usabilityReview.png) 
----
Esta revisión evalúa la eficacia de la experiencia de usuario en la web, centrándose en los flujos críticos de conversión: reserva de mesa y pedido online. Tras el análisis, se concluye que la plataforma ofrece una experiencia altamente persuasiva y visualmente excelente, aunque con oportunidades de mejora en la robustez técnica y el soporte al usuario.

El diseño visual es el pilar del sitio. La alta calidad de la fotografía de producto y una jerarquía clara no solo refuerzan el branding, sino que actúan como un motor de conversión directo al reducir la carga cognitiva. La navegación es minimalista y eficiente y los flujos de "Pedido" y "Reserva" están optimizados para dispositivos móviles, con llamadas a la acción que permiten completar tareas frecuentes en pocos pasos.

A pesar de ello, se han detectado debilidades en la prevención de errores. Los formularios carecen de una validación dinámica, generando fricción innecesaria. Asimismo, la arquitectura de información en secciones extensas como la carta se beneficiaría de indicadores de ubicación más claros para orientar al usuario durante el scroll. Por último, la sección de ayuda es bastante mejorable, delegando la resolución de dudas a canales externos sin ofrecer soporte web.

Esta web proporciona una experiencia de usuario correcta que cumple con éxito los objetivos de negocio. Para alcanzar la excelencia, se recomienda fortalecer los mecanismos de feedback del sistema y optimizar la sección de soporte técnico.

<br>

## Paso 2. UX Design  

### 2.a Reframing: EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

![Empathy Map](P2/EmpathyMapBoldBurger.jpg) 


 Interesante | Críticas   
| ------------- | -------
En lugar de hacer que el usuario busque "qué no puede comer", la interfaz le muestra directamente "todo lo que sí puede comer" | Obligar a cruzar datos entre la carta y un PDF de alérgenos genera ansiedad y desconfianza en el usuario 
Tratar las restricciones alimentarias (veganismo, celiaquía) no como un "problema médico" a esconder en un PDF, sino como una preferencia de estilo de vida premium | Las webs actuales interrumpen al usuario nada más entrar para pedirle el email (newsletter), lo que genera rechazo
La sensación de que el restaurante ha creado una carta exclusiva para ti al instante | Para un celíaco, equivocarse al leer la carta mezclada puede tener consecuencias de salud, lo que genera estrés al pedir

 Preguntas | Nuevas ideas   
| ------------- | -------
  ¿Por qué el usuario debe buscar activamente lo que no puede comer en lugar de que el sistema le muestre solo lo que sí puede? | Pantalla de bienvenida interactiva para marcar alérgenos/dietas antes de ver el menú
  ¿Cómo hacemos que este filtro inicial sea obligatorio pero tan rápido que no frustre al usuario que no tiene alergias (como Marcos)? | Sustituir el típico pop-up molesto de publicidad por una pantalla elegante de bienvenida: "¿Alguna alergia o dieta hoy?" con botones rápidos (Sin Gluten, Vegano, Lactosa) y un botón gigante de "Ninguna, ver todo"
    
Las plataformas actuales de fast-food premium priorizan el marketing agresivo y la estética sobre la usabilidad y la inclusión. Esto genera dos grandes fugas en el embudo de conversión:
- Los usuarios con prisa abandonan por la sobrecarga cognitiva (pop-ups y registros forzosos).
- Los usuarios con restricciones alimentarias (celíacos, intolerantes, veganos) sufren fatiga y ansiedad al tener que buscar la información nutricional en secciones aisladas o PDFs externos, lo que a menudo resulta en el abandono del pedido por falta de confianza.

Hipótesis y Propuesta de Valor:
Nuestra hipótesis es que al invertir la carga de trabajo cognitivo, pasando de un modelo donde el usuario busca la información a un modelo donde el sistema filtra proactivamente, aumentaremos la tasa de conversión y la retención.

Propuesta de Valor: Ofrecer una experiencia de pedido hiper-personalizada y segura desde el primer clic. Al acceder a la web, el usuario interactúa con un filtro de alérgenos y preferencias dietéticas. Una vez configurado, la interfaz genera un menú dinámico que muestra exclusivamente los productos 100% seguros y aptos para su consumo. Esto elimina el miedo, suprime la necesidad de consultar tablas externas y transforma la web en un entorno de confianza absoluta y conversión rápida.


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

>>> Propuesta de valor, pero ahora en vez de un texto es un ScopeCanvas que has subido a P2/ y enlazado desde aqui. Tambien vale una imagen miniatura del recurso.
>>> No olvides que tu propuesta ya tiene un nombre corto y puedes actualizar la cabecera de este archivo

En este lienzo plasmamos nuestro propósito central: democratizar el fast-food mediante un menú seguro para el usuario, inclusivo y sin fricciones. Para ello, estructuramos el análisis en dolores y motivadores del usuario, acciones clave, métricas de éxito y metas operativas. Esta visión global nos ayuda a mantener el foco durante el diseño, evitando desviaciones que no aporten valor directo. En definitiva, garantiza que cada decisión de interfaz que tomemos sea medible, viable y resuelva el problema planteado inicialmente.

### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

>>> Definir "User Map" y "Task Flow" ... enlazar desde P2/ y describir brevemente

En esta fase pasamos de las necesidades abstractas a la interacción real con la interfaz de Bold Burger.
Para garantizar una experiencia sin fricciones, planificamos la navegación usando dos enfoques complementarios.
El Task Flow define el camino lineal, rápido e ideal para completar una única acción específica.
El User Flow ilustra la ruta macroscópica completa, incluyendo bifurcaciones, decisiones y alternativas.
Analizar ambos flujos nos permite identificar y eliminar cuellos de botella antes de llegar al prototipado.
De este modo, aseguramos que el menú seguro para el usuario y el pago exprés exijan el menor esfuerzo cognitivo posible.



### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

>>> Identificar términos para diálogo con usuario (evita el spanglish) y la arquitectura de la información. Es muy apropiado un diagrama tipo sitemap y una tabla que se ampliaría para llevar asociado la columna iconos (tanto para la web como para una app).
>>>


Término | Significado     
| ------------- | -------
 Plataforma Bold Burger | Punto de acceso unificado al sistema, ya sea desde navegador web o aplicación móvil.
Página de Inicio | Pantalla principal que da la bienvenida al usuario y centraliza el acceso a las funciones clave.
Carta Interactiva | Catálogo digital de los productos ofrecidos, estructurado por categorías para facilitar la navegación.
Pedidos a Domicilio	 | Sección integral dedicada a la configuración, gestión y envío de comida a la dirección del usuario.
Filtro de Alérgenos	 | Herramienta de seguridad que permite al usuario excluir productos según intolerancias o dietas específicas (celiaquía, veganismo, etc.).
Hamburguesas	 | Categoría principal de la carta que agrupa todas las opciones de hamburguesas disponibles.
Entrantes y Acompañantes	 | Categoría secundaria de la carta para platos diseñados para compartir o acompañar el plato principal.
Bebidas y Postres	 | Categoría final de la carta que incluye refrescos, opciones alcohólicas y dulces.
Cesta de la Compra	 | Espacio temporal donde el usuario revisa y modifica los productos seleccionados antes de finalizar su pedido.
Pago Rápido  | (1-Clic)	Sistema de abono acelerado mediante plataformas móviles integradas (billeteras digitales) que no requiere introducir datos manuales.
Pago Tradicional	 | Proceso de compra estándar que requiere la introducción manual de datos personales, dirección de envío y tarjeta bancaria.
Sobre Nosotros	 | Espacio corporativo que relata la historia, la filosofía y el compromiso de la marca.
Contacto y Preguntas Frecuentes	 | Sección de soporte que resuelve dudas comunes y proporciona vías de comunicación directa con el servicio de atención al cliente.


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

>>> Plantear el diseño del layout para Web/movil (organización y simulación). Describa la herramienta usada 

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




