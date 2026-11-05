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

### [Agente de Optimización de Red Logística](https://github.com/CastilloFelipe/supply-chain-agent) · [app en línea](https://llm-supply-chain-agent.streamlit.app/)
Simulador *what-if* para redes de distribución: haces una pregunta de negocio ("¿qué pasa
si cerramos el CD de La Serena y el diésel sube 15%?"), un LLM la traduce a cambios en un
modelo MILP, **Gurobi** lo resuelve y se genera un reporte ejecutivo.
- Modelo validado: reproduce los óptimos publicados de los benchmarks **OR-Library**.
- Traductor evaluado a ciegas con 70 preguntas en tres sets de dificultad creciente.
- Demo web en Streamlit, tests y CI con GitHub Actions.

`Python` `Gurobi` `MILP` `Claude API` `Streamlit` `Plotly` `pytest`

### [Inventario estocástico con demanda real de Walmart](https://github.com/CastilloFelipe/inventario-estocastico) · [app en línea](https://inventario-estocastico.streamlit.app/)
¿La fórmula clásica de stock de seguridad entrega el servicio que promete? Lo probé con
3.049 productos reales (dataset M5 de Walmart), comparándola con políticas (R, S) calibradas
por **simulación Monte Carlo** y evaluadas con un año de demanda que el modelo no vio.
- La fórmula prometía 95% de servicio por ciclo y logró 90,5%. La brecha se asocia a que la
  demanda de días cercanos está correlacionada, algo que la fórmula supone que no pasa.
- Un **bootstrap por bloques** subió el servicio a 93,4%, a cambio de más inventario.
- Simulador validado contra la teoría de Poisson, curva inventario vs servicio, guía de
  conceptos y app en Streamlit.

`Python` `NumPy` `Monte Carlo` `Bootstrap` `pandas` `SciPy` `Streamlit` `pytest`

### [Ruteo de vehículos con ventanas horarias (VRPTW)](https://github.com/CastilloFelipe/ruteo-vehiculos)
¿Qué camión visita a qué clientes y en qué orden, con capacidad limitada y ventanas
horarias? Resolví las **56 instancias de Solomon** con inserción, búsqueda local y **ALNS**, y
comparé contra las mejores soluciones publicadas y contra el óptimo exacto de **Gurobi**.
- ALNS queda a un **1,6%** en promedio de los récords, con 10 s por instancia, e iguala el récord
  en las 17 instancias agrupadas.
- En cortes de 25 y 50 clientes, Gurobi prueba el óptimo y ALNS lo alcanza en 9 de 12 casos.
- App en Streamlit con una animación de las camionetas recorriendo sus rutas.

`Python` `Gurobi` `MILP` `ALNS` `Metaheurísticas` `Streamlit` `Plotly` `pytest`

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
| Optimización | Programación lineal y entera mixta, Gurobi (`gurobipy`), ruteo de vehículos (VRPTW), metaheurísticas (ALNS, búsqueda local), Solver de Excel |
| Modelos estocásticos | Simulación Monte Carlo, bootstrap (diario y por bloques), políticas de inventario (R, S), nivel de servicio y fill rate |
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
