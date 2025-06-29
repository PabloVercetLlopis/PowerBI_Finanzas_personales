# PowerBI_Finanzas_personales
# Proyecto 4 – Finanzas Personales 💰📊

Este repositorio contiene un proyecto centrado en la **gestión de finanzas personales**. El objetivo principal es diseñar un panel de control que permita al usuario tener una visión clara y detallada de sus ingresos, gastos, ahorro y evolución financiera a lo largo del tiempo.

---

## 📌 Objetivo del proyecto

El informe está diseñado para ayudar al usuario a:

- Monitorear sus ingresos y gastos mensuales.
- Analizar su capacidad de ahorro.
- Identificar patrones de consumo.
- Comparar el rendimiento económico mes a mes y año a año.

Este proyecto permite poner en práctica herramientas clave de Power BI, incluyendo:

- Importación y modelado de datos personales.
- Uso de **DAX** para crear medidas dinámicas.
- Visualizaciones limpias y fáciles de interpretar.
- Segmentación temporal por meses y años.

---

## 🧾 Fuente de datos

Se utiliza un archivo Excel simulado con las siguientes hojas:

- **Transacciones**: lista de ingresos y gastos clasificados por fecha y categoría.
- **Categorías**: desglose de los tipos de gasto (comida, transporte, ocio, etc.).
- **Presupuestos mensuales** (opcional): límite estimado por categoría.

Los datos están anonimizados y creados con fines educativos.

---

## 📊 Visualizaciones incluidas

El informe contiene:

- **Resumen general**: ingresos, gastos, ahorro neto y balance.
- **Gráficos de líneas**: evolución del saldo a lo largo de los meses.
- **Gráfico de columnas**: comparación entre ingresos y gastos por mes.
- **Gráfico circular**: desglose del gasto por categoría.
- **Segmentadores**: por mes, año, tipo de transacción, categoría.

---

## 🎯 KPIs destacados

- **Ingresos totales**
- **Gastos totales**
- **Ahorro neto mensual**
- **Porcentaje de ahorro respecto al ingreso**
- **Gasto medio por categoría**

Estos indicadores se calculan mediante medidas personalizadas con **DAX**.

---

## 📁 Estructura del repositorio

PowerBI_Finanzas_personales/
│
├─ Data/
│ └─ finanzas_personales.xlsx
│
├─ Powerbi/
│ └─ Proyecto4_FinanzasPersonales.pbix
│
├─ power_query/
│ └─ transformaciones
│
├─ Visualizaciones/
│ └─ captura_dashboard.png
│
└─ README.md
