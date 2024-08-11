# vanguard-a-b-test

# Análisis del Experimento A/B de Vanguard

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el impacto de una nueva interfaz digital implementada por Vanguard en el proceso de finalización de los clientes. Se realizó un experimento A/B para comparar la efectividad de la interfaz tradicional con una nueva versión mejorada. A continuación, se detalla el proceso del análisis.

## Objetivos

- Evaluar si la nueva interfaz mejora la tasa de finalización del proceso en comparación con la interfaz tradicional.
- Realizar un análisis estadístico para determinar la significancia de los resultados.
- Visualizar los datos para obtener insights interactivos y comprensibles.

## Datos Utilizados

1. **Datos Demográficos de Clientes** (`df_final_demo.csv`):
   - Información sobre la edad, género, número de cuentas y saldo total de los clientes.

2. **Datos de Interacción Digital** (`df_final_web_data.csv`):
   - Registros detallados de la interacción de los clientes con el sitio web, divididos en dos partes (`pt_1` y `pt_2`). Estos datos fueron combinados para un análisis exhaustivo.

3. **Lista de Participantes en el Experimento** (`df_final_experiment_clients.csv`):
   - Información sobre qué clientes participaron en el experimento de la nueva interfaz.

## Proceso del Proyecto

### 1. Preparación de Datos

**Objetivo**: Limpiar y preparar los datos para el análisis.

- **Combinar Datos**: Fusionar los archivos `pt_1` y `pt_2` del `df_final_web_data.csv`.
- **Limpieza de Datos**: Eliminar valores nulos y corregir errores en los datos.
- **Integración de Datos**: Unir los datos de interacción con la información demográfica y de experimentación.

### 2. Análisis Exploratorio de Datos (EDA)

**Objetivo**: Comprender las características de los datos y el comportamiento de los clientes.

- **Perfil de Clientes**: Analizar la distribución demográfica y comportamental de los clientes.
- **Comportamiento de Interacción**: Evaluar cómo interactúan los clientes con la interfaz tradicional y la nueva.

### 3. Pruebas de Hipótesis

**Objetivo**: Evaluar el impacto de la nueva interfaz en las tasas de finalización del proceso.

- **Definición de Métricas**: Establecer las métricas clave para evaluar el desempeño (e.g., tasa de finalización del proceso).
- **Realización de Pruebas Estadísticas**: Llevar a cabo pruebas A/B para comparar las tasas de finalización entre la interfaz tradicional y la nueva.
- **Evaluación de Significancia**: Analizar los resultados para determinar si las diferencias observadas son estadísticamente significativas.

### 4. Evaluación del Experimento

**Objetivo**: Revisar el diseño y la ejecución del experimento.

- **Efectividad del Diseño**: Evaluar la aleatorización, duración del experimento y cualquier sesgo potencial.
- **Recomendaciones**: Proponer mejoras basadas en los hallazgos del análisis.

### 5. Visualización de Datos

**Objetivo**: Crear visualizaciones interactivas para presentar los resultados.

- **Creación de Dashboards**: Utilizar Tableau para construir dashboards que faciliten la exploración de los datos y la interpretación de los resultados.
- **Exploración Interactiva**: Permitir la interacción con los datos para obtener insights más detallados.



