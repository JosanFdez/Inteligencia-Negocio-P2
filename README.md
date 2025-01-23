# Inteligencia-Negocio-P2
Asignatura Inteligencia de Negocio practica 2 Algoritmos de Clustering

# Segmentación mediante Clustering en Alojamientos Turísticos de Granada

## Descripción General

Este proyecto explora el aprendizaje no supervisado mediante algoritmos de clustering para analizar datos relacionados con la oferta de alojamientos turísticos en Granada. Utilizando un conjunto de datos con más de 194,000 registros de Booking.com, el objetivo es identificar patrones clave en tres casos de estudio, representativos de distintos segmentos del mercado turístico.

---

## Casos de Estudio

### Caso 1: Alojamientos de Calidad 4 y 5 en el Centro de Granada
- **Objetivo:** Identificar patrones en alojamientos de alta calidad en zonas céntricas.
- **Variables Analizadas:** Tipo, Calidad, Distancia, Valoración, Precio.
- **Resultados:** Segmentación en cuatro clusters con insights sobre precios y valoraciones.

### Caso 2: Apartamentos en el Barrio Centro de Granada
- **Objetivo:** Analizar las características específicas de apartamentos en esta zona.
- **Variables Analizadas:** Tipo, Precio, Valoración, Precio por noche, Duración de la estancia.
- **Resultados:** Identificación de grupos competitivos en términos de precio y calidad.

### Caso 3: Alojamientos Económicos y Bien Ubicados
- **Objetivo:** Destacar opciones accesibles con buena ubicación y valoración.
- **Variables Analizadas:** Precio, Distancia, Valoración, Superficie, Opiniones.
- **Resultados:** Detección de alojamientos con alta relación calidad-precio.

---

## Algoritmos Utilizados

1. **K-Means:** Clustering eficiente basado en centroides. Ideal para datos bien definidos.
2. **Mean Shift:** Agrupa en torno a zonas de alta densidad.
3. **DBSCAN:** Identifica clusters basados en densidad, manejando ruido y formas arbitrarias.
4. **Birch:** Agrupamiento incremental para grandes volúmenes de datos.
5. **Jerárquico Aglomerativo:** Representa relaciones jerárquicas mediante dendrogramas.

---

## Métricas de Evaluación

- **Coeficiente Silhouette:** Evalúa la cohesión interna de los clusters.
- **Índice Calinski-Harabasz:** Relación entre la dispersión intra-cluster e inter-cluster.
- **Índice Davies-Bouldin:** Similaridad media entre clusters.
- **Tiempo de Ejecución:** Eficiencia computacional de los algoritmos.

---

## Tecnologías y Herramientas

- **Python:** Análisis y desarrollo en Jupyter Notebooks.
- **Bibliotecas:** Scikit-learn, Pandas, Matplotlib, Seaborn.
- **Entorno:** Anaconda para gestión de dependencias.

---

## Resultados Destacados

- **K-Means:** Mejor equilibrio entre cohesión, separación y tiempo de ejecución.
- **Birch:** Eficiente para grandes conjuntos de datos con segmentaciones claras.
- **DBSCAN:** Excelente manejo de ruido y clusters irregulares, aunque sensible a parámetros.
- **Jerárquico Aglomerativo:** Segmentación jerárquica útil para visualización.
- **Mean Shift:** Ideal para datos con densidad variable, aunque computacionalmente costoso.

---

## Contribuciones

Las contribuciones son bienvenidas. Para colaborar:
1. Haz un fork del repositorio.
2. Realiza tus modificaciones.
3. Envía un pull request con los detalles.
