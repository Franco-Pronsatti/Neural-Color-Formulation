# Neural Color Formulation 🎨

> **Optimización de formulación de color industrial mediante Deep Learning inverso y simulación física (Kubelka-Munk).**

## 📋 Descripción
Este proyecto resuelve el problema de la formulación de pinturas en polvo, reduciendo el proceso tradicional de "prueba y error". Utiliza una **Red Neuronal Densa (DNN)** entrenada con 100,000 datos sintéticos generados mediante las leyes físicas de absorción y dispersión de la luz.

## 🚀 Resultados
- **Precisión:** Delta E = 0.76 (Indistinguible para el ojo humano).
- **Velocidad:** Predicción instantánea vs. días de trabajo manual.
- **Tecnología:** Python, TensorFlow/Keras, NumPy, Pandas.

## 🛠️ Cómo funciona
1. **Generador Físico:** Simula mezclas de pigmentos reales (Base, Rojo, Azul, Amarillo) usando coeficientes K/S.
2. **Entrenamiento Inverso:** La IA aprende a deducir la receta (gramos) a partir del color deseado (CIELAB).
3. **Validación:** Se verifica la receta predicha volviéndola a simular físicamente.

## 📂 Archivos
- `color_simulation.py`: Generación de dataset sintético.
- `neural_formulator.py`: Entrenamiento del modelo y predicción.
- `Technical_Report.pdf`: Informe detallado del caso de estudio.

---
*Autor: Franco Pronsatti - 2025*
