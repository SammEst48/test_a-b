# 📈 Análisis de Test A/B para Aumento de Ingresos en Tienda en Línea

## Descripción del Proyecto
De una tienda en línea el departamento de marketing ha recopilado una lista de hipótesis que pueden ayudar a aumentar los ingresos. Este proyecto tiene como objetivo priorizar estas hipótesis, lanzar un test A/B y analizar los resultados.

## Objetivos
 - Comparar y explicar los cambios en la priorización entre los métodos ICE y RICE.
 - Realizar análisis estadístico para encontrar la significancia en las diferencias entre los grupos.
 - Tomar decisiones basadas en los resultados de la prueba.

## Datasets
**Datos utilizados en la primera parte del proyecto**
`/datasets/hypotheses_us.csv`
- `Hypotheses`: breves descripciones de las hipótesis
- `Reach`: alcance del usuario, en una escala del uno a diez
- `Impact`: impacto en los usuarios, en una escala del uno al diez
- `Confidence`: confianza en la hipótesis, en una escala del uno al diez
- `Effort`: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor `Effort`, más recursos requiere la prueba.

**Datos utilizados en la segunda parte del proyecto**
`/datasets/orders_us.csv`
- `transactionId`: identificador de pedido
- `visitorId`: identificador del usuario que realizó el pedido
- `date`: fecha del pedido
- `revenue`: ingresos del pedido
- `group`: el grupo del test A/B al que pertenece el usuario

`/datasets/visits_us.csv`
- `date`: la fecha
- `group`: grupo del test A/B
- `visits`: el número de visitas en la fecha especificada para el grupo de test A/B especificado

## Herramientas utilizadas
- **Python**: pandas, datetime, numpy, matplotlib, seaborn, scipy
- **Jupyter Notebooks**: para análisis interactivo

## Pasos de análisis
**Parte 1**: Priorizar hipótesis sobre cómo aumentar los ingresos utilizando los frameworks ICE y RICE, comparar las prioridades obtenidas con ambos métodos (ICE - RICE). 
**Parte 2**: Se presenta un escenario de prueba A/B, donde se analizan datos de pedidos y visitas para determinar si una nueva implementación (grupo B) supera la versión existente (grupo A) en términos de ingresos, tamaño promedio de pedido, tasa de conversión y otros indicadores. Se realizan análisis estadísticos, gráficos y cálculos para determinar la significancia estadística de las diferencias encontradas entre los grupos, para finalmente, tomar una decisión sobre la prueba A/B basada en los resultados.

## Conclusiones
Los resultados muestran que el grupo B es considerado como líder, debido a un valor p significativo de 0.011, lo que indica una diferencia estadísticamente significativa en la tasa de conversión entre los grupos. El grupo B muestra un aumento del 16.0% en la tasa de conversión en comparación con el grupo A, sugiriendo que las estrategias implementadas en este grupo son más efectivas para convertir visitantes en transacciones. Se recomienda implementar las estrategias exitosas del grupo B en otros contextos o continuar optimizándolas para mejorar aún más los resultados.

**Nota**: Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten en el área de análisis de datos.

## Visualizaciones
![image](https://github.com/user-attachments/assets/9b85d6bc-11b6-4027-a97f-f1f828ff652c)
![image](https://github.com/user-attachments/assets/7dd1b3d3-cf2c-4d8e-83db-f72e9364cbcd)
![image](https://github.com/user-attachments/assets/eb04ec70-f44b-4f3c-bb08-630e7fbcc8e9)



