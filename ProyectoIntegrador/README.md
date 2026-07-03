# 📚 Informe de Análisis: Relación entre las horas de estudio y la calificación obtenida en un examen

## Objetivo

Analizar la relación entre las horas de estudio y la calificación obtenida en un examen mediante un modelo de regresión lineal simple, con el propósito de determinar si el tiempo dedicado al estudio puede utilizarse como un predictor del rendimiento académico y generar recomendaciones basadas en evidencia estadística.

---

# 1. Descripción del conjunto de datos

| Característica | Valor |
|---------------|------:|
| Número de registros | 50 |
| Número de variables | 5 |
| Tipo de datos | Demográficos y académicos |

La información fue obtenida mediante una encuesta diseñada y aplicada por las integrantes del equipo a estudiantes que recientemente presentaron un examen.

Las variables recopiladas fueron:

- Edad
- Sexo
- Semestre actual
- Horas de estudio
- Calificación obtenida

Para el modelo de regresión lineal simple se utilizaron las variables **Horas de estudio** como variable independiente y **Calificación obtenida** como variable dependiente.

---

# 2. Estadísticos descriptivos

### Tabla 1. Estadísticos descriptivos de las variables numéricas

*(Agregar la tabla generada con `df.describe()`.)*

## Hallazgos

- La muestra está conformada por **50 estudiantes** pertenecientes a distintos semestres.
- Las horas de estudio presentan variabilidad entre los participantes, lo que refleja diferentes hábitos de preparación.
- Las calificaciones obtenidas muestran distintos niveles de desempeño académico.
- La diversidad de los datos permite aplicar un modelo de regresión lineal simple para analizar la relación entre ambas variables.

---

# 3. Distribución de las horas de estudio

### Figura 1. Distribución de las horas de estudio

*(Agregar histograma.)*

## Hallazgos

- Se observa la frecuencia con la que los estudiantes dedican determinado número de horas al estudio.
- La mayor concentración de respuestas se encuentra dentro de un rango específico de horas.
- También es posible identificar estudiantes que estudian considerablemente menos o más que el resto de la muestra.

---

# 4. Distribución de las calificaciones

### Figura 2. Distribución de las calificaciones obtenidas

*(Agregar histograma.)*

## Hallazgos

- La distribución permite conocer el comportamiento general del rendimiento académico de los estudiantes.
- Se identifican los rangos de calificación con mayor frecuencia.
- También pueden observarse posibles valores atípicos dentro de la muestra.

---

# 5. Relación entre las horas de estudio y la calificación

### Figura 3. Horas de estudio vs. Calificación obtenida

*(Agregar diagrama de dispersión con la recta de regresión.)*

## Hallazgos

- El gráfico permite observar visualmente la relación entre las horas de estudio y la calificación obtenida.
- Si la tendencia de los puntos es ascendente, existe evidencia de una relación lineal positiva.
- La cercanía de los datos a la recta de regresión proporciona una primera indicación de la calidad del modelo.

---

# 6. Modelo de regresión lineal

### Ecuación de regresión

\[
\text{Calificación} = a + b(\text{Horas de estudio})
\]

## Hallazgos

- La pendiente representa el cambio esperado en la calificación por cada hora adicional de estudio.
- El intercepto corresponde a la calificación estimada cuando el tiempo de estudio es igual a cero.
- La ecuación obtenida permite realizar estimaciones del rendimiento académico de los estudiantes.

---

# 7. Calidad del modelo

### Figura 4. Gráfico de residuales

*(Agregar gráfico de residuales.)*

## Hallazgos

- El análisis de los residuales permite evaluar si el modelo lineal representa adecuadamente los datos.
- Una distribución aleatoria alrededor del valor cero indica un ajuste adecuado.
- La ausencia de patrones claros respalda el cumplimiento de los supuestos básicos del modelo.

---

# 8. Correlación y capacidad predictiva

### Tabla 2. Indicadores del modelo

*(Agregar tabla con r, R², pendiente e intercepto.)*

## Hallazgos

- El coeficiente de correlación indica la intensidad de la relación entre las horas de estudio y la calificación.
- El coeficiente de determinación muestra qué porcentaje de la variabilidad de las calificaciones puede explicarse mediante las horas de estudio.
- Estos indicadores permiten evaluar la utilidad del modelo para realizar predicciones.

---

# Conclusiones

Del análisis realizado se concluye que:

- El modelo de regresión lineal permitió evaluar la relación entre las horas de estudio y la calificación obtenida.
- El tiempo dedicado al estudio representa un factor importante para explicar el rendimiento académico; sin embargo, no es el único que influye en las calificaciones.
- El análisis estadístico proporciona evidencia para determinar si las horas de estudio constituyen un buen predictor del desempeño de los estudiantes.
- La calidad del modelo dependerá de los resultados obtenidos para el coeficiente de correlación, el coeficiente de determinación y el análisis de residuales.

---

# Recomendaciones

Se recomienda fomentar hábitos de estudio constantes y una adecuada planificación del tiempo antes de cada examen, ya que una mejor preparación puede favorecer el rendimiento académico.

Asimismo, se sugiere considerar otros factores que también pueden influir en las calificaciones, como las técnicas de estudio utilizadas, la dificultad del examen, la asistencia a clases y el tiempo de descanso. Incorporar estas variables en futuras investigaciones permitiría desarrollar modelos predictivos más completos.

---

# Recomendación general

Con base en los resultados obtenidos, se recomienda utilizar la regresión lineal simple como una herramienta para analizar la relación entre el tiempo de estudio y el rendimiento académico. No obstante, para comprender de manera más precisa el desempeño de los estudiantes, sería conveniente ampliar el análisis mediante modelos que incluyan variables adicionales relacionadas con los hábitos de estudio y el contexto académico.
