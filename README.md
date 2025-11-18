# Dashboards en Excel

This repository showcases interactive Excel dashboards designed for reporting and process analysis.
All scenarios are simulated and created for educational and professional development purposes.
Documentation is in Spanish, but the structure and visuals are intuitive and easy to follow.
Tools used include Excel, with dynamic elements such as slicers, charts, and calculated metrics.


Este repositorio presenta una colección de dashboards interactivos desarrollados en Excel como parte de ejercicios prácticos de análisis de datos. **Todas las situaciones descritas son simuladas** y fueron diseñadas con fines educativos y de desarrollo profesional. No representan experiencias laborales reales.
Cada proyecto parte de un escenario específico y propone una solución visual que permite explorar la información de forma clara, funcional y adaptable a distintos perfiles de usuario.

---
## ¿Qué encontrarás aquí?

- Dashboards en español, creados a partir de ejercicios independientes.
- Imágenes y vídeos que muestran la estructura y funcionalidad (incluyendo el efecto de los slicers).
- Breves descripciones de cada proyecto, con enfoque en el análisis realizado.
---

### Proyecto 3: Dashboard de Ventas y Comisiones – Ski Valle Silbador
Este dashboard fue diseñado para reconstruir el sistema de reporteo de Ski Valle Silbador, un parque de ski canadiense perteneciente a la Red Heroic. El análisis permite recuperar visibilidad sobre ingresos, comisiones, comportamiento de visitantes y uso de lifts, tras un incidente interno que dañó la base de datos de la temporada 2018–2019.

**Escenario simulado:**
Como analista de datos recién contratado por Ski Valle Silbador, se me asignó la tarea de reconstruir la base de ventas y el sistema de reporteo, luego de que un ex-empleado eliminara registros clave. La gerencia necesitaba recuperar métricas operativas y comerciales para evaluar el desempeño de la temporada, incluyendo ingresos por tipo de pase, comisiones pagadas a otros parques de la Red Heroic, y comportamiento de los visitantes.

**Descripción de los elementos evaluados:**
*Tipos de pase:*
- Pase por días: acceso limitado según la cantidad de días comprados.
- Pase de temporada: acceso ilimitado durante toda la temporada de nieve.
*Promociones aplicadas:*
- Regalo de 1 o 2 días extra según duración de estancia (solo para pases por días).
- Rentas gratis para paquetes comprados fuera de temporada.
*Red Heroic:*
- Visitantes con pase de otro parque de la red.
- Se paga comisión al parque que vendió el pase original.
*LIFTs:*
- Registro de cada acceso a telesillas por esquiadores con pase de temporada.

**Objetivo:**
Diseñar una herramienta interactiva que permita visualizar ingresos, comisiones, comportamiento de visitantes y uso de lifts, integrando múltiples fuentes de datos y aplicando fórmulas para reconstruir métricas clave.

**Elementos incluidos en el dashboard:**
- Tarjeta con el monto total de ventas en dólares
- Tarjeta con los días promedio de visita de quienes no tienen pase de temporada
- Gráfica de visitantes por Modo de Compra (% del total)
- Gráfica de visitantes por Parque Origen (% del total de Red Heroic)
- Tarjeta con el porcentaje de ventas que provienen de compras mayores a $1,000
- Tabla de ventas por Hotel (solo visitantes por paquete)
- Tabla de comisiones por Parque Origen (solo Red Heroic)
- Tarjeta con los días extra (regalo) que deben entregarse
- Tarjeta con el costo de rentas gratis para paquetes fuera de temporada
- Gráfica de viajes por LIFT por trimestre
- Tarjeta con ganancias/pérdidas de visitantes con pase de temporada
- Tabla de cantidad de lifts por día de la semana (solo el 33.33% que más esquía)
*Segmentadores incluidos:*
- Por Parque de Origen
- Por Modo de Compra
- Por días de visita

**Tratamiento de datos:**
Se integraron múltiples fuentes: base de ventas sin errores, tabla de comisiones incompleta, base de viajes en LIFT con errores, correos de hoteles y notas internas. Se aplicaron fórmulas para reconstruir comisiones, días extra, rentas gratis y márgenes de ganancia. Se corrigieron errores en la base de LIFTs y se normalizaron los nombres de hoteles y parques. El dashboard se diseñó para actualizarse dinámicamente con nuevos datos.

