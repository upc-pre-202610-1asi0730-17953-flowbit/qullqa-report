<div align="center">

<img src="assets/img/upc-logo.png" alt="UPC Logo" width="150"/>

# Universidad Peruana de Ciencias Aplicadas

## Facultad de Ingeniería

## Programa Académico de Ingeniería de Software

**Ciclo:** 2026-10

**Curso:** Aplicaciones Web

**NRC:** 17953

**Docente del curso:** Alex Humberto Sánchez Ponce


# Informe de Trabajo Final

**Nombre de la Startup:** Flowbit

**Nombre del producto:** Qullqa


## Integrantes

<p align="center">
u202416272 - Asmat Alminco, Martin Alejandro<br>
u202414802 - Contreras Torres, Arturo Valentino<br>
u2024113169 - Güere Calero, Fernando Julio<br>
u20231h067 - Huaman Oscco, Aldo Jesus<br>
u202018427 - Ramos Fuentes Rivera, Adriana Nicole<br>

</p>


*Abril, 2026*

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| | | | |

---

# Project Report Collaboration Insights

---

# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Güere Calero, Fernando Julio <br>**AV1** <br> <br> Huaman Oscco, Aldo Jesus <br>**AV1** <br> <br> Ramos Fuentes Rivera, Adriana Nicole <br>**AV1** <br> | |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Güere Calero, Fernando Julio <br>**AV1** <br> <br> Huaman Oscco, Aldo Jesus <br>**AV1** <br> <br> Ramos Fuentes Rivera, Adriana Nicole <br>**AV1** <br> | |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos **Flowbit**, una startup tecnológica creada por estudiantes de la carrera Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). Nuestra startup está enfocada en el desarrollo de soluciones digitales innovadoras orientadas a optimizar la gestión de negocios tradicionales mediante el uso de software inteligente y tecnologías emergentes. La empresa busca transformar procesos manuales e ineficientes en sistemas automatizados que permitan mejorar la toma de decisiones, reducir pérdidas y aumentar la productividad.

Nuestro producto principal es **Qullqa**, una solución diseñada para la gestión de bodegas y farmacias, integrando funcionalidades como control de inventario, reportes de ventas, alertas inteligentes y, como valor diferencial, el uso de dispositivos IoT para el seguimiento de entregas.

La misión de Flowhot es brindar soluciones tecnológicas accesibles e innovadoras que permitan a pequeños y medianos negocios optimizar sus procesos, mejorar su rentabilidad y tomar decisiones basadas en datos reales.

Nuestra visión es consolidarnos como una startup líder en el desarrollo de plataformas digitales para la gestión de negocios en Latinoamérica, destacando por la integración de tecnologías como IoT e inteligencia de datos, y contribuyendo a la transformación digital de sectores tradicionales como lo son las bodegas y farmacias.

Nuestros valores son:
- Innovación: Desarrollo constante de soluciones tecnológicas modernas y eficientes
- Compromiso: Enfoque en resolver problemas reales de nuestros clientes
- Accesibilidad: Crear herramientas fáciles y accesibles para negocios pequeños
- Responsabilidad: Garantizar confiabilidad en los datos y procesos
- Calidad: Priorizar la experiencia y necesidades del usuario

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/arturo-contreras.PNG" alt="Foto de Arturo Contreras" width="500"/>
    </td>
    <td><b>Nombre:</b> Arturo Valentino Contreras Torres</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414802</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Arturo Valentino Contreras Torres</b>, tengo 19 años y estudio la carrera de Ingeniería de Software en la UPC, actualmente estoy en el 5to ciclo. Me gusta aprender y aplicar tecnologías innovadoras para resolver problemas complejos y desarrollar soluciones eficientes. Me apasiona participar en concursos de programación en donde aprendo más sobre temas como programación competitiva, lenguajes como C++, Python, Java, frameworks como Flutter y habilidades como el trabajo en equipo.
      <br/><br/>
      Dentro del equipo, contribuyo en el desarrollo frontend y backend, asegurándome de aplicar principios de Domain Driven Design, patrones de diseño y buenas prácticas de desarrollo de software. Me considero una persona responsable, creativa y orientada al trabajo en equipo, con un enfoque en la mejora continua frente a nuevos desafíos.
    </td>
  </tr>
  <tr>
  </tr>

  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/Aldo-Jesus.png" alt="Foto de Aldo Huaman" width="500"/>
    </td>
    <td><b>Nombre:</b> Aldo Jesus Huaman Oscco</td>
  </tr>
  <tr>
    <td><b>Código:</b> u20231h067</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Aldo Jesus Huaman Oscco</b>, tengo 20 años y estudio la carrera de Ingeniería de Software en la UPC, estoy cursando el 5to ciclo de la carrera. Disfruto de resolver distintos tipos de problemas que impliquen logica para su resolucion. Tengo interes en desarrollar proyectos de interes social para el desarrollo de habilidades para mi portafolio profesional, manejo distintas tecnologias como lenguajes de programacion y de tipeado, conozco el desarrollo de fronted y backend. Disfruto de aplicar un manejo estructurado con el desarrollo de metodologias agiles en equipo. 
      <br/><br/>
      Dentro del equipo, contribuyo en fronted y backend con proyeccion a IOT, validare la aplicacion de principios DDD, y el seguimiento de patrones para la arquitectura asi como la implementacion de algoritmos que permitan la escalabilidad de nuestra base de datos en conjunto con el sistema.
    </td>
  </tr>
<tr>

</tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/Fernando-Guere.png" alt="Foto de Fernando Güere" width="500"/>
    </td>
    <td><b>Nombre:</b> Fernando Julio Güere Calero</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202413169</td>
  </tr>
  <tr>
    <td>
    <div align="Justify">
      <b>Descripción:</b><br/>
      Soy <b>Fernando Julio Güere Calero</b>, tengo 19 años y estudio la carrera de Ingeniería de Software en la UPC, estoy cursando el 5to ciclo de la carrera. Cuento con los conocimientos para programar en C++, Python y gestión de base de datos SQL. Además, tengo conocimiento para el desarrollo de páginas web usando HTML, CSS y JavaScript. Siempre estoy interesado en expandir mis conocimientos con otros lenguajes de programación para fortalecer mis competencias técnicas y enfrentar retos en la industria. 
      <br/><br/>
      Dentro del equipo, cumplo con las actividades de documentación y programación en un nivel intermedio. También quisiera destacar que soy responsable con las distintas tareas establecidas.
      </div>
    </td>
  </tr>

  <tr>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/adriana.jpg" alt="Foto de Adriana Ramos" width="500"/>
    </td>
    <td><b>Nombre:</b> Adriana Nicole Ramos Fuentes Rivera</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202018427</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Adriana Nicole Ramos Fuentes Rivera</b>, tengo 23 años y estudio la carrera de Ingeniería de Software en la UPC, actualmente estoy en el 5to ciclo. Me gusta aprender nuevas tecnologias y conocimientos complementarios que me permitan desarrollar soluciones a problematicas dentro de un contexto real. Cuento con experiencia en lenguajes de programación como C++ y Python, además de conocimientos en base de datos no relacional como MongoDB.
      <br/><br/>
      Dentro del equipo, me enfoco en el desarrollo de backend, aplicando principios de Domain Driven Design para mantener una lógica de negocio clara. Me considero una persona organizada y empática.
    </td>
  </tr>

  <tr>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/martin-asmat.png" alt="Foto de martin asmat" width="500"/>
    </td>
    <td><b>Nombre:</b> Martin Alejandro Asmat Alminco </td>
  </tr>
  <tr>
    <td><b>Código:</b> u202416272 </td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
    Soy <b>Martin Asmat</b>, estudiante de quinto ciclo de la carrera de Ingeniería de Software. Cuento con experiencia en lenguajes de programación como Python y C++ para proyectos enfocados en el desarrollo de habilidades computacionales, las cuales apliqué en proyectos académicos enfocados en solucionar un problema a través de procesos de documentación de Ingeniería de software.
      <br/><br/>
     Dentro del equipo, cumplo el rol de un full stack al realizar actividades de documentación y programación a un nivel medio. Considero que soy una persona responsable y adaptable a distintas situaciones con buen time-management.  
    </td>
  </tr>

</table>

## 1.2. Solution Profile

Qullqa es una aplicación desarrollada por la startup Flowbit, orientada a optimizar la gestión de bodegas y farmacias independientes mediante herramientas digitales accesibles y eficientes. La plataforma permite a los usuarios controlar su inventario, registrar ventas, gestionar productos y obtener reportes que faciliten la toma de decisiones.

El sistema está diseñado para reemplazar métodos manuales o poco eficientes, integrando funcionalidades como alertas de bajo stock, notificaciones de productos por vencer y dashboards interactivos que brindan un visión clara del estado del negocio. De esta manera, Qullqa contribuye a reducir pérdidas económicas, mejorar la organización y aumentar la rentabilidad de los negocios.

Además, como valor diferencial, la solución tiene integración con dispositivos IoT que permiten el seguimiento de entregas hacia el almacén o bodega, brindando mayor seguridad y control de los productos.

Qullqa se presenta como una solución escalable, con distintos planes que se adaptan a las necesidades de cada negocio, desde funcionalidades básicas hasta herramientas más avanzadas de análisis y gestión.


### 1.2.1. Antecedentes y problemática

- **What:**
<br>
  <div>
    Nuestra propuesta de solución, Qullqa, se propone resolver las siguientes 3 problemáticas recurrentes en el comercio independiente:
  </div>
  <br>
  <div align="justify">
    Uno de los problemas más comunes que se enfrentan los dueños de bodegas y farmacias es la deficiencia en la gestión de inventarios y falta de rotación, los cuales, por ausencia de un sistema de gestión que les permita registrar información relevante acerca de sus productos, como la fecha de caducidad, número de lote, proveedor, cadena de frío, ubicación exacta (pasillo, estante, nivel), etc. En consecuencia, provoca que muchos establecimientos mantengan productos vencidos en sus almacenes, lo cual representa un riesgo significativo, ya que, de acuerdo con el Artículo 30 del Código de Protección y Defensa del Consumidor (2010), los consumidores tienen derecho a consumir alimentos inocuos. Los proveedores son responsables de la inocuidad de los alimentos que ofrecen en el mercado, de conformidad con la legislación sanitaria.
  </div>
  <br>
  <div align="justify">
    Por otro lado, el desconocimiento de la rentabilidad y finanzas generales, también representa un problema difícil de resolver para los dueños de bodegas y farmacias. Según la Cámara de Comercio de Lima (2025), la falta de liquidez continúa siendo un obstáculo determinante para las pequeñas y medianas empresas en el Perú. Cada año, más de 100 mil de estas unidades económicas dejan de funcionar, y cerca del 40% lo hace debido a la imposibilidad de sostener su flujo de caja. Además, al ser un negocio independiente donde el manejo de las finanzas puede llegar a ser desordenado e incompleto debido a la inexperiencia y falta de conocimiento por parte del dueño, es más común no saber el margen de ganancia real de los productos vendidos. Por consecuencia, al momento de realizar decisiones importantes, en muchos casos, terminan siendo decisiones erradas, reflejadas en los precios mal establecidos, problemas de flujo de caja, elecciones erróneas de productos a vender, etc.
  </div>
  <br>
  <div align="justify">
    Por último, otro problema es la logística enfocada en las entregas de los proveedores, ya que cuando un proveedor envía un pedido, los dueños no tienen visibilidad en tiempo real de dónde está el vehículo, cuándo llegará aproximadamente o si hubo demoras, como resultado, genera descoordinación, pérdida de tiempo y, en el caso de productos perecibles y medicamentos, riesgos de calidad. Además, es usual que los pedidos lleguen incompletos, con productos distintos a los solicitados o en mal estado por golpes o manipulación incorrecta durante el transporte, por lo que, sin un registro de evidencia fotográfica o de sensores, no se podría realizar el reclamo correspondiente al proveedor. Por consiguiente, brindar una solución eficiente a este problema, generaría una reducción en las pérdidas de productos.
  </div> <br>


- **Where:**
  <div align="justify">
   
  Se encuentra en bodegas y farmacias emprendedoras que se encuentren dentro del rango en ingresos y gestión de productos del NRUS como régimen tributario. Dichos emprendedores necesitan poder reducir brechas de tiempo y de accesibilidad en la gestión de sus productos por la poca calidad de software gratuitos y el precio de los mismos, sin posibilidad de ajustar sus necesidades a sus casos específicos. Dicho sector se encuentra entre los más solicitados por los emprendedores, ya que alínea las necesidades no genera costos exorbitantes por pertenecer a la misma. 
  
  También ocurre con trabajadores de las bodegas o farmacias, los cuales utilizan la infraestructura del negocio planteada previamente propuesta.

  </div>


- **When:**
  <div align="justify">
   
   Cuando un usuario que gestiona la bodega y farmacias se encuentra con propuesta de gestión de inventario robustas que sobrepasan su capacidad de inversión en las mismas, por lo que recurre a propuestas más económicas que no cumple con un buen estándar de optimización o directamente no las utiliza, lo que genera el uso de técnicas manuales.
   Luego, ocurre también con los trabajadores, aunque no sean mayoría. Según la SUNAT (2025), el NRUS permite como máximo en las bajas categorías unos 8.000 soles, por lo que en promedio para no sobrepasar costos, se tiene que considerar máximo 2 trabajadores. Ellos, se encargan en su mayoría de registrar los productos, para lo cual tienen que entender, de ser que un software se utilice, interfaces poco intuitivas y complejas debido a la poca inversión dedicada. Luego, de ser que no exista uno, se recurre a registros manuales, como tomar apuntas en una hoja o cuaderno, lo que da chance a más errores de registro. 

  </div>


- **Who:** <br/>
  <div align="justify">
    El problema afecta principalmente a dos perfiles de microempresarios en el sector de ventas minoristas:
  </div>
  <ul>
    <li>
      <div align="justify">
        El primer segmento objetivo son los bodegueros independientes. Este segmento está conformado por propietarios de bodegas o minimarkets que, por lo general, gestionan su negocio de forma manual o apoyándose en herramientas muy básicas. Estos emprendedores suelen manejar sus establecimientos de manera independiente o con el soporte de su familia, basando su administración diaria mayormente en métodos empíricos que resultan insuficientes para las demandas actuales del mercado.
      </div>
    </li>
    <br/>
    <li>
      <div align="justify">
        Como consecuencia de esta gestión tradicional, los bodegueros enfrentan desafíos críticos como el descontrol total de su stock, pérdidas económicas por productos vencidos y una falta de claridad sobre las ganancias reales obtenidas mes a mes. Ante esta situación, nuestro grupo busca una solución tecnológica que sea simple y accesible, permitiéndoles organizar mejor su negocio y optimizar su rentabilidad de manera intuitiva.
      </div>
    </li>
  </ul>

</div>

- **Why:** <br/>
  <div align="justify">
    La realidad del sector minorista en el Perú se caracteriza por una profunda brecha tecnológica y operativa que compromete la sostenibilidad de miles de microempresas. Según Romero (2024), de las más de 535,000 bodegas que operan a nivel nacional, apenas un 12 % había logrado adoptar herramientas digitales antes de la emergencia sanitaria, cifra que experimentó un retroceso debido a la inexistencia de soluciones adaptadas a la realidad técnica de estos negocios. Esta situación es crítica si se considera que el 70 % de estos establecimientos son gestionados bajo métodos estrictamente tradicionales y manuales, donde la administración diaria depende casi en su totalidad de la memoria del propietario o de registros informales en papel. Esta dependencia de sistemas no automatizados genera un entorno de ineficiencia operativa que no solo ralentiza la atención, sino que anula la capacidad de crecimiento y competitividad frente a las grandes cadenas de retail moderno.
  </div>
  <br/>
  <div align="justify">
    Este rezago digital tiene un impacto financiero directo y medible, especialmente en el manejo de inventarios críticos. De acuerdo con Mendoza y Anchiraico (2018), la ausencia de sistemas de gestión técnica en las boticas independientes es el detonante principal de los quiebres de stock y la baja rotación de productos, factores que merman severamente la rentabilidad anual del negocio. En este contexto, la falta de una trazabilidad precisa sobre las existencias no solo deriva en pérdidas económicas por mercadería vencida, sino que escala a un riesgo latente para la salud pública al no poder garantizar la integridad de los fármacos. Asimismo, Delgado y Lopez (2024) sostienen que una gestión deficiente incide negativamente en los márgenes de ganancia al generar costos ocultos por almacenamiento inadecuado y desperdicio de capital. Esta problemática se agrava por la incertidumbre constante en la cadena de suministro y la falta de monitoreo en tiempo real, manteniendo al pequeño empresario en un estado de vulnerabilidad financiera ante un mercado cada vez más automatizado.
  </div>
  <br/>

- **How:** <br/>
  <div align="justify">
  La ineficiencia operativa en bodegas y farmacias independientes se manifiesta a través de un flujo de trabajo fragmentado y empírico. Actualmente, la gestión de inventarios se ejecuta mediante registros manuales en cuadernos o hojas sueltas, lo que imposibilita una alerta temprana sobre fechas de vencimiento o niveles críticos de stock. Este proceso "analógico" provoca que el control dependa exclusivamente de la memoria del dueño, derivando en una fricción operativa constante.

  La problemática se agrava significativamente cuando el negocio cuenta con personal, ya que la ausencia de trazabilidad digital facilita conductas de riesgo. Al no existir un sistema de control que registre cada salida de producto o ingreso de dinero, el dueño pierde la capacidad de auditar las operaciones de sus empleados. Esto genera un entorno donde el personal puede manipular el stock, ocultar gastos o incurrir en "robos hormiga" sin ser detectados. Asimismo, se produce una confusión sistemática entre gastos personales y del negocio, donde la falta de una plataforma de auditoría impide supervisar efectivamente las transacciones de caja, permitiendo fugas de capital y una gestión de costos opaca.

  Por otro lado, la problemática logística ocurre por la opacidad en la comunicación con proveedores, interrumpiendo la atención al cliente para recibir pedidos sin una verificación técnica, y la gestión financiera se da por "bolsillo único", donde el flujo de caja personal se mezcla con el del negocio, impidiendo conocer el margen de ganancia real.
  </div>

