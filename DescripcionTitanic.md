# Proyecto de Clasificación de Supervivencia en el Titanic

Este proyecto utiliza un modelo de clasificación para predecir la supervivencia de los pasajeros del Titanic. Aquí se exploran y aplican técnicas avanzadas de ingeniería de variables y optimización de hiperparámetros para mejorar la precisión del modelo.

**Nota:** Este trabajo está en desarrollo y no representa el resultado final.

## Descripción del Proyecto

El objetivo es construir un modelo de machine learning basado en el dataset del Titanic para predecir quiénes sobrevivieron al desastre. A lo largo del proyecto se implementan diversas técnicas avanzadas para la preparación y selección de características, así como para mejorar el rendimiento del modelo sin incurrir en overfitting.

## Técnicas Implementadas

### Ingeniería de Variables
1. **Tarifas Relativas**: Calculamos tarifas ajustadas basadas en el número de pasajeros por ticket.
2. **Rangos Etarios de Familia**: Creamos categorías etarias para representar la composición familiar.
3. **Interacción Edad y Clase**: Añadimos interacciones entre la edad y la clase del pasajero.
4. **Tamaño de Familia Ajustado**: Calculamos el tamaño de familia considerando la supervivencia probable.
5. **Tarifas por Persona**: Ajustamos las tarifas por persona para mejorar la precisión del modelo.
6. **Frecuencias de Títulos**: Creamos variables para capturar la frecuencia de títulos de los pasajeros.
7. **Promedio de Edad por Ticket**: Calculamos el promedio de edad para los grupos de pasajeros con el mismo ticket.

### Procesamiento de Datos
- **Escalado y Normalización**: Aplicamos técnicas de escalado y normalización para reducir sesgos en las variables.
- **Reducción de Dimensionalidad**: Utilizamos métodos para reducir la dimensionalidad de los datos sin perder información relevante.

### Optimización del Modelo
- **Ajuste de Hiperparámetros**: Probamos múltiples combinaciones de hiperparámetros para optimizar el rendimiento del modelo.
- **Prevención de Overfitting**: Aplicamos técnicas para minimizar el riesgo de overfitting y mejorar la generalización.

## Archivos en el Repositorio
- `TitanicFinalPorfavor.ipynb`: Notebook principal con el código y análisis preliminar del proyecto.

## Requisitos
- Python 3.x
- Bibliotecas: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

## Instrucciones
1. Clona este repositorio.
2. Instala los requisitos listados.
3. Ejecuta el notebook `TitanicFinalPorfavor.ipynb` para revisar los análisis y pruebas.

---

Este README se actualizará conforme avance el proyecto.