![Vista previa del dashboard](Valle_Silbador.png)

---
### Proyecto 2: Dashboard de Nómina – Gran Empresa de TI
Este dashboard fue diseñado para evaluar dos escenarios salariales en una empresa global de TI, considerando restricciones legales mexicanas y prácticas internacionales. El análisis permite tomar decisiones informadas sobre aumentos y despidos, con visuales claros y segmentación dinámica.

**Escenario simulado:**
Como analista de nómina en la división mexicana de una empresa global de tecnología, se me pidió evaluar dos propuestas de aumento salarial para el próximo año. Los gerentes locales proponían un aumento igualitario para todos los empleados, mientras que los vicepresidentes en Estados Unidos sugerían un modelo basado en desempeño, inspirado en prácticas de la competencia.

**Descripción de los planes evaluados:**
*Plan Mexicano:*
Aumento salarial igual para todos los empleados, sin despidos. Se aplican porcentajes estándar por concepto (salario base, bonos, vales, etc.) sin distinción por desempeño.
*Plan Americano:*
Despido inmediato de empleados con calificación de desempeño igual a 1, con cálculo de indemnización conforme a la Ley Federal del Trabajo. Los empleados con calificación 4 y 5 reciben el doble del aumento estándar. Los demás reciben el aumento normal.

**Objetivo:**
Diseñar una herramienta interactiva que permita comparar el impacto económico de ambos planes, visualizar los costos por área y por nivel de desempeño, y facilitar la toma de decisiones estratégicas.

**Elementos incluidos en el dashboard:**
- Gasto total de nómina actual (todos los conceptos)
- Costo de implementar el plan americano (en dólares y porcentaje)
- Costo de implementar el plan mexicano (en dólares y porcentaje)
- Gráfica de costos actuales por calificación de desempeño
- Tabla de costos actuales por área (en dólares y porcentaje)
- 2 segmentadores: por grado de evaluación y por área

**Tratamiento de datos:**
Se aplicó limpieza de errores en bandas y categorías, normalización de campos, y cálculo de indemnizaciones conforme al Artículo 50 de la Ley Federal del Trabajo. El dashboard se diseñó para actualizarse dinámicamente con nuevos datos.

![Vista previa del dashboard](Gran_Empresa_de_TI.png)

---
### Proyecto 1: Dashboard de Recursos Humanos – Selva Congo
**Escenario simulado:** 
Como analista recién incorporada al departamento de Recursos Humanos de SelvaCongo, se me encomendó rediseñar la forma en que se presenta la información sobre contrataciones y bajas del personal de almacén a nivel nacional. El analista anterior dedicaba más de la mitad de su tiempo mensual a generar reportes manuales en PowerPoint para **143 gerentes y jefes de operación**.

**Objetivo:**
Diseñar un dashboard interactivo en Excel que permita a los gerentes consultar de forma autónoma los indicadores clave relacionados con la rotación de personal, mejorando la eficiencia del área y facilitando la toma de decisiones.

**Elementos incluidos en el dashboard:**
- Cantidad de ingresos
- Cantidad de ubicaciones /rendimiento como porcentaje de ingresos
- Cantidad de liberaciones/ rendimiento como porcentaje de ingresos
- Índice de rotación de personal (definido como bajas sobre ingresos)
- 2 gráficas
- 2 segmentadores
- 1 tabla

**Información adicional considerada:**
- Objetivo de Dirección: superar la media de la industria en todos los indicadores logísticos.
- Datos comparativos de contrataciones en **Tiendas Manchester** (competencia) durante el primer semestre de 2017.
- Impacto de la **inseguridad** en las contrataciones.
- Medias de rotación en la industria:
  - Turno nocturno: **60%**
  - Turno diurno: **23%**

**Tratamiento de datos:**
Los datos fueron simulados y contenían inconsistencias y formatos mixtos. Se realizó limpieza, normalización de campos y creación de métricas derivadas. 

Este proyecto fue desarrollado con base en documentos internos simulados, incluyendo boletines, correos y reportes de otras áreas, para contextualizar las necesidades del negocio.

![Vista previa del dashboard](Selva_Congo.png)

---

## 📄 Licencia

Este repositorio está bajo la licencia [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Puedes reutilizar y modificar el contenido con atribución, pero no con fines comerciales.
