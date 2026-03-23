# 📊 Sistema de Auditoría de Facturas Automática

Este proyecto es una herramienta desarrollada en **Python** diseñada para optimizar procesos en el área **administrativa contable**. El script automatiza la lectura, limpieza y análisis de estados de cuenta de proveedores a partir de archivos Excel.

## 🚀 Funcionalidades
* **Limpieza de Datos:** Normalización automática de nombres de columnas (eliminación de espacios y errores de formato).
* **Análisis de Vencimientos:** Conversión de tipos de datos y filtrado inteligente de facturas pendientes con fecha de vencimiento vencida.
* **Cálculo de Riesgo:** Sumatoria automática del monto total en mora.
* **Generación de Informes:** Creación de un archivo Excel de salida con la fecha del día para seguimiento ejecutivo.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** * `Pandas`: Para la manipulación y análisis de estructuras de datos.
  * `Datetime`: Para el manejo de cronología y fechas actuales.
  * `Openpyxl`: Motor para la exportación a formatos Excel.

## 📁 Estructura del Proyecto
* `PROYECTO.py`: Script principal con la lógica de auditoría.
* `facturas.xlsx`: Archivo de entrada con los datos de proveedores (Ejemplo).
* `Informe_Mora_YYYY-MM-DD.xlsx`: Reporte generado automáticamente por el sistema.

## 📝 Cómo utilizarlo
1. Asegúrate de tener instaladas las dependencias: `pip install pandas openpyxl`
2. Coloca tu archivo de facturas con el nombre `facturas.xlsx` en la misma carpeta.
3. Ejecuta el script: `python PROYECTO.py`
4. Revisa el informe generado en la carpeta de salida.

---
*Desarrollado con el objetivo de integrar la programación en la gestión financiera diaria.*
