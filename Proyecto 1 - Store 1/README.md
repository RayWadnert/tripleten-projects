# Proyecto 1 — Store 1 (Limpieza de datos de clientes, ~7K registros)

## 📌 Problema
El dataset de clientes presentaba **IDs duplicados**, **nombres inconsistentes** y **edades fuera de rango**.  
Objetivo: obtener un **dataset limpio y estandarizado** para análisis posteriores y visualizaciones.

## 📊 Dataset
- Tamaño: ~**7,000** registros  
- Variables: `customer_id`, `name`, `age`, `gender`, (otras)  
- Origen: dataset de práctica (TripleTen)  
- Calidad: duplicados y valores inválidos detectados en campos clave

## 🛠️ Stack
- **Python:** pandas
- **Entorno:** Jupyter Notebook (`.ipynb`)
- (Opcional) **Excel** para validación rápida

## 🔎 Metodología
1. **Perfilado inicial** del dataset (dimensiones, nulos, tipos).  
2. **Depuración de duplicados** por `customer_id`.  
3. **Normalización de nombres** (espacios, mayúsculas/minúsculas).  
4. **Validación de edades** (rangos razonables e imputación/eliminación).  
5. **Exportación** a CSV limpio para usos posteriores.

## 📈 Resultados / KPIs
- 100% de **IDs válidos** y únicos.  
- Nombres estandarizados (casing y trimming).  
- Edades fuera de rango corregidas o removidas.  
- **Dataset listo para EDA/BI**.
