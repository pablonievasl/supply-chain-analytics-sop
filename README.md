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

## 📊 Dashboards

### 📈 Planificación de la Demanda

<img width="1870" height="729" alt="image" src="https://github.com/user-attachments/assets/64544071-5344-467d-82f3-51f51a2bf4d2" />

### 📦 Gestión de Inventarios

<img width="1869" height="731" alt="image" src="https://github.com/user-attachments/assets/09bd5d6c-af22-44e1-939d-fc8f4c53a2f9" />

### 🚚 Optimización del Transporte

<img width="1870" height="739" alt="image" src="https://github.com/user-attachments/assets/5a946239-1ad4-4e43-a6ba-69c4a38e1610" />

---

## 📁 Archivos del Repositorio
* 📊 `1-Planificación de la Demanda.xlsb` — Modelos de pronóstico, MAPE, WAPE, BIAS.
* 📦 `2-Gestión de Inventario.xlsb` — Clasificación ABC-XYZ, Stock de Seguridad, ROP y análisis de sobrestock/quiebres.
* 🚚 `3-Optimización del Transporte.xlsb` — Modelo de optimización lineal en Solver para asignación de flujos y capacidades de CDs.
* 📄 `Informe_Ejecutivo_SOP.pdf` — Reporte ejecutivo consolidado para toma de decisiones.

---

## 📐 Metodología

### 📈 Planificación de la Demanda
- Media Móvil Simple (MMS)
- Media Móvil Ponderada (MMP)
- Suavizamiento Exponencial Simple (SES)
- Suavizamiento Exponencial Doble (Holt)
- Regresión Lineal
- Suavizamiento Exponencial Triple (Holt-Winters)
- Evaluación mediante MAPE, WAPE, MAD, RMSE y BIAS

### 📦 Gestión de Inventarios
- Clasificación ABC-XYZ
- EOQ
- Stock de Seguridad
- Punto de Reorden (ROP)
- Cobertura y rotación
- Análisis de exceso de inventario y riesgo de quiebre

### 🚚 Optimización del Transporte
- Modelo de transporte/transbordo
- Restricciones de capacidad y distancia
- Optimización mediante Solver

---

## 🛠️ Herramientas Utilizadas
* **Microsoft Excel:** Tablas dinámicas, fórmulas avanzadas, modelos binarios (`.xlsb`).
* **Solver:** Optimización lineal aplicada a redes de transporte.
* **Supply Chain Analytics:** Modelado probabilístico de inventarios y series temporales.
