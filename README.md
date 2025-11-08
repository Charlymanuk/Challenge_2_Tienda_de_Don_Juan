# 🏪 Alura Store - Análisis de Rendimiento de Tiendas

## 📊 Propósito del proyecto

Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas pertenecientes a **Alura Store**, con el fin de determinar **cuál de ellas debería ponerse en venta** según su desempeño general.  
El análisis se basó en métricas clave como ingresos totales, calificaciones promedio de los clientes, categorías de productos, productos más y menos vendidos y costes de envío promedio.

El trabajo forma parte del desafío propuesto para aplicar técnicas de análisis de datos, visualización y toma de decisiones empresariales basadas en evidencia.

---

## 🧱 Estructura del proyecto

El repositorio se organiza de la siguiente manera:

```
📂 Alura_Store_Analisis/
│
├── 📘 Alura_Store_Analisis.ipynb   # Notebook principal (Google Colab o Jupyter)
├── 📄 informe_final_tiendas.pdf    # Informe final con la conclusión del análisis
├── 📊 datasets/
│   ├── ventas.csv                 # Datos de ventas y transacciones
│   ├── clientes.csv               # Datos de clientes (si aplica)
│   └── productos.csv              # Información de productos y categorías
│
├── 📈 imagenes/
│   ├── ingresos_por_tienda.png
│   ├── calificaciones_por_tienda.png
│   ├── productos_mas_vendidos.png
│   └── costos_envio_promedio.png
│
└── README.md                      # Este archivo
```

---

## 📈 Gráficos y *insights* destacados

Durante el análisis se generaron diversos gráficos para comprender el rendimiento de cada tienda:

### 🔹 Ingresos totales por tienda
- Tienda 1: **1,150,880,400.0**  
- Tienda 2: **1,116,343,500.0**  
- Tienda 3: **1,098,019,600.0**  
- Tienda 4: **1,038,375,700.0**  

📊 *Insight:* La Tienda 4 tiene los ingresos más bajos, lo que indica menor rentabilidad.

---

### 🔹 Calificación promedio de clientes
| Tienda | Calificación |
|--------|--------------|
| Tienda 1 | 3.98 |
| Tienda 2 | 4.04 |
| Tienda 3 | **4.05** |
| Tienda 4 | 4.00 |

📊 *Insight:* La Tienda 3 obtiene la mayor satisfacción del cliente, mientras que la Tienda 1 presenta la más baja.

---

### 🔹 Coste de envío promedio
| Tienda | Envío promedio (pesos) |
|--------|-------------------------|
| Tienda 1 | 26,018.61 |
| Tienda 2 | 25,216.24 |
| Tienda 3 | 24,805.68 |
| Tienda 4 | **23,459.46** |

📊 *Insight:* Aunque la Tienda 4 tiene el envío más económico, sus ventas son significativamente menores.

---

### 🔹 Categoría dominante y productos
- Todas las tiendas destacan en la categoría **Muebles**, que representa el mayor volumen de ventas.  
- Productos destacados:
  - Tienda 1: Armario, Microondas, TV LED UHD 4K  
  - Tienda 2: Libro “Iniciando en programación”  
  - Tienda 3: Kit de bancas  
  - Tienda 4: Cama box  

📊 *Insight:* La Tienda 4 depende de pocos productos con rotación limitada, lo que reduce su resiliencia comercial.

---

## 🧠 Conclusión principal

Tras integrar todos los indicadores:

➡️ **La Tienda 4 debe ponerse en venta**, ya que:
- Tiene los **menores ingresos totales (1,038 millones de pesos)**.  
- Muestra **baja diversidad de productos**.  
- Su **calificación media (4.0)** no compensa la baja rentabilidad.  
- Su potencial de crecimiento es limitado frente a las demás tiendas.

---

## ⚙️ Instrucciones para ejecutar el notebook

### 1. Clonar el repositorio

```bash
git clone https://github.com/tuusuario/Alura_Store_Analisis.git
cd Alura_Store_Analisis
```

### 2. Instalar dependencias

Si estás trabajando en un entorno local:
```bash
pip install pandas matplotlib seaborn numpy
```

En Google Colab no es necesario instalar manualmente, solo subir los datasets a tu entorno.

### 3. Ejecutar el notebook

Abre el archivo `Alura_Store_Analisis.ipynb` en Jupyter o Colab y ejecuta las celdas en orden.  
El notebook generará automáticamente los gráficos y métricas utilizadas en el informe.

### 4. Revisar resultados

Al final del notebook se muestra la síntesis con:
- Ranking de tiendas según desempeño global.
- Recomendación de cuál vender.
- Visualizaciones interactivas de apoyo.

---

## 🧾 Créditos

Proyecto desarrollado como parte del desafío **Alura Store Data Analysis**, aplicando:
- Python (pandas, matplotlib, seaborn)
- Google Colab / Jupyter Notebook
- Análisis de datos empresariales y visualización

Autor: **Carlos Caminos**  
Fecha: **Noviembre 2025**

---

## 🪄 Insight final

> “Los datos no solo cuentan lo que pasó, sino que orientan las decisiones sobre lo que conviene hacer.”  
> En este caso, los números muestran con claridad que vender la **Tienda 4** es la decisión más estratégica para optimizar los recursos y fortalecer el negocio.