- **How much:** <br/>
  <div align="justify">
  El impacto de esta problemática es crítico y medible tanto a nivel financiero como de mercado. A nivel macro, la falta de una gestión técnica contribuye a que el 40% de las microempresas en Perú cierren anualmente por insolvencia y mala administración de su liquidez (CCL, 2025). En el día a día, esta brecha tecnológica se traduce en pérdidas económicas directas que pueden representar entre el 10% y 15% del valor del inventario anual debido a productos vencidos o mermas logísticas.

  A esto se suma el impacto de la gestión negligente o malintencionada del personal: los costos ocultos por discrepancias de inventario, errores en el manejo de caja y la mezcla de gastos personales con los operativos, actúan como un factor silencioso que erosiona el margen de ganancia neto. Estas pérdidas, al no ser detectadas por un sistema de control centralizado, representan un "gasto fantasma" que acelera la insolvencia del establecimiento, impidiendo que el dueño tenga visibilidad real de cuánto dinero gana o pierde realmente.

  Desde la perspectiva del sector, el problema afecta a una escala masiva: el 88% de las más de 535,000 bodegas en el país operan en un estado de vulnerabilidad digital. Además, en el caso específico de las farmacias, el costo escala a un riesgo de salud pública, donde la falta de trazabilidad técnica pone en peligro la inocuidad de los medicamentos, exponiendo a los dueños a sanciones legales y multas que comprometen la continuidad de su patrimonio.
  </div>


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem statement 1:** <br>
Nuestro producto fue diseñado para optimizar la gestión de productos e inventario para micro empresas o emprendedores las cuales no poseen una ERP, donde les ofrecemos distintos tipos de planes que se adapten a sus necesidades particulares y con ello, optimicen costos por ganancia y tiempo invertido en el registro de los productos.

Hemos observado que estos negocios no están logrando una gestión adecuada del inventario, debido al uso de métodos manuales o herramientas digitales poco accesibles, complejas o costosas, que no cumplen con los requerimientos mínimos o los sobrepasan.

Esto genera pérdidas económicas por productos vencidos, errores en el registro de stock y falta de visibilidad sobre el estado real del negocio, lo que afecta directamente su rentabilidad y sostenibilidad.

Por tanto, nos preguntamos: ¿Cómo podríamos simplificar y hacer más accesible la gestión de inventario para estos microempresarios, de modo que reduzcan errores operativos y mejoren el control de su stock, medido a través de la disminución de pérdidas?

**Problem statement 2:** <br>
El producto que creamos fue diseñado para ayudar a los pequeños emprendedores da un sector retail minorista para optimizar la gestión de su inventario.
Con ello, hemos observado que los dueños y trabajadores de farmacias y tiendas pasan demasiado tiempo registrando salidas y entradas de productos, debido a las herramientas que no son fáciles de usar o por procedimientos manuales. Esto causa retrasos en la atención al cliente, equivocaciones en las transacciones y poco rendimiento de eficiencia en las actividades diarias de la empresa.

Por tanto, nos preguntamos: ¿Qué estrategias podemos emplear para agilizar los procesos de gestión y administración de un inventario, con el objetivo de reducir el tiempo invertido y mejorar la efectividad de operaciones?

#### 1.2.2.2. Lean UX Assumptions
<div align="Justify">

- **1. ¿Quién es el usuario?** <br/>
  
    Los usuarios de Qullqa principalmente son propietarios de bodegas y minimarkets independientes que gestionan sus negocios de forma empírica y manual, representando un sector donde el 70% de los dueños superan los 41 años. También se incluyen dueños de farmacias y boticas pequeñas que requieren un control técnico más estricto para evitar riesgos sanitarios y operativos.
  

- **2. ¿Dónde encaja nuestro producto en su trabajo o vida?** <br/>
  
    Qullqa se integra en el núcleo de la operación diaria del negocio. En las bodegas, sustituye el cuaderno de notas o la memoria del dueño por un centro de control digital para registrar ventas y stock en tiempo real. En las farmacias, se convierte en la herramienta de seguridad que monitorea la vigencia de los medicamentos. Además, facilita la recepción de mercadería al conectar la gestión del almacén con dispositivos IoT que rastrean el estado de las entregas.
  

- **3. ¿Qué problema tiene nuestro producto y cómo se puede resolver?** <br/>
  <ul>
    <li> 
      <b>Resistencia al cambio digital:</b> Muchos bodegueros temen la complejidad técnica. <b>Solución:</b> Una interfaz extremadamente simplificada y un proceso de acompañamiento inicial que no requiera conocimientos avanzados.
    </li>

    <li>
      <b>Costo de implementación:</b> Las MYPES suelen tener presupuestos limitados. <b>Solución:</b> Un modelo de precios escalonado (freemium) donde las funciones básicas sean accesibles para negocios muy pequeños.
    </li>

    <li>
      <b>Precisión de los datos IoT:</b> Fallos en la conectividad podrían generar desconfianza. <b>Solución:</b> Implementar un sistema de caché local para que la app funcione sin internet y sincronice datos apenas recupere la conexión.
    </li>

  </ul>

- **4. ¿Cuándo y cómo es usado nuestro producto?** <br/>
  
    Es una herramienta de uso constante: desde la apertura del local para verificar el inventario, durante todo el día para registrar cada venta, y al momento de recibir pedidos de proveedores para validar el ingreso de stock mediante sensores IoT. También se consulta el cierre de caja para visualizar el dashboard de ganancias netas y reportes de desempeño.
  

- **5. ¿Qué características son importantes?** <br/>
  <ul>
    <li><b>Gestión Inteligente de Inventario:</b> Registro automatizado de entradas, salidas y alertas de bajo stock.</li>
    <li><b>Notificaciones de Vencimiento:</b> Alertas proactivas para evitar pérdidas por productos caducados.</li>
    <li><b>Módulo IoT de Seguimiento:</b> Monitoreo de seguridad para productos en tránsito hacia el negocio.</li>
    <li><b>Dashboards Financieros:</b> Visualización clara de ventas y rentabilidad real mes a mes.</li>
  </ul>
</div>

- **6. ¿Cómo debe verse nuestro producto y cómo comportarse?** <br/>
  <div align="justify">
    Debe ser limpio, rápido y de alto contraste, facilitando la lectura para usuarios mayores que operan en entornos de iluminación variable. El comportamiento debe ser predictivo; por ejemplo, sugerir la reposición de un producto antes de que se agote basándose en patrones de venta previos.
  </div>
  <br/>

- **Business Outcomes:** <br/>
  <ul>
    <li>
    Posicionamiento como la plataforma de gestión para MYPES líder en el mercado peruano.</li>
    <li>Generación de ingresos mediante planes premium para funciones avanzadas de análisis de datos e integración IoT.</li>
    <li>Reducción del 20% en las pérdidas por productos vencidos en los negocios afiliados.</li>
    <li>Alianzas estratégicas con proveedores mayoristas para integrar sus catálogos directamente en la app.</li>
  </ul>

- **User Outcomes:** <br/>
  <ul>
    <li><b>Claridad financiera:</b> El usuario conoce exactamente cuánto dinero gana y qué productos son los más rentables.</li>
    <li><b>Ahorro de tiempo:</b> Reducción del tiempo dedicado a inventarios manuales de horas a solo minutos.</li>
    <li><b>Seguridad:</b> Mayor confianza al recibir mercadería gracias al rastreo IoT.</li>
    <li><b>Reducción de riesgos:</b> Eliminación de multas o riesgos sanitarios por venta de productos vencidos en farmacias.</li>
  </ul>

- **Features:** <br/>
  <ul>
    <li><b>Dashboard de Inventario:</b> Panel visual con estados de stock (disponible, crítico, agotado).</li>
    <li><b>Sistema de Alertas:</b> Notificaciones push y correos sobre vencimientos próximos.</li>
    <li><b>Integración con Sensores IoT:</b> Conexión con hardware para el seguimiento de entregas en tiempo real.</div></li>
    <li><b>Registro de Ventas POS:</b> Interfaz táctil rápida para facturación y boleteo.</li>
    <li><b>Reportes de Rentabilidad:</b> Gráficos automáticos de ingresos vs. egresos mensuales.</li>
  </ul>
</div> 


#### 1.2.2.3. Lean UX Hypothesis Statements
<div align="justify">

**Hypothesis Statement 1** <br>
Creemos que simplificar y hacer más accesible la gestión de inventario mediante una plataforma intuitiva permitirá a los microempresarios reducir errores operativos y mejorar el control de su stock. Sabremos que esto es cierto cuando veamos que las pérdidas por productos vencidos se reducen en al menos un 50%, y la precisión del inventario aumenta hasta un 90% o más.

**Hypothesis Statement 2** <br>
Creemos que implementar herramientas que agilicen el registro de entradas y salidas de productos permitirá a los usuarios reducir el tiempo invertido en la gestión del inventario. Sabremos que esto es cierto cuando veamos que el tiempo promedio de registro de productos se reduce en al menos un 60%, y la eficiencia en la atención al cliente mejora en un 40%.

#### 1.2.2.4. Lean UX Canvas
<div>
  <img src="assets/img/artefacts/lean_ux_canvas(v2).png" alt="Foto Lean UX Canvas (V2)" width="1000"/>
</div>

## 1.3. Segmentos objetivo

- **Bodegueros independientes** <br>
Propietarios de bodegas o minimarkets que gestionan su negocio de forma manual o con herramientas básicas. Presentan problemas como descontrol del stock, pérdidas por productos vencidos y falta de claridad sobre sus ganancias mes a mes. Buscan una solución simple y accesible para organizar mejor su negocio

- **Farmacias independientes** <br>
Pequeñas farmacias que requieran un control más riguroso del inventario, especialmente en fechas de vencimiento y disponibilidad de medicamentos. Necesitan herramientas más confiables que les permitan reducir riesgos, evitar pérdidas y asegurar un mejor control operativo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En esta sección se realiza la identificación y descripción de los principales competidores directos, los cuales ofrecen soluciones digitales enfocadas en la gestión de inventarios y operaciones comerciales, similares a la propuesta de valor de Qullqa.

- **Spry Sales** <br>
  Plataforma digital peruana enfocada en la gestión de ventas e inventario para pequeños y medianos negocios. Su propuesta se centra en simplificar el control de stock, registro de productos y seguimiento de ventas en tiempo real, permitiendo a los emprendedores tener una mejor visibilidad de su negocio. Ofrece funcionalidades como control de inventario, reportes básicos, gestión de clientes y ventas desde dispositivos móviles. Su principal fortaleza radica en su enfoque local y facilidad de uso; sin embargo, presenta limitaciones en cuanto a escalabilidad, automatización avanzada y personalización profunda de procesos, lo que puede restringir su adopción en negocios en crecimiento.

- **Zoho Inventory** <br>
  Solución global de gestión de inventario basada en la nube que permite a empresas gestionar pedidos, controlar stock, automatizar procesos y administrar múltiples canales de venta. Se integra con otras herramientas del ecosistema Zoho y plataformas externas como e-commerce y marketplaces, ofreciendo funcionalidades avanzadas como gestión de órdenes, seguimiento de envíos y reportes detallados. Su modelo de negocio se basa en suscripciones por niveles. Aunque es altamente robusto y escalable, su complejidad y costo pueden resultar poco accesibles para microempresarios o pequeños negocios que buscan soluciones más simples y económicas.

- **Odoo Inventory** <br>
  Parte del ecosistema ERP de Odoo, una plataforma modular que permite gestionar inventarios, logística, compras y ventas de manera integrada. Ofrece funcionalidades avanzadas como trazabilidad de productos, gestión de almacenes, automatización de reabastecimiento y control en tiempo real. Su principal ventaja es la integración con múltiples módulos empresariales (contabilidad, CRM, ventas, etc.), lo que permite una gestión completa del negocio. No obstante, su implementación puede ser compleja y requiere cierto nivel técnico o inversión en configuración, lo cual puede representar una barrera para microempresas o usuarios sin experiencia en sistemas ERP.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="6" align="left">Competitive Analysis Landscape</th>
  </tr>

  <tr>
    <td><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5">
      Con el fin de identificar oportunidades de diferenciación, fortalezas clave y posibles debilidades. Esto permitirá definir una ventaja competitiva clara orientada a microempresarios y negocios pequeños que requieren soluciones accesibles, simples y eficientes.
    </td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th>Qullqa</th>
    <th>Spry Sales</th>
    <th>Zoho Inventory</th>
    <th>Odoo Inventory</th>
  </tr>

  <!-- PERFIL -->
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>Plataforma de gestión de inventario simple y accesible enfocada en microempresas (bodegas y farmacias).</td>
    <td>Sistema de ventas e inventario enfocado en pequeños negocios peruanos.</td>
    <td>Software global de inventario en la nube con múltiples integraciones.</td>
    <td>Módulo ERP completo para gestión empresarial integral.</td>
  </tr>

  <tr>
    <td><b>Ventaja competitiva</b></td>
    <td>Simplicidad, bajo costo y enfoque específico en microempresarios con problemas reales de inventario.</td>
    <td>Fácil uso y enfoque local adaptado a pequeños negocios.</td>
    <td>Alta automatización e integración con múltiples plataformas.</td>
    <td>Integración total con otros módulos empresariales (ERP).</td>
  </tr>

  <!-- PERFIL DE MARKETING -->
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>Bodegueros y farmacias independientes.</td>
    <td>Pequeños negocios y emprendedores locales.</td>
    <td>PYMES y empresas en crecimiento.</td>
    <td>Empresas medianas y grandes con procesos complejos.</td>
  </tr>

  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>Enfoque en educación digital, redes sociales y validación con usuarios reales.</td>
    <td>Marketing digital local y enfoque en emprendedores.</td>
    <td>Estrategia global, contenido educativo y ecosistema SaaS.</td>
    <td>Marketing basado en soluciones empresariales integradas.</td>
  </tr>

  <!-- PERFIL DE PRODUCTO  -->
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos & Servicios</b></td>
    <td>Gestión de inventario, alertas de vencimiento, control de stock, reportes simples.</td>
    <td>Control de ventas, inventario y clientes.</td>
    <td>Gestión de pedidos, inventario, envíos y reportes avanzados.</td>
    <td>Gestión de almacenes, trazabilidad, compras, ventas y más.</td>
  </tr>

  <tr>
    <td><b>Precios & Costos</b></td>
    <td>Modelos de suscripción y un plan gratuito siendo accesible para las microempresas.</td>
    <td>Suscripción accesible.</td>
    <td>Planes por suscripción (más costosos).</td>
    <td>Costos variables según módulos e implementación.</td>
  </tr>

  <tr>
    <td><b>Canales de distribución</b></td>
    <td>Web y móvil (enfocado en facilidad de acceso).</td>
    <td>Web y móvil.</td>
    <td>Web (cloud-based).</td>
    <td>Web (cloud y on-premise).</td>
  </tr>

  <!-- ANÁLISIS SWOT -->
  <tr>
    <td rowspan="4"><b>Análisis SWOT</b></td>
    <td><b>Fortalezas</b></td>
    <td>Enfoque específico en microempresas, facilidad de uso y bajo costo accesible.</td>
    <td>Adaptación al mercado local, interfaz simple.</td>
    <td>Alta integración con otras herramientas, funcionalidades avanzadas.</td>
    <td>Sistema ERP completo, alta personalización.</td>
  </tr>

  <tr>
    <td><b>Debilidades</b></td>
    <td>Menor reconocimiento de marca, funcionalidades limitadas en etapas iniciales.</td>
    <td>Limitada escalabilidad, pocas funcionalidades avanzadas.</td>
    <td>Complejidad para usuarios básicos, costos relativamente altos.</td>
    <td>Complejidad de implementación, requiere conocimientos técnicos.</td>
  </tr>

  <tr>
    <td><b>Oportunidades</b></td>
    <td>Alto número de negocios informales sin sistemas digitales, crecimiento de la digitalización en pequeños negocios.</td>
    <td>Crecimiento de emprendedores digitales.</td>
    <td>Expansión de negocios digitales globales.</td>
    <td>Empresas que buscan soluciones integrales.</td>
  </tr>

  <tr>
    <td><b>Amenazas</b></td>
    <td>Competidores consolidados con más recursos, resistencia al cambio tecnológico.</td>
    <td>Competidores más robustos.</td>
    <td>Soluciones más simples y económicas.</td>
    <td>Alternativas más simples para pequeños negocios.</td>
  </tr>

</table>

### 2.1.2. Estrategias y tácticas frente a competidores

### **Spry Sales** 
Es una solución peruana de gestión comercial y facturación electrónica diseñada específicamente para micro y pequeñas empresas (MYPE). Se especializa en digitalizar negocios tradicionales como bodegas, farmacias y ferreterías, integrando la normativa de la SUNAT.
<http://www.spry.pe/>

##### **Características Principales**
* **Gestión de Inventario Local:** Permite el control de stock en tiempo real, alertas de stock mínimo y, crucial para farmacias, el seguimiento de fechas de vencimiento.
* **Cumplimiento Fiscal:** Generación automática de boletas y facturas electrónicas integradas directamente con los sistemas de la SUNAT.
* **Movilidad y Punto de Venta (POS):** Incluye una aplicación móvil que permite realizar ventas y arqueos de caja desde cualquier lugar, ideal para negocios con despacho o preventa.
* **Reportes de Rentabilidad:** Genera informes diarios de ganancias y egresos, facilitando la visión financiera del dueño del negocio.

##### **Estructura de Planes**

| Plan | Descripción / Enfoque | Costo |
| :--- | :--- | :--- |
| **Basico : Inicia** | Control basico en la app sin acceder a stock, almacen y otras funcionalidades | 49.90$ |
| **Emprendedor : Arranca** | Integracion de funcionalidades de almacen y reportes | 79.90$ |
| **Empresarial : Vuela** | Auditorías estrictas de inventario, credito y cobranzas | 99.90$ |
---

##### **FODA respecto a SPRY**

