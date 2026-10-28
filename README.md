# Modelos Matemáticos para el Control de Incendios Forestales: Fons y Rothermel

Este proyecto analiza el modelado matemático aplicado a la dinámica y control de incendios forestales, explorando la transición entre formulaciones analíticas termodinámicas y modelos semiempíricos avanzados.

---

## 📌 Contenido y Enfoque del Proyecto

1. **Clasificación de Modelos:**
   - **Modelos Estocásticos:** Aproximaciones probabilísticas y simulación por método de Monte Carlo frente a la incertidumbre.
   - **Modelos Deterministas:** Formulación mediante ecuaciones diferenciales y análisis de frentes de propagación.

2. **Modelo de Fons (1940):**
   - Fundamentos físicos basados en transferencia de calor por radiación y conducción ($q = q_C + q_R$).
   - Resolución de la ecuación diferencial para el cálculo del tiempo de ignición ($t_i$) y velocidad de avance lineal ($R$).
   - Discusión sobre las simplificaciones geométricas (doble semielipse de Anderson) y limitaciones ante factores topográficos.

3. **Modelo de Rothermel (1972/1983):**
   - Ecuación balanceada de propagación del frente de fuego en función del calor disponible ($I$), energía de ignición ($Q_{ig}$) y densidad de combustible ($P_b$).
   - Incorporación analítica de factores ambientales: aceleración por viento ($Q_w$) y pendiente del terreno ($Q_s$).
   - Análisis de aplicaciones estándar en la industria forestal y software de simulación (FARSITE, BEHAVE, Wildfire Management Tool).

4. **Implementación y Simulación Numérica:**
   - Implementación de algoritmos de propagación en **MATLAB** y **Python** aplicados a bosques de eucalipto.
   - Evaluación de sensibilidad de la velocidad de propagación de cabeza y flancos ante variaciones en la humedad relativa del combustible (40% vs. 70%).

---

## 📂 Archivos del Repositorio
- `MODELIZACION_PRESENTACION.pdf`: Presentación académica con el desglose teórico, ecuaciones y resultados comparativos.

---

## 👥 Autores
- **Lucía Marquina**
- **Pablo Herrera**
- **Andrea Ballesteros**
- **Patricia Fernández**
- **Gemma López Coloma**
