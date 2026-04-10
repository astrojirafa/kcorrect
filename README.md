# K-Correction Analysis & Cosmological Distances

Este repositorio una serie de Jupyter Notebooks diseñados para aplicar el algoritmo **kcorrect** (Blanton et al.) en diferentes escalas, desde galaxias individuales hasta muestras completas como la Muestra Principal de Galaxias de SDSS (Main Sample Galaxy, MSG), incluyendo cálculos de distancias cosmologías.


## Contenido del Repositorio

El análisis se divide en tres etapas progresivas:

| Notebook | Descripción | Enfoque |
| :--- | :--- | :--- |
| `kcorrect_1.ipynb` | **Análisis Individual** | Procesamiento y ajuste de SED para una sola galaxia. |
| `kcorrect_MSG.ipynb` | **Main Sample Galaxy (MSG)** | Aplicación de correcciones K a gran escala sobre la muestra principal. |
| `kcorrect_cosmology_MSG.ipynb` | **MSG + Cosmología** | Cálculos de distancias cosmológicas integrados para la muestra. |

---

## Cálculos Cosmológicos Incluidos

En el Notebook (`kcorrect_cosmology.ipynb`), se implementan las fórmulas para determinar:

* **Distancia Comóvil:** Tanto la línea de visión como la distancia comóvil transversa.
* **Distancia de Luminosidad ($d_L$):** Crucial para determinar magnitudes absolutas.
* **Distancia de Diámetro Angular ($d_A$):** Para el estudio del tamaño físico de las fuentes.

Estos cálculos permiten transformar los datos observacionales en parámetros físicos intrínsecos dependientes del redshift ($z$).

   pip install numpy pandas matplotlib astropy