| Categoría | Análisis de Spry Sales |
| :--- | :--- |
| **Fortalezas** | Cumplimiento nativo con SUNAT; marca establecida en el sector MYPE peruano. |
| **Oportunidades** | Crecimiento de la formalización de bodegas en provincias. |
| **Debilidades** | Interfaz de usuario (UI) anticuada; soporte técnico estandarizado y poco personalizado. |
| **Amenazas** | Aparición de soluciones con mejor diseño y mayor automatización. |
--

###### **Conexión Estratégica:**
* La estrategia de diferenciación ataca directamente la Debilidad de su interfaz rígida. Al detectar que el usuario valora la fluidez, la táctica de soporte proactivo transforma la amenaza de un competidor establecido en una oportunidad para captar a clientes insatisfechos con el trato impersonal de Spry.

##### **Estrategia respecto a Spry**
* Diferenciación por UX (Experiencia de Usuario). Spry es funcional pero su interfaz puede sentirse rígida.
* Especialización Técnica y Preventiva.
##### **Tactica respecto a Spry**
* Ofrece una interfaz más limpia e intuitiva que requiera menos clics para el ingreso de productos. Angelica prefiere un sistema por un año para ver errores, ofrécerle un soporte proactivo que Spry no suele dar a nivel personal. Ademas, el coste que piden respecto a porcentaje de funcionalidades que ofrece es muy dispareja lo que nos permite consolidarnos como una opcion mas amigable con el usuario.
* Sistema de notificaciones vía WhatsApp o correo que avise a la dueña 30, 60 y 90 días antes de que un lote de medicamentos venza, sugiriendo promociones automáticas para liquidar ese stock antes de que sea pérdida total.
<br></br>

### **Zoho Inventory**
**Perfil de la Empresa:** Es una plataforma global de gestión de inventarios basada en la nube, parte del ecosistema Zoho. Se destaca por su capacidad de integración con plataformas de e-commerce y su robustez para empresas en crecimiento que buscan automatización.
<https://www.zoho.com/inventory/>

##### **Características Principales**
* **Seguimiento de Lotes y Series:** Facilita el rastreo de medicamentos mediante números de lote y series, lo cual es fundamental para el cumplimiento de normativas de salud.
* **Integración Multicanal:** Sincroniza inventarios automáticamente con tiendas online como Shopify, Amazon o Mercado Libre.
* **Gestión de Almacenes:** Permite transferencias de stock entre múltiples depósitos y el seguimiento de pedidos desde el embalaje hasta la entrega.
* **Automatización de Reorden:** Configuración de puntos de pedido automáticos que notifican cuando un producto está por agotarse.

##### **Valor Agregado**

| Plan | Descripción / Enfoque | Costo |
| :--- | :--- | :--- |
| **Standard** | 500 orders/month / 2 users / 2 locations | 29$ |
| **Professional** | 3000 orders/month / 2 users / 4 locations | 79$ |
| **Premium** | 7500 orders/month / 2 users / 6 locations / 2000 bins/location | 129$ |
| **Enterprise** | 15000 orders/month / 7 users / 10 locations / 5000 bins/location | 249$ |
---

##### **FODA respecto a ZOHO**

| Categoría | Análisis de Zoho Inventory |
| :--- | :--- |
| **Fortalezas** | Automatización de procesos de alto nivel; integración con e-commerce global. |
| **Oportunidades** | Auge de farmacias que buscan vender por canales digitales (Marketplaces). |
| **Debilidades** | Curva de configuración alta; falta de campos específicos para la normativa de salud peruana. |
| **Amenazas** | Cambios regulatorios locales que Zoho no implemente a tiempo. |

###### **Conexión Estratégica:**
* La estrategia de Localización Extrema se construye sobre la Debilidad de Zoho de ser un software "genérico". La táctica del botón de "Reporte DIGEMID" resuelve la frustración de usuarios (como el caso de Angélica) que pierden tiempo configurando herramientas globales, convirtiendo la robustez de Zoho en una desventaja frente a la agilidad de Qullqa.

##### **Estrategia respecto a Zoho**
* Localización y cumplimiento legal específico. Zoho es potente pero no maneja las particularidades de DIGEMID o normativas de salud peruanas nativamente.
* Reportes legales asistidos.
##### **Tactica respecto a Zoho**
* Incluye de fábrica los campos legales necesarios para la venta de medicamentos en Perú que Zoho obligaría a configurar manualmente, un proceso que Angelica menciono era una de las cosas que mas detestaba debido a la perdida de tiempo y lo tedioso de hacerlo.
* Botón de "generar reporte para inspección" que exporte exactamente los formatos que pide la DIGEMID.
<br></br>

### **Odoo Inventory**
**Descripción General:** Es un módulo dentro del ERP de código abierto Odoo. Su gran fortaleza es la trazabilidad total y la modularidad, permitiendo que una farmacia crezca desde un simple inventario hasta una gestión contable y de compras compleja.
<https://www.odoo.com/app/inventory>

#### **Pilares Estratégicos**
* **Inventario de Doble Entrada:** Utiliza un sistema único donde no hay "salidas" de stock, sino "movimientos" entre ubicaciones, garantizando una trazabilidad del 100%.
* **Personalización Extrema:** Al ser modular, permite añadir campos específicos para farmacias (como registros sanitarios o composiciones químicas) mediante su herramienta Studio.
* **Reportes Avanzados:** Ofrece tableros en tiempo real con rotación de inventario, valoración de stock (FIFO/FEFO) y predicciones de demanda.
* **Trazabilidad FEFO:** Prioriza la salida de productos con fecha de vencimiento más próxima (First Expired, First Out), esencial para productos farmacéuticos.

#### **Resumen de Valor**

| Enfoque | Objetivo Principal |
| :--- | :--- |
| **App Free** | Una aplicación sin límite de usuarios Odoo en línea |
| **Estándar** | Todas las aplicaciones Odoo en línea |
| **Personalizado** | Todas las aplicaciones del sistema|
---

##### **FODA respecto a ODOO**

| Categoría | Análisis de Odoo Inventory |
| :--- | :--- |
| **Fortalezas** | Gestión de vencimientos impecable; sistema modular altamente escalable. |
| **Oportunidades** | Negocios que planean expandirse a múltiples sucursales rápidamente. |
| **Debilidades** | Costo de implementación elevado; requiere capacitación técnica para el usuario final. |
| **Amenazas** | Versiones gratuitas (Open Source) que pueden ser configuradas por terceros. |

###### **Conexión Estratégica:**
* La estrategia de simplicidad sadical responde a la Debilidad de la complejidad de Odoo. Mientras Odoo ofrece un sistema difícil de maniobrar, Qullqa ofrece una interfaz rápida. La táctica del Dashboard simplificado permite que el dueño del negocio se enfoque en la operación diaria, evitando el "parálisis por análisis" que generan los sistemas modulares pesados.

##### **Estrategia respecto a Odoo**
* Enfoque en Cero curva de aprendizaje, simplicidad radical y costo de Implementación.
* Simplicidad Radical y Costo de Implementación.
##### **Tactica respecto a Odoo**
* Posiciona a Qullqa como la solución "todo en uno pero simplificada". Mientras Odoo requiere consultoría para implementarse, tu sistema debe estar listo para usarse intuitivamente. De manera que al usuario se le acompañe en las funcionalidades generales y este cree rutas de uso rapido de manera empirica con el uso de la app.
* Dashboard ultra-simplificado diseñado para tablets, donde en una sola pantalla se vea: stock crítico, ventas del día y próximos vencimientos. Menos es más para un dueño de negocio que también atiende en el mostrador.
<br></br>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se presenta el diseño de las entrevistas dirigidas a los segmentos objetivos, con el propósito de recolectar información relevante que permita comprender sus necesidades, comportamientos y problemáticas. Para ello, se han formulado preguntas principales y complementarias que guían la conversación, asegurando la obtención de datos tanto generales como específicos.

**Preguntas complementarias:**
- ¿Cuál es su edad?
- ¿En qué distrito reside actualmente?
- ¿Cuál es su estado civil?
- ¿A qué se dedica?
- ¿Qué fue lo que le inspiró a abrir su negocio?
- ¿Qué habilidades considera que son más sobresalientes en usted?
- ¿Qué canales usa para comunicarse con sus clientes?
- ¿Cuál es su objetivo como bodeguero/dueña de farmacia respecto a ventas y gestión de su  negocio?
- ¿Tiene alguna frustración respecto al manejo de su inventario?

**Preguntas principales** <br>
- Segmento Objetivo 1: (Bodegueros independientes)
  - ¿Cómo es su rutina desde que llega la primera mercadería del día hasta que cierra la reja de la bodega?
  - ¿Qué aplicaciones usa más en su día a día (WhatsApp para pedidos, Facebook, apps de bancos o alguna de delivery)?
  - ¿Cómo anota o registra los productos que le traen los proveedores? ¿Usa cuaderno, Excel o confía en su memoria?
  - ¿Qué hace usted cuando nota que un producto está por vencer y todavía tiene varias unidades en el estante?
  - ¿Cuál es el mayor problema que enfrenta actualmente al manejar su inventario?
  - ¿Ha tenido pérdidas por productos vencidos o falta de stock? ¿Cómo suele manejar esas situaciones?
  - ¿Cómo calcula sus ganancias diarias o mensuales? ¿Le resulta fácil o complicado? 
  - Si tuviera que contratar a un ayudante, ¿qué información del negocio le permitiría ver y qué cosas preferiría manejar solo usted?
  - Si existiera una aplicación que le ayude a controlar su inventario y ventas de manera sencilla, ¿la usaría? ¿por qué?
  - ¿Qué le podría generar dificultades al usar una aplicación para gestionar su negocio?

- Segmento Objetivo 2: (Farmacias independientes)
  - ¿Cómo es el proceso desde que un proveedor llega hasta que el producto está disponible para la venta?
  - ¿Qué herramientas o aplicaciones utilizas en tu día a día para gestionar la farmacia?
  - ¿Cómo registras los productos que ingresan a la farmacia?
  - ¿Cómo controlas las fechas de vencimiento de los medicamentos? Cuáles son sus métodos para prevenirlo? 
  - ¿Cuál es el mayor problema que enfrentas al manejar tu inventario?
  - ¿Has tenido pérdidas por vencimientos o falta de stock? ¿Cómo las manejas?
  - ¿Cómo haces el seguimiento de tus ventas o ganancias?
  - ¿Qué información le gustaría tener para decidir qué productos comprar más o dejar de vender?
  - ¿Qué tarea te quita más tiempo en el día y te gustaría automatizar?
  - Si existiera una aplicación que te ayude a controlar inventario, vencimientos y ventas, ¿la usarías? ¿Qué te preocuparía o dificultaría al usarla?
  - ¿Cómo categorizan los productos?


### 2.2.2. Registro de entrevistas

**PRIMER SEGMENTO OBJETIVO (BODEGUEROS INDEPENDIENTES)**

<u>Entrevista 1:</u>

Entrevistador: Fernando Julio Güere Calero

Datos del entrevistado

- **Nombre:** Raul
- **Apellidos:** Gimenez
- **Edad:** 61 años
- **Distrito:** Chaclacayo
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Raul_Segmento1.png" alt="Entrevista con Raul Gimenez" width="500"/>
  <br/><i>Evidencia de entrevista: Raul Gimenez</i>
</p>

**Resumen descriptivo:**
<div align="justify">
Es un emprendedor de tercera generación. Gestiona su inventario de forma manual con cuadernos y su principal frustración es la presión de la SUNAT y la municipalidad. Aunque usa Yape y aplicaciones de proveedores, teme que las apps de gestión "encadenen" sus datos. Busca un punto de venta (POS) sencillo que no restrinja el acceso a su información histórica.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413169_upc_edu_pe/IQCNzoA_BvcPRJP9Baxc_4mKAVFCGG13ZxRKSkL4itnHBLA?e=mPE13c&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


<u>Entrevista 2:</u>

Entrevistador: Fernando Julio Güere Calero

Datos del entrevistado

- **Nombre:** Jimmy
- **Apellidos:** Viera
- **Edad:** 28 años
- **Distrito:** Chaclacayo
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Jimmy_Segmento1.png" alt="Entrevista con Jimmy Viera" width="500"/>
  <br/><i>Evidencia de entrevista: Jimmy Viera</i>
</p>

**Resumen descriptivo:**
<div align="justify">
Estudiante que apoya en el negocio familiar. Confía principalmente en su memoria para el inventario, lo que resulta tedioso al trabajar con más personas. Utiliza aplicaciones de proveedores para pedidos pero critica la falta de flexibilidad en los horarios de entrega. Considera que una app de gestión le facilitaría mucho el control de stock y la comunicación.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413169_upc_edu_pe/IQCeSnkB2TLFSYasRy9oINIGAd67FUgsN5274thKlHodem0?e=GaLWEi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


<u>Entrevista 3:</u>

Entrevistador: Arturo Valentino Contreras Torres

Datos del entrevistado

- **Nombre:** Ruben
- **Apellidos:** De la Cruz
- **Edad:** 53 años
- **Distrito:** Comas
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Ruben_Segmento1.png" alt="Entrevista con Ruben de la Cruz" width="500"/>
  <br/><i>Evidencia de entrevista: Ruben de la Cruz</i>
</p>

**Resumen descriptivo:**

<div align="justify">
El señor Rubén, dueño de una bodega con dos años de funcionamiento, gestiona su negocio de manera manual. Registra la mercadería en un cuaderno mientras atiende a los clientes, y se comunica con proveedores mediante WhatsApp. El control de inventario lo realiza físicamente, revisando constantemente el almacén para evitar productos vencidos, ya que no todos los proveedores aceptan cambios. Aunque las pérdidas por vencimiento no son frecuentes, sí afectan sus ingresos. Además, lleva un control básico de sus ganancias, sin tener claridad total sobre su rentabilidad. Si bien le interesa la idea de usar un sistema digital, percibe estas herramientas como difíciles de aprender y costosas, lo que le genera desconfianza y limita su adopción.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414802_upc_edu_pe/IQAwnxxLJTtrS6U2w2slSTN8AfUZdIlp36-Q1lKlwXCfn68?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fv17HA)

<br>

**SEGUNDO SEGMENTO OBJETIVO (FARMACIAS INDEPENDIENTES)**

<u>Entrevista 1:</u>

Entrevistador: Martin Alejandro Asmat Alminco 

Datos del entrevistado

- **Nombre:** Pedro Pablo 
- **Apellidos:**  Aguilar Noquez
- **Edad:** 55
- **Distrito:** Lima 
- **Timing:**

<p align="center">
  <img src="assets/img/Entrevistas/entrevista-pablo.png" alt="Entrevista con Pablo Aguilar" width="500"/>
  <br/><i>Evidencia de entrevista: Pablo Aguilar </i>
</p>

**Resumen descriptivo:**

El entrevistado Pablo Aguilar, es un administrador que lleva ejerciciendo su labor por aproximadamente 8 años. Considera que en el negocio es importante el uso de herramientas externas como calculadora o también el uso de un pequeño sistema. El conteo de productos lo gestiona acordemente con la llegada de pedidos y lo coordina con los trabajadores y el gerente. Luego, ve pertinente una funcionalidad que gestione le vencimiento de medicamentos y ciertas herramientas que ayuden con el apartado de pagos, ya que en caja suelen tener problemas de tiempo donde no cuentan con la tecnología adecuada para una óptima atención. 


***Enlace del video:***[Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416272_upc_edu_pe/IQApqvIQKAp9So3sO81gGlleAXXLnRJuWysvvT7iDuDZa60?e=f7PKe4)


<u>Entrevista 2:</u>

Entrevistador: Aldo Jesus Huaman Oscco

Datos del entrevistado

- **Nombre:** Angelica Sonia 
- **Apellidos:** Rojas Navarro
- **Edad:** 45
- **Distrito:** Pachacamac
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Angelica.png" alt="Entrevista con Angelica Rojas" width="500"/>
  <br/><i>Evidencia de entrevista: Angelica Rojas</i>
</p>

**Resumen descriptivo:**
<div align="justify">
La entrevistada, Angélica Rojas, es una farmacéutica que ha heredado el negocio de su familia y se dedica a continuar con las labores de atención en la farmacia local. Nos comenta que, al ser un negocio familiar, se vio influenciada a estudiar Farmacia para poder seguir con las actividades del negocio Asimismo, nos habla sobre la importancia de tener sistemas que gestionen el ingreso de productos para la logística interna, lo cual le permitiría monitorear ingresos y egresos; esto es vital también por el marco legal, al tratarse de productos de salud vendidos directamente al público. Finalmente, menciona que, en caso de probar un sistema, su preferencia sería un plazo anual para poder evaluar las funcionalidades y los posibles errores del software.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231h067_upc_edu_pe/IQDrNip7FRbETrfjdFNrZgaVAZn8UuX_zQCE4gZBN_hkycU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=vL2i7Z)

<br>


<u>Entrevista 3:</u>

Entrevistador: Adriana Nicole Ramos Fuentes Rivera

Datos del entrevistado

- **Nombre:** María Genoveva
- **Apellidos:** Mariños Robles
- **Edad:** 49
- **Distrito:** Comas
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Maria_Segmento2.png" alt="Entrevista con María Mariños" width="500"/>
  <br/><i>Evidencia de entrevista: María Mariños</i>
</p>

**Resumen descriptivo:**

<div align="justify">
  La señora Maria Mariños, quien es dueña de una farmacia, menciona en la entrevista que gestiona su inventario y venta de productos por medio de un cuaderno, y esta información, la pasa a un Excel posteriormente. Además, indica que el mayor problema al que se enfrenta es el inventario, puesto que le toma demasiado tiempo realizar y suele ser una actividad consecutiva. Por otro lado, respecto a la ganancia por producto, lo calcula de una forma básica, por lo que desconoce de la rentabilidad de su negocio. Por ultimo, menciona que le gustaría obtener un sistema que le permita mejorar, principalmente, la gestion de su inventario, pero que la adquisición de este producto depende de su precio.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202018427_upc_edu_pe/IQC4-_ubbFf6Q7HKqdCr4uCQAXuOPh_nO3Spldu0g0S0dUY?e=Rcjs2n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


### 2.2.3. Análisis de entrevistas

El 100% de los entrevistados consideran que deben mantener como información privada, su dinero ingresado de la bodega. Ello incluye al personal que trabaja con ellos a pesar de poder llevar cierto tipo de conteo o caja registradora. 

