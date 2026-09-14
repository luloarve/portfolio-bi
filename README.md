# portfolio-bi
Portafolio profesional de análisis de datos y Business Intelligence - Proyectos en Power BI y Salesforce.
# 🏢 Portafolio de Business Intelligence y Arquitectura de Datos

> **Autora:** Luisa | Analista de Datos & Economista  
> Portafolio de soluciones analíticas y de Business Intelligence desarrolladas para el sector inmobiliario, abarcando desde la arquitectura de datos y modelado en estrella hasta la automatización de pipelines y lógica de negocio avanzada.

---

## 📊 Proyecto 1: Dashboard de Rendimiento Comercial y Ranking de Vendedores

Herramienta ejecutiva diseñada para centralizar, ponderar y evaluar el desempeño del equipo comercial en función de su antigüedad y efectividad real.


### ⚙️ Desafíos y Arquitectura Técnica (De Cero a Producción)
- **Ingeniería y Extracción ETL:** Ante la ausencia de un pipeline previo, se diseñó e implementó todo el proceso de ingeniería de datos desde cero. Se estableció una conexión automatizada vía API conectando Power BI directamente con **Salesforce**, estructurando consultas avanzadas para el procesamiento de datos.
- **Modelado Dimensional (Star Schema):** Construcción de un modelo de datos robusto con tablas dimensionales optimizadas para garantizar rendimiento y consistencia en los cálculos.
- **Lógica de Negocio y Ponderación Avanzada:** 
  - Se crearon reglas de negocio personalizadas para el ranking de asesores. Por ejemplo, se ajustó el peso de las ventas y promesas filtradas según la antigüedad del asesor en la empresa (evitando sesgos al comparar personal nuevo vs. personal con trayectoria completa).
  - Desarrollo de medidas DAX complejas para cálculos YTD (Year-to-Date), comparativas porcentuales frente a años anteriores, y métricas de precios promedio y montos totales.
- **Interactividad Dinámica:** Implementación de filtros temporales avanzados (Año, Mes, selección múltiple para trimestres/semestres) asegurando que las matrices y gráficos reaccionen en tiempo real sin perder visibilidad de los totales históricos.

### 📈 Impacto de Negocio
- Centralización de la meta global anual (seguimiento dinámico de la meta de promesas) y visibilidad inmediata del líder del periodo.
- Detección precisa del rendimiento comercial real al eliminar distorsiones por tiempo de permanencia de los asesores.

---

## 📉 Proyecto 2: Embudo de Conversión Comercial (Sales Funnel)

Panel analítico enfocado en la trazabilidad completa del ciclo de vida del cliente (*Lead to Cash*), permitiendo identificar cuellos de botella en la operación comercial e inmobiliaria.

### ⚙️ Desafíos y Arquitectura Técnica
- **Rastreo Profundo en CRM (Salesforce):** Para estructurar el embudo de conversión (`Leads ➔ Descalificados ➔ Intentos de Contacto ➔ Contactados ➔ Citas ➔ Reservas ➔ Promesas`), fue necesario realizar un rastreo avanzado de objetos relacionales dentro de Salesforce, activando y extrayendo información de los historiales de campos nativos.
- **Automatización y Conectividad:** Extracción automatizada mediante consultas personalizadas para alimentar de forma consistente el modelo estrella sin intervención manual.
- **Análisis de Tasas de Conversión por Asesor:** Implementación de matrices dinámicas y gráficos de barras integrados para medir la efectividad específica en cada etapa (ej. tasa de conversión de citas vs. contactados por cada comercial).

### 📈 Impacto de Negocio
- Visibilidad absoluta de la pérdida de leads en cada etapa del embudo (permitiendo ver descalificaciones y caídas de reservas en tiempo real).
- Optimización de la asignación de esfuerzos operativos para el call center y el equipo de asesores inmobiliarios.

---

### 🛠️ Stack Tecnológico Utilizado
* **Visualización & BI:** Power BI Desktop / Service.
* **Modelado & Lenguaje:** DAX Avanzado, Modelado Estrella (*Star Schema*).
* **Ingeniería de Datos & ETL:** Consultas Avanzadas (Power Query).
* **Fuentes de Datos / CRM:** Salesforce API, Rastreo de Objetos e Historiales de Campos Nativos.
