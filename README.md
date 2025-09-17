#Evaluación Final Módulo 3 ADALAB

📌 Descripción

Este proyecto consiste en el análisis de datos de clientes pertenecientes a un programa de memebresías/lealtad de una aerolínea. Se han utilizado dos conjuntos de datos:

Customer Flight Analysis.csv → Información sobre la actividad de vuelo de los clientes (vuelos, distancia, puntos, redenciones, etc.).

Customer Loyalty History.csv → Información detallada de los clientes (país, educación, ingresos, tipo de tarjeta, CLV, etc.).

El análisis se ha desarrollado en Python, utilizando principalmente las librerías pandas, matplotlib y seaborn.

🎯 Objetivos del análisis
🔹 Exploración y limpieza

Carga de los datasets con pandas.

Revisión de valores nulos y duplicados.

Conversión de tipos de datos.

Unión de ambos datasets a través de la clave Loyalty Number.

🔹 Análisis y visualización

Se realizaron distintos análisis con apoyo de matplotlib y seaborn:

Distribución de clientes por país y tipo de tarjeta de lealtad.

Comparación entre puntos acumulados y puntos redimidos.

Relación entre salario y educación.

Evolución de vuelos reservados por mes y año.

Clientes con mayor cantidad de vuelos y kilómetros recorridos.

Identificación de patrones en las cancelaciones de membresía.

Análisis de la proporción de cancelaciones según tarjeta y nivel educativo.

🔹 Conclusiones principales

Los clientes con tarjetas de nivel superior tienden a acumular y redimir más puntos.

Existe correlación positiva entre ingresos y CLV.

Determinados perfiles (país + educación + tipo de tarjeta) presentan mayor riesgo de cancelar la membresía.

El análisis temporal muestra picos en la actividad de vuelos en determinados periodos.

🛠️ Tecnologías y Librerías Utilizadas

Lenguaje: Python 3.12

Librerías principales:

pandas → manipulación y limpieza de datos

matplotlib → visualización básica

seaborn → visualización avanzada y estadísticas descriptivas

numpy → operaciones numéricas


📊 Resultados

Se identificaron patrones en la frecuencia de vuelos y uso de puntos.

Se observó mayor salario cuanta mayor es la formación.

Tipo de tarjeta Star es la que más clientes tiene

Hay más mujeres clientes


✍️ Autora

Proyecto realizado por Marta Sanz como parte de la evaluación final del módulo 3 de Data Analyst de ADALAB (2025).
