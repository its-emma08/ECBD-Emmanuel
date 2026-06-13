# Extracción de Conocimiento de Bases de Datos

Este repositorio contiene las prácticas y laboratorios correspondientes al 1er Parcial de la materia **Extracción de Conocimiento de Bases de Datos**.

## Información del Alumno
*   **Nombre del Alumno:** Emmanuel Peña Ruiz
*   **Materia:** Extracción de Conocimiento de Bases de Datos
*   **Cuatrimestre:** Mayo - Agosto 2026

---

## Descripción General
Este proyecto integra laboratorios prácticos de análisis, limpieza y transformación de datos, aplicando metodologías como el modelo **DIKW** (Datos, Información, Conocimiento, Sabiduría) y principios fundamentales de calidad de datos como **GIGO** (Garbage In, Garbage Out). 

---

## Objetivo del Repositorio
Desarrollar un portafolio académico organizado que evidencie el proceso de extracción de conocimiento a partir de datasets reales y sintéticos, demostrando buenas prácticas de estructuración, control de versiones, documentación y análisis crítico de la información.

---

## Estructura del Proyecto
De acuerdo con los lineamientos establecidos para la evaluación del parcial, el repositorio cuenta con la siguiente estructura:

*   📁 **Notebooks/**: Contiene los notebooks de Jupyter (`.ipynb`) correspondientes a cada laboratorio (Lab01 al Lab10).
*   📁 **DataSet/**: Carpeta centralizada que almacena los datasets locales de origen y los datasets limpios procesados.
*   📄 **README.md**: Documentación principal del repositorio.

---

## Datasets Utilizados
1.  **Titanic Dataset** (`test.csv`): Datos de los pasajeros del Titanic, utilizados para ilustrar el flujo DIKW mediante limpieza, análisis descriptivo por género/clase y extracción de conclusiones.
2.  **Netflix Dataset** (`netflix_titles.csv`): Catálogo de series y películas en la plataforma para realizar análisis de distribución de ratings, años de lanzamiento y producción por país.
3.  **Ventas por Factura** (`ventas-por-factura.csv` / `Data_Limpio_Factura.csv`): Transacciones de ventas de e-commerce internacional con problemas de calidad (duplicados, cancelaciones, montos en texto con coma europea, valores negativos). Se aplicó limpieza de datos bajo el principio GIGO.
4.  **Telecom Churn** (Carga vía URL remota): Dataset sobre la tasa de cancelación de clientes en telecomunicaciones.

---

## Herramientas Utilizadas
*   **Lenguaje:** Python 3
*   **Librerías de Análisis:** Pandas, NumPy
*   **Librerías de Visualización:** Matplotlib, Seaborn
*   **Entornos de Desarrollo:** Jupyter Notebooks, VS Code
*   **Control de Versiones:** Git & GitHub

---

## Instrucciones de Ejecución General
1.  Clonar este repositorio en su entorno local:
    ```bash
    git clone https://github.com/[Usuario]/ECBD-Emmanuel.git
    ```
2.  Instalar las dependencias de Python necesarias:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Abrir Jupyter Notebook o VS Code e ingresar a la carpeta `Notebooks/`.
4.  Ejecutar el notebook deseado celda por celda.

---

## Conclusiones Generales del Parcial
A lo largo de los laboratorios del 01 al 07 (y posteriores), se consolidaron los siguientes aprendizajes:
*   **Importancia de la Estructura de Datos:** Un diseño coherente y una correcta definición de tipos (numéricos, categóricos, fechas) facilita el análisis exploratorio y evita fallos en las visualizaciones.
*   **El Principio GIGO:** Los análisis del Laboratorio 07 demostraron que procesar datos sin depurar (como sumar montos de facturas canceladas o cantidades negativas de corrección de inventario) genera métricas de negocio sesgadas y gráficos de distribución erróneos. La limpieza minuciosa es el pilar fundamental antes de cualquier modelo de negocio o Machine Learning.
*   **El Modelo DIKW:** Aplicado de forma transversal (sobre todo en Titanic y Netflix) para ir más allá del código técnico, traduciendo datos crudos en sabiduría e interpretaciones de valor práctico.
