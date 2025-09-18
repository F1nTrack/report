<!--* caratula -->

<div align="center">

# Informe Trabajo Final 📙

<img src="./resources/Cap-1/Banner-UPC.png" alt="Banner UPC">

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
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas-1)
      - [Entrevistas a estudiantes universitarios](#entrevistas-a-estudiantes-universitarios)
      - [Entrevistas a padres/madres o tutores](#entrevistas-a-padresmadres-o-tutores)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [Task Matrix](#task-matrix)
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
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
      - [Branding](#branding)
      - [Paleta de Colores – KapakID](#paleta-de-colores--kapakid)
      - [Tipografía – KapakID](#tipografía--kapakid)
      - [Iconografía](#iconografía)
      - [Jerarquía Visual](#jerarquía-visual)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
      - [Panel de control principal (Dashboard)](#panel-de-control-principal-dashboard)
      - [Gestión de Documentos y Pagos](#gestión-de-documentos-y-pagos)
      - [Transporte y Movilidad](#transporte-y-movilidad)
      - [Alertas y Notificaciones](#alertas-y-notificaciones)
      - [Comunicación y Soporte](#comunicación-y-soporte)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
      - [Landing Page e Inicio de la Aplicación](#landing-page-e-inicio-de-la-aplicación)
      - [Gestión de Documentos y Pagos](#gestión-de-documentos-y-pagos-1)
      - [Módulos de Transporte y Movilidad](#módulos-de-transporte-y-movilidad)
      - [Alertas y Notificaciones](#alertas-y-notificaciones-1)
      - [Historial de Transacciones y Actividades](#historial-de-transacciones-y-actividades)
      - [Contenido Personalizado por Perfil de Usuario](#contenido-personalizado-por-perfil-de-usuario)
      - [Búsqueda de Documentos y Servicios](#búsqueda-de-documentos-y-servicios)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
      - [Landing Page](#landing-page)
      - [Web Application](#web-application)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      - [Landing Page](#landing-page-1)
    - [4.2.4. Searching Systems – KapakID](#424-searching-systems--kapakid)
    - [4.2.5. Navigation Systems – KapakID](#425-navigation-systems--kapakid)
      - [Landing Page](#landing-page-2)
  - [El logotipo funcionará como acceso directo al inicio, asegurando navegación fluida.](#el-logotipo-funcionará-como-acceso-directo-al-inicio-asegurando-navegación-fluida)
      - [Web Application](#web-application-1)
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
      - [Repositorios del proyecto](#repositorios-del-proyecto)
      - [GitFlow Workflow](#gitflow-workflow)
        - [Ramas principales](#ramas-principales)
        - [Ramas de soporte](#ramas-de-soporte)
      - [Convenciones de versionado](#convenciones-de-versionado)
      - [Convenciones de commits](#convenciones-de-commits)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
      - [HTML](#html)
      - [CSS](#css)
      - [JavaScript](#javascript)
  - [Vue.js](#vuejs)
  - [C#](#c)
  - [BDD (Gherkin) para pruebas de aceptación](#bdd-gherkin-para-pruebas-de-aceptación)
  - [Resumen de nomenclatura por lenguaje](#resumen-de-nomenclatura-por-lenguaje)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [1. Landing Page](#1-landing-page)
    - [2. Web Services (Backend)](#2-web-services-backend)
    - [3. Frontend Web Applications](#3-frontend-web-applications)
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
 <article id="descripcion-startup" aria-labelledby="descripcion-startup-title">
  <h3 id="descripcion-startup-title">1.1.1 Descripción de la Startup</h3>

  <p>
    <strong>KapakID</strong> es una startup enfocada en desarrollar soluciones
    tecnológicas para la <strong>gestión personal de documentos e identidad digital</strong>. 
    Nuestro objetivo es ayudar a los usuarios a centralizar, proteger y acceder de forma segura 
    a sus documentos esenciales desde cualquier dispositivo conectado a internet.
  </p>

  <h4>Propuesta de valor</h4>
  <ul>
    <li><strong>Seguridad:</strong> reducción del riesgo de pérdida o robo de documentos físicos.</li>
    <li><strong>Ahorro de tiempo:</strong> búsqueda rápida y consolidación de información en un solo lugar.</li>
    <li><strong>Acceso inmediato:</strong> disponibilidad de documentos en situaciones de emergencia.</li>
    <li><strong>Gestión eficiente:</strong> recordatorios automáticos para fechas de vencimiento.</li>
    <li><strong>Integración:</strong> conexión con sistemas de pago y recarga de servicios.</li>
  </ul>

  <h4>Misión</h4>
  <p>
    Proporcionar soluciones digitales accesibles e innovadoras que permitan a estudiantes, 
    profesionales y familias <strong>gestionar de forma centralizada y segura sus documentos personales</strong>, 
    facilitando el acceso, la organización y la protección de su identidad digital.
  </p>

  <h4>Visión</h4>
  <p>
    Convertirnos en la <strong>plataforma líder en gestión de documentos e identidad digital en Latinoamérica</strong>, 
    reconocida por brindar seguridad, confianza y accesibilidad, contribuyendo al bienestar 
    de las personas y al avance hacia sociedades más digitales y organizadas.
  </p>
</article>



</div>
<div align='left'>
<h3>1.1.2. Perfiles de los integrantes del grupo</h3>
<div align='center'>
   <!--TODO: integrante 1 -->
  > 🧑‍💻 <strong>Matias Rodolfo Salcedo Champi</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/matias.png" alt="imagen Matias" width="100" align='right'>

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

   <img src="resources/Cap-1/Members/Image_raul_tasayco.png" alt="imagen Raul" width="100" align='right'>

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
**> 🧑‍💻 Ruiz Huisa, Daniel ELias**
   <div align='center'>

   <img src="resources/Cap-1/Members/Daniel.jpg" alt="" width="100" align='right'>

   ~~~txt
   Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente cursando el 6to ciclo de la carrera.
  Durante mi formación he adquirido conocimientos en diversas tecnologías y buenas prácticas de desarrollo. Mis principales fortalezas se encuentran lenguajes con orientados fuertemente a la POO como C++ y Java. 
  Adicionalmente, he trabajado con PGAdmin, MongoAtlas, MySQLlite como gestores de bases de datos, y con tecnologías web que me permiten tener una visión integral del desarrollo de software.

   ~~~

   </div>

   <!--TODO: integrante 4 -->
**> 🧑‍💻Jhunior Giussepe Taquiri Calderon (U20221C676)**
   <div align='center'>

   <img src="resources/Cap-1/Members/giussepe.png" alt="imagen Giussepe" width="100" align='right'>
  

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

   <img src="resources/Cap-1/Members/Fabrizio1.jpg" alt="imagen Raul" width="100" align='right'>

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
    <strong>gestionar, proteger y acceder a sus documentos importantes</strong>. 
    La dependencia de formatos físicos, el desorden en el almacenamiento digital y la ausencia de 
    herramientas tecnológicas accesibles generan pérdida de tiempo, riesgo de extravío y 
    complicaciones en trámites que requieren información inmediata. 
  </p>
  <p>
    Frente a esta problemática surge la necesidad de contar con soluciones digitales prácticas que 
    permitan a los usuarios centralizar, resguardar y disponer de sus documentos en cualquier momento 
    y lugar, de forma segura y confiable.
  </p>

  <h4>5“W”s + 2"H"</h4>
  <ul>
    <li>
      <strong>WHAT (QUÉ):</strong>  
      El problema principal es la <strong>dificultad para gestionar documentos personales y empresariales</strong>.  
      Muchos usuarios no tienen un sistema ordenado para guardar DNI, contratos, certificados o 
      recibos, lo que ocasiona pérdidas de información, duplicidad de archivos y retrasos en 
      procesos administrativos.
    </li>
    <br>
    <li>
      <strong>WHEN (CUÁNDO):</strong>  
      Este problema ocurre <strong>de manera frecuente</strong>, especialmente en situaciones críticas:  
      - Renovación de documentos o trámites legales.  
      - Acceso a información en emergencias.  
      - Fechas de vencimiento de contratos, pólizas o servicios.  
      La falta de organización se hace evidente justo cuando más se necesita la información.
    </li>
    <br>
    <li>
      <strong>WHERE (DÓNDE):</strong>  
      El problema se da en distintos <strong>ámbitos</strong>:  
      - En el <em>personal</em>, cuando alguien requiere documentos médicos, escolares o financieros.  
      - En el <em>profesional</em>, entre estudiantes y trabajadores que deben presentar certificados o 
        contratos.  
      - En el <em>empresarial</em>, en micro y pequeñas empresas que no cuentan con sistemas digitales 
        para organizar facturas, permisos o documentación interna.
    </li>
    <br>
    <li>
      <strong>WHO (QUIÉN):</strong>  
      Los principales afectados son:  
      - <strong>Personas naturales</strong> que dependen de trámites frecuentes.  
      - <strong>Estudiantes y profesionales</strong> que requieren tener certificados y documentos al día.  
      - <strong>Emprendedores y pequeñas empresas</strong> que no pueden costear soluciones corporativas 
        avanzadas de gestión documental.
    </li>
    <br>
    <li>
      <strong>WHY (POR QUÉ):</strong>  
      Porque actualmente <strong>no existen herramientas accesibles, seguras y fáciles de usar</strong> 
      que permitan gestionar documentos de manera integral.  
      Las soluciones disponibles suelen ser:  
      - Limitadas a almacenamiento básico en la nube sin organización avanzada.  
      - Costosas para usuarios comunes o pequeñas empresas.  
      - Poco personalizables para distintos tipos de documentos y recordatorios de vencimiento.
    </li>
    <br>
    <li>
      <strong>HOW (CÓMO):</strong>  
      La solución se plantea mediante el desarrollo de una <strong>plataforma web</strong> que:  
      - Centralice el almacenamiento digital de documentos.  
      - Brinde recordatorios automáticos para fechas de vencimiento.  
      - Permita acceso inmediato y seguro desde cualquier dispositivo.  
      - Ofrezca integración con pagos y recargas de servicios relacionados a la documentación.
    </li>
    <br>
    <li>
      <strong>HOW MUCH (CUÁNTO):</strong>  
      Actualmente, contratar un gestor documental empresarial o servicios especializados supone un 
      <strong>costo elevado</strong>, inaccesible para la mayoría.  
      KapakID busca ofrecer una solución <strong>económica, accesible y escalable</strong>, con planes 
      gratuitos para funciones básicas y opciones premium de bajo costo para usuarios con mayores 
      necesidades.
    </li>
  </ul>
</article>

___

### 1.2.2 Lean Ux Process
#### 1.2.2.1. Lean UX Problem Statements
 
Actualmente, las personas enfrentan grandes dificultades para gestionar y llevar consigo sus documentos personales y tarjetas, como DNI, pasaporte, tarjetas bancarias, licencias de conducir, carnés universitarios, entre otros, debido a la incomodidad de portar documentos físicos, el riesgo de pérdida o robo, y la falta de una solución digital integrada que facilite su uso y administración. Esto se debe a varios factores, como la ausencia de una plataforma centralizada para almacenar y verificar documentos, la complejidad de realizar trámites digitales como renovaciones o pagos, y la falta de acceso offline a información crítica, lo que resulta en inconvenientes, pérdida de tiempo y dificultades para gestionar trámites y pagos de manera eficiente.

Nosotros consideramos que estos usuarios necesitan una solución integral y segura que les permita centralizar, gestionar y utilizar sus documentos y tarjetas desde su celular, sin depender de llevar documentos físicos o acceder a múltiples plataformas para realizar trámites. Por ello, KapakID resuelve este problema mediante una aplicación web intuitiva desarrollada en Vue, que permite registrar y verificar documentos como DNI, pasaporte, tarjetas bancarias, licencias, carnés, certificados de vacunas, y más. Ofrece funcionalidades como recarga de tarjetas de transporte, pago de deudas, recarga de teléfono, renovación de documentos, consulta de saldos, historial de trámites y pagos, notificaciones de saldo bajo o vencimiento de documentos, modo offline para acceso limitado a documentos verificados, y una opción premium para gestionar múltiples perfiles (por ejemplo, documentos de hijos). Sabremos que hemos tenido éxito cuando los usuarios reporten una reducción significativa en el uso de documentos físicos, un aumento en la eficiencia al realizar trámites digitales, y una mejora en la satisfacción con la gestión de sus documentos y pagos dentro de los primeros tres meses de uso.

#### 1.2.2.2. Lean UX Assumptions

#### Business Outcomes 📊:


* **🔵 Crecimiento de la Base de Usuarios** <br>


     KapakID busca atraer a personas que desean gestionar sus documentos y tarjetas de manera digital con campañas de marketing que resalten la facilidad de uso de la plataforma. Su diseño intuitivo y herramientas como el registro de DNI, pasaporte, tarjetas bancarias y notificaciones fomentarán una adopción amplia y sostenida.



* **🔵 Alta Retención de Usuarios** <br>


     Buscamos retener a los usuarios comprometidos con una experiencia fluida y funcionalidades valiosas como consulta de saldos, historial de trámites y notificaciones de vencimiento. El dashboard principal, claro y accesible, asegurará que los usuarios integren KapakID en su rutina diaria.



* **🔵 Ingresos por Suscripciones Premium** <br>


     Generaremos ingresos a través de suscripciones premium, con funciones avanzadas como soporte para múltiples perfiles (por ejemplo, para gestionar documentos de hijos). Estas herramientas motivarán a los usuarios a optar por planes pagos para una mayor comodidad en la gestión de documentos.



* **🔵 Minimización del Churn Rate** <br>


     Reducir la pérdida de usuarios es clave para KapakID. Con un dashboard principal útil y herramientas como modo offline y notificaciones de vencimiento, la plataforma ofrecerá valor continuo, manteniendo a los usuarios leales y comprometidos a largo plazo.



* **🔵 Satisfacción del Usuario (NPS)** <br>


     KapakID maximizará la satisfacción con una interfaz intuitiva y funciones prácticas como recarga de tarjetas, renovación de documentos y modo offline. La retroalimentación constante permitirá ajustar la plataforma para superar las expectativas de los usuarios.



* **🔵 Adopción de Funciones de Gestión de Documentos** <br>


     Fomentaremos el uso de herramientas para registrar y verificar documentos como DNI, pasaporte, licencias y carnés, accesibles desde el dashboard principal. Estas funcionalidades serán clave para que los usuarios reemplacen documentos físicos por la app.



* **🔵 Establecimiento de Hábitos de Gestión Digital** <br>


     Buscaremos motivar a los usuarios a gestionar trámites y pagos, como recargas de teléfono o renovación de documentos, con una interfaz sencilla y notificaciones motivadoras en el dashboard principal. Esto convertirá a KapakID en un aliado para la organización personal.



* **🔵 Optimización de Trámites Digitales** <br>


     KapakID ayudará a los usuarios a optimizar trámites con herramientas de renovación de documentos, consulta de saldos y historial de pagos, accesibles desde el dashboard principal. Notificaciones personalizadas apoyarán la eficiencia y la organización.



* **🔵 Precisión en Notificaciones de Vencimiento** <br>


     KapakID mejorará la experiencia con notificaciones precisas sobre vencimientos de documentos o saldos bajos, integradas en el dashboard principal. Esto permitirá a los usuarios planificar y actuar con anticipación.



* **🔵 Usuarios Activos en Familias** <br>


     KapakID atraerá a familias con la opción premium para gestionar múltiples perfiles, como documentos de hijos, desde un dashboard principal intuitivo. Su enfoque práctico y escalable lo convertirá en la opción ideal para la gestión documental familiar.



* **🔵 Uso de Funciones de Pago y Recarga** <br>


     KapakID promoverá el uso de herramientas para recargar tarjetas de transporte, pagar deudas y recargar teléfonos desde el dashboard principal. Esto facilitará una gestión financiera responsable y aumentará la confianza en la plataforma.



* **🔵 Asociaciones con Entidades Gubernamentales y Financieras** <br>


     KapakID establecerá alianzas con entidades gubernamentales y financieras para integrar servicios como renovación de documentos y pagos de tarjetas. Estas colaboraciones, accesibles desde el dashboard principal, enriquecerán la experiencia y el valor para los usuarios.



* **🔵 Frecuencia de Uso del Dashboard Principal** <br>


     KapakID incentivará el uso frecuente del dashboard principal, que muestra documentos, saldos, historial de trámites y notificaciones de forma clara. Su diseño atractivo asegurará que los usuarios lo consulten regularmente para gestionar sus documentos y pagos.



* **🔵 Precisión en Notificaciones de Saldo Bajo**<br>

     KapakID fortalecerá la confianza con notificaciones precisas de saldos bajos en tarjetas, integradas en el dashboard principal. Estas alertas ayudarán a los usuarios a identificar necesidades de recarga y tomar medidas rápidas.



* **🔵 Reducción de Costos de Soporte**<br>

     KapakID minimizará los costos de soporte con tutoriales interactivos y FAQs integrados en la plataforma. Esto permitirá a los usuarios resolver dudas de forma autónoma, mejorando la experiencia general.

### User Outcomes 🙋

* **🟢 Control Documental Personal Mejorado**<br>

     Los usuarios de KapakID lograrán un mayor control sobre sus documentos personales y tarjetas, como DNI, pasaporte, licencias y carnés, al utilizar herramientas de registro y verificación digital. El dashboard principal les proporcionará una visión clara de sus documentos, saldos y trámites, permitiéndoles gestionar todo desde su celular y reducir la dependencia de documentos físicos.

* **🟢 Organización Eficiente para Familias**<br>

     Los usuarios, especialmente familias, usarán KapakID para organizar documentos de múltiples perfiles (como los de sus hijos) con la opción premium. El dashboard principal les ofrecerá una vista consolidada de documentos y trámites, ayudándoles a anticipar vencimientos y gestionar renovaciones de manera eficiente.

* **🟢 Optimización de Trámites Digitales**<br>

     Los usuarios optimizarán sus trámites con KapakID, utilizando herramientas para renovar documentos, recargar tarjetas de transporte y pagar deudas desde el dashboard principal. Esto les permitirá ahorrar tiempo, reducir la necesidad de acudir a oficinas físicas y mantener un historial organizado de sus gestiones.

* **🟢 Confianza en la Gestión de Pagos**<br>

     Los usuarios que realizan pagos encontrarán en KapakID una herramienta confiable para recargar tarjetas, pagar deudas o recargar teléfonos. Desde el dashboard principal, podrán consultar saldos y revisar el historial de pagos, tomando decisiones informadas sin comprometer su organización financiera.

* **🟢 Adopción de Gestión Documental Digital**<br>

     KapakID empoderará a los usuarios para gestionar documentos digitalmente, como DNI, pasaporte o certificados, con una interfaz sencilla y notificaciones de vencimiento en el dashboard principal. Esto les ayudará a mantenerse organizados y reducir el uso de documentos físicos con facilidad.

* **🟢 Reducción del Estrés Documental**<br>

     Los usuarios experimentarán menos estrés al gestionar documentos gracias a la claridad que ofrece el dashboard principal y las notificaciones de vencimiento o saldo bajo. Estas funcionalidades les permitirán monitorear sus documentos en tiempo real, reaccionar ante alertas y mantener el control sin esfuerzo.

* **🟢 Mayor Confianza en la Seguridad de Documentos**<br>

     KapakID aumentará la confianza de los usuarios al proporcionar un entorno seguro para almacenar y verificar documentos, con acceso offline a documentos verificados desde el dashboard principal. Esto permitirá a los usuarios sentirse protegidos y acceder a su información incluso sin conexión.

* **🟢 Experiencia de Uso Intuitiva**<br>

     Los usuarios disfrutarán de una experiencia fluida y accesible con KapakID, gracias a su interfaz intuitiva y al dashboard principal que centraliza documentos, saldos y trámites. Esto facilitará la adopción de la plataforma, incluso para aquellos con poca experiencia digital, integrándola en su rutina diaria.

* **🟢 Gestión Colaborativa de Documentos Familiares**<br>

     Las familias se beneficiarán de la opción premium de KapakID, que permite gestionar documentos de varios miembros desde el dashboard principal. Esto fomentará una organización coordinada, asegurando que todos los documentos estén centralizados y accesibles.

* **🟢 Acceso a Servicios de Trámites Externos**<br>

     A través de asociaciones con entidades gubernamentales y financieras, los usuarios de KapakID accederán a servicios como renovación de documentos o pagos directamente desde la plataforma. Esto, integrado en el dashboard principal, enriquecerá su experiencia y les proporcionará recursos adicionales para gestionar sus documentos.

* **🟢 Monitoreo Frecuente de Documentos y Pagos**<br>

     KapakID incentivará a los usuarios a monitorear sus documentos y pagos regularmente a través del dashboard principal, que presenta documentos, saldos, historial de trámites y notificaciones de forma clara. Este hábito les permitirá mantenerse informados y tomar medidas rápidas para mantener todo en orden.

* **🟢 Resolución Autónoma de Dudas**<br>

     Los usuarios resolverán dudas de manera autónoma con los tutoriales interactivos y FAQs integrados en KapakID. Esta funcionalidad reducirá la necesidad de soporte externo, permitiéndoles aprovechar al máximo la plataforma con confianza y facilidad.

* **🟢 Mayor Claridad en Trámites y Pagos**<br>

     KapakID ayudará a los usuarios a comprender mejor sus trámites y pagos mediante reportes claros en el dashboard principal. Esta claridad les permitirá ajustar sus hábitos de gestión y alinear sus decisiones con sus necesidades personales o familiares.

* **🟢 Motivación para Mantener Documentos Actualizados**<br>

     Los usuarios se sentirán motivados para mantener sus documentos actualizados con las notificaciones de vencimiento y recordatorios de KapakID, integrados en el dashboard principal. Esta funcionalidad les ayudará a mantenerse organizados y celebrar sus logros en la gestión documental.

* **🟢 Reducción de Errores en Gestión Documental**<br>

     KapakID minimizará los errores en la gestión documental al automatizar el registro de documentos y ofrecer notificaciones precisas en el dashboard principal. Esto permitirá a los usuarios evitar equivocaciones costosas y mantener registros precisos con menos esfuerzo.

#### 1.2.2.3. Lean UX Hypothesis Statements

💡Creemos que digitalizar y centralizar todos los documentos personales y tarjetas en KapakID facilitará la vida diaria de los usuarios al reducir la dependencia de llevar documentos físicos.

💭Sabremos que esto es cierto cuando los usuarios reporten un uso reducido de su billetera física para trámites o pagos cotidianos en el primer mes de uso.
___
💡Creemos que las notificaciones automatizadas sobre vencimientos de documentos y saldos bajos ayudarán a los usuarios a mantenerse proactivos y a evitar inconvenientes o estrés por no tener sus documentos al día.

💭Sabremos que esto es cierto cuando el 90% de los usuarios que reciban una notificación de vencimiento inicien el trámite de renovación directamente desde la app, y cuando el uso de la función de recarga aumente un 15% tras las alertas de saldo bajo.
___
💡Creemos que la función de modo offline proporcionará un valor esencial y aumentará la confianza del usuario, asegurando que siempre tengan acceso a sus documentos verificados, incluso sin conexión a internet.

💭Sabremos que esto es cierto cuando al menos el 20% de los usuarios acceda a la app en modo offline en un periodo de 30 días, y cuando los comentarios sobre la seguridad y la conveniencia de esta función sean consistentemente positivos.
___
💡Creemos que el plan premium con soporte para múltiples perfiles motivará a los usuarios a suscribirse, ya que les permitirá administrar de forma eficiente los documentos de sus hijos y otros miembros de la familia.

💭Sabremos que esto es cierto cuando al menos el 10% de los usuarios que usen la prueba gratuita del plan premium decidan pagar por la suscripción en el primer mes.
___
💡Creemos que una interfaz de usuario intuitiva y los tutoriales interactivos permitirán a usuarios con poca familiaridad tecnológica adoptar la app y completar tareas clave como el registro de documentos y los trámites sin necesitar soporte técnico directo.

💭Sabremos que esto es cierto cuando el 85% de los usuarios nuevos completen su perfil y registren al menos tres documentos personales en la primera semana sin abrir un ticket de soporte.
___
💡Creemos que la integración con entidades gubernamentales para la renovación de documentos y el acceso a servicios como el pago de impuestos o multas facilitará la adopción masiva, ya que los usuarios verán la app como una plataforma oficial y confiable para realizar trámites importantes.

💭Sabremos que esto es cierto cuando al menos el 25% de los usuarios que hayan registrado un documento con fecha de vencimiento próxima intenten iniciar el proceso de renovación a través de la app.
___
💡Creemos que la capacidad de pagar deudas y servicios básicos (como la recarga de teléfono) directamente desde KapakID aumentará la frecuencia de uso diario y posicionará a la app como una herramienta esencial para la gestión financiera personal.

💭Sabremos que esto es cierto cuando el 40% de los usuarios que tengan tarjetas bancarias registradas realicen al menos una transacción de pago o recarga en un periodo de 30 días.

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas](<resources/Cap-1/LeanUX/Lean UX Canvas.png>)

#### Segmentos Objetivos:

En KapakID, tenemos dos segmentos objetivos principales que se benefician de las funcionalidades de nuestra aplicación:

* **Estudiantes Universitarios (18–29)**

  Este segmento busca la conveniencia y eficiencia. Su principal problema es la necesidad de llevar múltiples tarjetas (universidad, transporte, débito), lo que aumenta el riesgo de pérdida. KapakID les permite centralizar todo en su celular para hacer consultas de saldo y recargas al instante, simplificando su rutina diaria y reduciendo el riesgo.

* **Padres/Madres o Tutores (25–45)**

  Este grupo se enfoca en la organización y la seguridad familiar. Su dolor es la gestión dispersa de los documentos de sus hijos, desde carnés escolares hasta certificados de vacunas. KapakID resuelve esto con su función premium de perfiles múltiples, que les permite centralizar de forma segura toda la información familiar en un solo lugar, brindándoles control total y tranquilidad.


# Capítulo II: Requeriments Elicitation & Analysis

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
| Entrevistado 1 | Hany Pareja Berocal |
| Edad          | 20 años |
| Distrito      | Miraflores |
| Foto          | ![Foto entrevistado 1](resources/Cap-2/registro%20de%20entrevistas/entrevista%20KapakID.png) |
| Timing        | [Ver grabación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c576_upc_edu_pe/EQuM6qNAe-5MhSFGE_dESuYBpHtdmfK5y9TPWPT4EQjGyA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1WERnv) |
---

| Campo          | Información |
|----------------|-------------|
| Entrevistado 1 | Sebastian Delgado  |
| Edad           | 20 años     |
| Distrito       | San Borja   |
| Foto           | ![Foto entrevistado 1](resources/Cap-1/SSInterview1.png) |
| Timing         | [Ver grabación](https://drive.google.com/file/d/1L56VeFgJNXZNlBG1SJi8R2q2ly_IwkGr/view?usp=sharing) |

---

| Campo         | Información |
|---------------|-------------|
| Entrevistado 3 | Santiago Baldeon |
| Edad          |     25      |
| Distrito      |  Villa Maria del Triunfo  |
| Foto          | ![Foto entrevistado 3](resources/Cap-1/SSSANTI.png) |
| Timing        | [Ver grabación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319698_upc_edu_pe/Ea0to8pDhttOhst0CPbOsT4B6GESisWNpC92K_xX7bteNA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=5T1kLL) |

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

**Segmento 1: Jóvenes universitarios usuarios de transporte y documentos digitales (Hany Pareja Berocal)**

  * **Perfil**
    * Hany, 20 años, estudiante universitario en Miraflores, usa diariamente DNI, carné universitario, tarjeta del corredor y tarjeta bancaria. Maneja múltiples documentos físicos para distintos contextos: identificación, acceso a campus, transporte y pagos.  

  * **Insights clave**
    * Los usuarios jóvenes dependen de una combinación de documentos físicos y tarjetas para actividades cotidianas, pero los procesos presenciales generan fricción y estrés, especialmente al olvidar tarjetas o enfrentar colas para recargas.  
    * Valoran la eficiencia, la conveniencia y la seguridad digital como factores determinantes para adoptar nuevas soluciones.  
    * Prefieren alertas multicanal (push y WhatsApp) con anticipación suficiente para evitar problemas con vencimientos o saldo bajo.  

  * **Problemas y frustraciones**
    * Olvido de tarjeta de transporte obliga a pagos en efectivo, generando inconvenientes.  
    * Recargar tarjetas físicas implica tiempo de espera y desplazamientos.  
    * Renovación de documentos como DNI es percibida como complicada y estresante por colas y citas.  

  * **Necesidades**
    ```
    Gestión centralizada de documentos y tarjetas para reducir fricción y olvidos.
    ```
    ```
    Alertas multicanal y personalizables que notifiquen vencimientos de documentos y saldo bajo.
    ```
    ```
    Funcionalidades offline y perfiles múltiples que permitan organizar documentos personales y académicos.
    ```
    ```
    Métodos seguros de almacenamiento digital (biometría, PIN, cifrado) para garantizar confianza.
    ```
    ```
    Recarga de transporte y pagos integrados dentro de la app para ahorrar tiempo.
    ```

  * **Oportunidades para KapakID**
    ```
    Alertas multicanal: Implementar notificaciones push y por WhatsApp para documentos y saldo bajo.
    ```
    ```
    Gestión integral: Permitir almacenar, organizar y acceder a documentos personales y académicos desde la app.
    ```
    ```
    Recargas y pagos integrados: Incluir funcionalidades para recargar tarjetas de transporte y realizar pagos de manera segura.
    ```
    ```
    Funcionalidades offline: Garantizar acceso a documentos y perfiles sin conexión a internet.
    ```
    ```
    Modelo freemium/premium: Ofrecer funciones avanzadas (historial, perfiles múltiples, checklist de trámites) con opción de suscripción anual.
    ```


## 2.3. Needfinding
### 2.3.1. User Personas

- **Estudiante universitario**  
<td><img src="resources/Luis%20Alberto%20Ramírez%20(2).png" alt="imagen Luis Alberto Ramírez" ></td>

- **Madre de familia**  
<td><img src="resources/Patricia%20Valverde%20(1).png" alt="imagen Patricia Valverde"></td>

### 2.3.2. User Task Matrix
### Task Matrix

| **Task** | **Estudiante universitario (Luis, 21 años)** | | **Madre de familia (Patricia, 39 años)** | |
|----------|---------------------------------------------|-------------------------------------------|------------------------------------------|------------------------------------------|
|          | Frequency                                   | Importance                                | Frequency                                | Importance                               |
| Centralizar documentos digitales | Often | High | Always | High |
| Recargar tarjeta de transporte | Always | High | Often | Medium |
| Recibir alertas de saldo bajo / vencimiento | Always | High | Always | High |
| Configurar y gestionar perfiles múltiples | Rarely | Medium | Often | High |
| Acceso offline a documentos | Sometimes | Medium | Often | High |
| Asistente para trámites (checklist, pasos guiados) | Sometimes | Medium | Often | High |
| Historial de transacciones (pagos, recargas, trámites) | Sometimes | Medium | Often | Medium |
| Seguridad y validación biométrica | Often | High | Always | High |
| Vincular billeteras digitales (Yape, Plin, Google Wallet) | Often | High | Sometimes | Medium |
| Compartir documentos verificados (ej. envío digital de DNI) | Sometimes | Medium | Often | High |
| Configurar notificaciones personalizadas (push, correo, WhatsApp) | Often | Medium | Often | High |
| Renovar documentos en línea (DNI, carné universitario, CONADIS) | Rarely | High | Sometimes | High |
| Gestionar pagos de servicios (teléfono, agua, luz, internet) | Rarely | Medium | Often | High |
| Monitorear gastos y generar reportes | Rarely | Medium | Often | Medium |

El análisis de las tareas de estudiantes universitarios y madres de familia muestra enfoques distintos en el uso de KapakID. Los estudiantes se orientan a actividades operativas y cotidianas, como recargar la tarjeta de transporte, recibir alertas de saldo bajo, centralizar documentos y acceder en modo offline. Su prioridad es evitar olvidos, ahorrar tiempo y simplificar la movilidad diaria, con alto valor en funciones de seguridad biométrica y vinculación con billeteras digitales. Sin embargo, relegan a un segundo plano tareas menos frecuentes como renovación de documentos o generación de reportes. Las madres de familia, en contraste, priorizan la gestión integral y el control familiar, enfocándose en administrar múltiples perfiles, recibir alertas de vencimientos, acceder a documentos de manera segura y simplificar trámites repetitivos. Además, otorgan gran importancia al seguimiento financiero, utilizando historial de transacciones, pagos de servicios y reportes como parte de su rol en la organización del hogar. Mientras ambos segmentos coinciden en valorar la centralización documental, las alertas inteligentes y la seguridad, difieren en su enfoque: el estudiante busca rapidez y autonomía personal, mientras que la madre necesita organización, control y previsión familiar, consolidando a KapakID como una solución versátil para ambos perfiles.

### 2.3.3. User Journey Mapping
- **Empathy Map Estudiante Universitario **
  
<td><img src="resources/Cap-2/Empathy-Map/Empathy map Luis.png" alt="Empathy map Luis" ></td>

- **Empathy Map Madre de Familia**
<td><img src="resources/Cap-2/Empathy-Map/Empathy map Madre de Familia (1).png" alt="Empathy map Madre de Familia" ></td>

### 2.3.4. Empathy Mapping
**User Journey Mapping Estudiante Universitario** 
 <td><img src="resources/Cap-2/User-Journey-Mapping/User Journey Mapping Estudiante universitario (1).png" alt="User Journey Mapping Estudiante universitario"></td>
 
**User Journey Mapping Madre de Familia**  
<td><img src="resources/Cap-2/User-Journey-Mapping/User Journey Mapping Estudiante universitario (1).png" alt="Empathy map Madre de Familia" ></td>

<td><img src="resources/Cap-2/User-Journey-Mapping/Customer journey map Madre de Familia.png" alt="Customer journey map Madre de Familia" ></td>

### 2.3.5. As-is Scenario Mapping

- **TO-BE Scenario Mapping Estudiante Universitario (Luis)**
  
 <td><img src="resources/Cap-2/AS-IS_Scenario_Mapping/TO-BE%20Scenario%20Mapping%20Luis.png" alt="TO-BE Scenario Mapping Luis" ></td>

- **TO-BE Scenario Mapping Madre de Familia (Patricia)**
  
 <td><img src="resources/Cap-2/AS-IS_Scenario_Mapping/TO-BE%20Scenario%20Mapping%20Patricia.png" alt="TO-BE Scenario Mapping Patricia" ></td>

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

- **TO-BE Scenario Mapping Estudiante Universitario (Luis)**
  
 <td><img src="resources/Cap-3/TO-BE_Scenario_Mapping/To-Be_Scenario_Mapping_Persona1_Estudiante_Universitario.png" alt="TO-BE Scenario Mapping Luis" ></td>

- **TO-BE Scenario Mapping Madre de Familia (Patricia)**
  
 <td><img src="resources/Cap-3/TO-BE_Scenario_Mapping/To-Be Scenario_Mapping_Persona2_Padre_de_Familia.png" alt="TO-BE Scenario Mapping Patricia" ></td>

## 3.2. User Stories
**Tabla de Epics**
| Epic ID | Título                       | Descripción                                                                 |
|---------|------------------------------|-----------------------------------------------------------------------------|
| E1      | Gestión de Usuarios y Perfiles | Administración de usuarios, autenticación y creación de múltiples perfiles familiares. |
| E2      | Gestión de Documentos Digitales | Registro, validación, visualización y renovación de documentos oficiales en la app. |
| E3      | Pagos y Recargas             | Recarga de tarjetas de transporte y celulares, pagos de deudas y registro de historial de transacciones. |
| E4      | Votaciones Digitales         | Emisión de votos únicos y seguros en procesos electorales mediante identificación digital. |
| E5      | Notificaciones y Alertas     | Envío de recordatorios y notificaciones sobre saldos bajos y vencimiento de documentos. |
| E6      | Acceso Offline               | Permitir acceso limitado a documentos previamente verificados sin conexión a internet. |
| E7      | Landing Page Informativa     | Presentar la propuesta de valor de KapakID, funcionalidades clave, guías de descarga y contacto. |
| E8      | API REST Backend             | Servicios técnicos para manejar autenticación, gestión de documentos, pagos y notificaciones. |

**Tabla de US**

| US ID | Título                     | Descripción | Criterios de Aceptación (Gherkin) | Epic Relacionada |
|-------|-----------------------------|-------------|----------------------------------|------------------|
| US1   | Registro de usuario         | Como **usuario**, quiero registrarme con mi correo o celular para crear mi cuenta en KapakID. | **Scenario 1:**<br>Given un usuario no registrado <br>When ingresa sus datos válidos <br>Then el sistema crea la cuenta y confirma el registro.<br><br>**Scenario 2:**<br>Given un usuario intenta registrarse <br>When ingresa datos inválidos o incompletos <br>Then el sistema rechaza el registro y muestra el motivo. | E1 |
| US2   | Creación de perfiles familiares | Como **usuario**, quiero agregar perfiles de mis hijos para administrar sus documentos desde mi cuenta. | **Scenario 1:**<br>Given un usuario autenticado <br>When agrega un nuevo perfil familiar <br>Then el sistema registra el perfil vinculado a la cuenta.<br><br>**Scenario 2:**<br>Given un usuario intenta crear un perfil <br>When excede el límite permitido <br>Then el sistema rechaza la acción con un mensaje. | E1 |
| US3   | Registro de documentos      | Como **usuario**, quiero registrar mi DNI, pasaporte y otros documentos para tenerlos disponibles en la app. | **Scenario 1:**<br>Given un usuario autenticado <br>When registra un documento válido <br>Then el sistema almacena el documento digitalmente.<br><br>**Scenario 2:**<br>Given un usuario ingresa un documento inválido <br>When intenta registrarlo <br>Then el sistema rechaza la operación con justificación. | E2 |
| US4   | Renovación de documentos    | Como **usuario**, quiero renovar mis documentos vencidos desde la app para evitar trámites presenciales. | **Scenario 1:**<br>Given un documento próximo a vencer <br>When el usuario solicita renovación <br>Then el sistema envía la solicitud a la entidad correspondiente.<br><br>**Scenario 2:**<br>Given un documento ya vencido <br>When el usuario intenta renovarlo <br>Then el sistema informa si la renovación aún es posible. | E2 |
| US5   | Recarga de transporte       | Como **usuario**, quiero recargar mi tarjeta del Metropolitano para no quedarme sin saldo. | **Scenario 1:**<br>Given un usuario autenticado <br>When selecciona una tarjeta válida y monto de recarga <br>Then el sistema procesa el pago y actualiza el saldo.<br><br>**Scenario 2:**<br>Given una tarjeta inválida <br>When el usuario intenta recargar <br>Then el sistema rechaza la operación. | E3 |
| US6   | Pago de deudas              | Como **usuario**, quiero pagar mis deudas de servicios o multas desde la app para evitar filas. | **Scenario 1:**<br>Given un usuario autenticado <br>When selecciona una deuda pendiente <br>Then el sistema procesa el pago y registra la operación.<br><br>**Scenario 2:**<br>Given un pago realizado <br>When el usuario consulta el historial <br>Then el sistema muestra el registro de pago exitoso. | E3 |
| US7   | Registro de transacciones          | Como **usuario**, quiero registrar los movimientos de los documentos que he realizado desde la aplicacion. | **Scenario 1:**<br>Given un usuario autenticado <br>When ingresa para revisar sus movimientos <br>Then el sistema le muestra los movimientos registrados de sus documentos.<br><br>**Scenario 2:**<br>Given un usuario autenticado <br>When accede a un documento vencido <br>Then el sistema le alerta que el documento vencio | E3 |
| US8   | Voto digital único          | Como **ciudadano**, quiero emitir mi voto en elecciones mediante KapakID para participar de manera segura. | **Scenario 1:**<br>Given un ciudadano autenticado <br>When emite su voto en el proceso electoral vigente <br>Then el sistema registra el voto de forma cifrada.<br><br>**Scenario 2:**<br>Given un ciudadano ya votó <br>When intenta hacerlo nuevamente <br>Then el sistema rechaza el intento.<br><br> **Scenario 3:** Given un cuidadano votante <br> When intenta votar con un Documento de Identidad Vencido <br> Then el sistema rechaza la solicitd y le informa que su documento vencio| E4 |
| US9   | Alerta de vencimiento       | Como **usuario**, quiero recibir una notificación cuando mis documentos estén próximos a vencer. | **Scenario 1:**<br>Given un documento con 30 días antes de su vencimiento <br>When el sistema procesa la verificación <br>Then envía una alerta al usuario.<br><br>**Scenario 2:**<br>Given un documento vencido <br>When el sistema detecta la fecha caducada <br>Then notifica al usuario inmediatamente. | E5 |
| US10   | Notificacion de Tramite       | Como **usuario**, quiero recibir una notificación cuando se haya cumplido una solicitu de tramite. | **Scenario 1:**<br>Given un documento puede ser recogido <br>When el sistema procesa la verificación <br>Then envía una alerta al usuario.<br><br>**Scenario 2:**<br>Given un documento nuevo <br>When el sistema detecta la generacion del documento <br>Then notifica al usuario inmediatamente. | E5 |
| US11   | Acceso a documentos offline | Como **usuario**, quiero acceder a mis documentos verificados incluso sin conexión a internet. | **Scenario 1:**<br>Given un usuario autenticado previamente <br>When no tiene conexión <br>Then el sistema permite visualizar documentos validados.<br><br>**Scenario 2:**<br>Given un usuario sin conexión <br>When intenta realizar una recarga <br>Then el sistema informa que la función no está disponible. | E6 |
| US12  | Información de funcionalidades | Como **visitante**, quiero ver en la landing page las funcionalidades principales de KapakID para entender sus beneficios. | **Scenario 1:**<br>Given un visitante accede a la landing <br>When navega a la sección de funcionalidades <br>Then visualiza la lista con descripciones claras.<br><br>**Scenario 2:**<br>Given un visitante explora la página <br>When busca información de seguridad <br>Then encuentra detalles sobre la protección de datos. | E7 |
| US13  | Acceso a la app          | Como **visitante**, quiero encontrar enlaces de acceso de KapakID en la landing page para acceder a la aplicación. | **Scenario 1:**<br>Given un visitante no registrado accede a la landing <br>When hace click en registrate <br>Then redirecciona al signin.<br><br> **Scenario 2:**<br>Given un visitante registrado accede a la landing <br>When hace click en ingresa <br>Then redirecciona al login.<br><br> | E7 |
| US14  | API de autenticación        | Como **developer**, quiero consumir un endpoint de autenticación para validar credenciales de usuarios. | **Scenario 1:**<br>Given un request con credenciales válidas <br>When se envía al endpoint de login <br>Then el sistema responde con un token válido.<br><br>**Scenario 2:**<br>Given un request con credenciales inválidas <br>When se procesa en el backend <br>Then el sistema devuelve un error 401 Unauthorized. | E8 |
| US15  | API de documentos           | Como **developer**, quiero consumir un endpoint para registrar y consultar documentos de un usuario. | **Scenario 1:**<br>Given un request válido con documento y metadatos <br>When se envía al endpoint correspondiente <br>Then el sistema responde confirmando el registro.<br><br>**Scenario 2:**<br>Given un request de consulta con un ID de documento válido <br>When se procesa en el backend <br>Then el sistema devuelve la información del documento. | E8 |

## 3.3. Impact Mapping

<td><img src="resources/Cap-3/Impact_Mapping/Impact_Mapping.png" alt="Impact Mapping" ></td>

## 3.4. Product Backlog

| Order | US ID | Título | Descripción | Story Points |
|-------|-------|--------|-------------|--------------|
| 1 | US12 | Información de funcionalidades | Como **visitante**, quiero ver en la landing page las funcionalidades principales de KapakID para entender sus beneficios. | 3 |
| 2 | US13 | Acceso a la app | Como **visitante**, quiero encontrar enlaces de acceso de KapakID en la landing page para acceder a la aplicación. | 2 |
| 3 | US1 | Registro de usuario | Como **usuario**, quiero registrarme con mi correo o celular para crear mi cuenta en KapakID. | 5 |
| 4 | US2 | Creación de perfiles familiares | Como **usuario**, quiero agregar perfiles de mis hijos para administrar sus documentos desde mi cuenta. | 4 |
| 5 | US3 | Registro de documentos | Como **usuario**, quiero registrar mi DNI, pasaporte y otros documentos para tenerlos disponibles en la app. | 5 |
| 6 | US4 | Renovación de documentos | Como **usuario**, quiero renovar mis documentos vencidos desde la app para evitar trámites presenciales. | 3 |
| 7 | US5 | Recarga de transporte | Como **usuario**, quiero recargar mi tarjeta del Metropolitano para no quedarme sin saldo. | 4 |
| 8 | US6 | Pago de deudas | Como **usuario**, quiero pagar mis deudas de servicios o multas desde la app para evitar filas. | 3 |
| 9 | US7 | Registro de transacciones | Como **usuario**, quiero registrar los movimientos de los documentos que he realizado desde la aplicación. | 4 |
| 10 | US8 | Voto digital único | Como **ciudadano**, quiero emitir mi voto en elecciones mediante KapakID para participar de manera segura. | 5 |
| 11 | US9 | Alerta de vencimiento | Como **usuario**, quiero recibir una notificación cuando mis documentos estén próximos a vencer. | 2 |
| 12 | US10 | Notificación de trámite | Como **usuario**, quiero recibir una notificación cuando se haya cumplido una solicitud de trámite. | 2 |
| 13 | US11 | Acceso a documentos offline | Como **usuario**, quiero acceder a mis documentos verificados incluso sin conexión a internet. | 3 |
| 14 | US14 | API de autenticación | Como **developer**, quiero consumir un endpoint de autenticación para validar credenciales de usuarios. | 3 |
| 15 | US15 | API de documentos | Como **developer**, quiero consumir un endpoint para registrar y consultar documentos de un usuario. | 4 |

En el siguiente apartado se mostrara el product Backlog generado en Jira, que ayudara al equipo durante el desarrollo de este proyecto

 <td><img src="resources/Cap-3/Product_Backlog/Product_Backlog.png" alt="Product Backlog" ></td>



# Capítulo IV: Product Design

En este capítulo se describen las directrices de diseño del producto **KapakID**, estableciendo lineamientos visuales y de interacción que garanticen una experiencia de usuario coherente, accesible y adaptada al contexto peruano.  
El objetivo es asegurar la consistencia estética y funcional en todas las plataformas (web y móvil), respetando tanto estándares internacionales de diseño como particularidades culturales y normativas locales.


## 4.1. Style Guidelines

Las guías de estilo definen la identidad visual del producto, determinando los principios básicos de **tipografía, color, iconografía, componentes y usabilidad**.  
Estas directrices buscan un equilibrio entre **modernidad, simplicidad y confianza**, elementos clave para una aplicación que gestiona documentos y pagos sensibles.



### 4.1.1. General Style Guidelines

#### Branding

El nombre **KapakID** proviene del término quechua *Qhapaq*, que significa **importante o principal**.  
Esta raíz cultural refuerza la esencia de la aplicación: ser una identidad digital central, segura y confiable para las personas.  

La marca proyecta tres valores fundamentales:

- **Seguridad**: protección de datos y confianza.  
- **Centralidad**: ser el eje principal de la identidad digital del usuario.  
- **Cultura**: rescatar lo importante (*Qhapaq*) como base de la modernidad.  

El logo combina un **escudo** como símbolo de protección, con un sistema de **nodos inspirados en los quipus**, que representan la unión de distintos servicios (documentos, movilidad, transacciones y validaciones).  
Esta integración transmite innovación tecnológica con un fuerte vínculo a la herencia cultural andina.  

<td><img src="resources/Cap-4/General_Style_Guidelines/Logo/Logo%20KapakID%20Moderno.png" alt="Logo KapakID Moderno"></td>


#### Paleta de Colores – KapakID

Los colores refuerzan los valores de **confianza, identidad cultural, seguridad y accesibilidad**.  
Se dividen en institucionales, de acción, alerta, neutrales y de acento cultural.  

<td><img src="resources/Cap-4/General_Style_Guidelines/Colors/Colors.png" alt="Paleta de Colores KapakID"></td>

**Colores institucionales**  
- Azul Escudo #0A3557: principal. Seguridad, headers, botones primarios.  
- Celeste Andino `#2D9CDB`: frescura, innovación, fondos alternativos.  

**Acción positiva**  
- Verde Conexión #17877D: validación, éxito, checkmarks.  
- Verde Andes #27AE60: energía, accesibilidad.  

**Alertas**  
- Rojo Señal #E85B46: errores críticos.  
- Naranja Inti #F2994A: advertencias preventivas.  

**Neutrales**  
- Blanco Nevado #F9FAFB: fondo principal.  
- Gris Claro #E5E7EB: fondos secundarios.  
- Gris Neutro #6B7280: textos secundarios, íconos inactivos.  
- Gris Oscuro #374151: textos principales.  

**Acento cultural**  
- Amarillo Inti #F2C94C: energía, resaltes, microinteracciones.  
- Lila Qhapaq #9B51E0: innovación, modernidad.  

#### Tipografía – KapakID

La tipografía es un eje central en la identidad visual. Se busca un estilo **moderno, claro y altamente legible** en dispositivos móviles y entornos digitales.  

<td><img src="resources/Cap-4/General_Style_Guidelines/Typos/Diseño%20Tipográfico%20.png" alt="Diseño Tipográfico"></td>

**Fuentes principales**  
- **Poppins Bold** → títulos y encabezados.  
- **Poppins Medium** → subtítulos y secundarios.  
- **Roboto Regular** → párrafos y formularios.  
- **Roboto Mono** → datos técnicos, validaciones, códigos.  
<td><img src="resources/Cap-4/General_Style_Guidelines/Typos/Fuentes%20y%20Tipografías.png" alt="Fuentes y Tipografías"></td>

**Escala tipográfica**  
- H1: 32–36 px, Poppins Bold, Azul Escudo.  
- H2: 24–28 px, Poppins Medium, Gris Oscuro.  
- H3: 18–22 px, Poppins Medium, Gris Neutro.  
- Texto cuerpo: 14–16 px, Roboto Regular.  
- Texto técnico: 12–14 px, Roboto Mono.  
- Texto ayuda: 12–14 px, Roboto Regular Gris Claro.  
<td><img src="resources/Cap-4/General_Style_Guidelines/Typos/Tipográfica%20.png" alt="Ejemplo Tipográfico"></td>

**Line-height y espaciado**  
- Encabezados: 110%.  
- Texto principal: 140–150%.  
- Texto técnico: 130%.  
#### Iconografía

La iconografía aporta **claridad, simplicidad y accesibilidad** en la navegación.  

<td><img src="resources/Cap-4/General_Style_Guidelines/Typos/Iconografía.png" alt="Iconografía KapakID"></td>

- Estilo outline minimalista, 2 px.  
- Esquinas redondeadas, coherentes con botones y tarjetas.  
- Colores según estado:  
  - Azul Escudo → íconos principales.  
  - Verde Conexión → validaciones.  
  - Rojo Señal → errores.  
  - Gris Neutro → inactivos.  
- Ejemplos: documentos, identidad, transporte, pagos, validaciones.  
- Todos los íconos deben tener etiquetas accesibles (`alt` / `aria-label`).  

#### Jerarquía Visual
La jerarquía organiza la información de forma clara y priorizada:  
- **Títulos principales (H1):** Azul Escudo, 32–36 px.  
- **Subtítulos (H2–H3):** Gris Neutro, 18–28 px.  
- **Texto principal:** Roboto Regular, 14–16 px, Gris Oscuro.  
- **Botón primario:** Azul Escudo, texto blanco.  
- **Botón secundario:** Verde Conexión o Gris Neutro.  
- **Acciones críticas:** Rojo Señal + ícono de advertencia.  


### 4.1.2. Web Style Guidelines
Para KapakID, se plantea una plataforma web con un enfoque de **seguridad, claridad y accesibilidad**, que ofrezca una experiencia confiable y eficiente para la gestión de identidad y servicios digitales.  
Se implementará un **diseño adaptable (Responsive Design)** que optimice la presentación de la información en cualquier dispositivo, garantizando legibilidad y usabilidad en todo momento.

#### Panel de control principal (Dashboard)
- Acceso centralizado a documentos digitales (DNI, pasaporte, carné universitario).  
- Visualización de saldo disponible y notificaciones relevantes.  
- Gestión rápida de pagos, recargas y alertas.  

#### Gestión de Documentos y Pagos
- Añadir, validar y consultar documentos oficiales.  
- Realizar pagos de servicios básicos y transporte.  
- Módulos organizados en tarjetas visuales fáciles de identificar con íconos representativos.  

#### Transporte y Movilidad
- Recarga de tarjetas de transporte.  
- Consulta de historial de viajes.  
- Alertas sobre vencimientos o saldos bajos.  

#### Alertas y Notificaciones
- Avisos sobre documentos próximos a vencer.  
- Pagos pendientes o validaciones críticas.  
- Priorización de seguridad para evitar contratiempos.  

#### Comunicación y Soporte
- Sección de ayuda accesible desde el menú principal.  
- Guías, preguntas frecuentes y chat de asistencia en tiempo real.  

Este diseño garantiza **usabilidad, eficiencia y confianza**, consolidando a KapakID como una **super-app peruana de conectividad y modernidad digital**.


## 4.2. Information Architecture
### 4.2.1. Organization Systems

#### Landing Page e Inicio de la Aplicación
- **Tipo de organización:** Jerárquica.  
- La landing page destacará: beneficios, funcionalidades principales (documentos, pagos, transporte y alertas) y testimonios.  
- En la pantalla de inicio se priorizan accesos rápidos al DNI digital, saldos, pagos pendientes y alertas urgentes.  

#### Gestión de Documentos y Pagos
- **Tipo de organización:** Secuencial.  
- Flujos: registro → validación → confirmación.  
- Reduce errores y refuerza la seguridad.  

#### Módulos de Transporte y Movilidad
- **Tipo de organización:** Matricial.  
- Acceso a recargas, historial de viajes y tarjetas vinculadas.  
- Exploración flexible por saldo, fecha o tipo de transporte.  

#### Alertas y Notificaciones
- **Esquema de categorización:** Por tópicos.  
- Categorías: seguridad, transporte, pagos, documentos.  
- Permite priorizar atención de forma inmediata.  

#### Historial de Transacciones y Actividades
- **Esquema de categorización:** Cronológico.  
- Pagos, recargas y validaciones ordenados por fecha.  
- Registro confiable y auditable.  

#### Contenido Personalizado por Perfil de Usuario
- **Esquema de categorización:** Según audiencia.  
- **Estudiantes:** Recargas rápidas, gestión de carné universitario, beneficios educativos.  
- **Familias:** Perfiles familiares para pagos y documentos de dependientes.  
- **Ciudadanos generales:** Validación de identidad, pagos de servicios básicos, transporte.  

#### Búsqueda de Documentos y Servicios
- **Esquema de categorización:** Alfabético.  
- Localización rápida de documentos y servicios.  
  
### 4.2.2. Labeling Systems
#### Landing Page
- **Home/Inicio:** Propuesta de valor de KapakID.  
- **Features/Características:** Funciones clave (identidad digital, pagos, transporte).  
- **Benefits/Beneficios:** Seguridad, rapidez, confianza y centralización.  
- **Testimonials/Testimonios:** Experiencias de usuarios.  
- **About/Acerca de:** Equipo desarrollador y propósito de KapakID (*Qhapaq = importante*).  
- **Contact/Contacto:** Soporte, redes sociales, correo.  

#### Web Application
- **Home/Inicio:** Accesos rápidos a DNI digital, saldo, pagos pendientes y alertas.  
- **Perfil:** Gestión de información personal, documentos, métodos de pago y preferencias.  
- **Documentos:** DNI, pasaporte, carné universitario, brevete.  
- **Pagos:** Servicios, transporte y recargas. Incluye historial.  
- **Transporte:** Tarjetas vinculadas, historial de viajes, saldos y recargas.  
- **Búsqueda:** Localización de documentos o servicios.  
- **Favoritos:** Acceso a elementos prioritarios.  
- **Alertas/Notificaciones:** Vencimientos, saldos bajos, pagos pendientes.  
- **Soporte:** FAQs, guías y contacto con atención al cliente.  
  

### 4.2.3. SEO Tags and Meta Tags
– KapakID  

#### Landing Page  
Title: Texto visible en la parte superior del navegador y en los resultados de búsqueda.  

```html
<title>KapakID – Tu identidad y pagos digitales seguros en un solo lugar</title>
-Codificación de caracteres:
<meta charset="utf-8">
-Description: Breve descripción de la aplicación.
<meta name="description" content="KapakID es tu plataforma digital segura para gestionar tu identidad, documentos y pagos en un solo lugar."/>

-Key Words: Palabras clave relacionadas con la app.
<meta name="keywords" content="identidad digital, billetera electrónica, pagos seguros, transporte, documentos digitales, Perú"/>

Author & Copyright:

<meta name="author" content="KapakID Team"/>
<meta name="copyright" content="Copyright KapakID Team" />

-Web Application
-Title:
<title>KapakID</title>
-Description
<meta name="description" content="KapakID – Plataforma oficial para gestionar tu identidad digital, documentos y pagos de forma segura."/>

-Key Words:
<meta name="keywords" content="KapakID, identidad digital, pagos, transporte, documentos, seguridad, conectividad"/>
-Author & Copyright:
<meta name="author" content="KapakID Team"/>
<meta name="copyright" content="Copyright KapakID Team" />

```

### 4.2.4. Searching Systems – KapakID  

- **Barra de búsqueda general:**  
  Ubicada en la parte superior derecha de la plataforma web y dentro del menú principal de la app.  
  Permitirá acceder rápidamente a recursos como: validación de documentos, historial de pagos, transporte, billetera digital y servicios vinculados.  

- **Sugerencias automáticas (autocompletado):**  
  El sistema mostrará resultados predictivos mientras el usuario escribe, basados en documentos registrados (DNI, brevete, carnés), transacciones recientes y accesos frecuentes.  

- **Filtros de búsqueda:**  
  Se ofrecerán filtros que permitan refinar la búsqueda según:  
  - Categorías: Identidad, Pagos, Transporte, Beneficios Sociales.  
  - Contenido: Documentos, Transacciones, Validaciones, Recibos.  
  - Estado: Activo, Expirado, Pendiente de validación.  

- **Filtros avanzados:**  
  Opciones adicionales como:  
  - Recientes / Más antiguos.  
  - Monto de transacción.  
  - Tipo de pago (tarjeta, QR, billetera digital).  
  - Institución asociada (RENIEC, bancos, transporte).  
---
### 4.2.5. Navigation Systems – KapakID  

#### Landing Page  
La navegación en la landing page estará orientada a generar confianza y facilitar el registro.  
Se implementará un menú superior con enlaces visibles hacia:  

- **Inicio:** Presentación general de KapakID.  
- **Características:** Explicación de las principales funciones (identidad digital, pagos, transporte).  
- **Beneficios:** Cómo mejora la vida del usuario en seguridad, accesibilidad y rapidez.  
- **Testimonios:** Opiniones de usuarios reales y casos de uso.  
- **Acerca de:** Información del equipo y visión de KapakID.  
- **Contacto:** Formulario y canales de atención.  


#### Web Application  

Dentro de la **aplicación web**, la navegación se centrará en un **dashboard central**, accesible tras el inicio de sesión.  

- **Dashboard principal:**  
  Vista general con accesos rápidos a identidad, billetera digital, transporte y notificaciones prioritarias.  

- **Panel lateral de navegación (sidebar):**  
  - **Perfil:** Información personal, configuración y preferencias.  
  - **Documentos:** Gestión y validación de DNI, brevete, carnés, etc.  
  - **Pagos:** Métodos de pago, recargas, historial de transacciones y comprobantes.  
  - **Transporte:** Tickets, pasajes electrónicos y servicios de movilidad urbana.  
  - **Historial:** Registro cronológico de actividades, transacciones y validaciones.  
  - **Notificaciones:** Alertas de vencimiento, confirmaciones y actualizaciones del sistema.  
  - **Soporte / Ayuda:** FAQs, chat en línea y contacto directo con asistencia.  

- **Consistencia visual:** El logotipo en la parte superior del sidebar permitirá volver al **dashboard principal**.  
- **Acciones rápidas:** Atajos destacados en el dashboard (ej. “Validar documento”, “Recargar saldo”, “Comprar pasaje”) para reducir clics y mejorar eficiencia.  

## 4.3. Landing Page UI Desing
### 4.3.1. Landing Page Wireframes
<img src="./resources/Cap-4/General_Style_Guidelines/Wireframe Landing.jpg" alt="Wireframe Landing">

### 4.3.2. Landing Page Mock-Up

<img src="./resources/Cap-4/General_Style_Guidelines/LandingPage KapaID Mockup.png" alt="Landing Page Mock-Up2">
<img src="./resources/Cap-4/General_Style_Guidelines/LandingPage KapaID Mockup2.png" alt="Landing Page Mock-Up">

## 4.4. Web Applications UX/UI Desing
### 4.4.1. Web Applications Wireframes
<img src="./resources/Cap-4/General_Style_Guidelines/wireframe webaplication1.png" alt="Wireframe web aplication">
<img src="./resources/Cap-4/General_Style_Guidelines/wireframe webaplication2.png" alt="Wireframe web aplication">
<img src="./resources/Cap-4/General_Style_Guidelines/wireframe webaplication3.jpg" alt="Wireframe web aplication">
<img src="./resources/Cap-4/General_Style_Guidelines/wireframe webaplication4.png" alt="Wireframe web aplication">
<img src="./resources/Cap-4/General_Style_Guidelines/wireframe webaplication5.png" alt="Wireframe web aplication">

### 4.4.2. Web Applications Wireflow Diagrams
<img src="./resources/Cap-4/General_Style_Guidelines/Typos/WireframeDiagram.jpg" alt="Wireframe web diagram">


### 4.4.3. Web Applications User Flow Diagrams
<img src="./resources/Cap-4/General_Style_Guidelines/Typos/UserFlowDiagram.jpg" alt="user flow diagram">

### 4.4.4. Web Applications Mockup

<img src="./resources/Cap-4/General_Style_Guidelines/Typos/WebMockup1.jpg" alt="application web diagram">
<img src="./resources/Cap-4/General_Style_Guidelines/Typos/WebMockup2.jpg" alt="application web diagram">
<img src="./resources/Cap-4/General_Style_Guidelines/Typos/WebMockup3.jpg" alt="application web diagram">
<img src="./resources/Cap-4/General_Style_Guidelines/Typos/WebMockup4.jpg" alt="application web diagram">


## 4.5. Web Applications Prototyping

https://www.figma.com/design/3HTodQ2CADUGConW20ZLCc/Untitled?node-id=0-1&p=f&t=WclMvp5kiCyljXH8-0

## 4.6. Domain-Driven Software Architecture
En el apartado de Domain Driven Software Architecture para KapakID, puedes introducir el concepto destacando cómo esta metodología guía el diseño de la aplicación alineándose con el dominio del negocio. Por ejemplo:
"La arquitectura orientada al dominio (DDD) para KapakID se centra en modelar el sistema en torno al dominio del negocio, que es la gestión digital de documentos y tarjetas personales, como DNI, pasaportes, carnés y tarjetas de transporte, junto con funcionalidades de transacciones, renovaciones y notificaciones. Este enfoque asegura que el software refleje fielmente las necesidades de los usuarios (jóvenes y adultos) y los procesos clave, como registro de documentos, pagos y soporte premium para perfiles familiares. Al emplear DDD, priorizamos un lenguaje ubicuo que unifica la comunicación entre el equipo técnico y los stakeholders, garantizando que cada componente del sistema responda directamente a los requisitos del dominio, promoviendo una solución robusta, escalable y alineada con el propósito de ofrecer una billetera digital integral, segura y accesible.
### 4.6.1. Software Architecture Context Diagram
![context diagram c4](<resources/Cap-4/Model_C4/structurizr-SystemContext-001.png>)
### 4.6.2. Software Architecture Container Diagram
![container diagram c4](<resources/Cap-4/Model_C4/structurizr-ContainerDiagram.png>)
### 4.6.3. Software Architecture Components Diagram
![](<>)
![](<>)
![](<>)
![](<>)
![](<>)
## 4.7. Software Object-Oriented Desing
### 4.7.1. Class Diagram
![](<>)
### 4.7.2. Class Dictionary

## 4.8. Database Desing
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

| Categoría                | Producto / Lenguaje / Framework | Propósito dentro del proyecto                                                                 | Ruta de descarga / referencia |
|---------------------------|---------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------|
| **Project Management**    | Trello                          | Gestión de tareas, backlog, sprints y seguimiento del avance del equipo.                      | [https://trello.com](https://trello.com) |
| **Requirements Management** | Notion                        | Documentar, centralizar y gestionar requerimientos, especificaciones y notas de proyecto.      | [https://www.notion.so](https://www.notion.so) |
| **Product UI/UX Design**  | Figma                          | Diseño de interfaces gráficas, prototipado colaborativo y validación con el cliente.           | [https://www.figma.com](https://www.figma.com) |
| **Software Development**  | Lenguaje: C#                   | Desarrollo del backend y lógica de negocio.                                                   | [https://dotnet.microsoft.com/download](https://dotnet.microsoft.com/download) |
|                           | Lenguaje: JavaScript (JS)      | Desarrollo del frontend dinámico y componentes interactivos.                                  | [https://nodejs.org](https://nodejs.org) |
|                           | Framework: .NET Core           | Construcción de APIs y servicios backend robustos y escalables.                               | [https://dotnet.microsoft.com/download](https://dotnet.microsoft.com/download) |
|                           | Framework: Vue (Vue CLI)       | Desarrollo del frontend como SPA (Single Page Application).                                   | [https://cli.vuejs.org/](https://cli.vuejs.org/) |
|                           | IDE: Visual Studio Code        | Editor ligero y multiplataforma para desarrollo general.                                      | [https://code.visualstudio.com](https://code.visualstudio.com) |
|                           | IDE: JetBrains Rider           | IDE especializado para backend con C#.                                                        | [https://www.jetbrains.com/rider/](https://www.jetbrains.com/rider/) |
|                           | IDE: JetBrains WebStorm        | IDE especializado para frontend con Vue.js.                                                   | [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/) |
|                           | Git                            | Control de versiones distribuido para gestionar cambios en el código.                         | [https://git-scm.com/downloads](https://git-scm.com/downloads) |
|                           | GitHub                         | Repositorio central para alojar el código, colaborar y gestionar integración continua.         | [https://github.com](https://github.com) |
| **Software Deployment**   | Azure DevOps                   | Automatización de CI/CD, gestión de pipelines e implementación en la nube.                    | [https://azure.microsoft.com/services/devops/](https://azure.microsoft.com/services/devops/) |
| **Software Documentation**| MkDocs                         | Generación de documentación técnica en formato estático, integrada con repositorios Git.       | [https://www.mkdocs.org](https://www.mkdocs.org) |

### 5.1.2. Source Code Management


En este proyecto se utilizará **GitHub** como plataforma y sistema de control de versiones para la gestión del código fuente.  

---

####  Repositorios del proyecto  

- **Documentación (Docs)** → [REPO_DOCS](https://github.com/F1nTrack/report.git)
- **Landing Page** → [REPO_LANDING](https://github.com/F1nTrack/landingPage.git)
- **Frontend Web Application** → [REPO_FRONTEND](https://github.com/F1nTrack/frontend-web-application.git) 
- **Web Services (Backend + Tests)** → [REPO_BACKEND]  

En el repositorio de **Web Services** se incluirán tanto el proyecto principal como los archivos de pruebas unitarias y de integración/aceptación.  

---

####  GitFlow Workflow  

El equipo aplicará la estrategia de ramificación **GitFlow**, propuesta por Vincent Driessen, para garantizar un control estructurado de versiones y facilitar el trabajo colaborativo.  

#####  Ramas principales  

1. **`main`**  
   - Rama principal del proyecto.  
   - Contiene únicamente versiones estables y liberadas en producción.  
   - Solo recibe merges desde ramas **release** o **hotfix**.  

2. **`develop`**  
   - Rama de integración donde se consolidan todas las funcionalidades en desarrollo.  
   - Representa el estado más actualizado previo a un release.  

#####  Ramas de soporte  

3. **`feature/<nombre-funcionalidad>`**  
   - Usada para el desarrollo de nuevas funcionalidades.  
   - Se crea a partir de `develop` y se fusiona de nuevo en `develop` cuando la tarea está lista.  
   - **Convención de nombres**: `feature/login-auth`, `feature/user-profile`, etc.  

4. **`release/x.y.z`**  
   - Preparación de una nueva versión estable.  
   - Permite pruebas finales, correcciones menores y documentación.  
   - Se fusiona en `main` (para liberar la versión) y en `develop` (para mantener consistencia).  
   - **Convención de nombres**: `release/1.0.0`, siguiendo **Semantic Versioning 2.0.0**.  

5. **`hotfix/x.y.z`**  
   - Para resolver errores críticos detectados en producción.  
   - Se crea a partir de `main` y se fusiona en `main` y `develop` tras la corrección.  
   - **Convención de nombres**: `hotfix/1.0.1`.  

---

####  Convenciones de versionado  

- Se aplicará **Semantic Versioning 2.0.0**, con el esquema:  
  - **MAJOR** → cambios incompatibles o nuevas arquitecturas.  
  - **MINOR** → nuevas funcionalidades compatibles.  
  - **PATCH** → correcciones y mejoras menores.  
---
####  Convenciones de commits  

Se aplicará el estándar **Conventional Commits**, con los siguientes prefijos:  

- **feat:** nueva funcionalidad → `feat: agregar autenticación con JWT`  
- **fix:** corrección de bug → `fix: resolver error en validación de email`  
- **docs:** cambios en documentación → `docs: actualizar guía de instalación`  
- **style:** cambios de formato (sin afectar la lógica)  
- **refactor:** reestructuración de código sin cambio funcional  
- **test:** agregar o modificar pruebas automatizadas  
- **chore:** tareas menores o de mantenimiento 

Ejemplo: `v1.0.0`, `v1.1.0`, `v1.1.1`.  

### 5.1.3. Source Code Style Guide & Conventions


El equipo adoptará un conjunto de **convenciones de estilo y guías de codificación** para mantener un código limpio, consistente y fácil de mantener.  
Todas las nomenclaturas (nombres de variables, funciones, clases, archivos y carpetas) se escribirán en **inglés**.  

---

 #### HTML
- Basado en: [W3C HTML Coding Style](https://www.w3.org/2009/cheatsheet/#source:html) y [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html).  
- Reglas principales:  
  - Código indentado con **2 espacios**.  
  - Uso de **minúsculas** para etiquetas y atributos.  
  - Uso de comillas dobles (`" "`) en atributos.  
  - Estructura semántica correcta (`<header>`, `<main>`, `<footer>`, etc.).  
  - Comentarios claros (`<!-- Descripción -->`).  

---

 #### CSS  
- Basado en: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html).  
- Reglas principales:  
  - **Kebab-case** para nombres de clases: `.main-container`, `.button-primary`.  
  - Organización de reglas siguiendo el orden: posición → caja → tipografía → visual → otros.  
  - Uso de **variables CSS** para colores y tipografías.  
  - Evitar el uso de `!important` salvo casos excepcionales.  
  - Código indentado con **2 espacios**.  

---

####  JavaScript  
- Basado en: [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html), [MDN Guidelines](https://developer.mozilla.org/en-US/docs/MDN/Guidelines) y [W3C JavaScript Guide](https://www.w3.org/wiki/JavaScript_best_practices).  
- Reglas principales:  
  - **camelCase** para variables y funciones: `userName`, `getUserData()`.  
  - **PascalCase** para clases y componentes: `UserService`, `LoginForm`.  
  - Declaraciones con `const` y `let` (evitar `var`).  
  - Uso de funciones flecha (`()=>`) cuando sea apropiado.  
  - Cada archivo debe exportar **una sola clase o componente principal**.  
  - Código indentado con **2 espacios**.  

---

##  Vue.js  
- Basado en: [Vue Style Guide (Oficial)](https://vuejs.org/style-guide/).  
- Reglas principales:  
  - Componentes en **PascalCase**: `UserProfile.vue`.  
  - Props en **camelCase** en JS y **kebab-case** en templates:  
    ```vue
    <UserProfile user-name="John" />
    props: { userName: String }
    ```  
  - Orden de secciones en componentes: `template` → `script` → `style`.  
  - Código indentado con **2 espacios**.  
  - Uso de **scoped styles** para evitar colisiones.  

---

##  C#  
- Basado en: [Microsoft C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) y [ASP.NET Core Guidelines](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#aspnet-core).  
- Reglas principales:  
  - **PascalCase** para clases, métodos y propiedades: `CustomerService`, `GetUser()`.  
  - **camelCase** para variables locales y parámetros: `int userId`.  
  - Nombres de interfaces comienzan con `I`: `IRepository`, `IService`.  
  - Cada archivo debe contener **una clase pública principal**.  
  - Uso de **expresiones lambda** y **LINQ** para colecciones.  
  - Código indentado con **4 espacios**.  

---

##  BDD (Gherkin) para pruebas de aceptación  
- Basado en: [Gherkin Conventions](https://cucumber.io/docs/gherkin/).  
- Reglas principales:  
  - Escenarios escritos en inglés.  
  - Formato estándar:  
    ```
    Feature: User Login
      Scenario: Successful login
        Given the user is on the login page
        When the user submits valid credentials
        Then the system redirects to the dashboard
    ```  

---

##  Resumen de nomenclatura por lenguaje  

- **HTML** → etiquetas y atributos en minúsculas.  
- **CSS** → `kebab-case`.  
- **JavaScript** → `camelCase` (variables/funciones), `PascalCase` (clases/componentes).  
- **Vue.js** → Componentes en `PascalCase`, props `camelCase/kebab-case`.  
- **C#** → `PascalCase` (clases/métodos), `camelCase` (variables/parametros), interfaces con prefijo `I`.  

---


### 5.1.4. Software Deployment Configuration

En esta sección se especifica la configuración necesaria para el despliegue de la solución digital, detallando los pasos para publicar satisfactoriamente cada producto a partir de sus repositorios de código fuente.

---

### 1. Landing Page
**Repositorio:** [REPO_LANDING](https://github.com/F1nTrack/landingPage.git)

**Configuración de despliegue:**
1. Clonar el repositorio desde GitHub.
2. Instalar dependencias necesarias con `npm install`.
3. Generar la build de producción con `npm run build`.
4. Configurar el hosting (ejemplo: Azure Static Web Apps, Vercel o Netlify).
5. Desplegar la carpeta generada `/dist` o `/build`.
6. Verificar la disponibilidad en el dominio configurado.

---

### 2. Web Services (Backend)
**Repositorio:** [URL_REPO_BACKEND]

**Configuración de despliegue:**
1. Clonar el repositorio desde GitHub.
2. Abrir el proyecto en **JetBrains Rider**.
3. Restaurar dependencias de .NET Core con `dotnet restore`.
4. Ejecutar las pruebas unitarias e integración incluidas en el repositorio.
5. Configurar variables de entorno (por ejemplo: cadenas de conexión a base de datos, credenciales).
6. Publicar el servicio con `dotnet publish`.
7. Implementar en Azure App Service u otro servicio de hosting para APIs.
8. Monitorear logs y asegurar la correcta disponibilidad de los endpoints.

---

### 3. Frontend Web Applications
**Repositorio:** [REPO_FRONTEND](https://github.com/F1nTrack/frontend-web-application.git)

**Configuración de despliegue:**
1. Clonar el repositorio desde GitHub.
2. Abrir el proyecto en **JetBrains WebStorm** o **VS Code**.
3. Instalar dependencias con `npm install`.
4. Generar la build de producción con `npm run build`.
5. Configurar el servidor de despliegue (ejemplo: Azure Static Web Apps, Vercel o Netlify).
6. Desplegar la carpeta generada `/dist`.
7. Validar la correcta integración con los Web Services desplegados.

---

📌 **Notas adicionales:**
- Se recomienda el uso de **Azure DevOps** para automatizar el despliegue mediante pipelines CI/CD.  
- Cada despliegue debe estar vinculado a una rama específica del GitFlow (generalmente `release` o `main`).  
- Todos los entornos deben contar con **versionado semántico** y logs de cambios documentados en GitHub.


## 5.2. Landing Page, Service & Applications Implementation
### 5.2.x. Sprints

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

# Conclusiones

Conclusiones y recomendaciones
