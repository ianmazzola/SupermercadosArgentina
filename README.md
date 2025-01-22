# **Análisis de Ventas de Supermercados en Argentina**

## **Descripción del Proyecto**
Este proyecto explora un dataset de ventas mensuales de supermercados en Argentina, con datos que abarcan desde 2017 hasta el mes de Agosto de 2024. Se analizan tendencias generales, impacto de la pandemia, distribución por categorías de productos y preferencias de medios de pago, utilizando Power BI.

El objetivo es presentar insights clave sobre el comportamiento de las ventas, destacar patrones relevantes y comunicar hallazgos de manera clara y visual a través de dashboards interactivos.

---

## **Contenido**
1. [Contexto del Proyecto](#contexto-del-proyecto)
2. [Objetivos](#objetivos)
3. [Herramientas Utilizadas](#herramientas-utilizadas)
4. [Estructura del Proyecto](#estructura-del-proyecto)
5. [Análisis Realizado e Insights](#análisis-realizado-e-insights)

---

## **Contexto del Proyecto**
Este proyecto utiliza datos abiertos del sitio [Datos Argentina](https://datos.gob.ar/) para analizar las ventas totales de supermercados a valores corrientes y constantes, desglosadas por:
- Grupos de productos 
- Canales de venta 
- Medios de pago 

---

## **Objetivos**
1. **General**: Extraer insights relevantes sobre las ventas de supermercados en Argentina.
2. **Específicos**:
   - Analizar la evolución de las ventas totales (corrientes y constantes).
   - Identificar categorías de productos con mayor impacto.
   - Evaluar el impacto de la pandemia en las ventas y preferencias de los consumidores.
   - Comunicar hallazgos mediante dashboards interactivos.

---

## **Herramientas Utilizadas**
- **Power BI**: Visualización de datos y creación de dashboards.
- **DAX**: Creación de métricas y cálculos en Power BI.

---

## **Estructura del Proyecto**
1. **Limpieza y Exploración de Datos**:
   - Durante el desarrollo del proyecto, se identificó que algunas columnas del dataset contenían valores en notación científica debido a su magnitud. Esto afectaba la legibilidad de los gráficos y la comprensión de los insights. Para solucionar este problema, se crearon métricas personalizadas en DAX en Power BI. Estas métricas permitieron redondear y formatear los datos de manera clara y comprensible para el usuario final.
2. **Dashboards**:
   - **Resumen General**: Ventas totales y desglosadas desde 2017 a Agosto de 2024.
   - **Impacto de la Pandemia**: Detalle de ventas durante el año 2020.
   - **Medios de Pago**: Evolución de las preferencias de pago de los consumidores.
   - **Análisis por Categorías**: Agrupación por consumo esencial, ocasional u otros.

---

## **Análisis Realizado e Insights**
1. **Resumen General**:
   - En el año **2023**, los productos de **electrónica** fueron los mas vendidos. Este rubro creció aproximadamente un **108,62%** respecto al año **2022**. Según el informe del cuarto trimestre del INDEC, los pequeños electrodomésticos fueron los artículos con mayor variación porcentual respecto al 2022.
   - El grupo de artículos de **indumentaria y calzado** llegó a ser el **segundo más vendido** del año **2021**, posicionandose por delante de productos de consumo alimenticio tales como los lácteos, carnes, frutas y verduras. Esto puede haber ocurrido debido a que el estilo de vida de trabajo remoto y estudios virtuales creo la necesidad de usar ropa cómoda para cumplir con las obligaciones desde el hogar.
   - El consumo de los argentinos suele **caer drásticamente** en el mes de **Junio** comparado con el mes anterior. En los únicos años donde no se registra esta caída son en **2018**, debido a un mal mes de Mayo de dicho año, en **2020** hubo una caída del **0,46%** y en **2021** vemos una subida del **5,14%**
   ![Dashboard 1](panel_general.png)
3. **Impacto de la Pandemia**:
   ![Dashboard 2](pandemia.png)
4. **Medios de Pago**:
   ![Dashboard 3](medios_de_pago.png)
5. **Categorías de Productos**:
   ![Dashboard 4](productos.png)
