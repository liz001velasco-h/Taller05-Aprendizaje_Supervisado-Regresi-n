# Predicción de Precios de Autos Usados mediante Aprendizaje Supervisado

## Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un modelo de **aprendizaje supervisado** para la predicción del precio de autos usados, utilizando técnicas de **regresión**. Se comparan distintos algoritmos con el fin de identificar el modelo con mejor desempeño predictivo.

El análisis incluye desde la exploración de datos hasta la evaluación de modelos, permitiendo comprender la relación entre las características del vehículo y su precio de mercado.

---

## Objetivos

- Analizar un conjunto de datos de autos usados.
- Realizar preprocesamiento y limpieza de datos.
- Aplicar técnicas de regresión supervisada.
- Comparar el rendimiento de diferentes modelos.
- Identificar las variables más influyentes en el precio del vehículo.

---

## Dataset

El dataset utilizado contiene información de autos usados, incluyendo variables como:

- Año del vehículo
- Kilometraje recorrido
- Potencia del motor
- Tipo de combustible
- Tipo de transmisión
- Número de propietarios anteriores
- Precio de venta (variable objetivo)

---

## Metodología

El flujo de trabajo del proyecto fue el siguiente:

1. **Carga y exploración de datos**
2. **Preprocesamiento de datos**
   - Manejo de valores faltantes
   - Transformación de variables categóricas
3. **Análisis exploratorio de datos (EDA)**
4. **División del conjunto de datos**
   - Entrenamiento (train)
   - Prueba (test)
5. **Escalamiento de variables**
6. **Entrenamiento de modelos**
   - Regresión Lineal
   - Árbol de Decisión
   - Random Forest
7. **Evaluación de modelos**
   - R² (Coeficiente de determinación)
   - MSE (Error cuadrático medio)
8. **Selección del mejor modelo**
9. **Análisis de importancia de variables**

---

## Modelos utilizados

| Modelo              | Descripción |
|---------------------|-------------|
| Regresión Lineal    | Modelo base para establecer relaciones lineales entre variables. |
| Árbol de Decisión   | Modelo no lineal que captura interacciones complejas. |
| Random Forest       | Ensamble de árboles que mejora la precisión y reduce el sobreajuste. |

---

## Resultados

El modelo con mejor desempeño fue **Random Forest**, obteniendo:

- **R² ≈ 0.97**
- Menor error cuadrático medio (MSE)
- Mejor capacidad de generalización

### Variables más importantes:

- **max_power** (potencia del motor)
- **year** (año del vehículo)
- **km_driven** (kilometraje)

---

## Conclusiones

- Los modelos basados en árboles superan significativamente a la regresión lineal.
- La potencia del vehículo es el factor más influyente en la predicción del precio.
- El kilometraje y la antigüedad del vehículo afectan directamente la depreciación del valor.
- Random Forest ofrece el mejor balance entre precisión y generalización.

---

## Tecnologías utilizadas

- Python 
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Autor

**Lizbeth Velasco Hernández**  
Proyecto académico – Bootcamp Ciencia de Datos
