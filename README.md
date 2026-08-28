# Caso de Estudio: Optimización Integrada de la Cadena de Suministro (S&OP)
**Supply Chain Analytics | Demand Planning • Inventory Management • Transportation Network Optimization**

Caso de estudio desarrollado en Microsoft Excel y Solver para analizar de forma integrada tres procesos clave de Supply Chain bajo un enfoque de Sales & Operations Planning (S&OP).

---

## 📌 Objetivo del Proyecto
Evaluar el desempeño integral del proceso de S&OP mediante la integración de pronósticos de demanda, políticas de inventario y optimización del transporte, identificando oportunidades para reducir costos, minimizar quiebres de stock y mejorar el nivel de servicio.

---

## 🔑 Resultados Clave
* **1.200 SKUs Analizados:** Evaluación de modelos MMS, MMP, SES, Holt, Regresión Lineal y Holt-Winters.
* **WAPE Global:** `2,23%` (Alta precisión en productos de mayor impacto financiero).
* **Sesgo de Demanda:** `70,33%` de los SKUs presentan subestimación sistemática.
* **Inventario Crítico:** `60 SKUs` bajo Punto de Reorden (ROP) y `$97.547,43` en exceso de stock recuperable.
* **Rotación y Cobertura:** Rotación anual de `16x` y cobertura promedio de `15 días`.
* **Red Logística Integrada:** Optimización de `537 pallets` mediante Solver con un costo total de `$39.026,96` y `75%` de nivel de servicio.

---

## 📁 Archivos del Repositorio
* 📊 `Planificación de la Demanda.xlsb` — Modelos de pronóstico, MAPE, WAPE, BIAS.
* 📦 `Gestión de Inventario.xlsb` — Clasificación ABC-XYZ, Stock de Seguridad, ROP y análisis de sobrestock/quiebres.
* 🚚 `Gestión de Transporte.xlsb` — Modelo de optimización lineal en Solver para asignación de flujos y capacidades de CDs.
* 📄 `Informe_Ejecutivo_SOP.pdf` — Reporte ejecutivo consolidado para toma de decisiones.

---

## 🛠️ Herramientas Utilizadas
* **Microsoft Excel:** Tablas dinámicas, fórmulas avanzadas, modelos binarios (`.xlsb`).
* **Solver:** Optimización lineal aplicada a redes de transporte.
* **Supply Chain Analytics:** Modelado probabilístico de inventarios y series temporales.
