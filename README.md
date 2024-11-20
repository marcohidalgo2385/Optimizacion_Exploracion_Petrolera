# Optimización de la Exploración Petrolera para OilyGiant

Trabajas en la compañía de extracción de petróleo OilyGiant, y tu tarea es encontrar los mejores lugares para abrir 200 nuevos pozos de petróleo. El objetivo es maximizar el beneficio y reducir el riesgo asociado a las inversiones en nuevas exploraciones.

## Objetivo del Proyecto
Desarrollar un modelo de regresión lineal que prediga el volumen de reservas de crudo en pozos nuevos y seleccionar las regiones con el mayor margen de beneficio y menor riesgo. Utilizar datos de muestras de crudo de tres regiones y aplicar la técnica de bootstrapping para evaluar los beneficios y riesgos potenciales.

## Contenidos del Proyecto
- **Lectura y Preparación de Datos**: Leer los archivos con los parámetros recogidos de pozos petrolíferos en cada región (calidad de crudo y volumen de reservas).
- **Desarrollo del Modelo de Predicción**: Crear un modelo de regresión lineal para predecir el volumen de reservas en pozos nuevos.
- **Selección de Pozos**: Identificar los pozos con los valores estimados más altos de reservas.
- **Evaluación de Beneficios y Riesgos**: Elegir la región con el mayor beneficio total y menor riesgo utilizando la técnica de bootstrapping.
- **Condiciones del Proyecto**:
  - Utilizar solo la regresión lineal para el entrenamiento del modelo.
  - Realizar un estudio de 500 puntos por región y seleccionar los 200 mejores puntos para el cálculo del beneficio.
  - El presupuesto para el desarrollo de 200 pozos petroleros es de 100 millones de dólares.
  - Un barril de crudo genera 4.5 USD de ingresos; el ingreso de una unidad de producto es de 4500 dólares (volumen de reservas en miles de barriles).
  - Mantener solo las regiones con un riesgo de pérdidas inferior al 2.5%.
  - Seleccionar la región con el beneficio promedio más alto de las que cumplan con los criterios.

## Herramientas y Tecnologías Utilizadas
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Cómo Contribuir
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para mejoras y sugerencias.


