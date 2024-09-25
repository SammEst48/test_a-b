# 📈 Análisis de Test A/B para Aumento de Ingresos en Tienda en Línea

## Descripción del Proyecto

De una tienda en línea el departamento de marketing ha recopilado una lista de hipótesis que pueden ayudar a aumentar los ingresos. Este proyecto tiene como objetivo priorizar estas hipótesis, lanzar un test A/B y analizar los resultados.

## Objetivos

 - Comparar y explicar los cambios en la priorización entre los métodos ICE y RICE.
 - Realizar análisis estadístico para encontrar la significancia en las diferencias entre los grupos.
 - Tomar decisiones basadas en los resultados de la prueba.

## Estructura del Proyecto

El proyecto está estructurado en dos partes principales: la priorización de hipótesis y el análisis de test A/B. Cada parte contiene análisis detallados y visualizaciones relevantes.


## Datasets

### Parte 1: Priorización de Hipótesis
- **`hypotheses_us.csv`**: 
    - **Hypotheses**: Breves descripciones de las hipótesis.
    - **Reach**: Alcance del usuario (escala del 1 al 10).
    - **Impact**: Impacto en los usuarios (escala del 1 al 10).
    - **Confidence**: Confianza en la hipótesis (escala del 1 al 10).
    - **Effort**: Recursos necesarios para probar la hipótesis (escala del 1 al 10).

### Parte 2: Datos para el Análisis de Test A/B
Los datasets utilizados son los siguientes:
- **`orders_us.csv`**: 
    - **transactionId**: Identificador de pedido.
    - **visitorId**: Identificador del usuario que realizó el pedido.
    - **date**: Fecha del pedido.
    - **revenue**: Ingresos del pedido.
    - **group**: Grupo del test A/B al que pertenece el usuario.

- **`visits_us.csv`**: 
    - **date**: Fecha.
    - **group**: Grupo del test A/B.
    - **visits**: Número de visitas en la fecha especificada para el grupo de test A/B.

## Librerías Necesarias

- pandas, datetime, numpy, matplotlib, seaborn, scipy

