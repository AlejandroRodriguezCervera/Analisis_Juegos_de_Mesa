# 🎲 Análisis de Juegos de Mesa con MongoDB y PyMongo

## 📋 Descripción
Análisis exploratorio del dataset de juegos de mesa de BoardGameGeek (BGG) utilizando MongoDB y PyMongo como herramientas principales. El objetivo es estudiar la evolución del sector y obtener insights sobre tendencias actuales y futuras de la afición.

## 📁 Estructura del proyecto
```
├── data/
│   └── bgg_dataset.json
├── notebook/
│   └── analisis_juegos_mesa.ipynb
└── README.md
```
## 🛠️ Tecnologías utilizadas
- Python 3.x
- MongoDB
- PyMongo
- Pandas
- Matplotlib
- Jupyter Notebook

## 📊 Análisis realizados
- Distribución de juegos por año de publicación
- Relación entre cantidad y calidad en el ranking global
- Rankings cruzados por categoría
- Evolución del rating promedio por año
- Umbrales de valoración de la comunidad
- Comparativa de ratings por número de categorías

## ⚠️ Limitaciones
MongoDB no dispone de funciones estadísticas avanzadas para realizar predicciones o correlaciones de forma nativa. Los análisis realizados permiten identificar tendencias claras que, combinadas con herramientas externas como `scipy` o `sklearn`, podrían dar lugar a modelos predictivos más precisos.

## 🚀 Cómo ejecutar el proyecto
1. Clona el repositorio
2. Instala las dependencias
```bash
pip install pymongo pandas matplotlib jupyter
```
3. Asegúrate de tener MongoDB en ejecución
4. Abre el notebook
```bash
jupyter notebook notebook/analisis_juegos_mesa.ipynb
```

## 📦 Dataset
Dataset obtenido de [BoardGameGeek](https://www.boardgamegeek.com/), que incluye los mejores juegos según la comunidad con información sobre año de publicación, ratings y rankings por categoría.
