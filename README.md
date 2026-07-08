# sprint7-final-project
# 📱 Proyecto 6 - Análisis de una Empresa de Telecomunicaciones (ConnectaTel)

## 📋 Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

A partir de la información de clientes, planes y registros de uso, se realizó un análisis exploratorio para identificar patrones de consumo, detectar valores atípicos y segmentar a los usuarios según su nivel de uso, con el propósito de generar recomendaciones que apoyen la toma de decisiones del negocio.

---

## 🎯 Objetivos

- Explorar y limpiar los datasets.
- Detectar problemas de calidad de datos.
- Construir métricas de uso por usuario.
- Identificar valores atípicos mediante el método IQR.
- Segmentar clientes por edad y nivel de uso.
- Visualizar patrones de comportamiento.
- Elaborar recomendaciones comerciales basadas en evidencia.

---

## 📂 Datasets utilizados

El análisis se realizó utilizando tres archivos:

- **plans.csv**
  - Información de los planes disponibles.
  - Precio mensual.
  - Minutos incluidos.
  - GB incluidos.
  - Costos por consumo adicional.

- **users_latam.csv**
  - Información demográfica de los clientes.
  - Edad.
  - Ciudad.
  - Fecha de registro.
  - Plan contratado.
  - Fecha de cancelación (churn).

- **usage.csv**
  - Historial de actividad de los usuarios.
  - Llamadas realizadas.
  - Duración de llamadas.
  - Mensajes enviados.

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Etapas del análisis

1. Carga y exploración de datos.
2. Identificación de problemas de calidad.
3. Limpieza de datos.
4. Resumen estadístico.
5. Visualización de distribuciones.
6. Detección de outliers mediante IQR.
7. Segmentación de clientes.
8. Elaboración de insights ejecutivos y recomendaciones.

---

## 🔍 Principales hallazgos

- Se identificaron valores faltantes y sentinels que fueron corregidos antes del análisis.
- Se detectaron usuarios con consumo significativamente mayor al promedio, considerados clientes de alto valor.
- La mayor parte de los usuarios presenta un consumo bajo o medio.
- Los outliers representan comportamientos reales y aportan información valiosa para el negocio.
- Se identificaron oportunidades para crear planes específicos para usuarios de alto consumo.

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar este repositorio.

```bash
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git
```

2. Abrir el notebook en **Jupyter Notebook** o **Google Colab**.

3. Instalar las librerías necesarias si es requerido:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Ejecutar todas las celdas del notebook en orden.

---

## 📁 Estructura del proyecto

```
├── data/
│   ├── plans.csv
│   ├── users_latam.csv
│   └── usage.csv
│
├── notebooks/
│   └── ConnectaTel_Analysis.ipynb
│
├── README.md
```

---

## 👨‍💻 Autor

**Néstor Daniel Valle**

Proyecto desarrollado como parte del programa **TripleTen - Data Analyst**.
