<div align="center">
	
  
## Universidad Peruana de Ciencias Aplicadas

![Image](assets/images/logo/upc_logo.png)


**1ACC0238 - Aplicaciones para Dispositivos Móviles**

Carrera de Ingeniería de Software

**NRC:** 1813

**Profesor:** Eduardo Martin Reyes Rodriguez

## Informe de TB1 

"KORA"

**Integrantes:**

Cabanillas Meza, Jose Mateo (u202311458)

Collantes Carrillo, Diego Mateo (u202311823)

Lizarbe Alvarez, Ariana Nickole (u202311704)

Ortiz Cardenas, Johanna Antuanete (u202310358)

Zegarra Lopez, Renato Sebastian Rubber (u202311558)



**2025**
</div>


## Registro de Versiones del Informe

<div align="center">
<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td>08/09/2025</td>
      <td>
  - Cabanillas Meza, Jose Mateo <br>
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
      </td>
      <td> </td>
    </tr>
  </tbody>
</table>
</div>

# Project Report Collaboration Insights

## **Contenido**
- [STUDENT OUTCOME](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    
 - [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)
      
- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME

ABET 7 - EAC - Student Outcome 7: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

<table border="1">
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>7.c1. Actualiza conceptos y
conocimientos necesarios para su
desarrollo profesional y en especial para
su proyecto en soluciones de ingeniería
de software</td>
      <td>
        <strong>Cabanillas Meza, Jose Mateo</strong><br>
        TB1: <br>
	      <br>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: <br>
	      <br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1:  <br>
	      	      <br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1:  <br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: <br>
      </td>
      <td>
        conclusiones
      </td>
    </tr>
    <tr>
      <td>7.c2. Reconoce la necesidad del
aprendizaje permanente para el
desempeño profesional y el desarrollo
de proyectos en soluciones de
tecnologías de ingeniería de software.</td>
      <td>
        <strong>Cabanillas Meza, Jose Mateo</strong><br>
        TB1: <br>
	      <br>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: <br>
        <br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
	       TB1: 
<br><br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: <br>
	      <br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: <br>
	      <br>
        </td>
      <td>
        conclusiones
      </td>
    </tr>
  </tbody>
</table>

## Objetivos SMART

# CAPÍTULO I: Presentación

# 1.1. Startup Profile

## 1.1.1. Descripción de la Startup

## 1.1.2. Perfiles de integrantes del equipo

# 1.2 Solution Profile
## 1.2.1. Antecedentes y problemática

## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

### 1.2.2.2. Lean UX Assumptions

### 1.2.2.3. Lean UX Hypothesis Statements
