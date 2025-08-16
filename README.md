# 📊 Challenge-DS-LATAM-TelecomX-P1 | Análisis de Evasión de Clientes

Este proyecto combina un enfoque **técnico de ciencia de datos** con una **visión estratégica de negocio**, para estudiar la evasión de clientes (*churn*) en TelecomX.

---

## 🎯 Objetivos
- Explorar los factores que impulsan la salida de clientes.  
- Entender el perfil de quienes permanecen vs. quienes abandonan.  
- Proveer un set de métricas y visualizaciones como base para modelos predictivos de churn.  

---

## 🔄 Flujo ETL
1. Extracción desde JSON.  
2. Transformación:  
   - Normalización de columnas  
   - Limpieza de nulos y tipos  
   - Variables derivadas (ej. `Charges.Daily`)  
   - Mapas binarios (`Yes/No → 1/0`)  
3. Carga final en `df_act`.  

---

## 📈 Insights Clave
- Contratos **mensuales** = mayor churn.  
- Método de pago **Electronic Check** = riesgo más alto.  
- Churn más fuerte en clientes con **poco tenure** y **altos cargos mensuales**.  
- La retención mejora en contratos anuales o bianuales.  

---

## 📦 Requisitos Técnicos

 Biblioteca         | Version               |
|-------------------|-----------------------|
| **pandas**        | 2.2.2                 |
| **numpy**         | 2.0.2                 |
| **matplotlib**    | 3.10.0                |
| **seaborn**       | 0.13.2                |
| **scikit-learn**  | 1.6.1                 |

---

## 🚀 Cómo usar
1. Clonar este repositorio.  
2. Abrir [TelecomX_P1_LATAM_RVJ.ipynb](https://github.com/ro-kazz/Challenge-DS-LATAM-Telecom-P1/blob/149e0ce22a9a9cfe6966190e8f2cc55c8232c7fb/TelecomX_P1_LATAM_RVJ.ipynb).  
3. Ejecutar las celdas.  

---

## 📑 Conclusiones
El análisis entrega información crítica para:  
- Detectar clientes en riesgo.  
- Entender patrones de evasión.  
- Apoyar la toma de decisiones en estrategias de retención.  
