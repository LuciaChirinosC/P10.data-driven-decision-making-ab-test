# P10.data-driven-decision-making-ab-test
# 🧠 Proyecto: Toma de decisiones basadas en datos

Este proyecto forma parte del curso **"La toma de decisiones de negocios basadas en datos"**, y tiene como objetivo aplicar técnicas analíticas para priorizar hipótesis y analizar los resultados de una prueba A/B en una tienda online.

## 📊 Contexto
Como analista de datos en una gran tienda online, colaboras con el departamento de marketing para aumentar los ingresos. Se han definido varias hipótesis que podrían impactar las ventas, y tu tarea es:

1. **Priorizar las hipótesis** según su potencial impacto y viabilidad.  
2. **Analizar un test A/B** para identificar diferencias significativas en el comportamiento de los grupos A y B.

## 📁 Datos
Se utilizan tres datasets:

- **`hypotheses_us.csv`** — contiene nueve hipótesis con las variables Reach, Impact, Confidence y Effort.  
- **`orders_us.csv`** — pedidos realizados durante la prueba A/B.  
- **`visits_us.csv`** — número de visitas diarias por grupo.

## ⚙️ Etapas del proyecto

### 1️⃣ Priorización de hipótesis
- Aplicación de los frameworks **ICE** y **RICE**.  
- Comparación de los resultados y análisis de los cambios en la priorización.

### 2️⃣ Análisis del test A/B
- Ingreso acumulado y tamaño promedio de pedido por grupo.  
- Tasa de conversión diaria.  
- Detección y filtrado de anomalías.  
- Cálculo de significancia estadística para:
  - Conversión entre grupos.  
  - Tamaño promedio de pedido (antes y después de filtrar anomalías).  
- Conclusiones y toma de decisiones finales.

## 🧮 Herramientas utilizadas
- **Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)**  
- **Jupyter Notebook / VS Code**  
- **GitHub** para control de versiones y documentación

## 📈 Resultados esperados
- Identificación de las hipótesis más prometedoras para implementar.  
- Evaluación estadística robusta del test A/B.  
- Recomendación final sobre la continuidad o cierre del experimento.

## 👩‍💻 Autor
**Lucía Chirinos Cornejo**  
Analista de Datos | Ingeniera Ambiental  


## 🏁 Estado del proyecto
✅ En progreso — fase de análisis de hipótesis y visualización de resultados.
