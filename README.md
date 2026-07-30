# Diplomado Módulo II: Modelos Estadísticos

Notebooks de trabajo del **Módulo II: Modelos Estadísticos**, del diplomado *Técnicas Estadísticas y Minería de Datos* de la UNAM.

## Sobre este módulo

La probabilidad y los modelos estadísticos son el lenguaje matemático que permite razonar sobre la incertidumbre en los datos. Antes de poder construir un modelo predictivo, una prueba A/B o un sistema de detección de anomalías, es necesario entender cómo se comportan los datos como fenómeno aleatorio: qué es un espacio de probabilidad, cómo se modela una variable aleatoria y cómo se pasa de una muestra a conclusiones generales mediante la inferencia estadística. Este módulo cubre precisamente esos fundamentos, que son la base teórica sobre la que se construye todo el trabajo posterior en ciencia de datos.

En el área de TI y ciencia de datos, estos conceptos aparecen constantemente, aunque no siempre de forma explícita:

- **Modelado predictivo y machine learning**: casi todos los algoritmos de aprendizaje supervisado (regresión, clasificación, redes neuronales) se fundamentan en supuestos probabilísticos sobre los datos y en el concepto de estimación estadística.
- **Minería de datos**: técnicas como la detección de patrones, el clustering o el análisis de asociación dependen de entender la distribución subyacente de los datos y de distinguir señal de ruido.
- **Pruebas A/B e ingeniería de producto**: decidir si un cambio en una aplicación o un sitio web mejora una métrica requiere pruebas de hipótesis e intervalos de confianza, temas centrales de la estadística inferencial.
- **Monitoreo de sistemas y detección de anomalías**: identificar comportamientos atípicos en logs, tráfico de red o métricas de infraestructura se apoya en modelar la variabilidad "normal" de los datos como una distribución de probabilidad.
- **Calidad y confiabilidad de datos**: entender el muestreo y la variabilidad estadística ayuda a evaluar qué tan representativo es un dataset antes de usarlo para entrenar un modelo.

En resumen, dominar estos fundamentos permite pasar de "programar" un algoritmo de datos a entender *por qué* funciona, cuáles son sus supuestos y cuándo sus resultados son confiables — una diferencia clave entre aplicar una herramienta y hacer ciencia de datos con rigor.

## Contenido

| # | Notebook | Tema | Abrir en Colab |
|---|----------|------|----------------|
| 1 | [`Notebook_1-espacio_de_probabilidad.ipynb`](Notebook_1-espacio_de_probabilidad.ipynb) | Espacio de probabilidad: axiomas, probabilidad condicional e independencia | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SosaDLuisR/diplomado_modulo_II_modelos_estadisticos/blob/main/Notebook_1-espacio_de_probabilidad.ipynb) |
| 2 | [`Notebook_2-variables_aleatorias.ipynb`](Notebook_2-variables_aleatorias.ipynb) | Variables aleatorias discretas y continuas: distribuciones, esperanza y varianza | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SosaDLuisR/diplomado_modulo_II_modelos_estadisticos/blob/main/Notebook_2-variables_aleatorias.ipynb) |
| 3 | [`Notebook_3-estadistica_inferencial.ipynb`](Notebook_3-estadistica_inferencial.ipynb) | Estadística inferencial: estimación, intervalos de confianza y pruebas de hipótesis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SosaDLuisR/diplomado_modulo_II_modelos_estadisticos/blob/main/Notebook_3-estadistica_inferencial.ipynb) |

## Requisitos

Los notebooks usan librerías estándar del ecosistema de ciencia de datos en Python:

```
numpy
pandas
matplotlib
scipy
```

Se pueden instalar con:

```bash
pip install numpy pandas matplotlib scipy
```

## Cómo usarlo

**Opción 1 — Google Colab (recomendado, sin instalar nada):**
Da clic en el botón "Open in Colab" del notebook que quieras revisar, en la tabla de arriba.

**Opción 2 — Localmente:**

```bash
git clone https://github.com/SosaDLuisR/diplomado_modulo_II_modelos_estadisticos.git
cd diplomado_modulo_II_modelos_estadisticos
pip install numpy pandas matplotlib scipy
jupyter notebook
```

Y abre el notebook que quieras desde el navegador.

## Autor

[SosaDLuisR](https://github.com/SosaDLuisR)
