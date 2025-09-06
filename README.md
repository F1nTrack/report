<!--* caratula -->

<div align="center">

# Informe Trabajo Final 📙

<img src="./resources/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas ♨️

🧑‍💻 Ingeniería de software - 2025-02

**Sección:** 7414

**Docente:** Alex Humberto Sánchez Ponce

**StartUp:** F1nTrack

**Producto:** Undefined

<div align='left'>	

~~~C#
static string[] Integrantes() {
    return new string[] {
        "🧑‍💻 Taquiri Calderon, Jhunior Giussepe - u20221C576",
        "👩‍💻 Tasayco Osorio, Raul Hiroshi - U202319415",
        "👩‍💻 Ruiz Huisa, Daniel Elias - U202210764",
        "👩‍💻 Salcedo Champi, Matias Rodolfo - u202319698 ",
        "👩‍💻 Quiroz Zambrano, Fabrizio Javier - u202213406", 
    };
}
~~~


## Contenido del Informe

- [Informe Trabajo Final 📙](#informe-trabajo-final-)
    - [Universidad Peruana de Ciencias Aplicadas ♨️](#universidad-peruana-de-ciencias-aplicadas-️)
  - [Contenido del Informe](#contenido-del-informe)
    - [1.2.2 Lean Ux Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [Business Outcomes 📊:](#business-outcomes-)
      - [User Outcomes 🙋](#user-outcomes-)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
      - [Segmentos Objetivos:](#segmentos-objetivos)
- [Capítulo II: Requeriments Elicitation \& Analysis](#capítulo-ii-requeriments-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [¿Por qué llevar a cabo este análisis?](#por-qué-llevar-a-cabo-este-análisis)
    - [2.1.1 Análisis competitivo (Comparativa)](#211-análisis-competitivo-comparativa)
    - [**¿Por qué KapakID es superior?**](#por-qué-kapakid-es-superior)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
      - [Preguntas:](#preguntas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
    - [Identity \& Documents (Identidad y Documentos)](#identity--documents-identidad-y-documentos)
    - [Transportation \& Cards (Transporte y Tarjetas)](#transportation--cards-transporte-y-tarjetas)
    - [Payments \& Transactions (Pagos y Transacciones)](#payments--transactions-pagos-y-transacciones)
    - [Governance \& Voting (Gobernanza y Votaciones)](#governance--voting-gobernanza-y-votaciones)
    - [Notifications \& Alerts (Notificaciones y Alertas)](#notifications--alerts-notificaciones-y-alertas)
    - [Access \& Profiles (Acceso y Perfiles)](#access--profiles-acceso-y-perfiles)
- [Capítulo III: Requeriments Specification](#capítulo-iii-requeriments-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Desing](#capítulo-iv-product-desing)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Desing](#43-landing-page-ui-desing)
    - [4.3.1. Landing Page Wireframes](#431-landing-page-wireframes)
    - [4.3.2. Landing Page Mock-Up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Desing](#44-web-applications-uxui-desing)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagram](#462-software-architecture-container-diagram)
    - [4.6.3. Software Architecture Components Diagram](#463-software-architecture-components-diagram)
  - [4.7. Software Object-Oriented Desing](#47-software-object-oriented-desing)
    - [4.7.1. Class Diagram](#471-class-diagram)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Desing](#48-database-desing)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Service \& Applications Implementation](#52-landing-page-service--applications-implementation)
    - [5.2.x. Sprints](#52x-sprints)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)


</div>
<div align='left'>
<!-- student outcome -->
<section id="startup-profile">
  <h2>1.1 Startup Profile</h2>

  <!-- 1.1.1 Descripción de la Startup -->
  <article id="descripcion-startup">
    <h3>1.1.1. Descripción de la Startup</h3>
    <p>
      <strong>F1nTrack</strong> es una startup enfocada en desarrollar soluciones
      tecnológicas para la <strong>gestión personal y empresarial de finanzas</strong>. Nuestro objetivo
      es ayudar a los usuarios a controlar ingresos, egresos, presupuestos y metas financieras mediante
      una aplicación web intuitiva y escalable.
    </p>
    <p>Propuesta de valor:</p>
    <ul>
      <li>Visualizaciones claras y amigables del estado financiero.</li>
      <li>Registro ágil de ingresos y gastos (manual y con importación de datos).</li>
      <li>Seguimiento de <em>metas financieras</em> personalizadas.</li>
      <li>Reportes y alertas para una toma de decisiones informada.</li>
    </ul>
    <p>
      Con F1nTrack buscamos fomentar la <strong>educación financiera</strong> y apoyar a estudiantes,
      profesionales y emprendedores en decisiones responsables sobre su economía.
    </p>
    <p>
      Como misión nos proponemos a brindar soluciones tecnológicas accesibles e innovadoras que permitan a personas, estudiantes,
      profesionales y pequeñas empresas <strong>gestionar de manera eficiente sus finanzas</strong>,
      facilitando el control de ingresos, egresos, presupuestos y metas económicas a través de una
      plataforma web intuitiva, confiable y educativa.
    </p>
    <p>
      Nuestra visión es convertirnos en la <strong>plataforma líder en educación y gestión financiera digital en Latinoamérica</strong>,
      reconocida por ayudar a nuestros usuarios a <em>tomar decisiones financieras inteligentes y responsables</em>,
      contribuyendo a su bienestar económico y al crecimiento sostenible de sus proyectos y negocios.
    </p>
  </article>

</div>
<div align='left'>
<h3>1.1.2. Perfiles de los integrantes del grupo</h3>
<div align='center'>
   <!--TODO: integrante 1 -->
  > 🧑‍💻 <strong>Matias Rodolfo Salcedo Champi</strong> 
   

   <div align='center'>
     
   <img src="resources/matias.png" alt="imagen Matias" width="100" align='right'>

   ~~~txt
   Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente cursando el 5to ciclo de la carrera.
   
   Durante mi formación he adquirido conocimientos en diversas tecnologías y buenas prácticas de desarrollo. Mis principales fortalezas se encuentran en C++, HTML y Java, lenguajes en los que me desenvuelvo con mayor seguridad, aplicando conceptos de programación estructurada y orientada a objetos, así como el diseño de interfaces y el desarrollo de aplicaciones.

   Adicionalmente, he trabajado con SQL para la gestión de bases de datos, y con tecnologías web que me permiten tener una visión integral del desarrollo de software.

   Me considero una persona responsable, comprometida y con facilidad para el trabajo en equipo, cualidades que me impulsan a mejorar constantemente.

   Mis expectativas para el curso de Aplicaciones Web son muy altas, ya que representa una gran oportunidad para ampliar mis conocimientos tanto en frontend como en backend, explorando nuevos frameworks como Vue, que complementarán mi formación y me permitirán crecer profesionalmente en el campo del desarrollo web. 💻
   ~~~

   </div>
  
   <!--TODO: integrante 2 -->
**> 🧑‍💻 Raul Hiroshi Tasayco Osorio**
   <div align='center'>

   <img src="resources/Image_raul_tasayco.png" alt="imagen Raul" width="100" align='right'>

   ~~~txt
   Soy un estudiante de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC),
   actualmente me encuentro cursando el 6to ciclo de la carrera.
    
    A lo largo del tiempo que me encuentro en la carrera pude aprender diferentes tecnologías, tanto lenguajes de programación, buenas prácticas de desarrollo, estructuras de datos, normalización de base de datos, así como su uso, finalmente Frameworks como mi Angular en el cual me desempeño en el Frontend:
      1️⃣ C++     
      2️⃣ Python  
      3️⃣ SQL     
      4️⃣ Angular    
      5️⃣ HTML,CSS & TS     
    Me considero una persona responsable, listo para trabajar en equipo y con un fuerte compromiso con todos mis deberes. 
    
    Mis expectativas para el curso de Aplicaciones Web son muy altas, puesto que es un curso en el cual aprenderé diferentes habilidades tanto frontend como backend, con un nuevo Framework el cual es Vue. 💻
   ~~~

   </div>

   <!--TODO: integrante 3 -->
**> 🧑‍💻 Nombre del alumno3**
   <div align='center'>

   <img src="" alt="" width="100" align='right'>

   ~~~txt
   
   ~~~

   </div>

   <!--TODO: integrante 4 -->
**> 🧑‍💻Jhunior Giussepe Taquiri Calderon (U20221C676)**
   <div align='center'>

   <img src="resources/giussepe.png" alt="imagen Giussepe" width="100" align='right'>
  

   ~~~txt
   Soy estudiante del sexto ciclo de Ingeniería de Software en la UPC, con una formación orientada al desarrollo de software y al uso de diversas tecnologías.
    Tengo experiencia en C++, Python, Java y SQL, además de bases en HTML, CSS y JavaScript, lo que me ha permitido trabajar tanto en lógica de programación como en aspectos de desarrollo web.
    Me considero una persona responsable, organizada y comprometida, con facilidad para el trabajo en equipo y con interés en seguir aprendiendo para fortalecer mi perfil profesional.
    Mis expectativas para el curso de Aplicaciones Web son muy altas, ya que representa una oportunidad para profundizar en el desarrollo frontend y backend, así como para aprender
    nuevos frameworks como Vue, que serán de gran valor en mi futuro como desarrollador.
   ~~~

   </div>
   <!--TODO: integrante 5 -->

**> 🧑‍💻 Fabrizio Javier Quiroz Zambrano (U202213406)**
   <div align='center'>

   <img src="resources/Fabrizio1.jpg" alt="imagen Raul" width="100" align='right'>

   ~~~txt
    Actualmente curso el sexto ciclo de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), donde he venido desarrollando una sólida base técnica y una visión crítica
    sobre el desarrollo de soluciones digitales. Mi formación me ha permitido explorar distintos lenguajes y herramientas, desde la lógica estructurada de C++ hasta el dinamismo de frameworks
    modernos como Angular, con los que he trabajado principalmente en el frontend. También tengo experiencia en Python y SQL, lo que me ha ayudado a comprender mejor la gestión de datos y la
    construcción de aplicaciones más completas.

    Más allá de lo técnico, me considero una persona comprometida con el aprendizaje constante, con facilidad para adaptarme a nuevos entornos y colaborar en equipo. Me gusta enfrentar desafíos
    que me obliguen a pensar fuera de lo convencional y a buscar soluciones eficientes y sostenibles.

    Tengo grandes expectativas para el curso de Aplicaciones Web, ya que representa una oportunidad para fortalecer mis habilidades en el desarrollo fullstack y familiarizarme con nuevas tecnologías
    como Vue. Estoy convencido de que este tipo de experiencias me acercan cada vez más al perfil profesional que quiero construir: uno capaz de crear software útil, escalable y centrado en las personas.
   ~~~

   </div>
   
<!-- 1.2.1 Antecedentes y problemática -->
<div align='left'>
<article id="solution-profile">

<h2>1.2. Solution profile</h2>
<article id="antecedentes-problematica">
  <h3>1.2.1 Antecedentes y problemática</h3>
  <p>
    En la actualidad, muchas personas y pequeñas empresas enfrentan dificultades al momento de 
    <strong>gestionar adecuadamente sus finanzas</strong>. La falta de educación financiera, el desorden en 
    el registro de ingresos y egresos, así como la ausencia de herramientas tecnológicas accesibles y fáciles 
    de usar, generan problemas de liquidez, endeudamiento innecesario y poca claridad en la toma de decisiones 
    económicas. 
  </p>
  <p>
    Frente a esta problemática surge la necesidad de contar con soluciones digitales prácticas que ayuden a 
    los usuarios a tener una visión clara, organizada y en tiempo real de su situación financiera.
  </p>

  <h4>5“W”s + 2"H"</h4>
  <ul>
    <li>
       <strong>WHAT (QUÉ):</strong>  
      El problema principal es la <strong>dificultad de gestionar finanzas personales y empresariales</strong>.  
      Muchos usuarios no llevan un control adecuado de sus ingresos, egresos ni presupuestos, lo que genera desorden, 
      desconocimiento de su estado financiero real y problemas para alcanzar metas económicas.
    </li>
    <br>
    <li>
       <strong>WHEN (CUÁNDO):</strong>  
      Este problema ocurre <strong>de manera constante y cotidiana</strong>.  
      Se hace más notorio en etapas de crecimiento (por ejemplo, cuando una persona comienza a generar más ingresos o 
      cuando un negocio aumenta sus operaciones), así como en momentos de desorganización financiera que pueden 
      derivar en deudas y falta de liquidez.
    </li>
    <br>
    <li>
       <strong>WHERE (DÓNDE):</strong>  
      El problema se da en distintos <strong>contextos</strong>:  
      - En el ámbito <em>personal</em>, al no saber administrar gastos diarios o planificar metas de ahorro.  
      - En el ámbito <em>académico</em>, entre estudiantes que manejan becas, préstamos o presupuestos limitados.  
      - En el ámbito <em>empresarial</em>, especialmente en micro y pequeñas empresas que carecen de un área contable formal.
    </li>
    <br>
    <li>
       <strong>WHO (QUIÉN):</strong>  
      Los principales afectados son:  
      - <strong>Personas naturales</strong> que carecen de educación financiera básica.  
      - <strong>Estudiantes y profesionales</strong> que quieren administrar mejor sus recursos.  
      - <strong>Emprendedores y pequeñas empresas</strong> que no cuentan con presupuesto para contratar un contador o comprar 
      software financiero costoso.
    </li>
    <br>
    <li>
       <strong>WHY (POR QUÉ):</strong>  
      Porque actualmente <strong>no existen herramientas accesibles, educativas y fáciles de usar</strong> que integren de manera 
      eficiente el control de ingresos, egresos, presupuestos y metas financieras.  
      Las soluciones existentes suelen ser:  
      - Demasiado técnicas y complejas para usuarios no especializados.  
      - Costosas para estudiantes y pequeñas empresas.  
      - Poco personalizables a las necesidades reales de cada usuario.
    </li>
    <br>
    <li>
       <strong>HOW (CÓMO):</strong>  
      La solución se plantea mediante el desarrollo de una <strong>aplicación web</strong> que:  
      - Permita registrar ingresos y egresos de forma ágil (manual o automática).  
      - Genere visualizaciones gráficas que faciliten la comprensión de la situación financiera.  
      - Ofrezca seguimiento de presupuestos y metas financieras personalizadas.  
      - Envíe reportes y alertas para apoyar la toma de decisiones responsables.
    </li>
    <br>
    <li>
       <strong>HOW MUCH (CUÁNTO):</strong>  
      Actualmente, contratar un contador o adquirir software especializado supone un <strong>costo elevado</strong>, inaccesible 
      para estudiantes y pequeñas empresas.  
      F1nTrack busca ofrecer una solución <strong>económica y escalable</strong>, con un modelo de bajo costo o incluso 
      gratuito en sus funciones básicas, para que más usuarios puedan acceder a herramientas de gestión financiera 
      sin una gran inversión inicial.
    </li>
  </ul>
</article>
___

### 1.2.2 Lean Ux Process
#### 1.2.2.1. Lean UX Problem Statements
 
Actualmente, personas particulares, emprendedores y pequeñas empresas enfrentan grandes problemas para gestionar sus finanzas de manera efectiva, ya que no cuentan con los conocimientos, recursos o herramientas necesarias para administrar lo que vienen a ser sus ingresos, gastos, proyecciones y metas financieras. Esto se debe a varios factores, entre ellos tenemos: la falta de educación financiera, el alto costo de contratar expertos en el área y la complejidad de soluciones existentes no adaptadas a sus necesidades, lo que resulta en desequilibrios presupuestarios, decisiones inciertas y dificultades para alcanzar objetivos financieros. <br>

Nosotros consideramos que estos segmentos objetivo necesitan una solución integral y eficiente que les permita tomar el control de sus finanzas sin tener la necesidad de depender de recursos externos que sean demasiado costosos. Por ello, FinTrack resuelve este problema mediante una aplicación web intuitiva, para que cualquier persona pueda usar de esta, que ofrece gestión automatizada de ingresos y gastos, proyecciones financieras basadas en datos históricos que se recopiló, establecimiento de metas y objetivos personalizados, como ahorros, rentabilidad o reducción de deudas, herramientas para simular y gestionar préstamos, y un dashboard home que destaca datos clave como saldos, flujo de dinero, alertas de gastos inusuales y progreso hacia metas. Sabremos que hemos tenido éxito cuando los usuarios reporten una reducción considerable en gastos innecesarios, un aumento significativo en la adherencia a metas financieras y una mejora en la satisfacción con la gestión financiera dentro de los primeros tres meses de uso.

#### 1.2.2.2. Lean UX Assumptions

#### Business Outcomes 📊:


* **🔵 Crecimiento de la Base de Usuarios**<br>

    FinTrack busca atraer a personas particulares, emprendedores y pequeñas empresas con campañas de marketing que resalten la facilidad de uso de la plataforma. Su diseño intuitivo y herramientas como el dashboard home y proyecciones fomentarán una adopción amplia y sostenida.

* **🔵 Alta Retención de Usuarios**<br>

    BUscamos retener a los usuarios comprometidos con una experiencia fluida y funcionalidades valiosas como metas personalizadas y alertas de gastos. El dashboard home, claro y accesible, asegurará que los usuarios integren la plataforma en su rutina financiera.

* **🔵 Ingresos por Suscripciones Premium**<br>

    Generaremos ingresos a través de suscripciones premium, con funciones avanzadas como proyecciones detalladas y análisis de préstamos. Estas herramientas motivarán a los usuarios a optar por planes pagos para mejorar su gestión financiera.

* **🔵 Minimización del Churn Rate**<br>

    Reducir la pérdida de usuarios es clave, incluso imprescindible, para FinTrack. Con un dashboard home útil y herramientas como metas y proyecciones, la plataforma ofrecerá valor continuo, manteniendo a los usuarios leales y comprometidos a largo plazo.

* **🔵 Satisfacción del Usuario (NPS)**<br>

    FinTrack maximizará la satisfacción con una interfaz intuitiva y funciones prácticas como el dashboard home y gestión de préstamos. La retroalimentación constante permitirá ajustar la plataforma para superar las expectativas de los usuarios.

* **🔵 Adopción de Proyecciones Financieras**<br>

     Fomentaremos el uso de proyecciones financieras, ayudando a los usuarios a planificar con datos históricos. Integrada en el dashboard home, esta herramienta será clave para que personas y empresas tomen decisiones estratégicas.

* **🔵 Establecimiento de Metas Financieras**<br>

     Buscaremos motivar a los usuarios a definir metas, como ahorrar o reducir deudas, con una interfaz sencilla y notificaciones motivadoras en el dashboard home. Esto convertirá a la plataforma en un aliado para el éxito financiero de cualquier negocio.

* **🔵 Optimización de Costos Empresariales**<br>

     FinTrack ayudará a pequeñas empresas a optimizar costos con herramientas de gestión de gastos e ingresos y reportes en el dashboard home. Recomendaciones personalizadas apoyarán la estabilidad y el crecimiento financiero.

* **🔵 Precisión en Proyecciones de Emprendedores**<br>

     FinTrack mejorará las proyecciones de emprendedores con datos históricos y escenarios confiables, accesibles desde el dashboard home. Esto les permitirá planificar estratégicamente y reducir riesgos en sus proyectos.

* **🔵 Usuarios Activos en Pequeñas Empresas**<br>

     FinTrack atraerá a pequeñas empresas con herramientas colaborativas y un  dashboard home intuitivo. Su enfoque asequible y escalable lo convertirá en la opción ideal para gestionar finanzas empresariales.

* **🔵 Uso de Gestión de Préstamos**<br>

     FinTrack promoverá el uso de su calculadora de préstamos, permitiendo a los usuarios evaluar opciones de financiamiento desde el dashboard home. Esto facilitará decisiones responsables y aumentará la confianza en la plataforma.

* **🔵 Asociaciones con Instituciones Financieras**<br>

    FinTrack establecerá alianzas con instituciones financieras para integrar servicios bancarios y préstamos. Estas colaboraciones, accesibles desde el dashboard home, enriquecerán la experiencia y el valor para los usuarios.

* **🔵 Frecuencia de Uso del Dashboard Home**<br>

    FinTrack incentivará el uso frecuente del dashboard home, que muestra saldos, tendencias y metas de forma clara. Su diseño atractivo asegurará que los usuarios lo consulten regularmente para gestionar sus finanzas.

* **🔵 Precisión en Alertas de Gastos**<br>

    FinTrack fortalecerá la confianza con alertas precisas de gastos inusuales, integradas en el dashboard home. Estas notificaciones ayudarán a los usuarios a identificar anomalías y tomar medidas rápidas.

* **🔵 Reducción de Costos de Soporte**<br>

     FinTrack minimizará los costos de soporte con tutoriales interactivos y FAQs integrados en la plataforma. Esto permitirá a los usuarios resolver dudas de forma autónoma, mejorando la experiencia general.

#### User Outcomes 🙋

* **🟢 Control Financiero Personal Mejorado**<br>

     Los usuarios de FinTrack, especialmente personas particulares, lograrán un mayor control sobre sus finanzas personales al utilizar herramientas de gestión de gastos e ingresos. El dashboard home les proporcionará una visión clara de sus saldos y tendencias, permitiéndoles identificar oportunidades de ahorro y tomar decisiones informadas para mejorar su estabilidad financiera.

* **🟢 Planificación Estratégica para Emprendedores**<br>

     Los emprendedores usarán FinTrack para planificar estratégicamente sus proyectos, aprovechando las proyecciones financieras basadas en datos históricos. El dashboard home les ofrecerá una vista consolidada de su flujo de caja y metas, ayudándoles a anticipar desafíos y ajustar sus estrategias para asegurar el éxito de sus iniciativas.

* **🟢 Optimización de Recursos en Pequeñas Empresas**<br>

     Las pequeñas empresas optimizarán sus recursos financieros con FinTrack, utilizando la gestión colaborativa de gastos e ingresos y reportes detallados en el dashboard home. Esto les permitirá identificar ineficiencias, reducir costos operativos y enfocar sus esfuerzos en el crecimiento sostenible de sus operaciones.

* **🟢 Confianza en Decisiones de Préstamos**<br>

     Los usuarios que buscan financiamiento encontrarán en FinTrack una herramienta confiable para evaluar préstamos mediante la calculadora integrada. Desde el dashboard home, podrán simular escenarios de endeudamiento, tomar decisiones responsables y planificar pagos sin comprometer su estabilidad financiera.

* **🟢 Adopción de Metas Financieras Personalizadas**<br>

     FinTrack empoderará a los usuarios para establecer y seguir metas financieras, como ahorrar para una compra o reducir deudas, con una interfaz sencilla y notificaciones motivadoras en el dashboard home. Esto les ayudará a mantenerse enfocados y a alcanzar sus objetivos financieros con mayor facilidad.

* **🟢 Reducción del Estrés Financiero**<br>

     Los usuarios experimentarán menos estrés financiero al usar FinTrack, gracias a la claridad que ofrece el dashboard home y las alertas de gastos inusuales. Estas funcionalidades les permitirán monitorear sus finanzas en tiempo real, reaccionar ante anomalías y mantener el control sin esfuerzo.

* **🟢 Mayor Confianza en Proyecciones Financieras**<br>

     FinTrack aumentará la confianza de los usuarios en sus proyecciones financieras al proporcionar escenarios precisos basados en datos históricos, accesibles desde el dashboard home. Esto permitirá a personas y empresas anticipar tendencias y tomar decisiones proactivas para su futuro financiero.

* **🟢 Experiencia de Uso Intuitiva**<br>

     Los usuarios disfrutarán de una experiencia fluida y accesible con FinTrack, gracias a su interfaz intuitiva y al dashboard home que centraliza datos clave. Esto facilitará la adopción de la plataforma, incluso para aquellos con poca experiencia financiera, integrándola en su rutina diaria.

* **🟢 Toma de Decisiones Colaborativas en Equipos**<br>

     Las pequeñas empresas se beneficiarán de las herramientas colaborativas de FinTrack, que permiten a los equipos gestionar finanzas juntos. El dashboard home ofrecerá una visión compartida de los datos, fomentando decisiones coordinadas que impulsen la eficiencia y el crecimiento.

* **🟢 Acceso a Recursos Financieros Externos**<br>

     A través de asociaciones con instituciones financieras, los usuarios de FinTrack accederán a servicios bancarios y opciones de préstamos directamente desde la plataforma. Esto, integrado en el dashboard home, enriquecerá su experiencia y les proporcionará recursos adicionales para gestionar sus finanzas.

* **🟢 Monitoreo Frecuente de Finanzas**<br>

     FinTrack incentivará a los usuarios a monitorear sus finanzas regularmente a través del dashboard home, que presenta saldos, metas y tendencias de forma clara. Este hábito les permitirá mantenerse informados y tomar medidas rápidas para mantener sus finanzas en orden.

* **🟢 Resolución Autónoma de Dudas**<br>

     Los usuarios resolverán dudas de manera autónoma con los tutoriales interactivos y FAQs integrados en FinTrack. Esta funcionalidad reducirá la necesidad de soporte externo, permitiéndoles aprovechar al máximo la plataforma con confianza y facilidad.

* **🟢 Mayor Claridad en Gastos e Ingresos**<br>

     FinTrack ayudará a los usuarios a comprender mejor sus patrones de gastos e ingresos mediante reportes claros en el dashboard home. Esta claridad les permitirá ajustar sus hábitos financieros y alinear sus decisiones con sus objetivos a largo plazo.

* **🟢 Motivación para Alcanzar Metas**<br>

     Los usuarios se sentirán motivados para alcanzar sus metas financieras con las notificaciones de progreso y recordatorios de FinTrack, integrados en el dashboard home. Esta funcionalidad les ayudará a mantenerse enfocados y celebrar sus logros financieros.

* **🟢 Reducción de Errores en Gestión Financiera**<br>

     FinTrack minimizará los errores en la gestión financiera al automatizar el registro de transacciones y ofrecer alertas precisas en el dashboard home. Esto permitirá a los usuarios evitar equivocaciones costosas y mantener registros precisos con menos esfuerzo.

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

#### Segmentos Objetivos:

# Capítulo II: Requeriments Elicitation & Analysis
---

## 2.1 Competidores

### ¿Por qué llevar a cabo este análisis?

El análisis de competidores es un paso esencial para el desarrollo estratégico de **KapakID**, ya que permite:

- **Identificar el panorama competitivo actual**: conocer qué aplicaciones ofrecen servicios similares (billeteras digitales, apps de identidad, apps de transporte) y cómo se posicionan en el mercado.
- **Detectar fortalezas y debilidades de la competencia**: entender qué hacen bien y en qué fallan, para aprovechar oportunidades y evitar errores.
- **Definir nuestra propuesta de valor diferencial**: garantizar que **KapakID** no sea “una app más”, sino una solución única que combine lo mejor de las demás y agregue funcionalidades innovadoras.
- **Optimizar la estrategia de marketing y producto**: orientar esfuerzos hacia segmentos desatendidos y necesidades no cubiertas por los competidores.
- **Reducir riesgos y anticipar amenazas**: prever cambios regulatorios, tendencias tecnológicas y movimientos de la competencia que puedan impactar el proyecto.


---

### 2.1.1 Análisis competitivo (Comparativa)


 Criterio                              | KapakID | Yape | Plin | IDPerú (RENIEC) | Google Wallet |
|--------------------------------------|---------|------|------|------------------|---------------|
| Centraliza documentos oficiales      | Sí      | No   | No   | Parcial          | No            |
| Gestión de tarjetas de transporte    | Sí      | Parcial | Parcial | No           | No            |
| Pagos y recargas                     | Sí (enlace a billeteras) | Sí | Sí | No | Sí |
| Alertas inteligentes                 | Sí      | No   | No   | No               | No            |
| Perfiles múltiples                   | Sí      | No   | No   | No               | No            |
| Modo offline                         | Sí      | No   | No   | No               | Parcial       |
| Asistente de trámites                | Sí      | No   | No   | No               | No            |
| Cumplimiento Ley 29733               | Sí      | Sí   | Sí   | Sí               | Sí            |
| Fortalezas clave                     | Centralización total, alertas, perfiles múltiples, seguridad | Popularidad, confianza bancaria | Interoperabilidad bancaria | Identidad digital oficial | Integración global |
| Debilidades                          | Requiere confianza del usuario | No gestiona documentos | No alertas ni documentos | No pagos ni transporte | No adaptado a trámites locales |


---

### **¿Por qué KapakID es superior?**
- **Integra lo mejor de todos los competidores**: pagos (como Yape/Plin), identidad segura (como IDPerú), y almacenamiento de tarjetas (como Google Wallet).
- **Agrega valor único**: centralización de documentos, alertas inteligentes, perfiles múltiples, modo offline y asistentes de trámites.
- **Diseñada para el contexto peruano**: compatible con Metropolitano, Línea 1, SUNEDU y CONADIS.


---

### 2.1.2 Estrategias y tácticas frente a competidores

**Estrategias:**
- Diferenciación por **centralización y seguridad** (cifrado, biometría).
- Experiencia **adaptada al contexto peruano** (Metropolitano, Línea 1, SUNEDU, CONADIS).
- Cumplimiento **Ley 29733** para generar confianza.

**Tácticas:**
- **Alianzas** con universidades y colectivos de transporte.
- **Campañas digitales**: “Olvídate de cargar documentos físicos, usa KapakID”.
- **Modelo freemium**: básico gratis, premium con alertas avanzadas y perfiles múltiples.

---

## 2.2 Entrevistas

### 2.2.1 Diseño de entrevistas

**Segmentos objetivo:**
- **Estudiantes universitarios (18–29)** que usan transporte público.
- **Padres/madres o tutores (25–45)** que gestionan documentos de hijos.

**Objetivo:** Validar confianza, fricciones en trámites y pagos, valor de alertas y perfiles múltiples para **KapakID**.

---

#### Preguntas:

1. **¿Qué documentos y tarjetas llevas contigo a diario?** (DNI, carné universitario, tarjetas de transporte, bancarias). ¿En qué situaciones los usas más?
2. **¿Has perdido u olvidado algún documento importante en el último año?** ¿Cómo lo resolviste?
3. **¿Cómo recargas actualmente tu tarjeta del Metropolitano o Línea 1?** ¿Qué pasos te resultan más molestos?
4. **¿Qué tan difícil es para ti renovar documentos como DNI, carné universitario o CONADIS?** ¿Qué parte del proceso te genera más estrés?
5. **Si KapakID te avisara del vencimiento de un documento o saldo bajo,** ¿qué tipo de alerta preferirías (push, correo, WhatsApp) y con cuánta anticipación?
6. **¿Confiarías en KapakID para guardar copias digitales de tus documentos?** ¿Qué medidas de seguridad necesitas (biometría, PIN, cifrado)?
7. **Si pudieras administrar documentos de tus hijos desde KapakID,** ¿qué funciones serían imprescindibles (alertas, perfiles separados, acceso offline)?
8. **¿Qué tan útil sería para ti que KapakID incluya un asistente con checklist para trámites** (renovación de DNI, carné universitario, CONADIS)?
9. **¿Qué funciones priorizarías en KapakID?** (alertas, recargas, historial, perfiles múltiples, modo offline)
10. **¿Estarías dispuesto a pagar por funciones premium en KapakID?** ¿Qué precio considerarías justo?

### 2.2.2. Registro de entrevistas


### 2.2.2 Registro de entrevistas

#### Entrevistas a estudiantes universitarios

| Campo         | Información |
|---------------|-------------|
| Entrevistado 1 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 1]() |
| Timing        | [Ver grabación]() |

---

| Campo         | Información |
|---------------|-------------|
| Entrevistado 2 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 2]() |
| Timing        | [Ver grabación]() |

---

| Campo         | Información |
|---------------|-------------|
| Entrevistado 3 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 3]() |
| Timing        | [Ver grabación]() |

---

#### Entrevistas a padres/madres o tutores

| Campo         | Información |
|---------------|-------------|
| Entrevistado 1 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 1]() |
| Timing        | [Ver grabación]() |

---

| Campo         | Información |
|---------------|-------------|
| Entrevistado 2 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 2]() |
| Timing        | [Ver grabación]() |

---

| Campo         | Información |
|---------------|-------------|
| Entrevistado 3 |             |
| Edad          |             |
| Distrito      |             |
| Foto          | ![Foto entrevistado 3]() |
| Timing        | [Ver grabación]() |

---


### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
- Administradores:
- Clientes:

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping
- Administradores:
- Clientes:

### 2.3.4. Empathy Mapping
- Administradores:
- Clientes:

### 2.3.5. As-is Scenario Mapping
- Administradores:
- Clientes:

## 2.4. Ubiquitous Language

En esta sección se presenta el glosario de términos y conceptos contemplados por el Bussiness  Domain.
Los términos están definidos en inglés (con su equivalente en español entre paréntesis) y su definición en español.  
Este lenguaje ubicuo debe ser utilizado de forma consistente por todos los miembros del equipo.

---

### Identity & Documents (Identidad y Documentos)
- **National ID (DNI – Documento Nacional de Identidad):** Documento oficial de identidad emitido por RENIEC, utilizado para acreditar identidad en Perú.  
- **Passport (Pasaporte):** Documento emitido por la autoridad competente que permite viajar al extranjero.  
- **Driver’s License (Licencia de Conducir):** Documento emitido por el MTC que autoriza a una persona a conducir vehículos.  
- **University ID (Carné Universitario):** Documento emitido por SUNEDU o universidades, utilizado para identificar a estudiantes en Perú.  
- **Disability ID (Carné CONADIS):** Documento oficial que acredita a una persona con discapacidad en Perú.  
- **Digital Document (Documento Digital):** Versión electrónica y certificada de un documento físico almacenado en KapakID.  

### Transportation & Cards (Transporte y Tarjetas)
- **Metro Card (Tarjeta del Tren):** Tarjeta recargable utilizada para acceder al Tren Electrico de Lima.  
- **Metropolitano Card (Tarjeta del Metropolitano):** Tarjeta recargable utilizada en el sistema de transporte público Metropolitano de Lima.  
- **Transport Balance (Saldo de Transporte):** Monto disponible en tarjetas de transporte registrado en KapakID.  
- **Top-Up (Recarga):** Acción de añadir saldo a una tarjeta de transporte o celular desde KapakID.  

### Payments & Transactions (Pagos y Transacciones)
- **Debt Payment (Pago de Deuda):** Transacción realizada para cancelar obligaciones pendientes como servicios, multas o préstamos.  
- **Phone Top-Up (Recarga Telefónica):** Proceso de añadir saldo a un número de celular desde KapakID.  
- **Transaction History (Historial de Transacciones):** Registro detallado de recargas, pagos y movimientos financieros realizados en la app.  
- **Service Renewal (Renovación de Documento/Servicio):** Trámite para actualizar o extender la vigencia de un documento desde KapakID.  

### Governance & Voting (Gobernanza y Votaciones)
- **Presidential Election (Elección Presidencial):** Proceso electoral nacional para elegir al Presidente del Perú, habilitado en KapakID mediante identificación única.  
- **Municipal Election (Elección Municipal):** Proceso electoral local para elegir alcaldes y autoridades municipales.  
- **Digital Vote (Voto Digital):** Emisión de voto certificado y único a través de KapakID utilizando la identidad verificada del usuario.  

### Notifications & Alerts (Notificaciones y Alertas)
- **Low Balance Alert (Alerta de Saldo Bajo):** Notificación enviada al usuario cuando el saldo de una tarjeta de transporte o celular es insuficiente.  
- **Expiration Alert (Alerta de Vencimiento):** Notificación enviada cuando un documento o tarjeta está próximo a caducar.  
- **Reminder (Recordatorio):** Aviso programado para acciones importantes como renovaciones, votaciones o recargas.  

### Access & Profiles (Acceso y Perfiles)
- **Offline Mode (Modo Offline):** Acceso limitado a documentos previamente verificados cuando no hay conexión a internet.  
- **Verified Document (Documento Verificado):** Documento validado oficialmente en la app para uso legal y seguro.  
- **User Profile (Perfil de Usuario):** Identidad principal del dueño de la cuenta en KapakID.  
- **Family Profile (Perfil Familiar):** Espacio dentro de la app que permite administrar documentos de hijos u otros dependientes.  


# Capítulo III: Requeriments Specification

## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Desing

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Desing
### 4.3.1. Landing Page Wireframes
### 4.3.2. Landing Page Mock-Up

## 4.4. Web Applications UX/UI Desing
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagram
### 4.6.3. Software Architecture Components Diagram

## 4.7. Software Object-Oriented Desing
### 4.7.1. Class Diagram
### 4.7.2. Class Dictionary

## 4.8. Database Desing
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Service & Applications Implementation
### 5.2.x. Sprints

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

# Conclusiones

Conclusiones y recomendaciones
