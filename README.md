# 🎵 Análisis Comparativo de Hábitos Musicales por Ciudad

Proyecto de análisis exploratorio de datos enfocado en comparar patrones de consumo musical entre usuarios de dos ciudades ficticias, a partir de registros simulados de reproducción.

El objetivo es identificar si existen diferencias relevantes en el comportamiento de escucha entre ambas ciudades, analizando volumen de reproducciones, preferencias musicales y actividad por día.

---

## 📌 Objetivo

Evaluar similitudes y diferencias en los hábitos de escucha musical entre usuarios de dos ciudades, utilizando técnicas de limpieza, transformación, análisis exploratorio y visualización de datos.

---

## 🧠 Contexto analítico

A partir de un conjunto de datos simulados de reproducciones musicales, se analizó el comportamiento de los usuarios de **Springfield** y **Shelbyville** para responder preguntas como:

- ¿Los usuarios de ambas ciudades escuchan una cantidad similar de música?
- ¿Existen diferencias en la actividad según el día de la semana?
- ¿Los géneros musicales más populares cambian entre ciudades?

Este tipo de análisis permite explorar patrones de comportamiento, comparar segmentos y generar hallazgos descriptivos útiles para la toma de decisiones basada en datos.

---

## 🗂️ Dataset

Se utilizó un archivo con registros de reproducciones musicales simuladas, que incluye información como:

- ciudad del usuario
- día de reproducción
- género musical
- canciones reproducidas

Antes del análisis se realizó una etapa de limpieza y normalización para corregir inconsistencias y preparar los datos para su exploración.

---

## 📊 Metodología

El proyecto se desarrolló en las siguientes etapas:

1. **Revisión inicial del dataset**  
   Exploración de la estructura general de los datos y detección de posibles problemas de calidad.

2. **Limpieza y preparación de datos**  
   Tratamiento de valores ausentes, normalización de nombres y estandarización de categorías.

3. **Análisis exploratorio**  
   Comparación del comportamiento de escucha por ciudad y por día de la semana.

4. **Análisis de géneros musicales**  
   Identificación de los géneros más populares y comparación de su distribución entre ambas ciudades.

5. **Visualización de resultados**  
   Construcción de gráficos para comunicar patrones y facilitar la interpretación de hallazgos.

---

## 📈 Principales hallazgos

- El promedio de canciones reproducidas por usuario fue muy similar entre ambas ciudades.
- Las diferencias en el volumen total de reproducciones estuvieron más relacionadas con la cantidad de usuarios activos que con diferencias fuertes en el comportamiento individual.
- Los géneros musicales más populares aparecieron en proporciones parecidas en ambas ciudades.
- En conjunto, los resultados sugieren hábitos de escucha comparables entre los dos grupos analizados.

---

## 📚 Valor del proyecto

Este proyecto demuestra habilidades clave de análisis de datos, como:

- limpieza y normalización de datos
- análisis exploratorio comparativo
- agrupación y transformación de información con pandas
- visualización de hallazgos
- comunicación clara de resultados

Aunque se trata de un caso con datos simulados, el flujo de trabajo refleja tareas comunes en proyectos reales de análisis descriptivo y segmentación de comportamiento.

---

## 🛠️ Herramientas Usadas

- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

---

## 🧱 Estructura del Proyecto

```
spotify-habits-city-comparison/
├── notebooks/
│   └── spotify_city_analysis.ipynb     # Notebook principal
│   └── genres_unicos.txt # Todos los géneros únicos (si se desea inspección completa)
├── data/
│   └── music_project_en.csv]
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Autor

**Jonathan García**  
📁 Proyecto parte de mi portafolio profesional en ciencia de datos.


