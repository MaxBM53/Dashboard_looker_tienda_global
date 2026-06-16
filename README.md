# 📊 Global Superstore - Sales & Orders Dashboard

## 🎯 Objetivo del Proyecto
El propósito de este proyecto fue diseñar un cuadro de mando (Dashboard) interactivo utilizando **Looker Studio** conectado a los datos de la "Global Superstore". El análisis se centró en identificar el volumen de transacciones de la empresa, entender el comportamiento de las categorías de productos y evaluar la tendencia de pedidos a lo largo del tiempo, permitiendo a la gerencia segmentar la información por región y tipo de cliente en tiempo real.

---

## 🛠️ Tecnologías Utilizadas
* **Origen de Datos:** Google Sheets / Kaggle Dataset.
* **Herramienta de BI & Visualización:** Looker Studio (Google Data Studio).
* **Infraestructura:** Procesamiento analítico en la nube.

---

## 🔍 Visualización e Interactividad (Demos)

### 1. Análisis de la Región Este (Segmento Consumidor)
Al filtrar por la región **East** y el segmento **Consumer**, el dashboard aísla dinámicamente 299 transacciones, mostrando que los suministros de oficina lideran el volumen.
![Región Este](https://github.com/MaxBM53/Dashboard_looker_tienda_global/blob/main/Captura%20de%20pantalla%202026-06-16%20172050.png)

### 2. Análisis Multiregional Combinado
El reporte demuestra su capacidad elástica al combinar los datos de las regiones **West** y **Central** en simultáneo, consolidando un volumen de 618 registros y recalculando las tendencias temporales al instante.
![Multiregional](https://github.com/MaxBM53/Dashboard_looker_tienda_global/blob/main/Captura%20de%20pantalla%202026-06-16%20172103.png)

### 3. Filtros Avanzados de Exclusión
Evaluación de la región **South** excluyendo los clientes corporativos corporativos, aislando con éxito 226 pedidos para analizar el comportamiento exclusivo de los demás segmentos.
![Filtro Avanzado](./captura3.png)

---

## 💡 Principales Insights del Negocio
* **Dominio de Categoría:** La categoría *Office Supplies* (Suministros de oficina) triplica en volumen de pedidos a *Furniture* y *Technology* de manera consistente en todas las geografías analizadas. Es el motor operativo del negocio.
* **Capacidad de Respuesta Dinámica:** La arquitectura del dashboard permite interactuar, cruzar y excluir variables de forma inmediata, facilitando la toma de decisiones basada en datos para mandos medios y directores regionales.
