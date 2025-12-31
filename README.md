# App-para-análisis-de-mezcla-bicompuesto
# ⚗️ TermoSuite: VLE Analyzer (n-Heptane / Toluene)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PyQt6](https://img.shields.io/badge/GUI-PyQt6-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**[English]**
A comprehensive desktop application designed for Chemical Engineers to model, simulate, and analyze Vapor-Liquid Equilibrium (VLE) data for the n-Heptane/Toluene binary system. It performs parameter fitting using non-linear regression and thermodynamic predictions.

**[Español]**
Una aplicación de escritorio integral diseñada para Ingenieros Químicos para modelar, simular y analizar datos de Equilibrio Líquido-Vapor (ELV) del sistema binario n-Heptano/Tolueno. Realiza ajuste de parámetros mediante regresión no lineal y predicciones termodinámicas.

---

## 🚀 Key Features / Características Principales

### 🇬🇧 English
* **Multi-Model Analysis:** Includes 7 thermodynamic models: Wilson, UNIQUAC, UNIFAC (Predictive), Margules (1P & 2P), NRTL (3 Parameters), and Van Laar.
* **Parameter Optimization:** Uses `scipy.optimize.least_squares` to fit binary interaction parameters to experimental data minimizing error in Gamma or Pressure.
* **Advanced Visualization:** Generates real-time plots using Matplotlib:
    * Unified Analysis (Model vs. Exp).
    * P-x-y and T-x-y Diagrams.
    * y-x Equilibrium Curve.
    * Gibbs Energy Analysis.
* **Data Management:** Built-in experimental datasets (13.33, 26.66, 53.33 kPa) and support for **importing external CSV/Excel files**.
* **Interactive GUI:** Built with **PyQt6**, featuring a tabbed interface, instant feedback logs, and data tables with error calculation.

### 🇪🇸 Español
* **Análisis Multi-Modelo:** Incluye 7 modelos termodinámicos: Wilson, UNIQUAC, UNIFAC (Predictivo), Margules (1P y 2P), NRTL (3 Parámetros) y Van Laar.
* **Optimización de Parámetros:** Utiliza `scipy.optimize.least_squares` para ajustar parámetros de interacción binaria a datos experimentales, minimizando el error en Gamma o Presión.
* **Visualización Avanzada:** Genera gráficos en tiempo real con Matplotlib:
    * Análisis Unificado (Modelo vs. Exp).
    * Diagramas P-x-y y T-x-y.
    * Curva de Equilibrio y-x.
    * Análisis de Energía de Gibbs.
* **Gestión de Datos:** Bases de datos experimentales integradas (13.33, 26.66, 53.33 kPa) y soporte para **importar archivos CSV/Excel**.
* **Interfaz Interactiva:** Construida con **PyQt6**, con navegación por pestañas, logs de resultados instantáneos y tablas de datos con cálculo de errores.

---

## 🛠️ Built With / Tecnologías

* **Python 3.x**
* **PyQt6** (User Interface)
* **Matplotlib** (Plotting)
* **NumPy & Pandas** (Data Processing)
* **SciPy** (Optimization/Regression)

---

## 📦 Installation & Usage / Instalación y Uso

1.  **Clone the repository / Clona el repositorio:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/TermoSuite-VLE.git](https://github.com/YOUR_USERNAME/TermoSuite-VLE.git)
    cd TermoSuite-VLE
    ```

2.  **Install dependencies / Instala las dependencias:**
    ```bash
    pip install numpy pandas matplotlib scipy PyQt6 openpyxl
    ```

3.  **Run the application / Ejecuta la aplicación:**
    ```bash
    python main.py
    ```

---

## 📊 Screenshots / Capturas

*(Add your screenshots here / Agrega tus capturas aquí)*

![App Screenshot](path_to_image.png)

---

**Author / Autor:** [Your Name / Tu Nombre]
