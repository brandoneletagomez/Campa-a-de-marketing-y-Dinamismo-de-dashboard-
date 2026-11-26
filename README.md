# Inteligencia Empresarial y BI para Apart Hotel (Tandil)

Caso de estudio académico desarrollado en la **Facultad de Ciencias Económicas** para **Herramientas de Inteligencia Empresarial**, junto a Rocío Andersson, Brenda Corsi, Aldana Fennema y Bautista Grasso.

## 1. Contexto y problemática de negocio

El **Apart Hotel** es un establecimiento de 4 estrellas ubicado en **Tandil**, con servicios de alojamiento, restaurante, spa, piscina, gimnasio y cochera.

El desafío crítico radicaba en la total fragmentación de su información: la empresa operaba con sistemas aislados y desconectados (software de reservas, de restaurante, planillas de spa y cochera, portales). Esta falta de integración generaba graves silos de datos, impidiendo una visión unificada para la toma de decisiones estratégicas y operativas.

<details>
<summary><strong>Ver principales problemas detectados</strong></summary>

- **Sistemas aislados:** Cero conectividad entre el software de reservas, gastronomía y servicios auxiliares.
- **Dispersión de datos:** Información crítica fragmentada en múltiples plataformas sin un repositorio central.
- **Carencia de insights:** Imposibilidad de medir el rendimiento global y evaluar la efectividad real de las campañas.

</details>

## 2. Solución propuesta: Unificación, Arquitectura y ETL

Para resolver el caos operativo, se diseñó e implementó una infraestructura integral de Inteligencia Empresarial que transformó datos dispersos en un activo estratégico:

- **Unificación de sistemas:** Se integraron las diversas fuentes operativas aisladas, centralizando el flujo de información.
- **Flujos ETL/ELT:** Procesos robustos de Extracción, Transformación y Carga para consolidar los datos en un entorno unificado de almacenamiento.
- **Modelado dimensional:** Creación de un modelo en estrella con la tabla de hechos **TH_Venta** (métrica de cantidad de noches e importe) vinculada a dimensiones clave como **TD_Cliente**, **TD_Tiempo**, **TD_Campaña**, **TD_Reserva**, **TD_Servicios** y **TD_Motor de Reserva**.

<details>
<summary><strong>Ver detalles de depuración y preparación de datos</strong></summary>

- **Limpieza profunda:** Identificación y eliminación de datos ruidosos e inconsistencias.
- **Conciliación de entidades:** Unificación de registros de clientes duplicados o con variaciones tipográficas bajo un mismo identificador.
- **Estandarización:** Normalización de formatos de fecha, moneda y textos en todas las ramas.
- **Enriquecimiento:** Categorización de servicios y creación de la columna calculada "Grupo Edad" para análisis de segmentación.

</details>

## 3. Visualización en Power BI y analítica avanzada

La capa de explotación se construyó en **Power BI**, utilizando la base de datos unificada para dotar al equipo de gestión de herramientas de exploración dinámica:

- **Dashboards interactivos:** Monitoreo en tiempo real de indicadores clave como importe vendido, ocupación y procedencia de huéspedes.
- **Análisis de efectividad:** Capacidad de segmentar el impacto de campañas por canal (Facebook, Instagram, Motores de búsqueda) y rango etario.
- **Proyección analítica:** Preparación de la arquitectura para incorporar modelos de analítica avanzada y procesamiento de lenguaje natural sobre reseñas para gestión de reputación.

<details>
<summary><strong>Ver impacto y beneficios para la gestión</strong></summary>

- **Decisiones basadas en datos:** Ajuste ágil de estrategias comerciales con información veraz y consolidada.
- **Eficiencia operativa:** Eliminación de la duplicidad de esfuerzos y del procesamiento manual de planillas.
- **Visión 360°:** Control total sobre las múltiples ramas del negocio desde una única interfaz.

</details>

