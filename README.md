# Alura-Store  
Análisis Exploratorio y Visualización de Datos de Ventas para Alura Store  
**Autor:** Kayychuu  
**Repositorio:** Kayychuu/Alura-Store

---

## Tabla de Contenidos

- Descripción del Proyecto  
- Motivación  
- Estructura del Repositorio  
- Fuentes de Datos  
- Tecnologías y Dependencias  
- Instalación y Ejecución  
- Metodología de Análisis  
- Principales Resultados y Visualizaciones  
- Contribuciones  
- Licencia

---

## Descripción del Proyecto

Alura-Store es un proyecto de análisis de datos enfocado en el procesamiento, exploración y visualización de información de ventas de una tienda minorista. Utilizando Python y Jupyter Notebooks, se extraen insights clave sobre productos, categorías, desempeño de vendedores, métodos de pago y distribución geográfica de las ventas.

---

## Motivación

El desafío propuesto por Alura Latam busca que el participante aplique técnicas de análisis exploratorio de datos (EDA), visualización y storytelling sobre un dataset realista, desarrollando habilidades prácticas para la toma de decisiones basadas en datos en el entorno de retail.

---

## Estructura del Repositorio

Alura-Store/
├── DesafioAluraStore.ipynb # Notebook principal de análisis
└── README.md # Este archivo


Los datos se descargan dinámicamente desde fuentes públicas, por lo que no se incluyen archivos CSV en el repositorio.

---

## Fuentes de Datos

Se utilizan cuatro datasets en formato CSV, provistos por Alura Latam, que contienen información histórica de ventas:

- tienda_1.csv  
- tienda_2.csv  
- tienda_3.csv  
- tienda_4.csv  

Cada archivo contiene columnas como:

- Producto, Categoría del Producto, Precio, Costo de Envío  
- Fecha de Compra, Vendedor, Lugar de Compra  
- Calificación, Método de Pago, Cantidad de Cuotas  
- Latitud y Longitud

Los archivos se cargan directamente desde enlaces públicos en GitHub.

---

## Tecnologías y Dependencias

El análisis fue desarrollado en Python 3 usando los siguientes paquetes:

- Jupyter Notebook  
- pandas (procesamiento de datos)  
- matplotlib (visualización)  
- seaborn (visualización avanzada)  

Para instalar las dependencias, ejecutar:

```
pip install pandas matplotlib seaborn notebook
```

---

## Instalación y Ejecución

Clonar el repositorio:

```
git clone https://github.com/Kayychuu/Alura-Store.git
cd Alura-Store
```

Instalar dependencias (si aún no se hizo):

```
pip install pandas matplotlib seaborn notebook
```

Abrir el notebook (localmente o en Google Colab):

```
jupyter notebook DesafioAluraStore.ipynb
```

Ejecutar las celdas siguiendo el flujo del notebook para reproducir el análisis completo.

---

## Metodología de Análisis

El flujo principal del análisis es:

- Carga y concatenación de datos: se importan y unifican los archivos fuente.  
- Análisis exploratorio de datos (EDA): revisión de estructura y tipos, estadísticas descriptivas, detección y tratamiento de valores atípicos y nulos.  
- Visualización: distribución de precios, costos de envío y calificaciones; comparativas por categoría y lugar de compra; análisis de métodos de pago y cuotas; mapeo geográfico de ventas.  
- Insights y conclusiones: identificación de productos más y menos vendidos, vendedores con mejor desempeño, preferencias de pago por región y patrones de calificación según categoría y método de compra.

---

## Principales Resultados y Visualizaciones

Algunos de los hallazgos clave incluyen:

- Las categorías Electrónica y Muebles concentran la mayor parte de las ventas.  
- El método de pago más utilizado es la Tarjeta de crédito, especialmente en compras de mayor valor.  
- Se detectan diferencias notables en la calificación promedio según ciudad y vendedor.  
- Las ventas están distribuidas principalmente en grandes centros urbanos, como Bogotá, Medellín y Cali.

Ejemplo de visualización generada: Pairplot mostrando las relaciones entre precio, costo de envío y calificación.

---

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el análisis, agregar nuevas visualizaciones o sugerir cambios, abre un issue o crea un pull request.

---

## Licencia

Este proyecto se distribuye bajo la licencia MIT.  
Los datos utilizados son públicos y provistos solo con fines educativos.
