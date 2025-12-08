# 💳 MiPyME Conecta --- Asignación Inteligente de Crédito

Plataforma web desarrollada en **Streamlit** para la **asignación
eficiente de crédito a MiPyMEs**, integrando:

-   🌱 Economía Circular\
-   📍 Polos de Desarrollo\
-   👩 Liderazgo Femenino\
-   🧠 Inteligencia Artificial (Random Forest)

Proyecto optimizado para **pitch de hackatón**, con enfoque en
**velocidad, visualización y explicabilidad**.

------------------------------------------------------------------------

## 🚀 Funcionalidades Principales

✅ Login de usuarios con roles (`admin`, `pitch`, `invitado`)\
✅ Generación de datos sintéticos representativos de MiPyMEs\
✅ Entrenamiento automático con **Random Forest**\
✅ Evaluación de crédito en tiempo real con **probabilidad estimada**\
✅ Visualización del **Índice de Economía Circular**\
✅ Análisis de **Polos de Desarrollo por estado**\
✅ Simulador de **impacto de política pública** (meta +3.5%)\
✅ Ranking de **importancia de variables del modelo**

------------------------------------------------------------------------

## 🧠 Modelo de Inteligencia Artificial

-   Algoritmo: `RandomForestClassifier`
-   Número de árboles: `120`
-   Profundidad máxima: `8`
-   Paralelización: `n_jobs = -1`
-   Métrica mostrada: **accuracy**
-   Variable objetivo: `credito` (0 = no aprobado, 1 = aprobado)

------------------------------------------------------------------------

## 📊 Variables del Modelo

  Variable              Descripción
  --------------------- -------------------------
  `ventas`              Ventas anuales
  `empleados`           Número de empleados
  `recicla_pct`         Economía circular
  `digital_score`       Digitalización
  `factura_e`           Facturación electrónica
  `ventas_online_pct`   Ventas online
  `lider_mujer`         Liderazgo femenino

------------------------------------------------------------------------

## ▶️ Ejecución Local

``` bash
streamlit run app.py
```

------------------------------------------------------------------------

## 🔐 Usuarios

  Usuario    Clave
  ---------- ----------
  admin      1234
  pitch      demo2025
  invitado   credito

------------------------------------------------------------------------

## 🖥️ Requisitos

    streamlit
    pandas
    numpy
    scikit-learn
    plotly

------------------------------------------------------------------------

## ⚠️ Nota

Los datos son **simulados** y no representan información real.
