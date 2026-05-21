# 🧹 Registro de limpieza del dataset

## 📊 Dataset trabajado

Dataset de ventas retail de e-cigarettes en Estados Unidos.

El archivo original contiene información mensual por estado, marca, sabor, tipo de producto, ventas, volumen de nicotina y variables regulatorias. Para este mini proyecto se trabajó en la limpieza y preparación del dataset con el fin de usarlo posteriormente en análisis, tablas dinámicas, KPIs y dashboard en Excel.

---

## 🎯 Objetivo de la limpieza

Preparar una versión limpia y organizada del dataset para facilitar el análisis posterior en Excel.

El objetivo principal fue mejorar la estructura del archivo, revisar formatos, crear columnas auxiliares y dejar las variables listas para ser utilizadas en tablas dinámicas, segmentadores, visualizaciones y construcción del dashboard final.

---

## 🔍 Revisión inicial

Durante la revisión inicial del dataset se identificaron aspectos que debían ser ajustados antes del análisis:

- Nombres de columnas poco claros o extensos.
- Necesidad de organizar mejor las columnas.
- Columnas numéricas con formatos que requerían revisión.
- Datos porcentuales que no estaban listos para analizar correctamente.
- Necesidad de construir un orden cronológico mensual.
- Columnas de fecha que requerían extracción de año y mes.
- Preparación del archivo para análisis en Excel y Power Query.

---

## 🔧 Acciones realizadas

### 1. Carga del archivo en Power Query

El dataset original fue cargado en **Power Query** para realizar el proceso de limpieza y transformación de manera más ordenada.

Se trabajó sobre una consulta referenciada dentro de Power Query, con el fin de conservar la consulta base y aplicar transformaciones sobre una versión derivada del dataset.

Esto permite mantener una mejor trazabilidad del proceso de limpieza y evitar modificar directamente la consulta original.

---

### 2. Revisión y organización de columnas

Se revisó la estructura general del dataset y se organizaron las columnas para facilitar su lectura y uso posterior en Excel.

El objetivo fue dejar el archivo con una estructura más clara para análisis de ventas, tablas dinámicas, KPIs y construcción de dashboard.

---

### 3. Cambio de nombre de columnas

Se realizó el cambio de nombre de varias columnas para facilitar el entendimiento del dataset y mejorar su uso en Excel.

El objetivo de este paso fue que los encabezados fueran más claros, descriptivos y fáciles de interpretar al momento de construir tablas dinámicas, KPIs y visualizaciones.

Este cambio fue clave porque nombres de columnas poco claros pueden dificultar el análisis, generar confusión y afectar la comunicación de los resultados.

El renombramiento permitió que el dataset limpio quedara más organizado y entendible para las siguientes etapas del proyecto.

---

### 4. Uso de columnas calculadas

Se crearon columnas calculadas dentro de Power Query para corregir y preparar variables necesarias para el análisis.

Estas columnas fueron utilizadas principalmente para:

- Corregir el formato de datos porcentuales;
- Preparar campos auxiliares para ordenamiento;
- Construir variables de tiempo más útiles para análisis mensual;
- Mejorar la estructura del dataset para futuras tablas dinámicas y gráficos.

---

### 5. Corrección de datos porcentuales

Se corrigió el formato de una columna que debía trabajarse como porcentaje.

Para esto se utilizó una columna calculada que permitió transformar el dato y dejarlo listo para análisis, evitando errores de interpretación en Excel.

Este ajuste fue importante porque los porcentajes mal formateados pueden afectar tablas dinámicas, gráficos, segmentadores y cálculos posteriores.

---

### 6. Construcción del orden de periodo mensual

Para ordenar correctamente los periodos mensuales, se extrajeron componentes de fecha como:

- Año;
- Mes.

A partir de estos elementos se construyó un código de orden mensual, lo que permite ordenar los periodos de forma cronológica y no alfabética.

Esto es importante porque, en análisis temporal, los meses deben visualizarse en el orden correcto para interpretar tendencias de ventas.

---

### 7. Revisión de formatos

Se revisaron formatos de fecha, texto y valores numéricos para evitar errores en el análisis.

La revisión incluyó:

- Campos de fecha;
- Columnas numéricas;
- Columnas de texto;
- Campos porcentuales;
- Variables usadas para segmentación.

---

### 8. Preparación del dataset limpio

Después del proceso de limpieza y transformación, se generó una versión limpia del archivo con el nombre:

```text
Dataset Limpio.xlsx
```

## 📁 Archivos relacionados

### Dataset original

```text
data/raw/
```

Contiene el archivo original antes del proceso de limpieza.

### Dataset limpio

```text
data/processed/
```

Contiene la versión limpia y organizada del dataset, preparada para análisis posterior.

---

## ✅ Resultado

Como resultado del proceso se obtuvo un dataset más claro, estructurado y preparado para análisis en Excel.

El archivo limpio quedó listo para ser utilizado en las siguientes etapas de la Semana 1:

- Creación de tablas dinámicas;
- Construcción de KPIs;
- Análisis de ventas por periodo;
- Análisis por categoría o producto;
- Visualizaciones;
- Dashboard final en Excel.

---

## 🧠 Aprendizajes

Este mini proyecto permitió reforzar que la limpieza de datos es una etapa fundamental antes de construir cualquier análisis.

También permitió practicar el uso de Power Query como herramienta para transformar datos, crear columnas calculadas, corregir formatos, renombrar columnas y preparar variables útiles para análisis posterior.

Un aprendizaje importante fue que no basta con tener los datos cargados: también es necesario revisar si los formatos son correctos, si los periodos se ordenan adecuadamente y si las columnas están nombradas de forma clara para facilitar la interpretación.

---

## ➡️ Próximo paso

Usar el dataset limpio para construir tablas dinámicas, KPIs, gráficos y visualizaciones durante los siguientes días de la Semana 1.
