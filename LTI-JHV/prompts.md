## Prompt 1 · Descripción breve del software LTI, valor añadido y ventajas competitivas

Actúa como un *product marketing manager* especializado en soluciones HRTech. Redacta una descripción ejecutiva del Applicant-Tracking System (ATS) **LTI**. Debes:

- Explicar en 2–3 párrafos qué problema resuelve, a quién sirve y qué lo diferencia en el mercado.
- Destacar su propuesta de valor cuantificable (ahorro de tiempo, mejora de conversión, métricas concretas) dirigida a equipos de talento en empresas medianas de tecnología.
- Cerrar con 3 bullets de ventajas competitivas, cada uno con un titular corto y una frase de soporte.
- Mantener un tono convincente y profesional; evita jerga vacía y frases genéricas.

## Prompt 2 · Explicación de las funciones principales

Desde la perspectiva de un *product manager* senior, elabora un inventario de funcionalidades clave para el ATS LTI. Instrucciones:

- Organiza el contenido en una tabla con columnas: Función, Objetivo para el usuario, Métrica de éxito, Nivel de madurez (MVP / En desarrollo / Futuro).
- Incluye al menos 8 funciones cubriendo todo el funnel de contratación: atracción, screening, entrevistas, colaboración interna y analítica.
- Para cada fila detalla cómo aporta valor a reclutadores, líderes de hiring y candidatos.
- Finaliza con un breve párrafo que resuma la estrategia de producto y las prioridades de roadmap inmediatas.

## Prompt 3 · Diagrama Lean Canvas del modelo de negocio

Te comportas como consultor de *lean startup*. Construye un Lean Canvas completo para el ATS LTI orientado a startups SaaS. Debes:

- Presentar cada uno de los 9 bloques en una tabla (Bloque, Contenido) con viñetas concretas de 1 línea.
- Incorporar supuestos medibles y riesgos principales en Problema, Propuesta de Valor y Canales.
- Añadir debajo del canvas una sección “Hipótesis para validar” con 3 experimentos priorizados (formato: Experimento, Métrica, Criterio de éxito).
- Mantener foco en cómo el ATS reduce tiempos de contratación y mejora la diversidad de candidatos.

## Prompt 4 · Casos de uso principales con diagrama por caso

Actúa como *product discovery lead*. Documenta 3 casos de uso prioritarios del ATS LTI. Requisitos:

- Para cada caso de uso crea una subsección numerada con: Contexto, Actor principal, Objetivo, Trigger, Flujo paso a paso (5–7 pasos), Resultado esperado y Métricas asociadas.
- Incluye un diagrama en formato mermaid `sequenceDiagram` o `flowchart` que represente el flujo clave del caso.
- Asegúrate de cubrir: (1) Publicación masiva de vacantes, (2) Gestión colaborativa de entrevistas, (3) Analítica de embudos de contratación.
- Concluye con un apartado “Insights de diseño” que compare los tres casos y señale oportunidades de mejora transversal.

## Prompt 5 · Modelo de datos (entidades, atributos y relaciones)

Piensa como *arquitecto de datos*. Diseña el modelo conceptual y lógico del ATS LTI. Indicaciones:

- Lista las entidades principales en una tabla con columnas: Entidad, Descripción, Atributos (con tipo de dato y si es obligatorio), Relaciones (nombre de la relación + cardinalidad).
- Incluye al menos: Empresa, Vacante, Candidato, Postulación, Entrevista, Evaluación, Usuario interno, Pipeline, Métrica agregada.
- Después de la tabla, describe las reglas de negocio clave que afectan integridad y seguridad (por ejemplo, retención de datos y permisos).
- Añade un diagrama en formato mermaid `erDiagram` que muestre las entidades y relaciones cardinales.

## Prompt 6 · Diseño del sistema a alto nivel

Enfócate como *arquitecto de software*. Entrega una descripción de arquitectura de alto nivel para el ATS LTI. Debes:

- Explicar en texto (3–4 párrafos) los dominios funcionales, componentes mayores y cómo interactúan: frontend web, backend de servicios, motor de workflows, integraciones externas (job boards, calendarios, HRIS) y capa de analítica.
- Presentar un diagrama en mermaid `flowchart` o `graph TD` que muestre los componentes, límites de contexto y canales de comunicación (REST, eventos, ETL).
- Enumerar 5 decisiones arquitectónicas con su justificación y trade-offs.
- Cerrar con una tabla de requerimientos no funcionales (RNF, Valor objetivo, Métrica de verificación).

## Prompt 7 · Diagrama C4 detallado de un componente

Asume el rol de *ingeniero de plataforma*. Profundiza en el componente “Motor de workflows de reclutamiento” del ATS LTI y crea un diagrama C4 a nivel Container y Component. Instrucciones:

- Describe brevemente el contexto (nivel 1) recordando actores externos que interactúan con el motor.
- Desarrolla el diagrama C4 en texto usando notación estructurada (ya sea con `PlantUML` C4 o mermaid C4 apoyado en comments) incluyendo: contenedores involucrados, componentes internos, responsabilidades y relaciones.
- Complementa con una tabla de contratos de API/eventos que el motor expone o consume (Nombre, Tipo, Consumidor/Proveedor, Payload clave).
- Añade una sección final de riesgos técnicos y mitigaciones asociadas al motor de workflows.
