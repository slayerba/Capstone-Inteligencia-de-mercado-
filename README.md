# Enci-Intel — Plataforma de Inteligencia de Mercado

**Capstone 2026 | Ingeniería en Informática | Duoc UC | Grupo 9**

Proyecto desarrollado por el Grupo 9 como parte de la asignatura Capstone de Ingeniería en Informática de Duoc UC durante el segundo semestre de 2026.

---

## Descripción

Enci-Intel es una plataforma de inteligencia de mercado orientada a automatizar la recopilación, procesamiento y análisis de información competitiva.

Actualmente, parte de la inteligencia competitiva se recopila manualmente mediante planillas Excel, lo que puede generar tiempos de respuesta de entre 1 y 7 días frente a cambios relevantes del mercado, como variaciones de precios, nuevos registros regulatorios o situaciones de desabastecimiento de competidores.

El proyecto busca centralizar esta información y transformarla en indicadores, análisis y alertas que faciliten la toma de decisiones comerciales y gerenciales.

---

## Problemática

La recopilación manual y dispersa de información competitiva dificulta la detección oportuna de cambios relevantes en el mercado.

Esta situación puede provocar:

* Retrasos en la identificación de cambios de precios.
* Dificultad para detectar nuevos productos o competidores.
* Información distribuida entre diferentes fuentes.
* Dependencia de procesos manuales de recopilación y análisis.
* Mayor tiempo para transformar datos en información útil.
* Menor capacidad de respuesta frente a cambios competitivos.

---

## Objetivo general

Desarrollar y mejorar una plataforma de inteligencia de mercado capaz de monitorear distintas fuentes de información, procesar los datos obtenidos y presentar información relevante mediante análisis, indicadores, dashboards y alertas priorizadas, con el propósito de apoyar una toma de decisiones comerciales más oportuna.

---

## Solución propuesta

Enci-Intel busca centralizar y automatizar parte del proceso de inteligencia competitiva mediante una plataforma que permita:

* Automatizar la recopilación de información competitiva.
* Centralizar datos provenientes de distintas fuentes.
* Procesar y analizar información de productos y competidores.
* Detectar cambios y variaciones relevantes.
* Generar alertas según niveles de criticidad.
* Visualizar indicadores mediante dashboards.
* Consultar información histórica.
* Facilitar el análisis comercial y gerencial.

---

## Usuarios objetivo

La solución está orientada principalmente a los siguientes tipos de usuario:

* **Área Comercial:** consulta de productos, precios, competidores y alertas.
* **Gerencia:** visualización de indicadores e información estratégica para apoyar la toma de decisiones.
* **Administración:** configuración, supervisión y gestión de la plataforma.

---

## Funcionalidades consideradas

Entre las funcionalidades consideradas para el desarrollo del proyecto se encuentran:

* Dashboard de alertas.
* Monitoreo de agentes de inteligencia.
* Benchmarking de precios.
* Análisis de productos.
* Comparación competitiva.
* Mapa competitivo.
* Alertas ante cambios relevantes.
* Gestión de usuarios y roles.
* Reportes exportables.
* Consultor Veterinario basado en inteligencia artificial.

> El alcance definitivo del MVP será establecido durante la fase de análisis y planificación del proyecto. Algunas funcionalidades podrán ser priorizadas, modificadas o planificadas para etapas posteriores según su viabilidad técnica, económica y temporal.

---

## Enfoque de analítica

El proyecto busca transformar datos competitivos en información útil para el negocio mediante:

* Comparación de precios.
* Cálculo de variaciones porcentuales.
* Análisis histórico.
* Identificación de tendencias.
* Seguimiento de competidores.
* Indicadores de mercado.
* Alertas según umbrales.
* Visualizaciones orientadas a usuarios comerciales y gerenciales.

El flujo conceptual del proyecto es:

```text
Fuentes de información
        |
        v
Recopilación
        |
        v
Procesamiento y validación
        |
        v
Almacenamiento
        |
        v
Análisis de datos
        |
        v
Indicadores y alertas
        |
        v
Dashboard
        |
        v
Toma de decisiones
```

---

## Indicador principal

Uno de los principales indicadores considerados por el proyecto es el **Tiempo de Respuesta Competitiva (TRC)**.

La situación actual contempla tiempos aproximados de entre:

**1 a 7 días**

Mientras que el objetivo establecido para el MVP es:

**TRC menor a 4 horas**

