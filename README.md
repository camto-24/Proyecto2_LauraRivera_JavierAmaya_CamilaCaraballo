# PROYECTO 2: Visualización y Construcción de Narrativas Basadas en Datos

## 1. Objetivo y Alcance del Estudio

El presente proyecto tiene como finalidad consolidar las competencias adquiridas en el curso, integrando tres pilares fundamentales del análisis de datos:
1.  **Análisis Exploratorio de Datos (EDA)** y depuración.
2.  **Modelación de Datos** para la estructura relacional.
3.  **Comunicación Visual y Narrativa** para la divulgación de hallazgos.

El proceso completo abarca desde la adquisición y el saneamiento de las fuentes de datos hasta el diseño de una **visualización interactiva** que facilita la exploración por parte del usuario y soporta la argumentación de las conclusiones obtenidas.

---

## 2. Pregunta de Investigación y Contexto Temático

La investigación aborda la relación entre el consumo de bebidas azucaradas y la prevalencia de enfermedades crónicas a nivel nacional. Los datos fuente provienen de la Encuesta de Calidad de Vida. Este estudio posee un enfoque netamente descriptivo y busca generar evidencia que complemente el análisis y la discusión en torno a la política pública del Impuesto saludable implementada por el Gobierno Nacional.

---

## 3. Estructura del Repositorio y Componentes

El repositorio se organiza bajo la siguiente estructura, reflejando el flujo de trabajo analítico:

| Archivo / Carpeta | Tipo de Componente | Descripción Funcional |
| :--- | :--- | :--- |
| `Trabajo final.RMD` | **Código Fuente** (R Markdown) | Contiene la totalidad del código R utilizado para la limpieza, el procesamiento, el análisis exploratorio (EDA) y la generación de los resultados intermedios. |
| `[nombre_archivo].pbix` | **Modelo de Datos y Visualización** (Power BI) | Archivo principal que alberga el Modelo de Datos relacional construido. |
| `data/` | **Datos Intermedios** | Almacena los conjuntos de datos finales y depurados(exportados desde el RMD). Estos archivos están preparados para ser importados directamente a la herramienta de modelación. |
| `Graficos - tablas/` | **Evidencia Descriptiva** | Contiene los archivos de gráficos y tablas estáticas generados durante la fase del Análisis Exploratorio de Datos (EDA). |
| `Documentos/` | **Poryecto 2** | Contiene el informe final en formato Word, el cual incluye la revisión bibliográfica, la metodología, la discusión de resultados y las conclusiones del estudio. |

---

## 4. Metodología de Replicación y Acceso a los Resultados

Para la correcta replicación del análisis y la exploración de los productos finales, se requiere el siguiente entorno de software:

### 4.1. Replicación del Análisis Descriptivo (Código)

1.  Entorno de programación *R* y el IDE *RStudio*.
2.  Abrir el archivo *Trabajo final.RMD* en RStudio. 

### 4.2. Exploración del Modelo y Visualización

1.  Software - Microsoft Power BI Desktop
2.  Abrir el archivo *[Modelo de datos BI].pbix*. Esto permitirá examinar el diseño del Modelo de Datos.
