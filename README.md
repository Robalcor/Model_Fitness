## Análisis de retención de clientes para Model Fitness
La retención de clientes es clave en cualquier industria para garantizar ingresos recurrentes y reducir costos de captación (hasta 5 veces más altos). En Model Fitness, el análisis de factores de retención y cancelación permite anticipar abandonos, crear programas de fidelización basados en datos y ofrecer experiencias personalizadas que aumenten el engagement.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Modelos de predicción](https://img.shields.io/badge/Modelos_de_predicción-295F98?style=for-the-badge)

### Preguntas Clave
¿Qué variables (demográficas o de uso) impactan más en la cancelación?
¿Cómo difieren los clientes leales frente a los que abandonan?
¿Qué segmentos permiten estrategias de retención personalizadas?

### Metodología
Limpieza de datos: Eliminación de duplicados, valores nulos y estandarización.
EDA: Identificación de patrones en cancelaciones (ej: frecuencia de visita, tipo de contrato).
Modelado predictivo: Logistic Regression (72% precisión) y Random Forest (81%) para predecir cancelaciones.
Clustering: Segmentación con K-means para agrupar clientes por comportamiento.

## Hallazgos Clave
Retención alta: Clientes cercanos al gimnasio, con contratos largos (+6 meses) y participación en clases grupales.
Riesgo de cancelación: Jóvenes con contratos mensuales y baja asistencia.

###Acciones Recomendadas
Incentivar contratos largos: Descuentos por compromisos de 3+ meses.

Impulsar clases grupales: Campañas destacando beneficios sociales y motivacionales.

Intervención temprana: Usar el modelo para alertar sobre clientes en riesgo y ofrecer promociones ad-hoc.

Segmentación inicial: Clasificar nuevos clientes por perfil (edad/contrato) para estrategias preventivas.

## visualizaciones

**histogramas de compararion de de caracteristicas no binarias**
Al examinar los patrones entre clientes que permanecen y aquellos que cancelan, emergen dos tendencias claras:

Patrón de contratación
Los clientes que cancelan muestran una marcada preferencia por compromisos a corto plazo, con una abrumadora mayoría optando por membresías mensuales. En contraste, los clientes leales tienden a seleccionar planes de mayor duración.

Perfil demográfico
Se observa una concentración notable de cancelaciones entre usuarios menores de 30 años, mientras que la base de clientes más estables presenta un rango de edad significativamente mayor.
![caracteristicas_no_binarias](assets/img/relacion_binario.png)

**clusteres**
El dendrograma revela que los clientes se organizan naturalmente en 4 segmentos diferenciados, agrupados según sus características y patrones de comportamiento clave, lo que permite diseñar estrategias de retención personalizadas para cada perfil.
![cluster](assets/img/cluster.png)
