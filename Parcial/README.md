# 📊 Dashboard de Visualización de Datos

Este repositorio contiene el **dashboard interactivo** desarrollado para responder consultas complejas a partir de **tres datasets de gran volumen**. Debido al tamaño considerable de los datos, la manipulación y visualización resultaron demandantes tanto en términos de recursos como de tiempo de carga. Para facilitar su despliegue y organización, este repositorio incluye **dos submódulos**: uno para el _frontend_ y otro para el _backend_.

## 🧩 Estructura del Proyecto

- `frontend/`: Submódulo con el código del dashboard desarrollado en **React** y **D3.js**, encargado de la visualización de los datos.
- `backend/`: Submódulo que contiene el servidor backend construido con **FastAPI**, el cual expone una API para consultar los datos, los cuales están indexados y gestionados mediante **Elasticsearch**.