El 75% de los entrevistados realizan algún tipo de apunte manual para el control de inventario o apuntes momentáneos para el monitereo de productos.

El 100% de los entrevistados siempre recibe inmediatamente a los proveedores a pesar de estar en proceso de atención con un cliente para luego poder desplegarlos lo antes posible y coordinarse con otros trabajadores de ser que hubieran.

El 50% de los entrevistados consideran relevante la comunicación con los trabajadores, especialmente los proveedores con lo que gestionan la venta de productos en la bodega. Es probable que alguna falla haya y ello genere confusión en la entrega de productos. 

El 100% de los entrevistados rematan o promocionana sus productos cuando la fecha de vencimiento se acerca, pero luego solo el 25% de de estos, cuando se les logra vencer el producto... desisten e intentan pedir cambio de producto al proveedor. 

El 100% de los usuarios entrevistados consideran una buena idea una aplicación que agilice sus procesos de control de inventario y mayor seguimiento de productos, para que a futuro se ahorren costos. 

El 75% de los entrevistados considera pertinente algún tipo de orientación o guia sobre el uso de una aplicación que se encargue de una gestión de inventario aceptable. 

El 50% mencióno que solo delegería gente de mucha confianza para tener trabajadores que agilicen el proceso de atención a los clientes.

El 100% mencionó que un problema grave con respecto a la atención es la rapidez con la cual se antiende. Se señala que se pierden potenciales clientes que intentan ser antendidos rápdiamente, pero al ser atendidos en orden y de forma manual, no es viable en muchos casos. 

EL 33% mencionó que ya tiene un programa preestablecido para su negocio pero que no cuenta con la funcionalidad de gestión de fecha de vencimiento, que es con lo que mayores problemas tienen en términos de optimización e inversión recuperable. 

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección se presentan los User Personas construidos a partir del análisis de entrevistas a bodegueros y farmacias independientes. Estos perfiles representan sus necesidades, comportamientos y dificultades en la gestión de inventario, permitiendo orientar el diseño de Qullqa hacia soluciones simples, prácticas y adaptadas a su realidad.

**PRIMER SEGMENTO OBJETIVO**

<img src="assets/img/artefacts/carlos_mendoza_segmento1_userpersona.png" width="500"/>

<br>

**SEGUNDO SEGMENTO OBJETIVO**

<img src="assets/img/artefacts/carmen_rojas_segmento2_userpersona.png" width="500"/>

### 2.3.2. User Task Matrix

<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; text-align: center; width: 100%;">
    <thead style="background-color: #f2f2f2;">
        <tr>
            <th rowspan="2">Tasks</th>
            <th colspan="2">Bodegueros independientes (Carlos Mendoza)</th>
            <th colspan="2">Farmacias independientes (Carmen Rojas)</th>
        </tr>
        <tr>
            <th>Frecuencia</th>
            <th>Importancia</th>
            <th>Frecuencia</th>
            <th>Importancia</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Registrar un nuevo producto</td>
            <td>Siempre</td>
            <td>Alta</td>
            <td>Siempre</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Hacer conteo de stock</td>
            <td>Siempre</td>
            <td>Alta</td>
            <td>A veces</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Supervisar fecha de vencimiento</td>
            <td>Siempre</td>
            <td>Alta</td>
            <td>Siempre</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Reportar pago realizado por un cliente</td>
            <td>A veces</td>
            <td>Baja</td>
            <td>A veces</td>
            <td>Media</td>
        </tr>
        <tr>
            <td>Consultar ingresos semanales o mensuales</td>
            <td>Siempre</td>
            <td>Alta</td>
            <td>Siempre</td>
            <td>Media</td>
        </tr>
        <tr>
            <td>Realizar promociones de productos</td>
            <td>A veces</td>
            <td>Media</td>
            <td>A veces</td>
            <td>Media</td>
        </tr>
    </tbody>
</table>

<p align = "center"> </p>

De las actividades recopiladas del primer segmento de bodegueros independientes, se obtiene que la actividad con mayor frecuencia que se realiza es la supervisión de productos 

vencidos debido a la gran pérdida que estas generan, luego, lógicamente la otra actividad más frecuente es el registro de un nuevo producto en la bodegua, así como también recibir stock de un proveedor. 

### 2.3.3. User Journey Mapping

<div align="justify">
  En esta sección se presentan los User Journey Maps elaborados a partir de los user persona por cada segmento. Estos mapas describen la experiencia actual del usuario en la gestión diaria de su negocio, identificando sus acciones, pensamientos, emociones y principales dificultades a lo largo del proceso. Asimismo, permiten visualizar los puntos de contacto y los pain points más relevantes, con el fin de detectar oportunidades de mejora que orienten el diseño de Qullqa hacia soluciones simples, prácticas y alineadas a su realidad.
</div>

<br>

**Primer segmento objetivo: Bodegueros Independientes**
<p align="center">
  <img src="assets/img/artefacts/user_journey_map_carlos_mendoza.png" width="500" alt="User Journey Map - Carlos Mendoza"/>
  <br/><i>Artefacto: User Journey Map basado en el user persona Carlos Mendoza.</i>
</p>

**Segundo segmento objetivo: Farmacias Independientes**
<p align="center">
  <img src="assets/img/artefacts/user_journey_map_carmen_rojas.png" width="500" alt="User Journey Map - Carmen Rojas"/>
  <br/><i>Artefacto: User Journey Map basado en el user persona Carmen Rojas.</i>
</p>

### 2.3.4. Empathy Mapping

<div align="justify">
El Empathy Mapping es un artefacto visual que permite profundizar en la comprensión de los usuarios, analizando lo que oyen, ven, dicen y hacen, además de sus dolores y ganancias. En el desarrollo de Qullqa, esta técnica es fundamental para transformar observaciones en insights accionables, garantizando que cada funcionalidad de la plataforma responda directamente a las experiencias emocionales y operativas reales de los dueños de negocios independientes.
</div>
<br/>

**Primer segmento objetivo: Bodegueros Independientes**
<p align="center">
  <img src="assets/img/artefacts/Empathy_map_Carlos_Mendoza.png" width="500" alt="Empathy Map - Carlos Mendoza"/>
  <br/><i>Artefacto 1: Mapa de empatía basado en el perfil del bodeguero tradicional.</i>
</p>

<br/>

**Segundo segmento objetivo: Farmacias Independientes**
<p align="center">
  <img src="assets/img/artefacts/Empathy_map_Carmen_Rojas.png" width="500" alt="Empathy Map - Segmento Farmacia"/>
  <br/><i>Artefacto 2: Mapa de empatía enfocado en la gestión técnica farmacéutica.</i>
</p>

## 2.4. Big Picture Event Storming

El Big Picture Event Storming es una técnica colaborativa de modelado que permite explorar y comprender el dominio de un negocio a alto nivel mediante la identificación de eventos clave, actores y sus interacciones. A través de esta herramienta, se obtiene una visión global del funcionamiento del sistema, facilitando la detección de procesos, relaciones y posibles problemáticas dentro del negocio.

En este contexto, se realizó con el objetivo de comprender el dominio del negocio de gestión de inventarios, identificando los eventos clave, actores y flujos principales. Este modelo no se limita a las herramientas actuales utilizadas, sino que representa el funcionamiento general del negocio, proporcionando el contexto en el cual se inserta la solución propuesta, Qullqa.

Para realizar el Big Picture Event Storming se utilizaron 3 pasos importantes:

- **Step 1: Generating Domain Events** <br>
  En esta etapa se identificaron todos los eventos relevantes del dominio del negocio, es decir, hechos significativos que ocurren en el sistema y que representan cambios de estado importantes. Estos eventos se expresan en pasado y permiten construir una visión inicial del funcionamiento del negocio.

  <div>
    <img src="assets/img/event_storming/big_picture_event_storming_step1.png" alt="Foto Lean UX Canvas (V2)" width="500"/>
  </div> <br>

- **Step 2: Sorting Domain Events (chronologically)** <br>
  En este paso se organizaron los eventos de dominio de forma cronológica, permitiendo visualizar el flujo natural de los procesos del negocio. Esto facilita la comprensión de cómo se desarrollan las operaciones y cómo se relacionan los distintos eventos entre sí.

  <div>
    <img src="assets/img/event_storming/big_picture_event_storming_step2.png" alt="Foto Lean UX Canvas (V2)" width="500"/>
  </div> <br>

- **Step 3: Adding Actors and External systems** <br>
  Finalmente, se incorporaron los actores y sistemas externos que interactúan con el dominio, identificando quiénes participan en los procesos y qué herramientas o medios intervienen. Esto permite contextualizar los eventos dentro del ecosistema real del negocio.

  <div>
    <img src="assets/img/event_storming/big_picture_event_storming_step3.png" alt="Foto Lean UX Canvas (V2)" width="500"/>
  </div> <br>

## 2.5. Ubiquitous Language

El Ubiquitous Language es un conjunto de términos y conceptos compartidos que permiten establecer una comunicación clara y consistente entre todos los miembros del equipo y los stakeholders del proyecto. Este lenguaje se construye a partir del dominio del negocio y busca eliminar ambigüedades en la interpretación de los procesos y entidades involucradas. <br>

En el contexto de Qullqa, se ha definido el siguiente glosario de términos clave relacionados con la gestión de inventarios en bodegas y farmacias independientes. Estos términos están expresados en inglés, incluyendo su equivalente en español, y sus definiciones permiten alinear el entendimiento del dominio entre todos los participantes del proyecto.

- **Store Owner (Dueño del negocio)** <br>
  Persona responsable de gestionar el inventario, registrar productos, realizar ventas y coordinar pedidos con proveedores.

- **Product (Producto)** <br>
  Bien físico que es almacenado, vendido o gestionado dentro del inventario del negocio.

- **Inventory (Inventario)** <br>
  Conjunto de productos disponibles en el negocio, incluyendo sus cantidades y estado.

- **Stock (Stock)** <br>
  Cantidad disponible de un producto específico dentro del inventario.

- **Updated Stock (Actualización de stock)** <br>
  Cambio en la cantidad disponible de un producto debido a ventas, reposiciones, pérdidas u otros factores.

- **Reduced Stock (Reducción de stock)** <br>
  Disminución de la cantidad de un producto debido a una venta, pérdida o ajuste.

- **Sale (Venta)** <br>
  Transacción en la que uno o más productos son entregados a un cliente a cambio de un pago.

- **Registered Sale (Registro de venta)** <br>
  Registro de una venta realizada, incluyendo productos, cantidades y monto.

- **Payment (Pago)** <br>
  Acción mediante la cual el cliente entrega dinero u otro medio de pago a cambio de productos.

- **Sale Cancellation (Cancelación de venta)** <br>
  Anulación de una venta previamente realizada.

- **Revenue (Ingresos)** <br>
  Dinero generado a partir de las ventas.

- **Revised Inventory (Revisión de inventario)** <br>
  Proceso de verificación del estado y cantidades del inventario.

- **Expired Product (Producto vencido)** <br>
  Producto cuya fecha de vencimiento ha sido superada y no puede ser vendido.

- **Expiring Product (Producto próximo a vencer)** <br>
  Producto cuya fecha de vencimiento está cercana.

- **Lost Product (Producto extraviado)** <br>
  Producto que no puede ser localizado físicamente en el inventario.

- **Stock Shortage (Falta de stock)** <br>
  Situación en la que no hay suficiente cantidad de un producto para satisfacer la demanda.

- **Inventory Loss (Pérdida de inventario)** <br>
  Pérdida de productos debido a vencimiento, extravío u otros factores.

- **Alert (Alerta)** <br>
  Notificación generada para informar sobre eventos importantes del inventario, como productos próximos a vencer.

- **Spare Stock (Stock de reposición)** <br>
  Cantidad adicional de productos utilizada para reabastecer el inventario.

- **Supplier (Proveedor)** <br>
  Persona o empresa encargada de suministrar productos al negocio.

- **Order (Pedido)** <br>
  Solicitud de productos realizada al proveedor para abastecer el negocio.

- **Order Delivery (Recepción de pedido)** <br>
  Proceso mediante el cual el negocio recibe productos del proveedor.

- **Lead Time (Tiempo de entrega)** <br>
  Tiempo entre la solicitud del pedido y su recepción.


# Capítulo III: Requirements Specification

## 3.1. User Stories

En esta sección se presenta el conjunto de Epics, User Stories y Technical Stories definidos para Qullqa, elaborados a partir de los requisitos identificados durante el proceso de investigación, análisis del dominio y necesidades de los segmentos objetivo. Cada historia describe una funcionalidad o capacidad que aporta valor al usuario, al negocio o al desarrollo técnico de la solución. Asimismo, se incluyen criterios de aceptación redactados bajo la estructura Gherkin (Given–When–Then), con el fin de establecer condiciones claras, comprobables y alineadas al comportamiento esperado del sistema.

Las historias consideradas abarcan tanto la Landing Page, orientada a visitantes de los segmentos objetivo, como la Web Application y los features técnicos del RESTful API, asegurando una especificación integral de los requisitos del producto digital Qullqa, según lo solicitado en el enunciado del proyecto.

