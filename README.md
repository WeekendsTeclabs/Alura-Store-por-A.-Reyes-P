# Alura-Store-por-A.-Reyes-P
Challenge de Alura Latam generado por mi con la resolución al analisis de los datos de 4 tiendas y en la revisión de los antecedentes de búsqueda de tiendas mas ineficientes en al cual solo 1 contaría para ser cerrada.

# 🛒 Análisis de Eficiencia para Tiendas - Proyecto Alura Store

## 📌 Propósito del proyecto

Este proyecto tiene como objetivo ayudar al Sr. João a tomar una decisión estratégica respecto al cierre de una de las tiendas de la cadena **Alura Store** para iniciar un nuevo emprendimiento.  
A través del análisis de datos reales de ventas, calificaciones de clientes, envíos y productos, se determina cuál tienda es la menos eficiente.  

Se utilizaron herramientas de análisis de datos como **Python**, **Pandas**, **Matplotlib**, **Seaborn** y **Scikit-Learn** para realizar una evaluación integral de desempeño.

---

## 🗂️ Estructura del proyecto

```

📁 alura-store-analysis/
├── Alura\_Store\_Analisis.ipynb   # Notebook principal con el análisis completo
├── README.md                    # Documentación del proyecto (este archivo)
├── requirements.txt             # Dependencias para ejecutar el proyecto localmente
├── data/
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
└── outputs/                     # (Opcional) Imágenes o exportaciones de resultados

````

---

## 📈 Ejemplos de análisis realizados

### 🔹 Ingresos por Tienda y Categoría
Se identificó qué tiendas y categorías generan mayores ingresos, visualizados mediante tablas y heatmaps.

### 🔹 Calificación Promedio por Tienda
Se evaluó la satisfacción de clientes mediante calificaciones promedio, visualizadas con gráficos de barras.

### 🔹 Productos Más y Menos Vendidos
Análisis de productos top más vendidos y menos vendidos, por tienda, utilizando visualizaciones con `seaborn`.

### 🔹 Costo Promedio de Envío
Se calculó el envío promedio por tienda, comparando eficiencia logística.

### 🔹 Recomendación Final
Se creó un **índice de eficiencia** considerando ingresos, calificación y envío.  
La tienda más ineficiente fue identificada, excluyendo la tienda con mayor volumen de ventas.

---

## 📋 Recomendación Final

> Después de un análisis exhaustivo de los indicadores clave, se concluye que una de las tiendas presenta bajo rendimiento en ingresos, calificaciones de cliente y eficiencia en envíos.  
>  
> Considerando que la tienda con más ventas debe mantenerse, se excluyó del análisis de cierre.  
>  
> La tienda con **menor score de eficiencia relativa** fue identificada como la **más ineficiente**, siendo la principal candidata para cierre.
> Esta decisión está basada en datos cuantificables y comparables entre todas las tiendas.

---

## ⚙️ Instrucciones para ejecutar el notebook

### 🧪 Opción 1: Ejecutar en Google Colab (recomendado)
1. Abre el archivo `Alura_Store_Analisis.ipynb` en [Google Colab](https://colab.research.google.com).
2. Sube los archivos `.csv` en la carpeta `data/`.
3. Ejecuta cada celda siguiendo el orden lógico del análisis.

### 💻 Opción 2: Ejecutar localmente
1. Instala Python 3.11+ y usa un entorno virtual (opcional).
2. Instala las dependencias con:

```bash
pip install -r requirements.txt
````

3. Ejecuta el notebook con Jupyter Notebook o VSCode.

---

## 🧾 Requisitos (`requirements.txt`)

```txt
pandas==2.2.2
matplotlib==3.8.4
seaborn==0.13.2
scikit-learn==1.4.2
```

---

## 📬 Contacto

Este proyecto fue desarrollado como parte de un desafío de análisis de datos.
Para sugerencias, mejoras o contacto profesional:

📧 Weekends Nomads.

---

## ✅ Licencia

Este proyecto se publica bajo la Licencia MIT.
Puedes usarlo y modificarlo libremente con atribución correspondiente.



