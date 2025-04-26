🚀 Análisis de Datos – Desafío Alura Store

¡Hola! 👋 Este proyecto tiene como objetivo analizar el desempeño de las 4 tiendas de la cadena Alura Store para ayudar al Sr. Juan a tomar una decisión estratégica: ¿cuál de sus tiendas debería vender para invertir en un nuevo negocio?

A través de un análisis completo de ventas, categorías, reseñas de clientes, productos y costos de envío, llegamos a una recomendación basada en datos.

⸻

🗂️ Estructura del Proyecto

AluraStore/
├── tienda_1.csv
├── tienda_2.csv
├── tienda_3.csv
├── tienda_4.csv
├── Informe de Análisis de AluraStore.docx
├── requirements.txt
├── AluraStoreLatam.ipynb
└── README.md

⸻

⚙️ Cómo Empezar

Clona este repositorio:

git clone https://github.com/diegogodinezr/DataScience_Challange
cd AluraStore

Crea un entorno virtual (opcional pero recomendado):

python3 -m venv venv
source venv/bin/activate   # En Linux/macOS
venv\Scripts\activate      # En Windows

Instala las dependencias:

pip install -r requirements.txt

Dependencias principales:
	•	pandas
	•	matplotlib

⸻

💻 ¿Cómo utilizar este proyecto?
	1.	Abre el archivo AluraStoreLatam.ipynb en Google Colab o Jupyter Notebook.
	2.	Ejecuta las celdas en orden para:
	•	Cargar y explorar los datos.
	•	Limpiar y preparar la información.
	•	Calcular métricas clave: ingresos, categorías más vendidas, evaluaciones promedio, productos top y menos vendidos, y costos de envío.
	•	Visualizar los datos con gráficos explicativos.
	3.	Consulta las conclusiones al final para identificar la tienda con menor rendimiento.

⸻

📊 Métricas Analizadas
	1.	Facturación Total: ¿Qué tienda genera más ingresos? 💰
	2.	Categorías Más Populares: ¿Qué tipo de productos se venden más en cada tienda? 🛋️📱🧸
	3.	Calificación de Clientes: ¿Qué tan satisfechos están los compradores? ⭐
	4.	Productos Más y Menos Vendidos: Análisis de productos top y con menos ventas. 🏆👇
	5.	Costo Promedio de Envío: ¿Qué tienda tiene mayores costos logísticos? 🚚
	6.	(Opcional) Análisis Geográfico: Visualización del comportamiento de compra en el mapa. 🗺️
	7.	Resumen Visual: Tres gráficos clave que resumen los hallazgos de forma clara y visual.

⸻

📌 Resultado Final

Con base en los datos y visualizaciones, se entrega una recomendación sobre cuál tienda debería vender el Sr. Juan, optimizando así su estrategia de inversión.
