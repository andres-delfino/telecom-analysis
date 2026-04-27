# Telecom Analysis – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.

Los datasets `plans`, `users_latam` y `usage` incluyen 4.000 registros de usuarios con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales de la empresa de telecomunicaciones ConnectaTel. Los datasets incluyen los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra), información de clientes: edad, ciudad, fecha de registro, plan contratado y el detalle de uso real: llamadas (duración) y mensajes (longitud), respectivamente. :contentReference[oaicite:2]{index=2}

## 📂 Contenido del repositorio

- `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/andres-delfino/telecom-analysis)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Realizar limpieza de datos
- Analizar comportamientos, distribuciones y outliers con un enfoque en edad, volumen de llamadas/mensajes y nivel de consumo
- Generar insights para los stakeholders de ConnectaTel