Este indicador permitirá evaluar la capacidad de la solución para reducir el tiempo existente entre la detección de un cambio relevante del mercado y la disponibilidad de información para apoyar una decisión empresarial.

---

## Arquitectura de la solución

La arquitectura definitiva se encuentra actualmente en etapa de análisis y validación.

De manera preliminar, la solución contempla el siguiente flujo:

```text
+-------------------------+
| Fuentes de información  |
+------------+------------+
             |
             v
+-------------------------+
| Agentes / Integraciones |
+------------+------------+
             |
             v
+-------------------------+
| Procesamiento de datos  |
+------------+------------+
             |
             v
+-------------------------+
| Almacenamiento          |
+------------+------------+
             |
             v
+-------------------------+
| Backend / API           |
+------------+------------+
             |
             v
+-------------------------+
| Analytics y Alertas     |
+------------+------------+
             |
             v
+-------------------------+
| Dashboard / Frontend    |
+-------------------------+
```

Las decisiones arquitectónicas definitivas serán documentadas y justificadas considerando:

* Requerimientos funcionales y no funcionales.
* Seguridad.
* Rendimiento.
* Escalabilidad.
* Disponibilidad.
* Costos de infraestructura.
* Facilidad de mantenimiento.
* Viabilidad económica para la organización.

---

## Tecnologías

Las tecnologías definitivas se encuentran actualmente en proceso de evaluación.

El equipo analizará las herramientas utilizadas por la solución existente y determinará cuáles se mantendrán, modificarán o incorporarán considerando criterios técnicos, económicos y de mantenibilidad.

| Área                    | Tecnología   |
| ----------------------- | ------------ |
| Frontend                | Por definir  |
| Backend                 | Por definir  |
| Base de datos           | Por definir  |
| Cloud                   | Por definir  |
| Analítica               | Por definir  |
| Inteligencia Artificial | Por definir  |
| Contenedores            | Docker       |
| Control de versiones    | Git / GitHub |

Las decisiones tecnológicas serán justificadas considerando:

* Necesidades reales del proyecto.
* Costo de implementación.
* Costo operacional.
* Escalabilidad.
* Tiempo de desarrollo.
* Mantenibilidad.
* Seguridad.
* Compatibilidad con la solución existente.

---

## Metodología de trabajo

El proyecto utilizará **Scrum** como marco principal de trabajo ágil.

El desarrollo se organizará mediante:

* Product Vision.
* Product Backlog priorizado.
* Historias de usuario.
* Sprint Backlog.
* Sprint Planning.
* Desarrollo incremental.
* Pruebas durante cada Sprint.
* Sprint Review.
* Retrospectivas.
* Definition of Done.

Como herramienta complementaria se utilizará un tablero Kanban mediante GitHub Projects para visualizar el estado de las tareas.

Flujo preliminar de trabajo:

```text
Backlog
   |
   v
To Do
   |
   v
In Progress
   |
   v
Review
   |
   v
Testing
   |
   v
Done
```

---

## Gestión del proyecto

La planificación del proyecto contempla las tres fases establecidas para Capstone:

### Fase 1 — Definición y planificación

* Definición de la problemática.
* Justificación del proyecto.
* Definición de objetivos.
* Alcance del MVP.
* Product Vision.
* Product Backlog inicial.
* Definición preliminar de arquitectura.
* Selección de tecnologías.
* Cronograma del proyecto.
* Evaluación de recursos y costos.

### Fase 2 — Desarrollo

* Desarrollo incremental mediante Sprints.
* Implementación de funcionalidades.
* Integración de componentes.
* Desarrollo y validación del modelo de datos.
* Pruebas unitarias.
* Pruebas de integración.
* Pruebas de rendimiento.
* Pruebas de seguridad.
* Documentación de evidencias.
* Despliegue de la solución.

### Fase 3 — Cierre y presentación

* Validación de resultados.
* Correcciones finales.
* Documentación técnica.
* Informe final.
* Preparación de la demostración.
* Presentación y defensa del proyecto.

---

## Calidad y pruebas

Durante el desarrollo se contemplarán diferentes niveles de pruebas para asegurar la calidad de la solución:

* Pruebas unitarias.
* Pruebas de integración.
* Pruebas funcionales.
* Pruebas de rendimiento.
* Pruebas de seguridad.
* Criterios de aceptación asociados a las historias de usuario.

Las pruebas serán realizadas progresivamente durante los diferentes Sprints y sus resultados quedarán documentados como evidencia del proyecto.

---

## Requisitos no funcionales

