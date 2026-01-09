# Píxeles y Ganancias: ¿Influye la puntuación en el éxito comercial? 🎮📊

Este repositorio contiene el **Análisis Exploratorio de Datos (EDA)** detallado sobre la industria de los videojuegos, investigando la relación real entre las puntuaciones de la crítica, los usuarios y el éxito en ventas a nivel global y regional.

## 📝 Descripción del Proyecto
¿Es una buena nota en Metacritic garantía de éxito en ventas? Este proyecto busca desmitificar la relación entre la calidad percibida y el rendimiento comercial. Mediante el cruce de datasets de ventas históricas y calificaciones de expertos/usuarios, analizamos patrones de consumo, diferencias culturales entre mercados (Japón vs. Occidente) y el impacto de la visibilidad mediática.

## ❓ Hipótesis Planteadas
Para guiar la investigación, se definieron tres ejes principales:
1. **Hipótesis Principal (Correlación Global):** Existe una correlación positiva entre el *Metascore* y las ventas globales; la crítica actúa como un filtro de calidad que impulsa la intención de compra.
2. **Hipótesis Regional (Divergencia Continental):** La influencia de la crítica occidental es significativamente menor en el mercado japonés debido a preferencias culturales y factores locales.
3. **Hipótesis Secundaria (El Peso del Consumidor):** El volumen de reseñas (indicador de visibilidad o *hype*) tiene un impacto más fuerte en las ventas que la nota numérica en sí misma.

## 🛠️ Tecnologías Utilizadas
El análisis ha sido desarrollado con el stack de **Data Science en Python**:
* **Pandas & NumPy:** Limpieza, manipulación y combinación de múltiples fuentes de datos.
* **Matplotlib & Seaborn:** Creación de visualizaciones complejas, mapas de calor y gráficos de regresión.
* **SciPy (Stats):** Validación estadística mediante el Coeficiente de Correlación de Pearson ($r$).
* **Jupyter Notebooks:** Documentación interactiva de todo el proceso de análisis.

## 📂 Estructura del Repositorio
* `data/`: Datasets originales (`vgsales.csv`, `games.csv`) y datos procesados.
* `notebooks/`: Cuadernos de trabajo (`pruebas_2.ipynb`) con el flujo de limpieza y análisis.
* `docs/`: Documentación oficial del proyecto incluyendo la **Memoria.pdf** y la **Presentación.pdf**.
* `README.md`: Este archivo informativo.

## 🚀 Instrucciones de Reproducción
Para ejecutar este proyecto en tu entorno local:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/danmascarilla/Project_EDA.git](https://github.com/danmascarilla/Project_EDA.git)
