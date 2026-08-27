# Predictor de Ausentismo

## Qué construí

Construí un agente para analizar información histórica anonimizada de ausentismo y estimar el nivel esperado de ausencias del período siguiente por operación.

El agente utiliza un método de promedio ponderado de los últimos tres meses y contempla la tendencia, el nivel de riesgo, la confianza de la estimación y un impacto económico simulado con valores ficticios.

## Cómo se lo pedí

El contrato del agente se dividió en seis piezas: rol, contexto, tarea, restricciones, formato y ejemplos.

Se realizaron tres corridas y dos iteraciones de mejora, modificando una sola pieza del contrato en cada iteración.

## Qué funciona

El agente analiza la información histórica, verifica la disponibilidad de los tres meses anteriores al período a predecir y aplica un método de predicción 50/30/20 cuando los datos son suficientes.

También detecta problemas de continuidad y cobertura y evita realizar predicciones cuando la información disponible no permite obtener una estimación razonablemente confiable.

## Qué falta o qué falló

En la primera corrida el agente utilizó períodos antiguos o no consecutivos para realizar algunas predicciones.

En la segunda corrida se corrigió ese problema, pero se detectó que algunos valores cero correspondían a períodos con cobertura parcial y podían interpretarse incorrectamente como cero ausentismo.

La tercera versión incorporó una validación de cobertura y comparabilidad antes de realizar la predicción.

La base utilizada es una base de simulación y presenta información incompleta para algunos períodos de 2026. Podrá actualizarse en el futuro sin modificar la estructura general del agente.

## Qué aprendí

Aprendí que mejorar un agente no significa necesariamente lograr que produzca más resultados. Las iteraciones permitieron establecer mejores límites sobre cuándo corresponde realizar una predicción.

También comprobé la importancia de diferenciar entre tener datos disponibles y tener datos suficientes y comparables para tomar una decisión.

El contrato resultó más confiable cuando el agente aprendió a informar "Datos insuficientes" en lugar de generar una estimación potencialmente engañosa.
