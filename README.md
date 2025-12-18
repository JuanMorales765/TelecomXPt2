# TelecomXPt2

Modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios en TelecomX.

🧠 **Objetivos del Desafío**

- Preparar los datos para el modelado (tratamiento, codificación, normalización).
- Realizar análisis de correlación y selección de variables.
- Entrenar dos o más modelos de clasificación.
- Evaluar el rendimiento de los modelos con métricas.
- Interpretar los resultados, incluyendo la importancia de las variables.
- Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.

**Consideración importante:** Llamar al archivo CSV con el nombre TelecomXPT2DatLimp.csv (en el archivo descargado) y cambiar las direcciones donde se guardan y se exporta el modelo para poder hacer uso del código.

Para poder ejecutarel de manera local, necesitarás instalar todas las librerías que importas en tu script. Aquí te dejo una lista de los paquetes que necesitarás y algunos detalles importantes:

### Librerías principales a instalar:
1. **Pandas** - `pip install pandas`
2. **Scikit-learn** - `pip install scikit-learn`
3. **Imbalanced-learn** - `pip install imbalanced-learn`
4. **Statsmodels** - `pip install statsmodels`
5. **Matplotlib** - `pip install matplotlib`
6. **Seaborn** - `pip install seaborn`
7. **NumPy** - `pip install numpy`
8. **Plotly** - `pip install plotly`
9. **XGBoost** - `pip install xgboost` (como lo mencionas al final)
10. **Pickle** - Viene incluido con Python, no necesita instalación.

### Consideraciones importantes:

1. **Orden de instalación**:
   - Es recomendable instalar primero las dependencias principales como numpy y scipy antes que scikit-learn.
   - XGBoost a veces requiere compilación, en Windows es más fácil instalarlo con `pip install xgboost` o usando conda.

2. **Versiones compatibles**:
   - Algunas versiones de estas librerías pueden tener incompatibilidades entre sí.
   - Si tienes problemas, considera usar un entorno virtual.

3. **Entorno recomendado**:
   - Te sugiero usar Anaconda o Miniconda para gestionar estos paquetes, especialmente si trabajas en Windows.
   - Alternativamente, puedes crear un entorno virtual con Python 3.8+.

4. **Instalación con pip**:
   Puedes instalar todo con un solo comando:
   ```
   pip install pandas scikit-learn imbalanced-learn statsmodels matplotlib seaborn numpy plotly xgboost
   ```

5. **Dependencias específicas**:
   - SMOTE (de imbalanced-learn) requiere scikit-learn
   - Plotly puede requerir kaleido para exportar imágenes

6. **Sistema operativo**:
   - En Linux/Mac, generalmente no hay problemas
   - En Windows, algunas librerías como XGBoost pueden requerir Microsoft Visual C++ Build Tools


