# 📊 Portafolio de Ciencia de Datos - Juan Pablo Tovar

Bienvenido a mi portafolio como analista de datos. Aquí encontrarás proyectos que demuestran mis habilidades en análisis, visualización y comunicación de datos con las herramientas de software Tableau y Power BI.

## 🧠 Sobre mí

Soy estudiante, atualmente cursando la Licenciatura en Ingeniería en Software y Redes. Me apasiona aplicar la tecnología a problemas reales, y siempre en busqueda de la alternativa más adecuada para los desafíos encomendados. 

# 🏘️ Caso de Estudio: Análisis de Mercado de Vivienda con Tableau

En este proyecto aplico técnicas de análisis de datos y visualización estratégica para apoyar a los interesados en la toma de decisiones informadas sobre el precio pactado o de venta de una vivienda nueva o usada en una región específica del territorio nacional. Utilizando Tableau Public y un conjunto de datos comparables, construyo un dashboard interactivo que permite explorar precios unitarios, detectar sobreprecios y estimar valores de mercado.

## 🎯 Objetivo del Proyecto

- **Conectar** datos comparables de vivienda con Tableau Public
- **Visualizar** precios unitarios ($/m²) por zona, clase y tipo de asentamiento
- **Estimar** el precio más probable mediante líneas de tendencia 
- **Detectar** posibles sobreprecios y gaps de mercado
- **Documentar** el proceso  
---

## 🏗️ Contexto del Caso de Estudio

La vivienda objetivo cuenta con:

- **Ubicación:** Fracc. AGEUAN Los Limones, Tepic, Nayarit, C.P. 63177  
- **Niveles:** 2  
- **Cochera:** 2 espacios  
- **Recámaras:** 3  
- **Baños:** 2 completos + 1 medio baño  
- **Superficie de terreno:** 96.00 m²  
- **Superficie de construcción:** 84.00 m²  
- **Edad:** 0 (vivienda nueva)

---

## 📊 Metodología de Análisis

El proyecto sigue un proceso estructurado de análisis de datos:

### 1. Formulación de la pregunta
> ¿Cuál es la distribución de precios unitarios de viviendas en Tepic y cómo estimar el valor más probable para una propiedad nueva?

### 2. Recolección de datos
Archivo fuente: `Proyecto_Datos_Portafolio_Media.xlsx`
![Vista de la hoja de cálculo](https://raw.githubusercontent.com/uimastus/Portafolio_de_Ciencia_de_Datos/main/HojaCalculoMedia.png)

Variables clave:

- Precio pactado, superficie, ubicación, clase, conservación
- Valor unitario de mercado, valor físico de acuerdo con SHF
- Gap de precio, condición de mercado, costo de avalúo

### 3. Análisis exploratorio de datos (EDA)
- Identificación de valores faltantes
- Cálculo de métricas: media, mediana, mínimo, máximo, desviación estándar

### 4. Preparación de datos
- Limpieza y transformación
- Campo calculado: [Precio_en_venta_o_pactado] / ([Sup_construcción_CH_m2] + [Sup_construcción_ACC_m2])
- Clasificación de outliers por desviación estándar
- Filtros por clase, tipo y niveles de la vivienda.
  
### 5. Visualización en Tableau Public
- Gráfico de dispersión por clase y ubicación
- Línea de tendencia para estimación de precios
- Mapa geoespacial con precios y coordenadas
- Panel de filtros interactivos
- Visualización de imágenes de fachada (si están disponibles)

---

## 🔐 Consideraciones Éticas

Este proyecto aplica principios de ética de los datos:

- **Confidencialidad:** No se incluyen datos personales ni direcciones exactas
- **Integridad:** Se documentan todas las transformaciones y decisiones analíticas
- **Transparencia:** El dashboard y el código están disponibles públicamente

---

## 📁 Estructura del Repositorio

Proyecto_Vivienda_Tepic/
│
├── README.md
├── Datos/
│   └── Proyecto_Datos_Portafolio_Media.xlsx
├── Documentación/
│   └── Guía_Conexión_Tableau.md
├── Capturas/
│   └── dashboard_preview.png
└── Enlace_Dashboard.txt

---

## 📬 Contacto
- LinkedIn: linkedin.com/in/juan-pablo-tovar-8aa896351
- Correo: uimastus@gmail.com