<table>
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>

  <tr>
    <td><strong>US01</strong></td>
    <td>Conocer la propuesta de valor para bodegueros</td>
    <td>
      Como visitante del segmento bodegueros independientes, quiero conocer la propuesta de valor de Qullqa,
      para entender cómo mejorar el control de stock, reducir pérdidas y conocer mejor la rentabilidad del negocio.
    </td>
    <td>
      <strong>Escenario 1: Consulta de beneficios para el segmento</strong><br>
      Dado que el visitante pertenece al segmento de bodegueros independientes<br>
      Cuando el visitante consulta la propuesta de valor de Qullqa<br>
      Entonces el sistema presenta beneficios relacionados con control de stock, vencimientos y ventas.
      <p></p>
      <strong>Escenario 2: Contenido alineado al problema del segmento</strong><br>
      Dado que el visitante revisa la información del producto<br>
      Cuando el sistema presenta el contenido para el segmento<br>
      Entonces el sistema comunica problemas y beneficios coherentes con la realidad operativa de una bodega independiente.
    </td>
    <td>EP01 – Landing Page y captación</td>
  </tr>

  <tr>
    <td><strong>US02</strong></td>
    <td>Conocer la propuesta de valor para farmacias</td>
    <td>
      Como visitante del segmento farmacias independientes, quiero conocer la propuesta de valor de Qullqa,
      para entender cómo controlar mejor vencimientos, disponibilidad y reposición de medicamentos.
    </td>
    <td>
      <strong>Escenario 1: Consulta de beneficios para farmacias</strong><br>
      Dado que el visitante pertenece al segmento farmacias independientes<br>
      Cuando el visitante consulta la propuesta de valor de Qullqa<br>
      Entonces el sistema presenta beneficios relacionados con control de vencimientos, stock crítico y disponibilidad de productos.
      <p></p>
      <strong>Escenario 2: Enfoque en control riguroso</strong><br>
      Dado que el visitante revisa la información del producto<br>
      Cuando el sistema presenta el contenido para farmacias<br>
      Entonces el sistema destaca la necesidad de control riguroso del inventario y reducción de riesgos operativos.
    </td>
    <td>EP01 – Landing Page y captación</td>
  </tr>

  <tr>
    <td><strong>US03</strong></td>
    <td>Visualizar funcionalidades y planes</td>
    <td>
      Como visitante, quiero visualizar las funcionalidades y planes de Qullqa,
      para comparar alternativas y reconocer cuál se ajusta mejor a mi negocio.
    </td>
    <td>
      <strong>Escenario 1: Visualización de funcionalidades por plan</strong><br>
      Dado que el visitante consulta la información comercial de Qullqa<br>
      Cuando el visitante revisa los planes disponibles<br>
      Entonces el sistema presenta las funcionalidades incluidas en Free, Pro y Premium.
      <p></p>
      <strong>Escenario 2: Comparación de planes</strong><br>
      Dado que el visitante analiza más de un plan<br>
      Cuando el sistema presenta el detalle de cada uno<br>
      Entonces el sistema diferencia claramente los límites y beneficios de cada plan.
    </td>
    <td>EP01 – Landing Page y captación</td>
  </tr>

  <tr>
    <td><strong>US04</strong></td>
    <td>Redirigirse desde la Landing Page hacia la aplicación</td>
    <td>
      Como visitante, quiero acceder desde la Landing Page a la vista correspondiente de la Web Application,
      para iniciar mi proceso de registro o uso del servicio.
    </td>
    <td>
      <strong>Escenario 1: Redirección hacia flujo correspondiente</strong><br>
      Dado que el visitante decide continuar con la propuesta de Qullqa<br>
      Cuando el visitante selecciona una acción de conversión<br>
      Entonces el sistema redirige al visitante a la vista correspondiente dentro de la Web Application.
      <p></p>
      <strong>Escenario 2: Consistencia entre experiencias</strong><br>
      Dado que el visitante pasa de la Landing Page a la Web Application<br>
      Cuando el sistema completa la redirección<br>
      Entonces la experiencia mantiene consistencia en contenido, propósito y continuidad del flujo.
    </td>
    <td>EP01 – Landing Page y captación</td>
  </tr>

  <tr>
    <td><strong>US05</strong></td>
    <td>Registrarse e iniciar sesión</td>
    <td>
      Como dueño de bodega o farmacia, quiero registrarme e iniciar sesión en Qullqa,
      para acceder de forma segura a la gestión de mi negocio.
    </td>
    <td>
      <strong>Escenario 1: Registro exitoso</strong><br>
      Dado que el usuario no cuenta con una cuenta registrada<br>
      Cuando el usuario registra datos válidos<br>
      Entonces el sistema crea la cuenta y habilita el acceso a la plataforma.
      <p></p>
      <strong>Escenario 2: Inicio de sesión exitoso</strong><br>
      Dado que el usuario cuenta con una cuenta activa<br>
      Cuando el usuario ingresa credenciales válidas<br>
      Entonces el sistema autentica al usuario y habilita su sesión.
      <p></p>
      <strong>Escenario 3: Credenciales inválidas</strong><br>
      Dado que el usuario intenta acceder a la plataforma<br>
      Cuando el usuario ingresa credenciales inválidas<br>
      Entonces el sistema rechaza la autenticación e informa que el acceso no es válido.
    </td>
    <td>EP02 – Acceso, cuentas y suscripción</td>
  </tr>

  <tr>
    <td><strong>US06</strong></td>
    <td>Gestionar el plan contratado y sus límites</td>
    <td>
      Como dueño del negocio, quiero conocer y gestionar el plan contratado,
      para entender las capacidades habilitadas y los límites de uso disponibles.
    </td>
    <td>
      <strong>Escenario 1: Visualización de límites del plan</strong><br>
      Dado que el usuario tiene un plan activo<br>
      Cuando el usuario consulta la información de su suscripción<br>
      Entonces el sistema presenta el plan contratado y sus restricciones operativas.
      <p></p>
      <strong>Escenario 2: Restricción según plan</strong><br>
      Dado que el usuario intenta utilizar una capacidad no incluida en su plan<br>
      Cuando el sistema valida el acceso a esa capacidad<br>
      Entonces el sistema restringe la operación e informa que la funcionalidad requiere un plan superior.
    </td>
    <td>EP02 – Acceso, cuentas y suscripción</td>
  </tr>

  <tr>
    <td><strong>US07</strong></td>
    <td>Registrar producto</td>
    <td>
      Como dueño del negocio, quiero registrar productos con sus datos principales,
      para mantener un inventario organizado y controlado.
    </td>
    <td>
      <strong>Escenario 1: Registro exitoso de producto</strong><br>
      Dado que el usuario cuenta con permisos para gestionar inventario<br>
      Cuando el usuario registra un producto con datos válidos<br>
      Entonces el sistema guarda el producto y lo incorpora al inventario.
      <p></p>
      <strong>Escenario 2: Validación de datos obligatorios</strong><br>
      Dado que el usuario intenta registrar un producto<br>
      Cuando el registro no incluye datos obligatorios<br>
      Entonces el sistema rechaza el registro e informa que los datos son incompletos.
    </td>
    <td>EP03 – Gestión de productos e inventario</td>
  </tr>

  <tr>
    <td><strong>US08</strong></td>
    <td>Actualizar producto y precio</td>
    <td>
      Como dueño del negocio, quiero actualizar la información y precio de un producto,
      para mantener los datos comerciales y operativos al día.
    </td>
    <td>
      <strong>Escenario 1: Actualización exitosa</strong><br>
      Dado que el producto existe en el inventario<br>
      Cuando el usuario modifica información válida del producto<br>
      Entonces el sistema actualiza los datos del producto.
      <p></p>
      <strong>Escenario 2: Conservación de trazabilidad</strong><br>
      Dado que el producto es actualizado<br>
      Cuando el sistema guarda los cambios<br>
      Entonces el sistema conserva el registro actualizado del producto para futuras consultas.
    </td>
    <td>EP03 – Gestión de productos e inventario</td>
  </tr>

  <tr>
    <td><strong>US09</strong></td>
    <td>Consultar lista de productos y disponibilidad</td>
    <td>
      Como dueño del negocio o vendedor, quiero consultar la lista de productos y su disponibilidad,
      para conocer el estado actual del inventario.
    </td>
    <td>
      <strong>Escenario 1: Consulta del inventario</strong><br>
      Dado que el usuario cuenta con acceso al inventario<br>
      Cuando el usuario consulta el catálogo interno<br>
      Entonces el sistema presenta los productos registrados con su disponibilidad actual.
      <p></p>
      <strong>Escenario 2: Identificación de productos no disponibles</strong><br>
      Dado que existen productos sin stock suficiente<br>
      Cuando el usuario consulta el inventario<br>
      Entonces el sistema identifica los productos con disponibilidad insuficiente.
    </td>
    <td>EP03 – Gestión de productos e inventario</td>
  </tr>

  <tr>
    <td><strong>US10</strong></td>
    <td>Controlar stock por almacén</td>
    <td>
      Como dueño del negocio con plan Pro o superior, quiero controlar el stock por almacén,
      para conocer la distribución exacta del inventario en cada ubicación.
    </td>
    <td>
      <strong>Escenario 1: Consulta por almacén</strong><br>
      Dado que el negocio gestiona más de una ubicación<br>
      Cuando el usuario consulta el stock por almacén<br>
      Entonces el sistema presenta la cantidad disponible de cada producto por ubicación.
      <p></p>
      <strong>Escenario 2: Restricción por plan</strong><br>
      Dado que el usuario no cuenta con una suscripción compatible<br>
      Cuando el usuario intenta acceder al control por almacén<br>
      Entonces el sistema restringe la funcionalidad.
    </td>
    <td>EP03 – Gestión de productos e inventario</td>
  </tr>

  <tr>
    <td><strong>US11</strong></td>
    <td>Recibir alertas de bajo stock</td>
    <td>
      Como dueño del negocio, quiero recibir alertas de bajo stock,
      para reponer productos antes de afectar la venta o disponibilidad.
    </td>
    <td>
      <strong>Escenario 1: Generación de alerta</strong><br>
      Dado que un producto alcanza o cae por debajo del stock mínimo definido<br>
      Cuando el sistema evalúa el nivel de inventario<br>
      Entonces el sistema genera una alerta de bajo stock.
      <p></p>
      <strong>Escenario 2: Consulta de alertas activas</strong><br>
      Dado que existen alertas de bajo stock generadas<br>
      Cuando el usuario consulta las alertas operativas<br>
      Entonces el sistema presenta los productos afectados y su nivel de stock actual.
    </td>
    <td>EP04 – Alertas y control operativo</td>
  </tr>

  <tr>
    <td><strong>US12</strong></td>
    <td>Recibir alertas de productos por vencer</td>
    <td>
      Como dueño de bodega o farmacia, quiero recibir alertas de productos por vencer,
      para tomar acciones preventivas y reducir pérdidas.
    </td>
    <td>
      <strong>Escenario 1: Detección de vencimiento próximo</strong><br>
      Dado que un producto se encuentra dentro del umbral de vencimiento definido<br>
      Cuando el sistema evalúa la fecha de expiración<br>
      Entonces el sistema genera una alerta por vencimiento próximo.
      <p></p>
      <strong>Escenario 2: Priorización de productos críticos</strong><br>
      Dado que existen varios productos próximos a vencer<br>
      Cuando el usuario consulta las alertas<br>
      Entonces el sistema presenta primero los productos con vencimiento más cercano.
    </td>
    <td>EP04 – Alertas y control operativo</td>
  </tr>

  <tr>
    <td><strong>US13</strong></td>
    <td>Registrar ingreso o recepción de stock</td>
    <td>
      Como dueño del negocio, quiero registrar ingresos o recepciones de stock,
      para mantener actualizado el inventario real del establecimiento.
    </td>
    <td>
      <strong>Escenario 1: Registro de ingreso exitoso</strong><br>
      Dado que el usuario cuenta con permisos para registrar movimientos<br>
      Cuando el usuario registra una recepción válida de stock<br>
      Entonces el sistema incrementa el inventario del producto correspondiente.
      <p></p>
      <strong>Escenario 2: Actualización del historial de movimientos</strong><br>
      Dado que se registra un ingreso de stock<br>
      Cuando el sistema procesa la operación<br>
      Entonces el sistema guarda el movimiento para fines de control y consulta.
    </td>
    <td>EP04 – Alertas y control operativo</td>
  </tr>

  <tr>
    <td><strong>US14</strong></td>
    <td>Registrar venta POS</td>
    <td>
      Como vendedor, quiero registrar una venta POS,
      para actualizar el inventario y dejar trazabilidad comercial de la operación.
    </td>
    <td>
      <strong>Escenario 1: Venta registrada correctamente</strong><br>
      Dado que el producto cuenta con stock suficiente<br>
      Cuando el vendedor registra una venta válida<br>
      Entonces el sistema guarda la venta y descuenta el stock correspondiente.
      <p></p>
      <strong>Escenario 2: Venta rechazada por stock insuficiente</strong><br>
      Dado que el producto no cuenta con stock suficiente<br>
      Cuando el vendedor intenta registrar la venta<br>
      Entonces el sistema rechaza la operación e informa la insuficiencia de stock.
    </td>
    <td>EP05 – Ventas, dashboard y reportes</td>
  </tr>

  <tr>
    <td><strong>US15</strong></td>
    <td>Visualizar dashboard del negocio</td>
    <td>
      Como dueño del negocio, quiero visualizar un dashboard con indicadores clave,
      para tomar decisiones basadas en ventas, stock y alertas.
    </td>
    <td>
      <strong>Escenario 1: Visualización de indicadores</strong><br>
      Dado que el usuario accede al resumen del negocio<br>
      Cuando el sistema carga la información disponible<br>
      Entonces el sistema presenta indicadores de ventas, inventario y alertas.
      <p></p>
      <strong>Escenario 2: Información actualizada</strong><br>
      Dado que existen operaciones recientes en el negocio<br>
      Cuando el usuario consulta el dashboard<br>
      Entonces el sistema presenta datos actualizados respecto al estado operativo.
    </td>
    <td>EP05 – Ventas, dashboard y reportes</td>
  </tr>

  <tr>
    <td><strong>US16</strong></td>
    <td>Consultar y descargar reportes detallados</td>
    <td>
      Como dueño del negocio con plan Premium, quiero consultar y descargar reportes detallados,
      para analizar el desempeño por día, semana, producto y ventas.
    </td>
    <td>
      <strong>Escenario 1: Consulta de reportes</strong><br>
      Dado que el usuario cuenta con acceso a reportes avanzados<br>
      Cuando el usuario solicita un reporte por criterio de análisis<br>
      Entonces el sistema genera la información correspondiente al período y filtro solicitado.
      <p></p>
      <strong>Escenario 2: Descarga de reporte</strong><br>
      Dado que el sistema genera correctamente el reporte<br>
      Cuando el usuario solicita exportarlo<br>
      Entonces el sistema entrega el reporte en un formato descargable.
    </td>
    <td>EP05 – Ventas, dashboard y reportes</td>
  </tr>

  <tr>
    <td><strong>US17</strong></td>
    <td>Gestionar proveedores</td>
    <td>
      Como dueño del negocio, quiero registrar y consultar proveedores,
      para mantener organizado el abastecimiento y facilitar la reposición de productos.
    </td>
    <td>
      <strong>Escenario 1: Registro de proveedor</strong><br>
      Dado que el usuario cuenta con permisos de administración<br>
      Cuando el usuario registra un proveedor con datos válidos<br>
      Entonces el sistema guarda la información del proveedor.
      <p></p>
      <strong>Escenario 2: Consulta de proveedor asociado a productos</strong><br>
      Dado que existen proveedores registrados<br>
      Cuando el usuario consulta la información de abastecimiento<br>
      Entonces el sistema presenta los proveedores disponibles y su relación con productos cuando corresponda.
    </td>
    <td>EP06 – Proveedores, usuarios y colaboración</td>
  </tr>

  <tr>
    <td><strong>US18</strong></td>
    <td>Gestionar roles y usuarios del negocio</td>
    <td>
      Como administrador del negocio, quiero asignar roles y controlar usuarios,
      para distribuir responsabilidades entre administración y ventas.
    </td>
    <td>
      <strong>Escenario 1: Creación de usuario con rol válido</strong><br>
      Dado que el administrador cuenta con capacidad para gestionar accesos<br>
      Cuando el administrador registra un usuario con rol válido<br>
      Entonces el sistema crea el usuario con los permisos correspondientes.
      <p></p>
      <strong>Escenario 2: Restricción por límite del plan</strong><br>
      Dado que el negocio alcanzó el número máximo de usuarios permitidos<br>
      Cuando el administrador intenta registrar un nuevo usuario<br>
      Entonces el sistema rechaza la operación e informa el límite del plan.
    </td>
    <td>EP06 – Proveedores, usuarios y colaboración</td>
  </tr>

  <tr>
    <td><strong>US19</strong></td>
    <td>Rastrear entrega de productos al almacén</td>
    <td>
      Como dueño del negocio con plan Premium, quiero rastrear la entrega de productos mediante IoT,
      para conocer el estado y ubicación de los envíos hacia mi bodega o almacén.
    </td>
    <td>
      <strong>Escenario 1: Consulta de ubicación de entrega</strong><br>
      Dado que existe una entrega asociada a un dispositivo IoT activo<br>
      Cuando el usuario consulta el estado del envío<br>
      Entonces el sistema presenta la ubicación y estado más reciente de la entrega.
      <p></p>
      <strong>Escenario 2: Entrega finalizada</strong><br>
      Dado que la entrega llega a destino<br>
      Cuando el sistema recibe la confirmación de finalización<br>
      Entonces el sistema actualiza el estado de la entrega como completada.
    </td>
    <td>EP07 – Seguimiento de entregas con IoT</td>
  </tr>

  <tr>
    <td><strong>TS01</strong></td>
    <td>Enviar alertas operativas mediante API Notificación</td>
    <td>
      Como developer, quiero enviar alertas operativas mediante la API Notificación,
      para informar eventos críticos como bajo stock o productos próximos a vencer.
    </td>
    <td>
      <strong>Escenario 1: Envío exitoso de alerta de bajo stock</strong><br>
      Dado que existe un producto cuyo stock ha alcanzado el umbral mínimo<br>
      Cuando el developer envía una solicitud POST a /api/notificaciones/alertas con el tipo LOW_STOCK<br>
      Entonces la API responde con 201 Created<br>
      Y registra la alerta correctamente<br>
      Y devuelve el estado de envío de la notificación.
      <p></p>
      <strong>Escenario 2: Envío exitoso de alerta por vencimiento próximo</strong><br>
      Dado que existe un producto dentro del umbral de vencimiento configurado<br>
      Cuando el developer envía una solicitud POST a /api/notificaciones/alertas con el tipo EXPIRATION_WARNING<br>
      Entonces la API responde con 201 Created<br>
      Y registra la alerta correctamente<br>
      Y devuelve el detalle de la notificación generada.
      <p></p>
      <strong>Escenario 3: Consulta de alertas generadas</strong><br>
      Dado que existen alertas registradas para el negocio<br>
      Cuando el developer envía una solicitud GET a /api/notificaciones/alertas/{businessId}<br>
      Entonces la API responde con 200 OK<br>
      Y devuelve la lista de alertas activas<br>
      Y cada alerta incluye tipo, producto relacionado y fecha de generación.
      <p></p>
      <strong>Escenario 4: Solicitud inválida de alerta</strong><br>
      Dado que el developer envía una solicitud sin tipo de alerta o sin identificador de producto<br>
      Cuando la API valida el request<br>
      Entonces la API responde con 400 Bad Request<br>
      Y devuelve el detalle del error de validación.
    </td>
    <td>EP08 – Technical Stories RESTful API</td>
  </tr>

  <tr>
    <td><strong>TS02</strong></td>
    <td>Consultar ubicación de entrega mediante API Geolocalización</td>
    <td>
      Como developer, quiero consultar la ubicación de una entrega mediante la API Geolocalización,
      para mostrar el estado y la posición actual del envío hacia el almacén o bodega.
    </td>
    <td>
      <strong>Escenario 1: Consulta exitosa de ubicación de entrega</strong><br>
      Dado que existe una entrega asociada a un dispositivo o evento de rastreo válido<br>
      Cuando el developer envía una solicitud GET a /api/geolocalizacion/entregas/{deliveryId}<br>
      Entonces la API responde con 200 OK<br>
      Y devuelve la ubicación más reciente de la entrega<br>
      Y devuelve el estado actual del envío.
      <p></p>
      <strong>Escenario 2: Entrega finalizada</strong><br>
      Dado que la entrega ya llegó al destino final<br>
      Cuando el developer consulta /api/geolocalizacion/entregas/{deliveryId}<br>
      Entonces la API responde con 200 OK<br>
      Y devuelve el estado COMPLETED<br>
      Y devuelve la última ubicación registrada como destino final.
      <p></p>
      <strong>Escenario 3: Entrega no encontrada</strong><br>
      Dado que el identificador de entrega no existe en el sistema<br>
      Cuando el developer envía la solicitud de consulta<br>
      Entonces la API responde con 404 Not Found<br>
      Y devuelve un mensaje indicando que la entrega no fue encontrada.
      <p></p>
      <strong>Escenario 4: Solicitud sin autenticación válida</strong><br>
      Dado que el developer intenta consultar una entrega sin token válido<br>
      Cuando la API valida el acceso<br>
      Entonces la API responde con 401 Unauthorized<br>
      Y rechaza la consulta de geolocalización.
    </td>
    <td>EP08 – Technical Stories RESTful API</td>
  </tr>
</table>

## 3.2. Impact Mapping

<div align="justify">
  En esta sección se presentan los Impact Mapping elaborados a partir de los user persona por cada segmento. Estos mapas son una técnica de planificación estratégica (creada por Gojko Adzic) que sirve para evitar que los equipos de desarrollo construyan software que nadie necesita o que no ayuda al negocio.
</div>

<br>

**Bussiness Goals: Gestion de Stock y perdidas**
<p align="center">
  <img src="assets/img/artefacts/Mapa_impacto_uno.png" width="500" alt="User Journey Map - Carlos Mendoza"/>
  <br/><i>Artefacto: Mapa de impacto orientado a reduccion de perdidas.</i>
</p>

**Bussiness Goals: Rentabilidad**
<p align="center">
  <img src="assets/img/artefacts/Mapa_impacto_dos.png" width="500" alt="User Journey Map - Carlos Mendoza"/>
  <br/><i>Artefacto: Mapa de impacto orientado rentabilidad del flujo de negocio.</i>
</p>

**Bussiness Goals: Tiempo**
<p align="center">
  <img src="assets/img/artefacts/Mapa_impacto_tres.png" width="500" alt="User Journey Map - Carlos Mendoza"/>
  <br/><i>Artefacto: Mapa de impacto orientado a la velocidad de tareas administrativas.</i>
</p>

## 3.3. Product Backlog

