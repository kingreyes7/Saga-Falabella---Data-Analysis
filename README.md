# 📊 Análisis de Dotación y Eficiencia Comercial – Marzo 2026

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar la operación de Falabella Retail Perú durante marzo de 2026, enfocándose en la gestión de personal, rotación y eficiencia del gasto en remuneraciones en relación con las ventas.

Para ello, se desarrolló un proceso de limpieza y transformación de datos (ETL) en Python, seguido de la construcción de un dashboard en Power BI que permite visualizar los principales indicadores del negocio.

---

## 🧩 Fuentes de Datos

Se trabajó con las siguientes bases:

- **Dotación de colaboradores**
- **Diccionario de homologación (departamento → gerencia)**
- **Remuneración vs ventas por tienda y vertical**

---

## ⚙️ Proceso ETL (Python)

El proceso ETL fue desarrollado en un notebook (`.ipynb`) e incluyó:

### 🔹 Limpieza de datos
- Estandarización de DNI a 8 dígitos
- Eliminación de duplicados
- Corrección de nombres inconsistentes (tiendas, verticales, etc.)
- Normalización de texto

### 🔹 Transformación
- Creación de variables clave:
  - `Activo_marzo`
  - `Cese_marzo`
- Homologación de departamentos a gerencias

### 🔹 Integración
- Generación de bases finales limpias:
  - `dotacion.txt`
  - `remuneracion.txt`

---

## 📊 Dashboard en Power BI

Se construyó un dashboard interactivo dividido en dos vistas principales:

### 🟣 Gestión de Personal
- Dotación total
- Ceses del mes
- Rotación
- Análisis por tipo de salida, tienda, vertical y gerencia

### 💰 Eficiencia Comercial
- Remuneración total
- Ventas totales
- Ratio de eficiencia (Remuneración / Venta)
- Comparativo por tienda y vertical

---

## 📈 Principales Insights

- Las verticales con mayor rotación están asociadas a contratos temporales, como Útiles Escolares.
- Tecnología presenta altos niveles de venta, pero también un mayor gasto en remuneraciones.
- No todas las tiendas con mayores ventas son las más eficientes en términos de gasto en personal.

---

## 🛠️ Tecnologías utilizadas

- Python (pandas, limpieza de datos)
- Power BI (visualización y análisis)
- Jupyter Notebook



