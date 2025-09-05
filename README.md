# 📊 Portafolio de Ciencia de Datos - Juan Pablo Tovar

Bienvenido a mi portafolio como analista de datos. Aquí encontrarás proyectos que demuestran mis habilidades en análisis, visualización y comunicación de datos con las herramientas de software Tableau y Power BI.

## 🧠 Sobre mí
Soy estudiante del último cuatrimestre (sept-oct de 2025), cursando la Licenciatura en Ingeniería en Software y Redes, con cursos especializantes en análisis y analítica de datos. Me apasiona aplicar la tecnología a problemas reales, y siempre en busqueda de la alternativa más adecuada para los retos. 

A continuación abordare el siguiente caso de estudio desarrollado con Tableau:

# 🏘️ Análisis de Mercado de Vivienda en Tepic, Nayarit

## 🎯 Objetivo del Proyecto

Este proyecto tiene como finalidad analizar el comportamiento del mercado inmobiliario en Tepic, Nayarit, mediante el uso de Tableau Public. Se busca proporcionar al desarrollador de vivienda información estratégica para definir un precio competitivo, evitando que el producto final se sitúe fuera de los rangos del mercado.

---

## 🏗️ Contexto del Caso de Estudio

La constructora ha adquirido un terreno con las siguientes características:

- **Ubicación:** Calle Arquitectura S/N, Fracc. AGEUAN Los Limones, Tepic, Nayarit, C.P. 63177  
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
- Archivo fuente: `Proyecto_Datos_Portafolio_Media.xlsx`
- Variables: precio de venta, superficie construida, ubicación geográfica, clase de vivienda, imagen de fachada

### 3. Exploración de datos (EDA)
- Identificación de valores faltantes
- Cálculo de métricas: media, mediana, mínimo, máximo, desviación estándar

### 4. Preparación de datos
- Limpieza y transformación
- Campo calculado: `Precio unitario = Precio de venta / Superficie construida`
- Clasificación de outliers mediante fórmulas en Tableau

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








## 📬 Contacto
- LinkedIn: linkedin.com/in/juan-pablo-tovar-8aa896351
- Correo: uimastus@gmail.com
