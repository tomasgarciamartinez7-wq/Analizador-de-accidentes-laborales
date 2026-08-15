# Analizador de Accidentes Laborales

## Qué construí

Construí una herramienta de análisis de accidentes laborales destinada al área de Seguridad e Higiene. La aplicación permite cargar una base de accidentes en Excel, analizar indicadores y detectar los principales focos de riesgo. A partir de esos hallazgos, genera recomendaciones preventivas y correctivas, propuestas de capacitación y un plan de acción con prioridades, responsables sugeridos, plazos e indicadores de seguimiento.

## Cómo se lo pedí

Prompt 1 – Definición inicial del proyecto
Soy principiante total y no sé programar. Quiero construir con tu ayuda una herramienta pequeña para analizar accidentes laborales.

El usuario de la herramienta será el área de Seguridad e Higiene.

Quiero poder cargar un archivo Excel con información de accidentes laborales y que la herramienta analice la información disponible.

Me gustaría que muestre indicadores como cantidad de accidentes, evolución mensual, áreas con mayor cantidad de accidentes, causas, gravedad, días perdidos y otros indicadores relevantes que puedan surgir de la información del Excel.

Además del análisis numérico, quiero que identifique los principales focos de riesgo y proponga acciones concretas para Seguridad e Higiene.

Las recomendaciones deberían incluir, según corresponda:

- acciones preventivas;
- acciones correctivas;
- capacitaciones;
- revisión de procedimientos;
- otras medidas que surjan del análisis.

Finalmente, quiero que genere un plan de acción con prioridades, acciones concretas, responsables sugeridos, plazos e indicadores de seguimiento.

El sistema puede recomendar acciones, pero las decisiones finales siempre deben quedar en manos de una persona.

Quiero mantener el proyecto pequeño y realizable.

No escribas código todavía. Primero explicame, en lenguaje sencillo:

1. Qué entendiste que quiero construir.
2. Qué partes tendría la herramienta.
3. Cómo funcionaría desde que cargo el Excel hasta que obtengo el resultado.
4. Qué información necesitás de mí para empezar.
5. Qué versión mínima podríamos construir primero.

Como soy principiante, guiame paso a paso, uno por vez, y esperá mi confirmación antes de avanzar.

Prompt 2 – Revisión de la base y definición de indicadores
La propuesta me parece bien. Quiero trabajar con un Excel real anonimizado.
Antes de definir definitivamente los indicadores, quiero que revises el archivo completo y me indiques qué indicadores relevantes se pueden obtener de los datos existentes.
No quiero limitar el análisis solamente a total de accidentes, mes, área, causa y días perdidos si el archivo permite obtener otros indicadores útiles para Seguridad e Higiene.
Una vez revisado el archivo, proponeme cuáles incluirías en la primera versión y explicame brevemente por qué.
No escribas código todavía. Esperá mi aprobación de los indicadores antes de construir la herramienta.

Prompt 3 – Ajustes a la propuesta del agente
Apruebo los 8 pasos. Te pido por favor no incluir anonimizarlo (no incluir nombres de empresas). En el punto 7, te pido que incluyas acciones de capacitación vinculadas a las principales problemáticas, aparte de lo que sugieras

## Qué funciona
La aplicación funciona correctamente en forma local. Se verificó que permite cargar un archivo Excel con la base de accidentes, procesar la información y generar los indicadores y análisis definidos durante el desarrollo. También identifica focos de riesgo y genera recomendaciones y un plan de acción. Finalmente, permite generar el resultado en formato PDF para su descarga y posterior utilización.

## Qué falta o qué falló
Solamente falta seguir puliéndola con gráficos, ponerla en práctica y evaluar su utilidad en el campo real. No se pudo trabajar con python pero por un problema puntual de windows.

## Qué aprendí
Aprendí a interactuar mejor con Codex, a definir el problema antes de comenzar a construir y a diferenciar cuándo utilizar ChatGPT para analizar y diseñar una solución y cuándo utilizar Codex para llevarla a la práctica
