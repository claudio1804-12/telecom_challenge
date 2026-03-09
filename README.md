# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la **evasión de clientes** en Telecom X. La empresa enfrenta una alta tasa de cancelaciones de servicios, lo que impacta directamente en sus ingresos y crecimiento.

El propósito del análisis es **identificar patrones y factores asociados a la pérdida de clientes**, utilizando herramientas de análisis de datos en Python. Los resultados permitirán al equipo de Data Science desarrollar **modelos predictivos y estrategias de retención** para disminuir la tasa de cancelación.

---

## 🎯 Objetivos

* Recopilar y procesar los datos de clientes de Telecom X.
* Limpiar y preparar los datos para su análisis.
* Explorar las variables que influyen en la evasión de clientes.
* Generar visualizaciones que permitan identificar patrones relevantes.
* Entregar información que apoye el desarrollo de modelos predictivos de churn.

---

## 🗂️ Datos

Los datos utilizados contienen información sobre clientes de Telecom X, incluyendo:

* Información demográfica de los clientes
* Tipo de contrato
* Servicios contratados
* Antigüedad del cliente en la empresa
* Cargos mensuales y totales
* Estado de evasión del cliente (**Churn**)

El dataset fue procesado para:

* Normalizar estructuras JSON
* Limpiar valores faltantes
* Convertir variables a tipos adecuados para el análisis

---

## 🧰 Tecnologías Utilizadas

El análisis se realizó utilizando el lenguaje **Python** y las siguientes bibliotecas:

* pandas – manipulación y limpieza de datos
* numpy – operaciones numéricas
* matplotlib – visualización de datos
* requests – obtención de datos desde API

---

## 🔎 Análisis Realizado

Durante el proyecto se realizaron las siguientes etapas:

### 1. Extracción de Datos

Obtención de información desde una fuente externa mediante API en formato **JSON**.

### 2. Transformación de Datos

* Normalización de estructuras JSON
* Conversión de tipos de datos
* Tratamiento de valores faltantes

### 3. Análisis Exploratorio de Datos (EDA)

Se realizaron diferentes análisis visuales para identificar patrones de churn:

* Distribución de clientes que cancelan el servicio
* Relación entre antigüedad del cliente y evasión
* Impacto de cargos mensuales y totales
* Influencia de características demográficas y servicios contratados

---

## 📈 Ejemplos de Visualizaciones

El proyecto incluye visualizaciones como:

* Gráficos de barras de distribución de churn
* Gráficos de dispersión para analizar correlaciones
* Gráficos de pastel para distribución de clientes
* Comparaciones entre variables relevantes

---

## 💡 Resultados Esperados

A partir de este análisis se busca:

* Detectar **factores que aumentan la probabilidad de cancelación**
* Identificar **segmentos de clientes con mayor riesgo de churn**
* Proporcionar información útil para la **construcción de modelos predictivos**
