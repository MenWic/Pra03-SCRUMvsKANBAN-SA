# Práctica 03 — UniMarket CUNOC: Scrum vs. Kanban

Propuesta de planificación ágil para el desarrollo del **MVP de UniMarket CUNOC**, comparando dos formas de gestionar el mismo producto: **Scrum** y **Kanban**.

> **Video de presentación:** [Ver video](https://drive.google.com/file/d/1FtbzU12jLgX33GuSIe9m1nGd0bNzTALz/view?usp=sharing)
>
> **Informe final:** [Ver `Informe_Pra03.pdf`](./Informe_Pra03.pdf)

---

## Descripción

UniMarket CUNOC se plantea como un marketplace interno para la comunidad universitaria, orientado a facilitar la publicación, descubrimiento e intercambio de productos dentro del campus.

La práctica toma un mismo alcance funcional y lo convierte en dos propuestas completas de gestión. El objetivo no es comparar metodologías en abstracto, sino observar cómo cambia la planificación, el flujo de trabajo, la inspección y la toma de decisiones cuando el mismo MVP se aborda con **Scrum** y con **Kanban**.

El alcance se organiza alrededor de cinco capacidades principales:

- **Identidad y acceso**
- **Catálogo**
- **Descubrimiento de productos**
- **Pedidos**
- **Notificaciones**

A partir de estas capacidades se consolidó un **Product Backlog de 15 historias de usuario y 61 Story Points**, con prioridades, dependencias y criterios de aceptación en Gherkin.

---

## Propuesta con Scrum

La planificación Scrum se construye alrededor de un equipo pequeño y multifuncional de **5 personas**:

- 1 Product Owner
- 1 Scrum Master
- 3 Developers

El MVP se organiza en **2 Sprints de 3 semanas**:

| Sprint | Enfoque | Historias | Story Points |
|---|---|---:|---:|
| **Sprint 1** | Primer flujo transaccional de UniMarket | 7 | 30 |
| **Sprint 2** | Ciclo completo del MVP | 8 | 31 |

El seguimiento se apoya en **Sprint Goals**, Sprint Backlogs, Definition of Done, eventos Scrum y **Burndown proyectado** para visualizar el trabajo restante durante cada iteración.

---

## Propuesta con Kanban

Kanban utiliza el mismo backlog, pero cambia la lógica de gestión hacia un sistema **pull** con control explícito del trabajo en progreso.

El flujo definido es:

**Backlog → Ready → Development → Review → Validation → Done**

Los límites establecidos son:

| Estado | Límite |
|---|---:|
| Ready | 4 |
| Development | 3 |
| Review | 2 |
| Validation | 2 |
| Done | Sin límite activo |

La propuesta incorpora métricas de flujo para observar capacidad, acumulación y envejecimiento del trabajo:

- **Cycle Time medio proyectado:** 4.27 días laborables
- **Throughput proyectado:** 0.54 PBI por día laborable
- **SLE inicial:** 85 % de los PBIs Standard en 5 días laborables o menos
- **CFD proyectado** sobre un escenario de 28 días laborables

---

## Scrum vs. Kanban

La comparación se realiza sobre el **mismo producto, el mismo backlog y el mismo tamaño de equipo**. Lo que cambia es la forma de controlar y sincronizar el trabajo.

**Scrum** concentra al equipo alrededor de objetivos de Sprint, iteraciones y puntos definidos de inspección. **Kanban** regula la entrada de trabajo mediante capacidad disponible, límites WIP y métricas de flujo continuo.

Para la construcción actual del MVP de UniMarket CUNOC, la propuesta recomienda **Scrum como marco principal**, debido a que el producto parte de un objetivo claro, un backlog cohesivo y dos incrementos funcionales naturales.

Kanban conserva especial valor para una etapa posterior donde predominen **mantenimiento, soporte, demanda continua o prioridades más variables**. También se contempla la posibilidad de incorporar prácticas Kanban dentro de Scrum cuando el flujo real lo justifique, dando lugar a una evolución tipo **Scrumban**.

---

## Jira como soporte de la planificación

Las dos propuestas fueron materializadas en Jira para representar de forma visual y operativa la planificación definida.

En Scrum se utilizaron, entre otros elementos:

- Product Backlog
- Story Points
- dependencias
- Sprint Goals
- dos Sprints
- tablero de trabajo

En Kanban se representaron:

- Backlog separado del trabajo preparado
- workflow `Ready → Development → Review → Validation → Done`
- límites WIP
- dependencias
- flujo pull

Las capturas y evidencias correspondientes se encuentran dentro del informe final.

---

## Contenido del informe

El PDF desarrolla de forma completa:

- fundamentos y principios ágiles aplicados a UniMarket;
- riesgos de un enfoque secuencial;
- Product Backlog consolidado;
- planificación Scrum;
- planificación Kanban;
- Burndown de ambos Sprints;
- métricas y CFD de Kanban;
- comparación multidimensional Scrum vs. Kanban;
- recomendación metodológica;
- posible evolución hacia Scrumban;
- historias de usuario con criterios de aceptación Gherkin;
- evidencias de los espacios Scrum y Kanban en Jira.

**Documento completo:** [Informe_Pra03.pdf](./Informe_Pra03.pdf)

---

## Estructura del repositorio

- `README.md` descripción general de la práctica y acceso a los entregables.
- `Informe_Pra03.pdf` informe final de la propuesta, planificación, comparación y evidencias.

---

## Autor

**Luis Alejandro Méndez Rivera**  
Carné: **202030627**  
Centro Universitario de Occidente - CUNOC  
Análisis y Diseño de Sistemas 2
