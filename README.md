# Hola, soy Felipe Castillo 👋

**Estudiante de Ingeniería Civil Industrial · Universidad del Desarrollo** · 📍 Santiago, Chile

Supply Chain · Investigación de Operaciones · Analítica de Datos · IA aplicada

Me interesa usar datos, optimización e IA para tomar mejores decisiones en logística:
dónde ubicar un centro de distribución, cómo responder a un alza de demanda o qué
envíos van a llegar tarde. Busco mi **primer empleo o práctica** en supply chain,
operaciones o analítica.

> 🇬🇧 *Industrial Engineering student at Universidad del Desarrollo (Santiago, Chile), focused on supply chain, operations research and
> data analytics. I build tools that combine optimization (Gurobi), machine learning and
> LLMs to support logistics decisions. Open to entry-level roles and internships.*

---

## 🚚 Proyectos destacados

### [Agente de Optimización de Red Logística](https://github.com/CastilloFelipe/supply-chain-agent)
Simulador *what-if* para redes de distribución: haces una pregunta de negocio ("¿qué pasa
si cerramos el CD de La Serena y el diésel sube 15%?"), un LLM la traduce a cambios en un
modelo MILP, **Gurobi** lo resuelve y se genera un reporte ejecutivo.
- Modelo validado: reproduce los óptimos publicados de los benchmarks **OR-Library**.
- Traductor evaluado a ciegas con 70 preguntas en tres sets de dificultad creciente.
- Demo web en Streamlit, tests y CI con GitHub Actions.

`Python` `Gurobi` `MILP` `Claude API` `Streamlit` `Plotly` `pytest`

### [Monitor de Atrasos Logísticos](https://github.com/CastilloFelipe/monitor-atrasos-logisticos) · [app en línea](https://monitor-atrasos-logisticos.onrender.com)
Detecta en tiempo real los envíos con riesgo de atraso: carga de datos a SQL, modelo de
**Random Forest** explicado con SHAP, API REST y dashboard con KPIs y alertas. Además
consume una API de clima externa.

`Python` `SQL` `scikit-learn` `SHAP` `FastAPI` `JavaScript` `Chart.js`

### [Preparación y Análisis de Datos – Región 05](https://github.com/TomasAllendeJ/iele756-region-05) · *en equipo con [Tomás Allende](https://github.com/TomasAllendeJ)*
Portafolio del curso IELE756 con datos públicos chilenos (Censo 2024, ENO y egresos
hospitalarios GRD): limpieza, análisis exploratorio, modelamiento cruzado entre fuentes y
detección y defensa de una anomalía.

`Python` `pandas` `NumPy` `Matplotlib` `Jupyter`

### [Pronóstico S&P 500 vs Dow Jones](https://github.com/TomasAllendeJ/sp500-dji-time-series-forecasting) · *en equipo con Tomás Allende y Juan Costa*
Pronóstico de series de tiempo financieras comparando **Holt-Winters**, **ARIMA rolling**
(walk-forward) y una red **LSTM**, con test de estacionariedad y de cointegración de
Engle-Granger. Los modelos rolling bajan el MAPE de 12,75% (Holt-Winters) a cerca de 0,67%.

`Python` `statsmodels` `pmdarima` `TensorFlow/Keras` `scikit-learn` `yfinance`

---

## 🛠️ Habilidades

| Área | Herramientas |
|---|---|
| Programación y datos | Python (pandas, NumPy, scikit-learn), SQL, Jupyter |
| Optimización | Programación lineal y entera mixta, Gurobi (`gurobipy`), Solver de Excel |
| Analítica y BI | Power BI (intermedio), Excel (intermedio: tablas dinámicas, Solver), Matplotlib, Plotly |
| Desarrollo | FastAPI, Streamlit, Git y GitHub Actions, pytest |
| IA aplicada | LLMs con *tool use* (Claude), evaluación de modelos, ML explicable (SHAP) |

## 🎯 Intereses

- Diseño de redes de distribución y localización de instalaciones
- Gestión de inventarios y pronóstico de demanda
- Optimización y simulación de operaciones
- IA aplicada a decisiones logísticas

## 📫 Contacto

- ✉️ felipecastilloriq@gmail.com
- 💻 [github.com/CastilloFelipe](https://github.com/CastilloFelipe)
