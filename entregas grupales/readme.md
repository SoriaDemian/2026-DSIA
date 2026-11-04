
# HR Analytics – Análisis de Rotación de Personal

## Descripción del proyecto

El presente proyecto tiene como finalidad analizar un conjunto de datos del área de Recursos Humanos, denominado **HR Analytics**, compuesto por 3.000 registros de empleados y 38 columnas con información sobre sus características personales y laborales.

El análisis se centra en la rotación del personal (*Attrition*), con el propósito de identificar posibles factores asociados a la decisión de los empleados de abandonar la organización.

A través de técnicas de análisis de datos y aprendizaje automático, se busca estudiar el comportamiento de las distintas variables y desarrollar modelos capaces de clasificar a los empleados según su posible riesgo de renuncia.

## Dataset seleccionado

**HR Analytics**

### Descripción del dataset

El dataset reúne información vinculada con la gestión del capital humano dentro de una organización.

Sus variables abarcan diferentes dimensiones de la experiencia laboral de los empleados, entre ellas:

- Características personales.
- Puesto y condiciones laborales.
- Ingresos.
- Antigüedad.
- Satisfacción laboral.
- Información relacionada con el entorno de trabajo.

La variable **Attrition** indica si un empleado dejó la empresa. Esto permite distinguir entre quienes permanecen en la organización y quienes se desvinculan, y estudiar cómo se relacionan estas situaciones con las demás variables disponibles.

## Desarrollo del proyecto

El trabajo se organiza en las siguientes etapas:

### 1. Exploración y limpieza de datos

- Exploración inicial del conjunto de datos.
- Identificación de tipos de variables.
- Análisis de valores faltantes y posibles inconsistencias.
- Limpieza y preparación de los datos para las etapas posteriores.

### 2. Análisis exploratorio de datos (EDA)

- Análisis individual de las variables.
- Estudio de la distribución de los datos.
- Análisis de relaciones entre variables.
- Identificación de posibles factores asociados a la rotación del personal.

### 3. Modelos de aprendizaje automático

Se implementan tres modelos de clasificación para estimar el posible riesgo de renuncia de los empleados:

- **Regresión Logística:** modelo de clasificación utilizado como alternativa para analizar la relación entre las variables y la rotación.
- **Árbol de Decisión:** modelo que permite representar las decisiones mediante reglas y condiciones.
- **Random Forest:** modelo basado en un conjunto de árboles de decisión que permite combinar múltiples predicciones.

### 4. Evaluación y comparación de modelos

Los modelos se comparan mediante distintas métricas de evaluación:

- **Precision:** mide la proporción de predicciones positivas que fueron correctas.
- **Recall:** mide la proporción de casos positivos que el modelo logró identificar.
- **F1-Score:** combina Precision y Recall en una única métrica.
- **AUC-ROC:** permite evaluar la capacidad del modelo para distinguir entre las clases.

A partir de estos resultados se busca seleccionar el modelo más adecuado según los objetivos del proyecto.

## Objetivo del análisis

Comprender cómo el análisis de datos y la inteligencia artificial pueden contribuir a la toma de decisiones en el área de Recursos Humanos.

Se busca proporcionar información útil para identificar grupos de empleados con mayor riesgo de renuncia y orientar posibles estrategias de retención del personal.

## Tecnologías y herramientas

- Python.
- Pandas.
- NumPy.
- Matplotlib.
- Seaborn.
- Scikit-learn.
- Jupyter Notebook / Deepnote.

## Conclusión

El proyecto permite integrar distintas etapas del proceso de análisis de datos, desde la exploración y preparación de la información hasta la implementación y evaluación de modelos de aprendizaje automático.

A través del estudio de la variable Attrition y su relación con las características personales y laborales de los empleados, se busca obtener información que contribuya a comprender los factores asociados a la rotación del personal.

De esta manera, se explora la aplicación de técnicas de Ciencia de Datos e Inteligencia Artificial en problemáticas reales del área de Recursos Humanos.
