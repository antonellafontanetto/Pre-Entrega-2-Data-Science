# 🛢️ Proyecto 4x4 YPF - Análisis de Vaca Muerta

# Pre-Entrega 2 - Data Science
# Grupo 3 - Fundación YPF / Programa Ingenias+

# Introducción 

El proyecto 4x4 de YPF plantea cuadruplicar la producción en los próximos 4 años, enfocándose en la eficiencia operativa, la generación de valor y la concentración de esfuerzos en los activos más rentables a corto plazo, como Vaca Muerta, la principal cuenca petrolera del país.

Este trabajo busca analizar el crecimiento de la producción de petróleo y gas en la cuenca neuquina desde el año 2023 en adelante, considerando exclusivamente los datos correspondientes a YPF S.A.. El análisis se basa en indicadores clave como la producción por pozo, la cantidad de pozos terminados y las etapas de fractura registradas en los últimos años.

Con este análisis, se busca aportar evidencia empírica sobre la evolución y el potencial de expansión de YPF en Vaca Muerta, en línea con los objetivos planteados en su plan estratégico 4x4.

# Objetivo

El objetivo del proyecto es analizar y predecir el crecimiento de la producción de petróleo y gas por parte de YPF S.A. en la cuenca neuquina, evaluando el impacto de diferentes variables relacionadas con la actividad extractiva y operativa.

# Integrantes - Grupo 3

Este proyecto fue desarrollado por el Grupo 3 del curso de Data Science de Fundación YPF en el marco del programa Ingenias+, que busca incorporar más mujeres al mundo de la programación.

* Cyntia Nasabun – Diplomada en Análisis de Datos e IA ([Agregar institución])

* Antonella Fontanetto – Licenciada en Economía, Universidad de Buenos Aires

# Datasets utilizados

Los datos provienen de fuentes públicas oficiales del Gobierno Nacional y de la Provincia del Neuquén:

* Producción de Pozos de Petróleo y Gas
http://datos.energia.gob.ar/dataset/produccion-de-petroleo-y-gas-por-pozo

* Perforación de Pozos de Petróleo y Gas
http://datos.energia.gob.ar/dataset/perforacion-de-pozos-de-petroleo-y-gas

* Datos de fractura de pozos de hidrocarburos
http://datos.energia.gob.ar/dataset/datos-de-fractura-de-pozos

Mapas y documentos complementarios:

* Mapa Energía Río Negro
https://mapa.rionegro.com.ar/energia

* Distribución de Fluidos – Energía Neuquén
https://www.energianeuquen.gob.ar/distribucion-de-fluidos/

* Línea estratégica YPF 4x4
https://www.rystadenergy.com/news/vaca-muerta-smashes-crude-output-record-in-3q

* Presentación IR Day 2025 – YPF
https://inversores.ypf.com/documents/presentaciones/YPF-IR-DAY-2025-presentation.pdf

* YPF – Mayo 2024 – IAméricas
https://iamericas.org/2024/05/YPF_Horacio-Marin_Mesa-Redonda_Mayo-8-presentation.pdf

* Análisis potencial exportador de Vaca Muerta – La Nación
https://www.lanacion.com.ar/el-potencial-exportador-vaca-muerta-el-planparaalcanzarlos30milmillonesdedolares

# Estructura del repositorio

La estructura del repositorio está compuesta por diferentes archivos, los cuales fueron necesarios para el desarrollo del proyecto. 
Los mismos son:
La carpeta contiene el dataset: la producción de pozos de petróleo y gas. Cada dataset contiene información global de todas las cuencas que se encuentran en las diferentes provincias a nivel nacional.

Diferentes versiones de notebook con las que el equipo fue trabajando y programando en base a los recursos y la necesidad de cumplir con el objetivo principal. 
Luego está conformada por la notebook principal donde está presentado en su primera fase el análisis exploratorio de los datos que analizamos en base a 3 dataset relacionados a la industria del Oil & Gas y el impacto de determinadas variables en la cuenca neuquina principalmente Vaca Muerta,apuntando al foco principal del proyecto 4x4 de YPF S.A.

📁 data/             → Datasets originales y procesados  
📁 notebooks/        → Jupyter Notebooks con análisis exploratorio y visualización  
📄 README.md         → Este archivo  

# Metodología

La maetodología implementada en el proyecto está relacionada con la búsqueda minuciosa de la información relevante para el desarrollo de mismo en función de las respuestas a nuestro modelo predictivo en base a las variable analizada como la producción de petróleo y gas en Vaca Muerta por parte de YPF S.A. en estos últimos años.

La metodología implementada abarcó las siguientes etapas:

* Recolección y limpieza de datos
Estandarización de nombres, conversión de tipos, detección de valores faltantes y duplicados.

* Análisis Exploratorio de Datos (EDA)
Identificación de tendencias, relaciones y evolución histórica de variables clave: producción, pozos, cuenca, empresa, etc.

* Visualización de resultados
Uso de gráficos de evolución temporal, mapas y visualizaciones interactivas para comunicar hallazgos.

# Herramientas utilizadas

Lenguaje: Python 3.10+

Librerías:

Primera entrega

* Análisis exploratorio de datos: Pandas

* Visualización: matplotlib, seaborn, plotly

* Otros: jupyter, openpyxl, google colab, GitHub


