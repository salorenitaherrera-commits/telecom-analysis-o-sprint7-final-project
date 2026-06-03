📊 Telecom Analysis

## 🎯 Objetivo del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones, con el fin de identificar patrones de uso, segmentar usuarios y generar recomendaciones para optimizar los planes de servicio.

---

## 📁 Datasets utilizados

Se utilizaron dos fuentes principales de datos:

- plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

---

## 🧭 Etapas del análisis

El análisis se realizó en las siguientes etapas:

### 1. Exploración de datos (EDA)
- Revisión de valores nulos
- Identificación de valores atípicos (outliers)
- Análisis de variables numéricas y categóricas

### 2. Limpieza de datos
- Tratamiento de valores faltantes
- Corrección de valores inválidos (sentinels)
- Conversión de tipos de datos

### 3. Análisis descriptivo
- Distribución de edad, llamadas, mensajes y minutos
- Comparación por tipo de plan

### 4. Segmentación de clientes
- Creación de grupos por edad
- Creación de grupos por nivel de uso (bajo, medio, alto)

### 5. Análisis de correlación
- Evaluación de relación entre edad y uso del servicio

---

## 📊 Principales hallazgos

- La mayoría de los usuarios presenta un uso medio del servicio.
- Existen usuarios “heavy users” con consumo significativamente alto.
- No se encontró una correlación significativa entre edad y uso del servicio.
- El tipo de plan no está fuertemente diferenciado por edad.

---

## 💡 Recomendaciones

- Segmentar clientes según nivel de uso en lugar de edad.
- Crear planes específicos para usuarios de alto consumo.
- Implementar estrategias de upselling para usuarios de uso medio.
- Analizar comportamiento de usuarios intensivos para maximizar ingresos.
