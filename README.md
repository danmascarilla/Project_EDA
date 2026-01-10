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

## 💡 Principales Conclusiones

Tras el análisis exhaustivo de los datos, los hallazgos clave de nuestra investigación son:

* **Correlación Débil ($r=0.20$):** La relación entre la nota de la crítica (**Metascore**) y las ventas globales es mucho menor de lo esperado. Una buena calificación ayuda a reducir el riesgo de fracaso, pero no es un factor que garantice por sí solo un éxito masivo en ventas.
* **Independencia del Mercado Japonés:** Existe una clara diferencia geográfica. Mientras que EE.UU. y Europa tienen una correlación casi perfecta entre sí ($r > 0.97$), **Japón** muestra una dinámica independiente ($r=0.71$), lo que valida la necesidad de estrategias de marketing específicas para ese territorio.
* **Marketing vs. Calidad (El "Efecto Hype"):** El volumen de críticas (`metascore_count`) resultó ser un predictor de ventas más potente que la nota numérica media. Esto indica que la **visibilidad y la conversación mediática** influyen más en el éxito comercial que la calidad técnica percibida.
* **Divergencia Crítica/Usuario:** Se detectó una brecha de percepción moderada ($r=0.47$) entre la prensa especializada y los jugadores finales. Esto sugiere que los consumidores valoran aspectos del producto (como la diversión o la rejugabilidad) que no siempre coinciden con los criterios técnicos de los analistas.

## Miembros del proyecto

* [danmascarilla](https://github.com/danmascarilla)
* [IvanMontero04](https://github.com/IvanMontero04)
* [jonatan-luzon](https://github.com/jonatan-luzon)
