# Salario de profesionales a nivel global
## Proyecto de Visualización y Storytelling

Este sitio presenta el desarrollo completo de un proyecto analítico orientado a identificar y conocer los diferentes salarios entre profesionales a nivel mundial, integrando procesos de limpieza, transformación y visualización de datos.

---

## Dashboard interactivo

<iframe width="100%" height="650"
src="https://lookerstudio.google.com/embed/reporting/af5e0a50-936f-486f-9fea-438c774adb38/page/hatnF"
frameborder="0"
style="border:0"
allowfullscreen>
</iframe>

---

## Objetivo del análisis

Analizar cómo varían los salarios según la industria, la ubicación geográfica y el género, permitiendo identificar patrones relevantes dentro del mercado laboral global.

---

## Insight principal

Los datos utilizados en este proyecto provienen del “Ask A Manager Salary Survey 2021”.  
Se realizó un proceso de limpieza y estandarización de variables como país, ciudad y moneda.

Los salarios fueron convertidos a pesos colombianos (COP) utilizando la Tasa Representativa del Mercado (TRM) del día 08-02-2026, con el fin de permitir comparaciones homogéneas entre países.

Posteriormente se construyeron variables derivadas como:

- Salario anual en COP  
- Compensaciones en COP  
- Ingreso total anual  
- Promedios por industria  
- Distribución geográfica  

El modelado fue realizado en Python y la visualización desarrollada en Looker Studio.

---
# Documentación del proyecto

A continuación se presentan los archivos que soportan el desarrollo analítico:

### Dataset utilizado
- [Ask A Manager Salary Survey 2021](Ask%20A%20Manager%20Salary%20Survey%202021.xlsx)

### Base de datos modelada
- [BD_Modelada_Dashboard_TRM](BD_Modelada_Dashboard_TRM.xlsx)

### Diccionario de variables
- [Descripción de Variables](Descripcion%20de%20Variables.docx)

### Notebook de modelado
- [Modelado Storytelling](ModeladoST.ipynb)

### Metodología paso a paso
- [Paso a paso del modelado](Paso%20a%20paso%20modelado.docx)

### Dashboard final
- [Sueldos de profesionales](Sueldos_de_profesionales.pdf)

## Tecnologías utilizadas

- Python  
- Pandas  
- Looker Studio  
- GitHub Pages  

---

## Autor  
Victor Bonilla  
Maestría en Inteligencia Analítica de Datos - Visualizacion y Storytelling
