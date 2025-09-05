# 🖥️ Dashboard de Reservas de Hotel – Hotel Bookings

Este proyecto presenta un **dashboard interactivo desarrollado en Power BI**, basado en el archivo `hotel_bookings.csv`.  
El objetivo es analizar el comportamiento de las **reservas hoteleras**, identificando patrones de estacionalidad, cancelaciones, duración de estadías y variaciones de tarifa (ADR), para **facilitar la toma de decisiones** en gestión y estrategia comercial.

Recomiendo leer primero el documento del proyecto 2 para mayor comprensión de la base de datos que se utilizará : [README de Data Power Bi](Data%20Power%20Bi/README.md)


---

## 🎯 Objetivos del proyecto
- Visualizar métricas claves.
- Analizar el comportamiento. 
- Detectar **tendencias** y **variaciones**.  
- Entregar una vista ejecutiva que apoye **decisiones operativas y comerciales** (capacidad, pricing, marketing).

---

## 📊 Vistas principales del dashboard – Hotel Bookings

### 📌 Portada y KPIs
Tarjetas con indicadores clave:
- **Total de reservas**
- **% de cancelaciones**
- **Promedio de noches por reserva**
- **Ingreso estimado total** (ADR × noches)
- **Nacionalidad más frecuente**

![Dashboard de Cancelaciones Hoteleras](Imagenes/KPI_Importantes.png)

> Estos KPIs permiten dimensionar el volumen, el riesgo (cancelaciones), la duración típica de estadías y el potencial de ingresos.

### ⚙️ Importancia de los filtros y segmentadores
Los **filtros** permiten explorar los datos de forma interactiva y responder preguntas específicas:
- **Tipo de hotel** (City vs Resort): diferencias operativas y comerciales.
- **Estado de reserva** (efectiva/cancelada): impacto en ocupación e ingresos esperados.

**Beneficios**: facilitan interpretar grandes volúmenes, encontrar patrones en distintos contextos y adaptar el dashboard a distintas audiencias y decisiones.

![Dashboard de Cancelaciones Hoteleras](Imagenes/Filtros.png)

### 🔢 Reservas por hotel (categorías comparables)
**Gráfico de barras**  
Muestra el **estado y cantidad de reservas** por hotel.  

![Dashboard de Cancelaciones Hoteleras](Imagenes/ComparacionHoteles.png)

### 📈 Estado de la Reserva según Dias de anticipación.
**Gráfico de líneas**  
Muestra la **tendencia del estado de las reservas** según la **cantidad de dias de anticipación** con la cual se realizo esta. 
Ayuda a detectar un comportamiento.

![Dashboard de Cancelaciones Hoteleras](Imagenes/leadtime.png)

---

## 📂 Archivos del repositorio
Archivo principal de Power BI.  
- `/data/hotel_bookings.csv` – Dataset utilizado.  
- `/images/` – Capturas del dashboard.  
- `/docs/medidas_dax.md` – Medidas DAX utilizadas.  
- `/docs/diccionario_datos.md` – Descripción de columnas.

---

## 🚀 Cómo usarlo
1. Descarga el archivo `.pbix` desde `/pbix/`.  
2. Ábrelo en **Power BI Desktop**.  
3. Explora las páginas y **filtros interactivos** (Año, Mes, Tipo de hotel, Estado de reserva).

---

## 🧠 Hallazgos clave (ejemplos a validar con tu data)
- La **cancelacion** tiende a aumentar mientras mas dias de anticipación tenga la reserva.  
- **City Hotel** vs **Resort Hotel** muestran patrones distintos de **cancelación**, donde la segunda tiende a tener un menor índice.
- Ciertos **mercados/nacionalidades** presentan mayor propensión a cancelación o estadías más largas.

---

## 📌 Tecnologías utilizadas
- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