* El Product Backlog funciona como una lista que nos ayudara a priorizar todas las funcionalidades, mejoras y requisitos técnicos necesarios para dar vida a Qullqa.
En el marco de Scrum, nuestro equipo utilizara este inventario para seleccionar las tareas más valiosas durante la planeación de cada sprint, transformando ideas abstractas en entregables tangibles. Para ello usaremos la Herramienta de Jira para el trabajo colaborativo en tiempo real.

## Product Backlog Priorizado

| # Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| :--- | :--- | :--- | :--- | :---: |
| 1 | **TS-02** | Consultar ubicación de entrega mediante API Geolocalización | Como developer, quiero consultar la ubicación de una entrega mediante la API Geolocalización para mostrar el estado y la posición actual del envío hacia el almacén o bodega. | 5 |
| 2 | **US-16** | Consultar y descargar reportes detallados | Como dueño del negocio con plan Premium, quiero consultar y descargar reportes detallados, para analizar el desempeño por día, semana, producto y ventas. | 5 |
| 3 | **US-19** | Rastrear entrega de productos al almacén | Como dueño del negocio con plan Premium, quiero rastrear la entrega de productos mediante IoT, para conocer el estado y ubicación de los envíos hacia mi bodega o almacén. | 5 |
| 4 | **US-05** | Registrarse e iniciar sesión | Como dueño de bodega o farmacia, quiero registrarme e iniciar sesión en Qullqa, para acceder de forma segura a la gestión de mi negocio. | 3 |
| 5 | **US-06** | Gestionar el plan contratado y sus límites | Como dueño del negocio, quiero conocer y gestionar el plan contratado, para entender las capacidades habilitadas y los límites de uso disponibles. | 3 |
| 6 | **US-11** | Recibir alertas de bajo stock | Como dueño del negocio, quiero recibir alertas de bajo stock, para reponer productos antes de afectar la venta o disponibilidad. | 3 |
| 7 | **US-12** | Recibir alertas de productos por vencer | Como dueño de bodega o farmacia, quiero recibir alertas de productos por vencer, para tomar acciones preventivas y reducir pérdidas. | 3 |
| 8 | **US-13** | Registrar ingreso o recepción de stock | Como dueño del negocio, quiero registrar ingresos o recepciones de stock, para mantener actualizado el inventario real del establecimiento. | 3 |
| 9 | **TS-01** | Enviar alertas operativas mediante API Notificación | Como developer, quiero enviar alertas operativas mediante la API Notificación para informar eventos críticos como bajo stock o productos próximos a vencer. | 3 |
| 10 | **US-10** | Controlar stock por almacén | Como dueño del negocio con plan Pro o superior, quiero controlar el stock por almacén, para conocer la distribución exacta del inventario en cada ubicación. | 3 |
| 11 | **US-14** | Registrar venta POS | Como vendedor, quiero registrar una venta POS, para actualizar el inventario y dejar trazabilidad comercial de la operación. | 3 |
| 12 | **US-15** | Visualizar dashboard del negocio | Como dueño del negocio, quiero visualizar un dashboard con indicadores clave, para tomar decisiones basadas en ventas, stock y alertas. | 3 |
| 13 | **US-18** | Gestionar roles y usuarios del negocio | Como administrador del negocio, quiero asignar roles y controlar usuarios, para distribuir responsabilidades entre administración y ventas. | 3 |
| 14 | **US-03** | Visualizar funcionalidades y planes | Como visitante, quiero visualizar las funcionalidades y planes de Qullqa, para comparar alternativas y reconocer cuál se ajusta mejor a mi negocio. | 2 |
| 15 | **US-07** | Registrar producto | Como dueño del negocio, quiero registrar productos con sus datos principales, para mantener un inventario organizado y controlado. | 2 |
| 16 | **US-08** | Actualizar producto y precio | Como dueño del negocio, quiero actualizar la información y precio de un producto, para mantener los datos comerciales y operativos al día. | 2 |
| 17 | **US-09** | Consultar lista de productos y disponibilidad | Como dueño del negocio o vendedor, quiero consultar la lista de productos y su disponibilidad, para conocer el estado actual del inventario. | 2 |
| 18 | **US-17** | Gestionar proveedores | Como dueño del negocio, quiero registrar y consultar proveedores, para mantener organizado el abastecimiento y facilitar la reposición de productos. | 2 |
| 19 | **US-01** | Conocer la propuesta de valor para bodegueros | Como visitante del segmento bodegueros independientes, quiero conocer la propuesta de valor de Qullqa, para entender cómo mejorar el control de stock, reducir pérdidas y conocer mejor la rentabilidad del negocio. | 1 |
| 20 | **US-02** | Conocer la propuesta de valor para farmacias | Como visitante del segmento farmacias independientes, quiero conocer la propuesta de valor de Qullqa, para entender cómo controlar mejor vencimientos, disponibilidad y reposición de medicamentos. | 1 |
| 21 | **US-04** | Redirigirse desde la Landing Page hacia la aplicación | Como visitante, quiero acceder desde la Landing Page a la vista correspondiente de la Web Application, para iniciar mi proceso de registro o uso del servicio. | 1 |
</br>
<p align="center">
  <img src="assets/img/artefacts/epics.png" width="500" alt="Epicas"/>
  <br/><i>Artefacto: Jira para Epics</i>
</p>

<p align="center">
  <img src="assets/img/artefacts/storys.png" width="500" alt="Historias de Usuario"/>
  <br/><i>Artefacto: Jira para User Storys</i>
</p>

<p align="center">
  <img src="assets/img/artefacts/backlog.png" width="500" alt="Product Backlog"/>
  <br/><i>Artefacto: Jira para Backlog Priorizado</i>
</p>

>Acceso a artefacto Jira para el desarrollo de Backlog
<https://upc-team-open-source.atlassian.net/jira/software/projects/QULLQA/boards/67/timeline?atlOrigin=eyJpIjoiYzQxN2FjYjgxN2M3NDBiMzk2OTU4OTg3Y2I4NWU5YTYiLCJwIjoiaiJ9>

# Capítulo IV: Product Design
## 4.1. Style Guidelines
<div align="justify">
  En esta parte se presentan una serie de criterios y orientaciones que indican cómo elaborar y dar formato a los documentos de un proyecto. Además, estas pautas ayudan a conservar uniformidad en el estilo, la estructura, el lenguaje y los elementos visuales, lo que contribuye a una comunicación más clara entre los miembros del equipo y a una presentación consistente y profesional.
</div>

### 4.1.1. General Style Guidelines
**Branding**
<div align="justify">
  El nombre de nuestra propuesta de solución es Qullqa, un término de origen quechua que hace referencia a los espacios de almacenamiento utilizados en el antiguo Imperio Inca para conservar recursos de manera organizada y segura. Asimismo, Qullqa simboliza la gestión eficiente y ordenada de la información, lo cual refleja el propósito de la plataforma de centralizar y estructurar datos de forma accesible y confiable. Por otro lado, el uso de una palabra en quechua resalta la conexión con nuestras raíces culturales, aportando identidad y valor local al proyecto. En conjunto, Qullqa representa una solución enfocada en el almacenamiento inteligente de información, promoviendo organización, accesibilidad y una gestión eficiente de los recursos dentro del sistema.
</div>
<br>

<p align="center">
  <img src="assets/img/qullqa_logo.jpeg" width="500" alt="Qullqa logo"/>
  <br/><i>Logo de Qullqa</i>
</p>

**Typography**
<div align="justify">
  La tipografía del nombre de marca en Qullqa cumple un papel fundamental en la construcción de su identidad visual, ya que no solo asegura la legibilidad, sino que también transmite su esencia. Se eligió Orbitron por su estilo geométrico y futurista, que comunica modernidad, innovación y un enfoque tecnológico, alineándose con la personalidad de la marca, mientras que de forma complementaria se utiliza Segoe UI Emoji para integrar elementos gráficos como símbolos o detalles visuales que aportan cercanía y dinamismo. Las formas limpias y angulares de Orbitron permiten que el nombre destaque con claridad en distintos formatos, mientras que su estética distintiva facilita el reconocimiento, y el apoyo de Segoe UI Emoji añade un matiz visual amigable sin perder coherencia. En conjunto, esta combinación tipográfica refuerza una imagen sólida, contemporánea y versátil, haciendo que el brand name sea memorable y visualmente equilibrado.
</div>
<br>

**Orbitron**
<p align="center">
  <img src="assets/img/font1.png" width="500" alt="Orbitron"/>
  <br/>
</p>
<br>

**Segoe UI Emoji**
<p align="center">
  <img src="assets/img/font2.png" width="500" alt="Segoe UI Emoji"/>
  <br/>
</p>

**Colors**
<div align="justify">
  La paleta de colores de Qullqa se compone de una combinación equilibrada de tonos que transmiten modernidad, confianza y dinamismo, alineándose con la identidad innovadora de la marca. Se utilizan colores profundos como el azul (#0B3558) y el gris azulado (#64748B) que aportan solidez y profesionalismo, junto con tonalidades vibrantes como el rojo (#EF4444), amarillo (#FACC15) y verde (#22C55E) que añaden energía, diversidad y vitalidad. Asimismo, los tonos claros y neutros como el celeste (#E0F2FE), crema (#FEF3C7) y grises suaves (#F1F5F9,#F4F6F9,#FAFAF7) contribuyen a generar equilibrio visual, limpieza y una experiencia agradable para el usuario. En conjunto, esta paleta crea una identidad visual atractiva, versátil y contemporánea, capaz de destacar en distintos entornos y aplicaciones.
</div>
<br>
<p align="center">
  <img src="assets/img/colors.png" width="500" alt="Color Palette"/>
  <br/>
</p>

### 4.1.2. Web Style Guidelines.
<div align="justify">
  Una aplicación como Qullqa requiere ser intuitiva y fácil de usar para cualquier usuario, por lo que, aplicando los elementos visuales y tipográficos definidos previamente, se busca ofrecer una experiencia de navegación clara, fluida y accesible. El diseño prioriza la simplicidad sin perder el carácter moderno de la marca, permitiendo que los usuarios interactúen de manera eficiente mientras perciben seguridad y confianza, especialmente al gestionar información o recursos dentro del sistema. Asimismo, mediante un enfoque responsivo y el uso de elementos gráficos equilibrados, se pretende proyectar una imagen atractiva y profesional, manteniendo al usuario interesado y correctamente informado sobre el funcionamiento de la aplicación en todo momento. 
</div>

## 4.2. Information Architecture

### 4.2.1. Organization Systems
La arquitectura de la información en **Qullqa** está diseñada para que el bodeguero o farmacéutico acceda de manera inmediata a los indicadores de riesgo de su negocio, minimizando la carga cognitiva mediante flujos intuitivos y una organización lógica de los datos.

<a name="org-hierarchy"></a>
**a) Jerarquía visual** </br>
El sistema emplea una estructura donde la información crítica se destaca en los puntos de acceso más frecuentes:
* **Landing Page:** Se utiliza un flujo descendente que inicia con la propuesta de valor en el Hero Section ("Gestión inteligente para tu bodega o farmacia"), seguida de indicadores de impacto social (535K+ bodegas) para generar confianza, y finalmente el detalle de servicios y visión.
* **Dashboard de la aplicación:** Se prioriza la visualización de estados críticos. En la parte superior se ubican tarjetas de resumen con colores de contraste: "Stock Bajo" (Amarillo/Alerta) y "Por Vencer" (Rojo/Peligro), asegurando que el usuario identifique el riesgo antes que la información general.

<a name="org-sequential"></a>
**b) Organización secuencial** </br>
Los flujos complejos se descomponen en pasos simples para evitar la sobrecarga cognitiva:
* **Registro de Ventas (POS):** El usuario sigue un flujo lógico: Selección de productos a visualización de carrito con cálculo de impuestos (IGV), luego a Confirmación de venta y actualización automática de stock.
* **Gestión de inventario:** El flujo de añadir un nuevo producto descompone la carga de datos en campos específicos (Nombre, Precio, Stock, Vencimiento) para asegurar que no se omitan datos críticos de trazabilidad.

<a name="org-matrix"></a>
**c) Organización matricial** </br>
Diseñada para el análisis detallado donde el usuario puede cruzar información de múltiples dimensiones:
* **Control de movimientos:** El usuario puede cruzar información de entradas, salidas y ajustes de stock por tipo de movimiento y fecha, facilitando auditorías rápidas del almacén.

<a name="org-categorization"></a>
**d) Sistemas de categorización** </br>
* **Según Audiencia:**
    * **Bodegueros independientes:** Enfoque en ventas y ganancias reales.
    * **Farmacias/Boticas:** Enfoque en lotes, vencimientos y trazabilidad.
* **Por tópicos:** La aplicación organiza sus funcionalidades en módulos temáticos claramente diferenciados: Inventario, Alertas, Ventas, Proveedores y Reportes.
* **Cronológico:** Las alertas de vencimiento y el historial de movimientos se organizan temporalmente para permitir una gestión proactiva de la merma.

### 4.2.2. Labeling Systems

El sistema de etiquetado busca la máxima simplicidad, utilizando términos cotidianos para el comerciante peruano y eliminando tecnicismos innecesarios que puedan generar confusión.

<a name="label-navigation"></a>
**a) Etiquetas de navegación** </br>
Estas etiquetas se encuentran en los menús principales y barras laterales para orientar al usuario sobre su ubicación actual:
* **Landing Page:** Inicio, Servicios, Visión, Portafolio, Contacto, Iniciar Sesión, Registrarse.
* **Web Application:** Dashboard, Productos, Venta POS, Movimientos, Almacenes, Alertas, Reportes, Proveedores.

<a name="label-action"></a>
**b) Etiquetas de acción** </br>
Identifican las operaciones que el usuario puede ejecutar dentro de la plataforma:
* **CTAs Principales:** "Comenzar gratis", "Ver demo", "Añadir Producto", "Finalizar Venta".
* **Acciones Operativas:** "Editar", "Eliminar", "Filtrar", "Exportar Reporte".

<a name="label-metadata"></a>
**c) Etiquetas informativas y de estado** </br>
Utilizadas para encabezados de métricas y estados del negocio:
* **Indicadores de Inventario:** "Stock Bajo", "Por Vencer", "Valor Inventario", "Productos Totales".
* **Atributos de Producto:** "SKU / Código", "Precio Unitario", "Stock Actual", "Fecha Expiración".

<a name="label-system"></a>
**d) Mensajes de sistema y ayuda** </br>
Etiquetas diseñadas para retroalimentar al usuario sobre procesos internos:
* **Notificaciones:** "Producto añadido con éxito", "Alerta: Stock insuficiente", "Venta registrada".

### 4.2.3. SEO Tags and Meta Tags
Las meta etiquetas permiten codificar y especificar metadatos en las páginas web del proyecto. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las utilizan para leer y analizar la estructura del sitio. Así, facilitan tareas de indexación, mantenimiento del contenido y, sobre todo, mejoran el posicionamiento de la landing page y demás secciones de Qullqa en los motores de búsqueda.

<a name="seo-encoding"></a>
**Codificación de caracteres** </br>
Se utiliza el estándar `utf-8` para asegurar la correcta visualización de tildes y caracteres especiales del idioma español, optimizando además el uso de memoria para la mayoría de casos comunes.

<a name="seo-main-tags"></a>
**Etiquetas principales utilizadas** </br>

* **Title:** Permite definir el nombre visible de la pestaña y el identificador principal para indexación y búsquedas:
  `<title>Qullqa - Gestión Inteligente para tu Negocio</title>`

* **Description:** Describe el objetivo y contenido de la página, mostrándose como resumen en los resultados de búsqueda:
  `<meta name="description" content="Qullqa digitaliza tu inventario, controla tus ventas y monitorea tus entregas con IoT en tiempo real. La solución ideal para bodegas y farmacias en Perú.">`

* **Keywords:** Lista palabras relacionadas al propósito y alcance de la plataforma, ayudando a los buscadores en la categorización temática:
  `<meta name="keywords" content="gestión de inventario, bodega, farmacia, control de stock, IoT, ventas POS, MYPE, Perú, Flowbit, Qullqa">`

* **Author y copyright:** Se especifica el equipo autor y los derechos de autor del desarrollo:
  `<meta name="author" content="Flowbit Team">`
  `<meta name="copyright" content="Copyright Flowbit 2026" />`

<a name="seo-example"></a>
**Ejemplo completo de Meta Tags en una página principal del proyecto** </br>

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qullqa - Gestión Inteligente para tu Negocio</title>
    <meta name="description" content="Digitaliza tu inventario, controla tus ventas y monitorea tus entregas con IoT en tiempo real.">
    <meta name="keywords" content="inventario, bodega, farmacia, stock, IoT, POS, Qullqa">
    <meta name="author" content="Flowbit">
    <meta name="copyright" content="Copyright Flowbit 2026" />
</head>
```


### 4.2.4. Searching Systems

Para evitar que el usuario se sienta perdido ante un volumen alto de productos, se han implementado sistemas de búsqueda reactivos que garantizan una toma de decisiones rápida y precisa.

<a name="search-keywords"></a>
**a) Búsqueda por palabras clave** </br>
Implementada en el módulo de inventario, permite al usuario localizar productos de manera instantánea:
* **Criterios de búsqueda:** Nombre de producto o escaneo de código de barras.
* **Ubicación:** Barra de búsqueda superior persistente en el módulo de Inventario.

<a name="search-filters"></a>
**b) Sistemas de filtrado avanzado** </br>
Permite reducir el ruido informativo y aislar rápidamente los productos en situación crítica:
* **Filtros por Alerta:** Capacidad de aislar productos con "Stock Bajo" o "Próximos a Vencer" para priorizar la reposición o el retiro.
* **Filtros por Categoría:** Clasificación de productos según el rubro (Abarrotes, Medicamentos, Bebidas, etc.).

<a name="search-results"></a>
**c) Visualización de resultados** </br>
* **Resultados con códigos de color:** Si una búsqueda devuelve un producto con stock crítico, este se resalta visualmente para forzar la atención del administrador.
* **Estado de "Sin resultados":** Si no se encuentra un producto, el sistema ofrece un acceso directo para "Añadir nuevo producto", manteniendo el flujo operativo sin interrupciones.

### 4.2.5. Navigation Systems

El sistema de navegación de **Qullqa** guía al usuario de forma satisfactoria tanto en la fase de descubrimiento (Landing) como en la fase operativa (App), asegurando que siempre mantenga la noción de su ubicación dentro de la plataforma.

<a name="nav-global"></a>
**a) Navegación global** </br>
Es el nivel superior de navegación que permite moverse entre las áreas principales de la solución de forma persistente:
* **Landing Page:** Menú superior persistente (Navbar) con navegación por anclas (`#hero`, `#servicios`, `#vision`) que permite recorrer la página sin recargas.
* **Web Application:** Menú lateral izquierdo (Sidebar) que permite el salto directo entre los módulos operativos (Inventario, Ventas, Alertas) de manera constante.