Los requisitos no funcionales definitivos serán establecidos durante la fase de análisis.

Se considerarán al menos los siguientes aspectos:

* Seguridad.
* Rendimiento.
* Escalabilidad.
* Disponibilidad.
* Mantenibilidad.
* Portabilidad.
* Trazabilidad.
* Usabilidad.

---

## Viabilidad del proyecto

Además de la factibilidad técnica, el proyecto considerará su viabilidad temporal y económica.

Se evaluarán aspectos como:

* Horas-persona requeridas.
* Tiempo total de desarrollo.
* Costo equivalente de desarrollo.
* Costos de infraestructura Cloud.
* Costos asociados a APIs o servicios externos.
* Costos de operación.
* Costos de mantenimiento.
* Escalabilidad de costos.
* Beneficios operacionales esperados.
* Relación costo-beneficio.
* Retorno estimado de la inversión cuando sea posible determinarlo.

El objetivo es asegurar que la arquitectura seleccionada no solo sea técnicamente viable, sino también económicamente razonable para la organización.

---

## Innovación y propuesta de valor

La propuesta de valor de Enci-Intel no consiste únicamente en visualizar información mediante un dashboard.

La solución busca integrar distintas fuentes de información competitiva y transformar cambios relevantes del mercado en información priorizada y accionable.

El proyecto busca pasar de un proceso:

```text
Datos dispersos
        |
        v
Revisión manual
        |
        v
Análisis
        |
        v
Decisión
```

a un proceso:

```text
Monitoreo automatizado
        |
        v
Procesamiento
        |
        v
Análisis
        |
        v
Alertas e indicadores
        |
        v
Decisión más oportuna
```

La propuesta busca reducir el tiempo existente entre un cambio relevante del mercado y la capacidad de la organización para analizarlo y actuar.

---

## Ejecución local

Las instrucciones definitivas de ejecución serán incorporadas una vez finalizada la revisión y configuración del proyecto existente.

La estructura esperada será similar a la siguiente:

```bash
# Clonar el repositorio
git clone <URL-DEL-REPOSITORIO>

# Acceder al proyecto
cd enci-intel

# Configurar las variables de entorno
# Instrucciones pendientes

# Construir y levantar los servicios
docker compose up --build
```

Esta sección será actualizada con:

* Dependencias necesarias.
* Variables de entorno.
* Configuración de servicios.
* Configuración de base de datos.
* Ejecución mediante Docker.
* Puertos utilizados.
* Credenciales de desarrollo.
* Procedimiento de despliegue.

---

## Equipo

Proyecto desarrollado por estudiantes de Ingeniería en Informática de Duoc UC.

**Grupo 9**

| Integrante      | Rol         |
| --------------- | ----------- |
| Alejandro Rojas | Por definir |
| Vicente Abarzúa | Por definir |
| Gabriel Rubilar | Por definir |

Los roles serán establecidos durante la planificación del proyecto considerando las competencias, intereses profesionales y responsabilidades de cada integrante.

Independientemente del rol principal, todos los integrantes deberán aportar evidencia verificable en desarrollo de software, base de datos, documentación, pruebas y gestión del proyecto.

---

## Control de versiones

El proyecto utilizará Git y GitHub para mantener la trazabilidad del desarrollo.

El flujo de trabajo considerará:

```text
Issue
  |
  v
Branch
  |
  v
Commits
  |
  v
Pull Request
  |
  v
Code Review
  |
  v
Testing
  |
  v
Merge
```

Los avances de cada integrante deberán quedar registrados mediante commits, ramas, Pull Requests, Issues y documentación asociada.

---

## Estado del proyecto

**En desarrollo — Capstone 2026**

Actualmente el equipo se encuentra en la fase de análisis, definición, planificación y revisión de la solución existente.

Estado actual:

* Proyecto seleccionado.
* Equipo conformado.
* Problemática preliminar definida.
* Objetivo preliminar definido.
* Metodología Scrum seleccionada.
* Arquitectura en evaluación.
* Tecnologías en evaluación.
* Alcance MVP en definición.
* Product Backlog en elaboración.
* Cronograma en elaboración.
* Presupuesto y costos en evaluación.

---

## Contexto académico

**Proyecto:** Enci-Intel — Plataforma de Inteligencia de Mercado
**Grupo:** 9
**Asignatura:** Capstone
**Carrera:** Ingeniería en Informática
**Institución:** Duoc UC
**Periodo:** Segundo semestre de 2026
