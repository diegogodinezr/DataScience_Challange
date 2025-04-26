## 🚀 ¡Bienvenido al Análisis de Datos de Alura Store!

Hola 👋, aquí encontrarás todo lo necesario para entender cómo vimos las ventas de las 4 tiendas de Alura Store y recomendamos cuál sería la mejor para vender.

## 🗂️ Estructura del proyecto

```
AluraStore/
├── tienda_1.csv
├── tienda_2.csv
├── tienda_3.csv
├── tienda_4.csv
├── Informe de Análisis de AluraStore.docx
├── requirements.txt
├── AluraStoreLatam.ipynb
└── README.md
```
---

🛠️ Cómo empezar

Clona este repositorio:

```
git clone https://github.com/kevinbonillamontesdeoca/AluraStore.git
cd AluraStore
```

Crea un entorno virtual (opcional, pero recomendado):

```
python3 -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate    # Windows
```

Instala las dependencias:

```
pip install -r requirements.txt
```

El archivo requirements.txt incluye:

```
pandas
matplotlib
```

---

## 🚀 ¿Cómo usarlo?

1. Abre **Google Colab** y carga `AluraStoreLatam.ipynb`.
2. Ejecuta las celdas en orden:
   - **Carga de datos** desde GitHub.
   - **Limpieza y exploración** para ver nulos o irregularidades.
   - **Cálculo de métricas**: ingresos, ventas por categoría, calificaciones, top/bottom productos, costo de envío.
   - **Visualizaciones**: gráficos de barras, pastel, boxplot, línea y mapas.
3. Observa al final los **gráficos resumen** para identificar la tienda con menor rendimiento.

---

## 🔍 ¿Qué analizamos?

1. **Ingresos Totales**: ¿Cuál tienda factura más? 💰
2. **Ventas por Categoría**: ¿Qué productos dominan? 🛋️📱🧸
3. **Satisfacción del Cliente**: ¿Cómo califican las tiendas? ⭐
4. **Top/Menos Productos**: Lo que más y menos se vende. 🏆👇
5. **Costo de Envío Promedio**: ¿Quién cobra más por el envío? 🚚
6. **Análisis Geográfico (Opcional)**: Mapa de dispersión y heatmap para ver dónde compran más. 🗺️
7. **Resumen Gráfico**: Tres gráficos clave para entenderlo todo de un vistazo.

---