<a name="nav-local"></a>
**b) Navegación local y contextual** </br>
Permite la exploración de contenidos específicos dentro de un módulo sin perder el contexto global:
* **Dashboard Contextual:** Desde las tarjetas de resumen (ej. "Stock Bajo"), el usuario puede hacer clic para navegar directamente a la lista filtrada de productos en riesgo.
* **Detalle de Producto:** Permite navegar entre la visualización de datos básicos y el historial específico de movimientos de ese ítem.

<a name="nav-sequential"></a>
**c) Navegación secuencial** </br>
Diseñada para procesos que requieren una serie de pasos lógicos y ordenados:
* **Proceso de Venta:** Carrito → Selección de pago → Confirmación.
* **Registro de Usuario:** Elección de plan → Datos del negocio → Configuración inicial de almacén.

<a name="nav-suplementaria"></a>
**d) Navegación suplementaria** </br>
Proporciona vías alternativas para encontrar información o realizar acciones rápidas:
* **Breadcrumbs:** Implementados en las vistas profundas de la aplicación para que el usuario pueda retornar fácilmente a los niveles superiores.


## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
<img src="assets/img/mock-ups/desktop/Landing_page_mock-up.jpeg" alt="Landing Page" width="900"/> <br>
### 4.3.2. Landing Page Mock-up
<img src="assets/img/mock-ups/desktop/Landing_page_mock-up.jpeg" alt="Landing Page" width="900"/> <br>

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes
<img src="assets/img/wireframes/desktop/Dashboard_desktop_wireframe.png" alt="Dashboard Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Iniciar_sesion_desktop_wireframe.png" alt="Iniciar Sesion Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Registro_desktop_wireframe.png" alt="Registro Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Productos_desktop_wireframe.png" alt="Productos Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Registro_productos_desktop_wireframe.png" alt="Registro Productos Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Registro_POS_desktop_wireframe.png" alt="Registro POS Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Movimientos_desktop_wireframe.png" alt="Movimientos Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Alertas_stock_desktop_wireframe.png" alt="Alertas Stock Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/desktop/Alertas_vencimiento_desktop_wireframe.png" alt="Alertas Vencimiento Desktop Wireframe" width="900"/> <br>
<img src="assets/img/wireframes/mobile/Inicio_sesion_mobile_wireframe.png" alt="Inicio Sesion Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Registro_1_mobile_wireframe.png" alt="Registro 1 Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Registro_2_mobile_wireframe.png" alt="Registro 2 Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Menu_mobile_wireframe.png" alt="Menu Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Dashboard_mobile_1_wireframe.png" alt="Dashboard Mobile 1 Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Dashboard_mobile_2_wireframe.png" alt="Dashboard Mobile 2 Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Nuevo_producto_mobile_wireframe.png" alt="Nuevo Producto Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Nuevo_producto_2_mobile_wireframe.png" alt="Nuevo Producto 2 Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Registrar_venta_POS_mobile_wireframe.png" alt="Registrar Venta POS Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Registrar_venta_POS_2_mobile_wireframe.png" alt="Registrar Venta POS 2 Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Movimientos_mobile_wireframe.png" alt="Movimientos Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Movimientos_mobile_2_wireframe.png" alt="Movimientos Mobile 2 Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Alertas_1_stock_mobile_wireframe.png" alt="Alertas 1 Stock Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Alertas_1_vencimiento_mobile_wireframe.png" alt="Alertas 1 Vencimiento Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Alertas_2_stock_mobile_wireframe.png" alt="Alertas 2 Stock Mobile Wireframe" width="300"/> <br>
<img src="assets/img/wireframes/mobile/Alertas_2_vencimiento_mobile_wireframe.png" alt="Alertas 2 Vencimiento Mobile Wireframe" width="300"/> <br>

#### Wireflow: Visualización del plan de suscripción adquirido y posible mejora 


######  User goal: 

Que el usuario pueda observar a todo detalle cuales son las funcionalidades que desbloquea dependiendo del tipo de suscripción que posea para luego evaluar cambiarlo.

###### US asociada: US06	-- Gestionar el plan contratado y sus límites

<img src="assets/img/wire1.png" alt="Design Level Event Storming - Qullqa" width="500"/>


#### Wireflow: Visualización del reporte y generación de archivos multimedia


###### User goal: 

Que el usuario pueda observar todas las métricas posibles dentro de su lógica del negocio. Luego, podrá realizar un reporte en un formato conocido resumiendo el reporte.

###### US asociada: US16 -Consultar y descargar reportes detallados

<img src="assets/img/wire2.png" alt="Design Level Event Storming - Qullqa" width="500"/>


### 4.4.3. Web Applications Mock-ups
<img src="assets/img/mock-ups/desktop/Dashboard_desktop.png" alt="Dashboard Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Iniciar_sesion_desktop.png" alt="Iniciar Sesion Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Registro_desktop.png" alt="Registro Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Productos_desktop.png" alt="Productos Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Registro_productos_desktop.png" alt="Registro Productos Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Registro_POS_desktop.png" alt="Registro POS Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Movimientos_desktop.png" alt="Movimientos Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Alertas_stock_desktop.png" alt="Alertas Stock Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/desktop/Alertas_vencimiento_desktop.png" alt="Alertas Vencimiento Desktop" width="900"/> <br>
<img src="assets/img/mock-ups/mobile/Inicio_sesion_mobile.png" alt="Inicio Sesion Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Registro_1_mobile.png" alt="Registro 1 Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Registro_2_mobile.png" alt="Registro 2 Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Menu_mobile.png" alt="Menu Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Dashboard_mobile_1.png" alt="Dashboard Mobile 1" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Dashboard_mobile_2.png" alt="Dashboard Mobile 2" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Nuevo_producto_mobile.png" alt="Nuevo Producto Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Nuevo_producto_2_mobile.png" alt="Nuevo Producto 2 Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Registrar_venta_POS_mobile.png" alt="Registrar Venta POS Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Registrar_venta_POS_2_mobile.png" alt="Registrar Venta POS 2 Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Alertas_1_mobile.png" alt="Alertas 1 Mobile" width="300"/> <br>
<img src="assets/img/mock-ups/mobile/Alertas_2_mobile.png" alt="Alertas 2 Mobile" width="300"/> <br>

### 4.4.4. Web Applications User Flow Diagrams

##### User goal: 

##### Userr flow: Visualización del plan de suscripción adquirido y posible mejora 


##### User goal: 

Que el usuario pueda observar a todo detalle cuales son las funcionalidades que desbloquea dependiendo del tipo de suscripción que posea para luego evaluar cambiarlo.


###### Descripción del flujo: 

Dashboard → Plan y Límites → Funciones y funcionalidades → Planes disponibles

###### Explicación del flujo:

El usuario, desde el dashboard principal puede entrar a visualizar el tipo de suscripción que posee en planes, para luego poder ingresar al apartado de planes disponibles para el caso que intente cambiar de plan. 


<img src="assets/img/userflow1.png" alt="Design Level Event Storming - Qullqa" width="500"/>


###### Elementos de diseño

El flujo utiliza tarjetas informativas, listas de funcionalidades y bloques de comparación de planes. Se incluyen etiquetas de estado (activo, límites), listas con iconos de verificación y secciones diferenciadas para funcionalidades y restricciones del sistema.

###### Aplicación de principios de diseño

Se aplica correctamente el principio de jerarquía al destacar el estado del plan actual en la parte superior. La proximidad agrupa funcionalidades disponibles y límites de uso en bloques diferenciados, lo que facilita su comprensión. La consistencia en iconografía y colores permite identificar rápidamente funcionalidades habilitadas y restricciones.

###### Diseño inclusivo

El diseño es claro y comprensible, utilizando lenguaje directo y visual (checks, etiquetas). Esto facilita la interpretación incluso para usuarios no técnicos. Como mejora, podría reforzarse el contraste en algunas secciones para asegurar accesibilidad visual en distintos contextos.

###### Arquitectura de la información

La estructura sigue una lógica clara:

Estado actual del usuario (plan activo)
Funcionalidades disponibles
Límites de uso
Métricas actuales del sistema
Comparación de planes

Esta organización permite que el usuario entienda primero su situación actual y luego evalúe posibles mejoras o cambios de plan.

###### Heurísticas de usabilidad

Se cumple el principio de transparencia del sistema, mostrando claramente límites y capacidades. También se evidencia control del usuario, al permitir evaluar y comparar planes antes de tomar una decisión. Como mejora, podría incorporarse mayor feedback en acciones como cambio de plan.

###### Information Architecture & Logistics

Desde el enfoque de arquitectura y logística, el flujo optimiza la toma de decisiones al presentar la información en un orden lógico: estado → capacidades → límites → comparación. Esto reduce la incertidumbre del usuario y facilita procesos como la actualización de suscripción o gestión de recursos del sistema.



###### Userr flow: Visualización del reporte y generación de archivos multimedia


###### User goal: 

Que el usuario pueda observar todas las métricas posibles dentro de su lógica del negocio. Luego, podrá realizar un reporte en un formato conocido resumiendo el reporte.


###### Descripción del flujo: 

Dashboard → Reportes→ Descargar reportes 

###### Explicación del flujo:

El usuario, desde el dashboard principal puede entrar a visualizar el apartado reportes para luego ir scroleando abajo del todo y encuentrar la opción que nos marca la descarga de un resumen de un reporte en formatos clásicos.



<img src="assets/img/userflow2.png" alt="Design Level Event Storming - Qullqa" width="500"/>


###### Elementos de diseño
El flujo presenta una interfaz basada en tarjetas informativas (cards), gráficos estadísticos y paneles de resumen. Se incluyen componentes como indicadores clave (KPIs), gráficos de líneas y barras, listas categorizadas y botones de descarga. La navegación es vertical y progresiva, permitiendo al usuario explorar desde métricas generales hasta detalles específicos.

###### Aplicación de principios de diseño
Se evidencia una adecuada jerarquía visual, donde los indicadores principales (ventas, productos, movimientos) se ubican en la parte superior, seguidos de visualizaciones más analíticas. El uso de tarjetas separadas refuerza el principio de proximidad, facilitando la agrupación de información relacionada. Además, la consistencia en colores y estilos contribuye a una experiencia uniforme.

###### Diseño inclusivo
El diseño prioriza la claridad mediante el uso de etiquetas descriptivas y estructuras simples. Los gráficos permiten una interpretación visual rápida, reduciendo la carga cognitiva. Sin embargo, podría mejorarse incorporando alternativas textuales más explícitas para usuarios con dificultades en la interpretación gráfica.

###### Arquitectura de la información
La información se organiza de manera jerárquica y progresiva:
Resumen general (KPIs)
Análisis temporal (ventas de la semana)
Comparativas (productos más vendidos)
Detalle operativo (inventario y categorías)
Acciones finales (descarga de reportes)
Esta estructura permite que el usuario pase de una visión global a un análisis detallado sin perder contexto, favoreciendo la toma de decisiones.


###### Heurísticas de usabilidad
El flujo cumple con el principio de visibilidad del estado del sistema, mostrando datos actualizados y comparativos. También favorece el reconocimiento sobre la memoria, al presentar información ya procesada visualmente. Como mejora, podría reforzarse el feedback al momento de interactuar con filtros o descargas.

###### Information Architecture & Logistics
Desde una perspectiva de arquitectura y logística de la información, el sistema organiza los datos según su valor operativo, priorizando primero los indicadores críticos y luego los elementos analíticos. El flujo permite una navegación eficiente entre análisis y acción, reduciendo fricción en tareas como evaluación del rendimiento o generación de reportes.


## 4.5. Web Applications Prototyping

  <div>
    <img src="assets/img/prototypes/prototipo_escritorio.png" alt="Prototipo Desktop - Qullqa" width="500"/>
  </div> <br>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414802_upc_edu_pe/IQD-6yWqUeH0Q6vF38H0ZKtyAWr8-l5OcorW5kveBpszCzE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=J1HICp)

  <div>
    <img src="assets/img/prototypes/prototipo_mobile.png" alt="Prototipo Mobile - Qullqa" width="500"/>
  </div> <br>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414802_upc_edu_pe/IQBRYjvsldiZRrHfLLrnWJFYAVI452UMLxj62G48YWe1Y5k?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=hTV8ws)


## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

En esta sección se presenta el Design-Level EventStorming de Qullqa, realizado con el fin de detallar y refinar el modelado del dominio identificado previamente. Durante la sesión, el equipo organizó eventos de dominio, comandos, políticas, agregados y bounded contexts relacionados con los principales procesos del sistema, como la gestión de inventario, ventas, alertas, almacenes, proveedores, reportes y suscripciones. Este análisis permitió comprender mejor las responsabilidades de cada contexto y sus relaciones, sirviendo como base para el diseño de la arquitectura del software.

**Design Level Event Storming - Qullqa**

  <div>
    <img src="assets/img/event_storming/design_level_event_storming.png" alt="Design Level Event Storming - Qullqa" width="500"/>
  </div> <br>

**Bounded Contexts**

Identity & Access Management <br>

 <div>
    <img src="assets/img/event_storming/dlev_identity_access_management.png" alt="Identity & Access Management - Qullqa" width="500"/>
  </div> 

<br>
Subscription & Plan Management <br>

 <div>
    <img src="assets/img/event_storming/dlev_subscription_plan_management.png" alt="Subscription & Plan Management - Qullqa" width="500"/>
  </div> 

<br>
Delivery Tracking <br>

 <div>
    <img src="assets/img/event_storming/dlev_delivery_tracking.png" alt="Delivery Tracking - Qullqa" width="500"/>
  </div> 

<br>
Product & Inventory Management <br>

 <div>
    <img src="assets/img/event_storming/dlev_product_inventory_management.png" alt="Product & Inventory Management - Qullqa" width="500"/>
  </div> 

<br>
Sales & POS Management <br>

 <div>
    <img src="assets/img/event_storming/dlev_sales_pos_management.png" alt="Sales & POS Management - Qullqa" width="500"/>
  </div> 

<br>
Alerts & Operational Monitoring <br>

 <div>
    <img src="assets/img/event_storming/dlev_alerts_operational_monitoring.png" alt="Alerts & Operational Monitoring - Qullqa" width="500"/>
  </div> 

<br>
Supplier & Replenishment Management <br>

 <div>
    <img src="assets/img/event_storming/dlev_supplier_replenishment_management.png" alt="Supplier & Replenishment Management - Qullqa" width="500"/>
  </div> 

<br>
Dashboard & Analytics <br>

 <div>
    <img src="assets/img/event_storming/dlev_dashboard_analytics.png" alt="Dashboard & Analytics - Qullqa" width="500"/>
  </div> 

### 4.6.2. Software Architecture Context Diagram

*Diagrama de contexto*

<img src="assets/img/d-contexto.png" alt="Dashboard & Analytics - Qullqa" width="500"/>

### 4.6.3. Software Architecture Container Diagrams

*Diagrama de contenedores*

<img src="assets/img/d-contenedores.png" alt="Dashboard & Analytics - Qullqa" width="500"/>

### 4.6.4. Software Architecture Components Diagrams

#### Diagrama de componentes

###### Diagrama de componentes de Access Management
<p align = "center">
<img src="assets/img/componentes-access.png" alt="access" width="500"/>

###### Diagrama de componentes de Billing
<p align = "center">
<img src="assets/img/componentes-billing.png" alt="billing" width="500"/>

###### Diagrama de componentes de Inventory Management
<p align = "center">
<img src="assets/img/componentes-inventory.png" alt="invent" width="500"/>

###### Diagrama de componentes de notifications
<p align = "center">
<img src="assets/img/componentes-notifications.png" alt="noti" width="500"/>

###### Diagrama de componentes de tracking
<p align = "center">
<img src="assets/img/componentes-tracking.png" alt="tracking" width="500"/>

###### Diagrama de componentes de sales
<p align = "center">
<img src="assets/img/componentes-sales.png" alt="sales" width="500"/>


## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<img src="assets/img/diagrams/class/Alerts_and_Supplier.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/Identity_and_Product.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/Product_and_Alerts.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/Product_and_Dashboard.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/Sales_and_Dashboard.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/subscription_and_delivery.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/diagrams/class/Supplier_and_Replenishment.png" alt="Class Diagram" width="1000"/> <br>

## 4.8. Database Design
<p align="justify">
  Para el proyecto, la elaboración del diagrama de base de datos resulta fundamental, ya que permite estructurar de manera clara y organizada todas las entidades, atributos y relaciones del sistema. Esto facilita la comprensión del funcionamiento de la plataforma, asegura una correcta gestión de la información y ayuda a prevenir errores en el desarrollo. Además, el diagrama sirve como guía durante la implementación, optimiza el diseño del sistema y contribuye a que la solución sea escalable y mantenible a lo largo del tiempo. Además, se decidió usar MySQL como motor de base de datos.
</p>

### 4.8.1. Database Diagrams
<p align="center">
  <img src="assets\img\diagrams\qullqa_database_diagram_.png" width="500" alt="Qullqa Database Diagram"/>
  <br/><i>Qullqa Database Diagram</i>
</p>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

A continuación se detallarán los productos de software que se han utilizado para el proyecto de acuerdo a las diferentes actividades realizadas.

**Project Management**

**WhatsApp:** Es una aplicación de mensajería instantánea que permite la comunicación asíncrona y coordinación rápida de tareas operativas entre los miembros del equipo. </br>
Referencia: https://web.whatsapp.com/

**Google Meet:** Es una plataforma de videoconferencias que permite realizar reuniones virtuales con audio, video y compartir pantalla. Se hizo uso de esta plataforma para la realización de ceremonias Scrum, reuniones de sincronización técnica y compartición de pantalla en tiempo real. </br>
Referencia: https://meet.google.com/

**Discord:** Es una plataforma de comunicación en línea que permite realizar llamadas, videollamadas y chats por canales. Lo utilizamos para reuniones rápidas entre los miembros disponibles del equipo y para resolver dudas de forma rápida. </br>
Referencia: https://discord.com/

---

**Product UX/UI Design**

**UXPressia:** Es una plataforma en línea especializada en el mapeo de la experiencia del usuario y diseño de servicios. Se usó para elaborar las user personas, user journey mapping, empathy mapping e impact mapping del proyecto. </br>
Referencia: https://uxpressia.com/

**Miro:** Es una pizarra colaborativa digital que permite crear diagramas y esquemas de forma visual y en tiempo real. Se usó para desarrollar sesiones de Event Storming para identificar procesos de negocio y definir Bounded Contexts. </br>
Referencia: https://miro.com/

**Figma:** Es un editor de gráficos vectoriales y herramienta de prototipado de interfaces basada principalmente en la web. Lo utilizamos para elaborar los wireframes, mockups y prototipos del proyecto. </br>
Referencia: https://www.figma.com/

**Jira:** Es un software de gestión de proyectos diseñado para equipos ágiles que utilizan Scrum o Kanban. Se usó para gestionar el Product Backlog, priorizar requerimientos y documentar las User Stories con sus criterios de aceptación. </br>
Referencia: https://www.atlassian.com/es/software/jira

---

**Software Development**

**Visual Studio Code:** Es un editor de código fuente ligero, altamente extensible y compatible con múltiples lenguajes de programación. Se usó para realizar ediciones rápidas, refactorización de scripts y desarrollo de componentes frontend específicos. </br>
Descargar: https://code.visualstudio.com/

---

**Software Deployment**

**GitHub:** Es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git y servicios de hosting. Se usó para alojar el código fuente del proyecto y gestionar el despliegue continuo de la Landing Page. </br>
Referencia: https://github.com/

---

**Software Documentation**

**GitHub:** Es una plataforma de control de versiones y colaboración en línea. Se usó para redactar, organizar y dar seguimiento al informe completo del proyecto. </br>
Referencia: https://github.com/

**Structurizr:** Es una herramienta para modelado de arquitectura de software mediante el enfoque C4. Lo utilizamos para construir los diagramas de arquitectura C4 del proyecto. </br>
Referencia: https://structurizr.com/

**Vertabelo:** Es una herramienta en línea para el diseño y modelado visual de bases de datos relacionales, que permite crear, compartir y exportar diagramas de forma colaborativa. Se usó para elaborar el diagrama de la base de datos del proyecto. </br>
Referencia: https://vertabelo.com/

---

### 5.1.2. Source Code Management

Para la gestión del código fuente y el control de versiones, el equipo utiliza **GitHub** como plataforma principal. Esta herramienta permite la colaboración distribuida y asegura la integridad de los artefactos digitales del proyecto.

**Repositorios del Proyecto:** </br>
Landing Page: https://github.com/Flowbit-app/Qullqa-LandingPage

**Estrategia de Flujo de Trabajo (GitFlow):** </br>
El equipo adoptará formalmente el modelo **GitFlow** para mantener un ciclo de vida profesional. Se utilizarán dos ramas principales de larga duración:
* **`main`:** Almacena exclusivamente versiones estables y probadas del software (versiones listas para producción).
* **`develop`:** Funciona como la rama de integración principal donde se consolidan las funcionalidades antes de un lanzamiento.

Para el desarrollo dinámico, se aplicarán las siguientes convenciones de ramificación:
* **Feature branches:** Utilizadas para desarrollar nuevas funcionalidades. Ejemplo: `feature/landing-page-services`.
* **Release branches:** Ramas temporales creadas desde `develop` para preparar el despliegue de una nueva versión (`v1.0.0`, `v1.1.0`, etc.).
* **Hotfix branches:** Ramas de emergencia creadas desde `main` para corregir errores críticos en producción que no pueden esperar al siguiente ciclo de desarrollo.

**Convención de Mensajes de Commit:** </br>
Se implementa el estándar de **Conventional Commits** con el formato obligatorio: `<type>(<scope>): <description>`.
* `feat`: Para la implementación de nuevas características.
* `fix`: Para la corrección de errores de código.
* `docs`: Para cambios exclusivos en la documentación.
* `style`: Para cambios que no afectan la lógica del código (formato, CSS, espacios).
* `refactor`: Para cambios en el código que no corrigen errores ni añaden funciones.

**Versionamiento Semántico (Semantic Versioning):** </br>
El equipo utiliza el formato `vMAJOR.MINOR.PATCH` para identificar las versiones del producto:
* `MAJOR`: Incrementado en cambios que rompen la compatibilidad (ej. `v2.0.0`).
* `MINOR`: Incrementado al añadir funcionalidades compatibles (ej. `v1.1.0`).
* `PATCH`: Incrementado al realizar correcciones de errores menores (ej. `v1.0.1`).

---

### 5.1.3. Source Code Style Guide & Conventions

**1. HTML**
* **Lower-case Element Names:** Los nombres de etiquetas deben estar en minúsculas para mantener la consistencia con los estándares de la W3C. Ejemplo: `<div>` en lugar de `<DIV>`.
* **Close All Elements:** Todo elemento HTML debe cerrarse correctamente para evitar errores de renderizado. Ejemplo: `<p>Update stock.</p>`.
* **Lowercase Attribute Names:** Atributos como `class`, `id`, `src` y `href` deben escribirse en minúsculas. Ejemplo: `<img class="inventory-icon" ... />`.
* **Alt, Width, and Height for Images:** Es obligatorio especificar el atributo `alt` por accesibilidad y las dimensiones para optimizar el Cumulative Layout Shift (CLS).
* **Spaces and Equal Signs:** Se evita el uso de espacios alrededor del signo igual en los atributos. Ejemplo: `type="text"` en lugar de `type = "text"`.

**2. CSS**
* **Naming Style (Kebab-case):** Se utilizarán nombres significativos y descriptivos usando el formato kebab-case. Ejemplo: `#inventory-dashboard`, `.product-card-title`.
* **Shorthand Properties:** Se prioriza el uso de propiedades abreviadas para reducir el peso del archivo. Ejemplo: `padding: 10px 5px;`.
* **0 and Units:** Se omite la unidad de medida cuando el valor es `0`. Ejemplo: `margin: 0;`.
* **Declaration Order:** Las propiedades se ordenan alfabéticamente para facilitar la edición y mantenimiento por múltiples desarrolladores.

**3. JavaScript**
* **Variable and Function Naming:** Se aplica el formato `lowerCamelCase`. Los nombres deben ser verbos para funciones y sustantivos para variables. Ejemplo: `let productPrice = 25.50;`, `function updateInventoryStock() { ... }`.
* **Declaration (ES6+):** Se prohíbe el uso de `var`. Solo se permite `const` para valores inmutables y `let` para variables con ámbito de bloque.
* **Expanded Syntax:** Las llaves de apertura se colocan en la misma línea que la declaración, y las de cierre en una línea nueva.

**4. C#**
* **PascalCase:** Utilizado obligatoriamente para nombres de clases, namespaces y métodos. Ejemplo: `public class InventoryManager { public void SaveProduct() { ... } }`.
* **camelCase:** Utilizado para parámetros de métodos y variables locales. Ejemplo: `int currentStockCount = 50;`.
* **Single Responsibility Principle:** Cada clase o método debe realizar una única tarea bien definida dentro de la lógica de Qullqa.
* **Comments & Documentation:** Uso de comentarios XML (`///`) para documentar el propósito de métodos complejos y clases.

**5. Gherkin**
* **Given-When-Then Structure:** Se sigue estrictamente esta estructura para definir el comportamiento del sistema desde la perspectiva del usuario.
* **Business-Readable Language:** Los escenarios deben redactarse en un lenguaje comprensible para el usuario final, evitando tecnicismos.
* **Scenario Outline:** Se utiliza para pruebas masivas con diferentes juegos de datos.

```gherkin
Scenario Outline: Product stock alert
  Given the store owner is in the inventory dashboard
  When the stock of "<product>" falls below <threshold>
  Then the system should display a "Low Stock" alert
  Examples:
    | product | threshold |
    | Rice    | 10        |
    | Milk    | 5         |
```
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

En este apartado se documenta la ejecución técnica de QULLQA, abarcando desde la construcción de la Landing Page informativa hasta el despliegue de los microservicios y la aplicación web para bodegas y farmacias. Siguiendo el orden de prioridad de nuestro Product Backlog, el desarrollo se ha ejecutado en iteraciones ágiles, asegurando que funcionalidades como la autenticación de usuarios sean implementadas bajo estándares de diseño adaptable (Responsive Web Design) y desplegadas en la nube de forma progresiva.

### 5.2.1. Sprint 1

Este primer ciclo de desarrollo se centró en establecer los pilares operativos de QULLQA, integrando el esfuerzo colaborativo para entregar un producto funcional inicial. Durante este Sprint, el equipo priorizó la captación de usuarios mediante la Landing Page, documentando cada fase desde la planificación hasta el despliegue final para validar la funcionalidad base del sistema.

#### 5.2.1.1. Sprint Planning 1

El Sprint Planning Meeting marcó el inicio formal del desarrollo del código de QULLCA. Durante esta sesión, el equipo de desarrollo junto al Product Owner seleccionaron las Historias de Usuario más prioritarias del Product Backlog para definir el objetivo central de la iteración. A continuación, se presenta el cuadro resumen con los detalles y acuerdos de esta reunión:

| **Sprint #** | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2026-04-18 |
| **Time** | 9:00 AM |
| **Location** | Cubiculo - Pabellon L |
| **Prepared By** | Arturo Valentino Contreras Torres  |
| **Attendees (to planning meeting)** | Asmat Alminco, Martin Alejandro / Contreras Torres, Arturo Valentino / Güere Calero, Fernando Julio / Huaman Oscco, Aldo Jesus / Ramos Fuentes Rivera, Adriana Nicole |
| **Sprint n – 1 Review Summary** | Al ser el primer Sprint de desarrollo, la revisión anterior corresponde a la fase de ideación. Resultados alcanzados: arquitectura C4 finalizada, modelado de base de datos diseñada y repositorios GitHub configurados para el uso de gitflow. El Product Owner brindó el feedback necesario para iniciar la codificación orientada al dominio y siguiendo como base las User Storys. |
| **Sprint n – 1 Retrospective Summary** | Como retrospectiva inicial de la forma de trabajo, el equipo identificó como acierto el uso de diagramas compartidos, el uso de herramientas colaborativos como GitHub y Jira, pero reconoció como oportunidad de mejora establecer reglas más estrictas de GitFlow para evitar colisiones en los Pull Requests futuros. |
| **Sprint Goal & User Stories** | |
| **Sprint n Goal** | **Contexto:** El equipo de producto de QULLQA ha decidido priorizar el establecimiento de la identidad digital de la plataforma y la seguridad de acceso para los primeros usuarios. El esfuerzo se centra en comunicar de manera efectiva la propuesta de valor diferenciada para dueños de bodegas independientes (enfocada en control de stock) y farmacias (enfocada en vencimientos). Asimismo, se implementará el sistema base de gestión de identidad para permitir que los usuarios reales comiencen a interactuar con el módulo de inventario, transformando el diseño de arquitectura y mock-ups previos en un entorno funcional y seguro. <br><br> **Sprint Goal:**<br>*“Our focus is on establishing a trustworthy digital presence and a secure entry point for our initial business owners. We believe it delivers clarity on the product’s value proposition to prospective customers and a reliable onboarding experience to independent store and pharmacy owners.This will be confirmed when visitors can identify specific benefits for their business segment on the Landing Page, and administrators (like Carlos and Carmen) can successfully register, log in, and perform the initial registration of their product catalog without errors.” |
| **Sprint n Velocity** | 25 Story Points. (Velocidad estimada basada en la capacidad inicial del equipo para configurar los entornos y desarrollar los módulos de autenticación básicos). |
| **Sum of Story Points** | 12 Story Points. |

#### 5.2.1.2. Aspect Leaders and Collaborators

* En esta sección se presenta la **Leadership-and-Collaboration Matrix (LACX)**. Esta matriz detalla los líderes (L) y colaboradores (C) para cada aspecto clave del Sprint, asegurando una comunicación clara y una distribución de responsabilidades eficiente para el proyecto **SmartLock**.

La organización de líderes y colaboradores está directamente relacionada con la selección de tareas (tasks) que se desarrollarán durante el Sprint.

| Team Member | GitHub Username | Arquitectura & DDD (L/C) | Desarrollo Backend & API (L/C) | Simulacion IoT & Hardware (L/C) | Frontend & UI/UX (L/C) | QA & Testing (L/C) |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| Asmat Alminco, Martin Alejandro | Alemarr2 | C | C | C | C | L |
| Contreras Torres, Arturo Valentino | Arturouu  | L | C | C | C | C |
| Güere Calero, Fernando Julio | FerG17 | C | C | L | C | C |
| Huaman Oscco, Aldo Jesus | Jesusho22 | C | C | C | L | C |
| Ramos Fuentes Rivera, Adriana Nicole | Adriana832 | C | L | C | C | C |
---

> **Leyenda:**  </br>
> **L:** Lider (Líder del aspecto)  
> **C:** Colaborador (Colaborador y desarrollo)

#### 5.2.1.3. Sprint Backlog 1

**Periodo:** 6 de abril – 4 de mayo  
**Objetivo del Sprint:** Tener la landing funcional con usuarios reales accediendo y mostrando interes, estableciendo la base visual y funcional de QULLQA.

---

| **User Story Id** | **Título de la Historia** | **Task Id** | **Título de la Tarea** | **Descripción de la Tarea** | **Est. (Hrs)** | **Asignado** | **Status** |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :---: |
| **QULLQA-13** | Registrarse e iniciar sesión | T-13-1 | Diseño de formularios | Crear la interfaz visual para el registro de nuevos dueños y el acceso seguro. | 6 | Usuario | To-Do |
| | | T-13-2 | Lógica de autenticación | Programar la validación de credenciales y creación de cuentas en la base de datos. | 8 | Usuario | To-Do |
| | | T-13-3 | Pruebas de acceso | Verificar que el usuario pueda entrar y salir de su sesión correctamente. | 3 | Usuario | To-Do |
| **QULLQA-15** | Registrar producto | T-15-1 | Formulario de datos | Implementar el formulario para ingresar nombre, precio, stock y categoría del producto. | 6 | Usuario | To-Do |
| | | T-15-2 | Guardado en inventario | Configurar el envío de datos para que el producto aparezca en la lista oficial. | 5 | Usuario | To-Do |
| **QULLQA-16** | Actualizar producto y precio | T-16-1 | Función de edición | Habilitar el botón de editar para cargar los datos actuales en el formulario. | 4 | Usuario | To-Do |
| | | T-16-2 | Actualización de costos | Programar el cambio de precios en tiempo real para reflejar datos actuales. | 4 | Usuario | To-Do |
| **QULLQA-17** | Consultar lista de productos y disponibilidad | T-17-1 | Vista de tabla principal | Crear la pantalla donde se listan todos los productos registrados. | 7 | Usuario | To-Do |
| | | T-17-2 | Buscador de stock | Implementar una barra de búsqueda para filtrar productos por nombre o código. | 4 | Usuario | To-Do |
| **QULLQA-09** | Conocer la propuesta de valor para bodegueros | T-09-1 | Redacción de beneficios | Escribir los textos que explican cómo Qullqa ayuda específicamente a las bodegas. | 3 | Usuario | To-Do |
| | | T-09-2 | Diseño sección Bodegas | Crear el bloque visual en la landing page enfocado en el segmento bodeguero. | 5 | Usuario | To-Do |
| **QULLQA-10** | Conocer la propuesta de valor para farmacias | T-10-1 | Contenido especializado | Redactar la sección sobre control de vencimientos y reposición de medicamentos. | 3 | Usuario | To-Do |
| | | T-10-2 | Diseño sección Farmacias | Implementar los elementos gráficos que representen el valor para el sector farmacéutico. | 5 | Usuario | To-Do |
| **QULLQA-12** | Redirigirse desde la Landing Page hacia la aplicación | T-12-1 | Configuración de botones | Crear y enlazar los botones de "Empezar" o "Login" en la página principal. | 2 | Usuario | To-Do |
| | | T-12-2 | Flujo de navegación | Asegurar que al hacer clic, el usuario llegue a la pantalla correcta de la app. | 2 | Usuario | To-Do |
| **TOTAL** | | | | **Esfuerzo total estimado para el Sprint** | **77** | | |

---

<p align="center">
  <img src="assets/img/artefacts/sprint.png" width="800" alt="Product Backlog"/>
  <br/><i>Artefacto: Jira para Sprint Priorizado</i>
</p>

##### Resumen Técnico
- **Total de Horas:** 77 horas.
- **Distribución:** 2 semanas de desarrollo (considerando jornada laboral estándar).
- **Entregable Principal:** Aplicación base con Landing Page informativa y módulo funcional de inventario (CRUD de productos).

---

#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

Romero, P. (2024, 10 de enero). Retos para impulsar la expansión de las billeteras digitales en las bodegas peruanas. Conexión ESAN. Recuperado de https://www.esan.edu.pe/conexion-esan/retos-para-impulsar-la-expansion-de-las-billeteras-digitales-en-las-bodegas-peruanas

Delgado, R. S. B., & Lopez, H. Y. B., (2024). Modelo PDCA para incrementar el índice de rotación de inventario aplicando la clasificación ABC-SLP, Kanban y Conteo Cíclico en una pequeña empresa de comercio farmacéutico [Tesis de maestría, Universidad Peruana de Ciencias Aplicadas]. Repositorio Académico UPC. https://repositorioacademico.upc.edu.pe/handle/10757/682410

Mendoza, B. J. F., & Anchiraico, B. W. R., (2018). Determinación de patrones de ventas en boticas independientes para mejorar las ventas [Tesis de maestría, Universidad San Ignacio de Loyola]. Repositorio Académico USIL. https://hdl.handle.net/20.500.14005/8591

# Anexos
