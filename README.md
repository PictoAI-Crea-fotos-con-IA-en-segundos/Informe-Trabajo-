**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

![Logotipo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714691535/gmplcgrlsv9sihpusivm.png)

**SI728 Arquitecturas De Software Emergentes**

Informe del trabajo TP

**Profesor:** Royer Edelwer Rojas Malasquez

**Startup:** LooGood

**Producto:** PictoAI

**Integrantes:**

Josef Cesar Romero Florida (U201910655)

Richar Varoni Romero Cacha (U20201B428)

Ángel Gustavo Chuco Michel (U201613694)

Frank Yamil Alva Cordova (U202020026)

Lino Abraham Quenta Leon (U20211F978)

**Abril, 25 de 2024**

Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [Startup Profile](#startup-profile)
    - [Descripción de Startup](#descripción-de-startup)
    - [Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [Solution Profile](#solution-profile)
    - [Antecedentes y Problemática](#antecedentes-y-problemática)
    - [Lean UX Process](#lean-ux-process)
  - [Segmento Objetivo](#segmento-objetivo)
    - [Segmento Objetivo 1: El Usuario Entusiasta](#segmento-objetivo-1-el-usuario-entusiasta)
    - [Segmento Objetivo 2: El Usuario Profesional](#segmento-objetivo-2-el-usuario-profesional)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [Competidores](#competidores)
    - [Análisis competitivo](#análisis-competitivo)
    - [Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [Entrevistas](#entrevistas)
    - [Diseño de entrevistas.](#diseño-de-entrevistas)
    - [Registro de entrevistas](#registro-de-entrevistas)
  - [Needfinding](#needfinding)
    - [User Personas](#user-personas)
    - [User Task Matrix](#user-task-matrix)
    - [Empathy Mapping](#empathy-mapping)
    - [As-is Scenario Mapping](#as-is-scenario-mapping)
  - [Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [To-Be Scenario Mapping](#to-be-scenario-mapping)
  - [User Stories](#user-stories)
  - [Impact Mapping](#impact-mapping)
  - [Product Backlog](#product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [Strategic-Level Attribute-Driven Design](#strategic-level-attribute-driven-design)
    - [Design Purpose](#design-purpose)
    - [Attribute-Driven Design Inputs](#attribute-driven-design-inputs)
    - [Architectural Drivers Backlog](#architectural-drivers-backlog)
    - [Architectural Design Decisions](#architectural-design-decisions)
    - [Quality Attribute Scenario Refinements](#quality-attribute-scenario-refinements)
  - [Strategic-Level Domain-Driven Design](#strategic-level-domain-driven-design)
    - [EventStorming](#eventstorming)
    - [Candidate Context Discovery](#candidate-context-discovery)
    - [Domain Message Flows Modeling](#domain-message-flows-modeling)
    - [Context Mapping](#context-mapping)
  - [Software Architecture](#software-architecture)
    - [Software Architecture System Landscape Diagram](#software-architecture-system-landscape-diagram)
    - [Software Architecture Context Level Diagrams](#software-architecture-context-level-diagrams)
    - [Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams)
    - [Software Architecture Deployment Diagrams](#software-architecture-deployment-diagrams)
- [Capítulo V: Tactical-Level Software ![Interfaz de usuario gráfica Descripción generada automáticamente con confianza baja](media/b083affb6155b5203b7a589180585271.png)Design.](#capítulo-v-tactical-level-software-design)

    - [5.1. Bounded Context: PhotoRepository](#51-bounded-context-photorepository)

      - [5.1.1. Domain Layer.](#511-domain-layer)

      - [5.1.2. Interface Layer.](#512-interface-layer)

      - [5.1.3. Application Layer.](#513-application-layer)

      - [5.1.4. Infrastructure Layer.](#514-infrastructure-layer)

      - [5.1.6. Bounded Context Software Architecture Component Level Diagrams.](#516-bounded-context-software-architecture-component-level-diagrams)

      - [5.1.7. Bounded Context Software Architecture Code Level Diagrams.](#517-bounded-context-software-architecture-code-level-diagrams)

- [Capítulo VI: Solution UX Design.](#capítulo-vi-solution-ux-design)

  - [6.1. Style Guidelines.](#61-style-guidelines)
    - [6.1.1. General Style Guidelines.](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines.](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.2. Labeling Systems.](#622-labeling-systems)
    - [6.2.3. SEO Tags and Meta Tags.](#623-seo-tags-and-meta-tags)
    - [6.2.4. Searching Systems.](#624-searching-systems)
    - [6.2.5. Navigation Systems.](#625-navigation-systems)
    - [6.3. Landing Page UI Design.](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe.](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up.](#632-landing-page-mock-up)
    - [6.4. Applications UX/UI Design.](#64-applications-uxui-design)
      - [6.4.1. Applications Wireframes.](#641-applications-wireframes)
      - [6.4.2. Applications Wireflow Diagrams.](#642-applications-wireflow-diagrams)
        
- [ANEXO.](#anexo)

# Capítulo I: Introducción

## Startup Profile

### Descripción de Startup

El startup se enfoca en desarrollar una solución de generación de fotos de personas mediante inteligencia artificial con la herramienta Stable Diffusion. Nuestra plataforma utiliza algoritmos avanzados de procesamiento de imágenes para crear retratos realistas y personalizados. Nuestro objetivo es ofrecer una experiencia única y satisfactoria para nuestros usuarios, ya sean entusiastas de la fotografía o profesionales que buscan herramientas innovadoras para su trabajo

### Perfiles de integrantes del equipo

| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714691769/plsom3g062z266k84csh.jpg)  | Soy Ángel Gustavo Chuco Michel, tengo 24 años, estudió la carrera de Ingeniería de Software, soy una persona amante de la tecnología y las nuevas tendencias. Considero que tengo aptitudes positivas en el trabajo en equipo y me gusta participar constantemente con mis compañeros.                                                                                                                                                                                                                |
|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714691858/yrgbt9kbb78auh44e0q6.jpg)  | Soy Frank Alva Cordova, tengo 21 años, estudio la carrera de Ingenieria de Software, soy una persona responsable y entusiasta.  Puedo aportar mis conocimientos en desarrollo web y móvil para alcanzar los objetivos planteados. Considero que puedo aportar con el grupo con los conocimientos adquiridos en el curso.                                                                                                                                                                              |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714691838/bdtt9jwaolx4hf7w38ev.jpg)  | Romero Florida, Josef Ingeniería de SoftwareTengo 21 años y soy originario de Lima. Mi formación escolar fue en el colegio Nuestra Señora del Sagrado Corazón. Actualmente, me encuentro cursando la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, una elección motivada por mi pasión hacia la tecnología. Creo firmemente en la llegada de la Inteligencia General Artificial (AGI) y siempre busco oportunidades para incrementar mi conocimiento en el campo |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714691883/w3sdrjtgmvdua5ukmg6p.jpg) | Soy Lino abraham quenta leon, 20 año soy estudiante de la universidad peruana de ciencias aplicadas, actualmente curso el 8 ciclo de la carrera de ingeniería de software, me considero una persona super creativa, me gustas el diseño y la programación web, además de gestionar proyectos, con habilidades blandas ya definidas, además que siempre busco mejorar cada vez más.                                                                                                                    |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714691900/usb0eonta1gw1mlny8ol.jpg)  | Soy Richar Romero, Tengo 22 años, entre mis principales habilidades se encuentra la capacidad de guardar información, la empatía, el ser resiliente y tengo conocimiento en los lenguajes de C++, C\#, python,JS,Kotlin y en frameworks como vue y angular.                                                                                                                                                                                                                                           |

## Solution Profile

### Antecedentes y Problemática

La generación de fotos de personas mediante inteligencia artificial surge como respuesta a la creciente demanda de herramientas innovadoras en el campo de la fotografía digital. En la búsqueda de empleo, una fotografía profesional en el currículum vitae (CV) es crucial. Sin embargo, muchos enfrentan dificultades para obtener una foto adecuada debido a la falta de tiempo para programar una sesión de fotos tradicional, lo que lleva a explorar opciones innovadoras, como una plataforma de generación de fotos mediante inteligencia artificial.

### Lean UX Process

1.  **Lean UX Problem Statements:**

    Limitaciones de tiempo para sesiones de fotos tradicionales: Muchos usuarios tienen agendas ocupadas que dificultan la programación de sesiones de fotos profesionales.

    Accesibilidad y conveniencia: La falta de estudios fotográficos cercanos o la necesidad de desplazarse pueden hacer que obtener una foto profesional sea inconveniente para algunos usuarios.

2.  **Lean UX Assumptions:**  
    **Para los clientes entusiastas:**

    Se asume que los clientes entusiastas valoran la facilidad de uso y la conveniencia en las soluciones de generación de fotos, priorizando herramientas intuitivas que les permitan crear imágenes de manera rápida y sencilla.

    **Para los clientes profesionales:**

    Se asume que los clientes profesionales priorizan la calidad y la personalización en las herramientas de generación de fotos, buscando soluciones que les permitan crear retratos de alta calidad y adaptados a sus necesidades específicas para su uso en entornos laborales.

    **Para ambos:**

    Se asume que tanto los clientes entusiastas como los profesionales valoran los resultados profesionales en las fotos generadas, así como la accesibilidad y la facilidad de uso de la plataforma. Ambos segmentos buscan soluciones que les permitan obtener fotos de calidad con poco esfuerzo y sin la necesidad de habilidades técnicas avanzadas.

3.  **Lean UX Hypothesis Statements**

| **Creemos que:** Al ofrecer una interfaz de usuario intuitiva y sencilla para cargar y editar fotografías, los usuarios estarán más inclinados a utilizar nuestra aplicación. **Sabremos que:** Cuando realicemos pruebas de usabilidad con usuarios de diferentes niveles de experiencia en edición de fotos y la mayoría pueda completar las tareas básicas sin problemas. **Cuando veamos:** Un aumento en la tasa de retención de usuarios y una disminución en el abandono durante el proceso de edición de fotos en comparación con versiones anteriores de la aplicación.                                                                                                                                                                       |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Creemos que:** Al proporcionar opciones de personalización y ajustes automáticos basados en inteligencia artificial, los usuarios podrán crear fotografías de alta calidad que se adapten a sus necesidades específicas. **Sabremos que:** Cuando realicemos encuestas de satisfacción con usuarios que hayan utilizado nuestra aplicación y la mayoría reporte una mejora significativa en la calidad de sus fotos en comparación con métodos tradicionales de edición. **Cuando veamos:** Un aumento en el número de usuarios que comparten sus fotos editadas en redes sociales y reciben comentarios positivos sobre la calidad de las imágenes.                                                                                                 |
| **Creemos que:** Al integrar algoritmos de inteligencia artificial para el reconocimiento facial y la mejora automática de imágenes, podemos reducir significativamente el tiempo necesario para editar fotos, aumentando así la eficiencia de nuestros usuarios. **Sabremos que:** Cuando realicemos pruebas de rendimiento comparando el tiempo promedio necesario para editar una foto con y sin la ayuda de nuestra inteligencia artificial, y observamos una reducción del tiempo de edición en al menos un 50%. **Cuando veamos:** Un aumento en la frecuencia de uso de la aplicación por parte de los usuarios que necesitan editar fotos regularmente para diferentes propósitos, como perfiles de redes sociales o documentos profesionales. |

4.  ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692267/klstzwcisbd0zqxzy4kz.jpg)**Lean UX Canvas**

## Segmento Objetivo

### Segmento Objetivo 1: El Usuario Entusiasta

Este segmento está compuesto por individuos apasionados por la fotografía y la edición de imágenes, pero que no necesariamente tienen formación profesional en el área. Son personas creativas que disfrutan experimentando con diferentes estilos, efectos y técnicas de edición para crear imágenes únicas y originales. Para ellos, la fotografía es un hobby o una forma de expresión artística que les permite explorar su creatividad y capturar momentos especiales de manera única y personalizada. A menudo buscan herramientas intuitivas y divertidas que les permitan llevar sus habilidades de edición al siguiente nivel y compartir sus creaciones con amigos y seguidores en redes sociales. Son usuarios que valoran la creatividad, la originalidad y la posibilidad de crear imágenes visualmente impactantes y memorables.

### Segmento Objetivo 2: El Usuario Profesional

Este segmento incluye a profesionales de la fotografía, diseñadores gráficos, artistas visuales y otros expertos en medios visuales que utilizan la fotografía como parte de su trabajo o negocio. Para ellos, la calidad y la precisión son aspectos fundamentales en el proceso de edición de imágenes, ya que sus creaciones suelen tener un propósito específico y están destinadas a un público profesional o comercial. Buscan herramientas de edición de fotos que les permitan trabajar de manera eficiente y producir resultados de alta calidad que cumplan con los estándares profesionales. Además, pueden necesitar funciones especializadas y avanzadas, así como soporte para formatos de archivo profesionales, para satisfacer las demandas de sus proyectos y clientes. Son usuarios que valoran la precisión, la eficiencia y la capacidad de obtener resultados profesionales en sus proyectos de fotografía y diseño.

# Capítulo II: Requirements Elicitation & Analysis

## Competidores

### Análisis competitivo

¿Cómo podemos ofrecer un mejor servicio en nuestro producto frente a nuestros competidores? ¿Qué debemos mejorar?

El objetivo de llevar a cabo este análisis competitivo es conocer mejor a nuestros competidores, en qué aspectos son mejores que nosotros, qué funcionalidades o mejoras han implementado o implementan que nosotros no y saber en qué podemos mejorar.

| Startup                                               | PictoAI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Midjourney                                                                                                                                                                                                                                                                                                                                                                                                              | Shutterstock                                                                                                                                                                                                                                                                                                                                                                                                                             | Fotor                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Origen                                                | Lima, Peru                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Colorado, EEUU                                                                                                                                                                                                                                                                                                                                                                                                          | Nueva York, Estados Unidos                                                                                                                                                                                                                                                                                                                                                                                                               | Chengdu, China.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Descripcion General                                   | La idea de PictoAI nació de la creciente necesidad de democratizar la edición de fotografía de alta calidad. En un mundo donde las imágenes se han convertido en el principal medio de comunicación y expresión personal en redes sociales, blogs y marketing digital, el fundador de PictoAI, un apasionado fotógrafo y desarrollador de software, observó que muchas personas luchaban por mejorar sus fotos debido a la falta de herramientas accesibles y fáciles de usar que ofrecieran resultados profesionales. | Es una herramienta de inteligencia artificial que se utiliza para generar imágenes a partir de descripciones textuales. Funciona a través de un modelo de red neuronal avanzado que interpreta las palabras y frases para crear visualizaciones únicas y creativas. Es especialmente popular en el ámbito del diseño y la creatividad artística, permitiendo a los usuarios explorar nuevas formas de expresión visual. | Más que una herramienta de IA generativa de imágenes, Shutterstock es conocido como un banco de imágenes, vídeos y música. Sin embargo, Shutterstock ha integrado herramientas de IA para ayudar en la búsqueda y edición de imágenes. Por ejemplo, ofrece funciones que utilizan la IA para mejorar las imágenes, realizar búsquedas más inteligentes y personalizadas, y crear diseños automáticamente a partir de ciertos parámetros. | Es una plataforma en línea de edición de fotos y diseño gráfico que utiliza algunas capacidades de inteligencia artificial para mejorar las imágenes automáticamente. Fotor proporciona herramientas para ajustar la exposición, el color, y aplicar varios efectos de forma inteligente. También ofrece funciones de diseño gráfico y creación de collages, lo que la hace útil tanto para profesionales como para aficionados. |
| Ventaja competitiva ¿Qué valor ofrece a los clientes? | Una ventaja competitiva clave de PictoAI es su enfoque en democratizar la edición de fotografía de alta calidad, lo que significa que está dirigido a un mercado amplio y diverso de usuarios que desean mejorar sus fotos de manera profesional pero que carecen de conocimientos especializados en edición de imágenes. Al ofrecer herramientas accesibles y fáciles de usar que brindan resultados profesionales                                                                                                    | La ventaja competitiva de Midjourney radica en el valor que ofrece a sus clientes a través de sus servicios y productos innovadores, de alta calidad y personalizados                                                                                                                                                                                                                                                   | La ventaja competitiva de Shutterstock radica en el valor que ofrece a sus clientes a través de su amplia variedad de imágenes de alta calidad, videos y música de stock. Esto permite a los clientes acceder a contenido visual de manera rápida y sencilla para sus proyectos creativos, lo que les ayuda a ahorrar tiempo y recursos. .                                                                                               | La ventaja competitiva de Fotor radica en el valor que ofrece a sus clientes a través de su plataforma de edición de fotos en línea fácil de usar y repleta de funciones avanzadas. Fotor permite a los usuarios editar, retocar y crear imágenes de manera profesional sin la necesidad de tener conocimientos especializados en diseño gráfico                                                                                 |
| Mercado Objetivo                                      | Se dirige a una amplia audiencia de personas que desean mejorar la calidad de sus fotos de manera profesional, pero que carecen de conocimientos especializados en edición de imágenes. Su mercado objetivo incluye desde entusiastas de la fotografía hasta usuarios casuales de redes sociales, blogs y marketing digital.                                                                                                                                                                                           | Está orientado a empresas y profesionales que buscan servicios y productos innovadores en el campo del diseño y la creatividad. Su mercado objetivo abarca desde agencias de publicidad y marketing hasta empresas de medios y entretenimiento que buscan soluciones creativas y personalizadas                                                                                                                         | Se enfoca en creadores de contenido, diseñadores gráficos, editores de video, agencias de publicidad y marketing, y empresas que necesitan acceso a una amplia variedad de imágenes de stock, videos y música de alta calidad para sus proyectos creativos. Su mercado objetivo incluye a profesionales creativos de diversos sectores.                                                                                                  | Está dirigido a usuarios individuales y empresas que buscan una plataforma de edición de fotos en línea fácil de usar y repleta de funciones avanzadas. Su mercado objetivo abarca desde entusiastas de la fotografía hasta emprendedores y profesionales que necesitan crear contenido visual atractivo para sus proyectos en redes sociales, blogs y marketing digital                                                         |
| Estrategias de Marketing                              | - Estrategia de marketing de contenidos: Publicación de blogs, tutoriales y guías sobre edición de fotografía de alta calidad para atraer a usuarios interesados en mejorar sus habilidades.  - Publicidad en redes sociales: Anuncios pagados en plataformas como Instagram y Facebook para llegar a usuarios interesados en la edición de fotos.                                                                                                                                                                     | - Estrategia de marketing B2B: Enfoque en la generación de leads y relaciones comerciales con agencias de publicidad, empresas de medios y entretenimiento a través de campañas de email marketing y eventos sectoriales. - Marketing de contenidos especializado: Creación de contenido relevante y especializado sobre diseño y creatividad para posicionar a la empresa como líder en el sector.                     | - SEO y marketing de contenidos: Optimización de motores de búsqueda y creación de contenido relevante sobre tendencias visuales, fotografía y diseño para atraer tráfico orgánico a la plataforma. - Programa de afiliados: Colaboración con sitios web y blogs de fotografía y diseño para promocionar Shutterstock a través de enlaces de afiliados.                                                                                  | - Freemium y marketing de producto: Ofrecimiento de una versión gratuita con funciones básicas y una versión premium con características avanzadas para atraer a usuarios y convertirlos en clientes de pago. -Programas de referidos: Incentivos para usuarios existentes que recomienden Fotor a amigos y familiares, fomentando el crecimiento orgánico de la base de usuarios.                                               |
| Características y servicios                           | - Plataforma de edición de fotos basada en inteligencia artificial. - Herramientas avanzadas de edición como corrección de color, mejora de imagen y eliminación de imperfecciones. - Funciones de retoque facial y filtros personalizables.                                                                                                                                                                                                                                                                           | - Servicios de diseño gráfico y creatividad para empresas y profesionales. -Soluciones personalizadas de branding, diseño web y marketing visual. - Consultoría en estrategias de comunicación visual y storytelling. - Desarrollo de campañas publicitarias y contenido multimedia.                                                                                                                                    | - Banco de imágenes de stock, videos y música de alta calidad. - Amplia variedad de contenido visual para proyectos creativos. - Licencias flexibles para uso comercial y editorial.                                                                                                                                                                                                                                                     | Plataforma de edición de fotos en línea con versión gratuita y premium. - Herramientas de edición básicas y avanzadas para mejorar fotos. - Plantillas y efectos prediseñados para crear diseños visuales atractivos.                                                                                                                                                                                                            |
| Precios y costos                                      | Precio personalizado para cada plan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Precio personalizado para cada plan                                                                                                                                                                                                                                                                                                                                                                                     | Precio personalizado para cada plan                                                                                                                                                                                                                                                                                                                                                                                                      | Precio personalizado para cada plan                                                                                                                                                                                                                                                                                                                                                                                              |
| Canales de distribución (web o móvil)                 | Web                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Web                                                                                                                                                                                                                                                                                                                                                                                                                     | Web                                                                                                                                                                                                                                                                                                                                                                                                                                      | Web                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Fortalezas                                            | - Tecnología avanzada de inteligencia artificial aplicada a la edición de fotos. - Herramientas de edición potentes y precisas que permiten mejorar la calidad de las imágenes. - Integración con redes sociales y almacenamiento en la nube para facilitar el flujo de trabajo.                                                                                                                                                                                                                                       | - Experiencia y expertos en diseño gráfico, branding y marketing visual. - Capacidad para ofrecer soluciones creativas y personalizadas a empresas de diversos sectores. - Colaboración con agencias de publicidad y medios para proyectos de gran envergadura.                                                                                                                                                         | - Amplia y diversa biblioteca de imágenes de stock, videos y música de alta calidad. - Licencias flexibles que se adaptan a las necesidades de diferentes tipos de clientes. - Herramientas de búsqueda avanzada y recomendaciones personalizadas para facilitar la selección de contenido.                                                                                                                                              | - Plataforma de edición de fotos versátil y fácil de usar, con opciones gratuitas y premium. - Amplia gama de herramientas de edición y efectos para mejorar fotos y crear diseños atractivos. - Integración con redes sociales y almacenamiento en la nube para compartir y guardar proyectos.                                                                                                                                  |
| Debilidades                                           | - Dependencia de la tecnología de inteligencia artificial, lo que puede limitar la creatividad humana en algunos casos. - Posible resistencia de algunos usuarios a confiar en la edición automática de fotos. - Necesidad de una conexión a Internet estable para aprovechar plenamente todas las funciones.                                                                                                                                                                                                          | - Costos potencialmente elevados para servicios de diseño personalizado, lo que puede limitar su accesibilidad a pequeñas empresas o emprendedores. - Competencia intensa en el mercado de diseño gráfico y branding, lo que puede dificultar destacar entre otros proveedores. - Necesidad de mantenerse actualizado constantemente con las tendencias y tecnologías en diseño y marketing visual.                     | - Posible percepción de algunas imágenes de stock como genéricas o poco auténticas. - Dependencia de la disponibilidad y calidad del contenido proporcionado por colaboradores externos. - Competencia de otras plataformas de imágenes de stock y bancos de recursos visuales.                                                                                                                                                          | - Limitaciones en comparación con software de edición de fotos más avanzado y profesional. - Posible falta de funciones especializadas para usuarios con necesidades específicas en diseño gráfico. - Necesidad de una conexión a Internet para acceder a la plataforma en línea.                                                                                                                                                |
| Oportunidades                                         | - Expansión de su tecnología de inteligencia artificial a otros sectores, como la seguridad, la medicina o la industria. - Colaboración con empresas de impresión, publicidad o medios para ofrecer soluciones personalizadas de edición de fotos. - Desarrollo de nuevas funciones y herramientas basadas en IA para mejorar la experiencia del usuario y la calidad de los resultados.                                                                                                                               | - Ampliación de su cartera de servicios para incluir diseño web, desarrollo de aplicaciones móviles o marketing digital. - Colaboración con empresas emergentes o startups para ofrecer servicios de diseño y branding desde etapas tempranas. - Expansión a mercados internacionales para llegar a una audiencia más amplia y diversa.                                                                                 | - Diversificación de su contenido para incluir más formatos como realidad aumentada, realidad virtual o contenido 3D. - Colaboración con agencias de viajes, turismo o medios para ofrecer contenido visual exclusivo y atractivo. - Expansión a mercados emergentes y regiones con alto potencial de crecimiento en el uso de imágenes de stock.                                                                                        | - Desarrollo de una versión móvil de la plataforma para llegar a más usuarios y facilitar la edición de fotos sobre la marcha. - Colaboración con influencias, bloggers o creadores de contenido para promocionar la plataforma y llegar a nuevas audiencias. - Integración de nuevas funciones de edición y efectos visuales para mantenerse al día con las tendencias y preferencias de los usuarios.                          |

### Estrategias y tácticas frente a competidores

A continuación, te presento algunas estrategias y prácticas que los competidores podrían implementar para mantenerse competitivos en el mercado de la edición de fotos y contenido visual:

**Innovación constante:**

-   Estrategia: Mantenerse a la vanguardia de la innovación tecnológica en la edición de fotos, como la integración de nuevas herramientas de inteligencia artificial o la mejora de algoritmos de reconocimiento de imágenes.
-   Práctica: Realizar investigaciones continuas sobre las últimas tendencias en edición de fotos y desarrollar nuevas funciones y características que satisfagan las necesidades cambiantes de los usuarios.

**Diversificación de servicios:**

-   Estrategia: Ampliar la gama de servicios ofrecidos más allá de la edición de fotos, como la creación de contenido visual para redes sociales, diseño gráfico personalizado o servicios de branding.
-   Práctica: Identificar oportunidades para expandir la cartera de servicios y adaptarse a las demandas del mercado diversificando las ofertas de la empresa.

**Enfoque en la experiencia del usuario:**

-   Estrategia: Priorizar la experiencia del usuario en la plataforma, asegurando una interfaz intuitiva, herramientas fáciles de usar y un excelente servicio al cliente.
-   Práctica: Recopilar retroalimentación de los usuarios de forma regular para identificar áreas de mejora, realizar pruebas de usabilidad y optimizar la experiencia del usuario en todos los puntos de contacto con la empresa.

**Colaboraciones estratégicas:**

-   Estrategia: Establecer alianzas con otras empresas o profesionales del sector creativo para ampliar la red de clientes y ofrecer servicios complementarios.
-   Práctica: Buscar oportunidades de colaboración con fotógrafos, diseñadores gráficos, agencias de publicidad u otras empresas afines para crear sinergias y llegar a nuevos segmentos de mercado.

## Entrevistas

### Diseño de entrevistas.

**Segmento objetivo 1: El Usuario Entusiasta**

**Preguntas Generales**

-   ¿Cuál es su nombre, edad, ocupación y estado civil?
-   ¿En qué distrito reside actualmente?
-   ¿Qué tecnología suele usar en su día a día?
-   ¿Para usted aprender a utilizar aplicaciones nuevas es sencillo o tiene alguna dificultad?
-   ¿Cuáles son sus aplicaciones, páginas web y marcas favoritas? ¿Por qué?
-   ¿Se considera introvertido o extrovertido.?
-   ¿Cuáles son sus dispositivos preferidos.?

**Preguntas Específicas**

-   ¿Qué le atrae de la idea de poder generar fotografías creativas y divertidas de sí mismo sin necesidad de un fotógrafo o estudio profesional?
-   ¿Con qué frecuencia le gustaría generar este tipo de imágenes únicas? ¿Para qué propósitos principalmente las utilizaría (redes sociales, proyectos personales, etc.)?
-   ¿Ha utilizado anteriormente alguna aplicación o servicio para generar fotografías con IA? Si es así, ¿qué le gustó y qué aspectos mejoraría de esa experiencia?
-   ¿Qué tipo de opciones de personalización le gustaría tener al generar sus fotografías (por ejemplo, fondos, vestuario, estilos, etc.)?
-   Si existiera una aplicación que le permitiera generar fotografías súper realistas de usted mismo sin límites a su creatividad, ¿qué lo motivaría a probarla y utilizarla regularmente?
-   Pensando en compartir sus fotografías generadas, ¿qué opciones de compartir en redes sociales o formatos de exportación serían más convenientes para usted?
-   Basándose en su experiencia y deseos, ¿qué otros usos o aplicaciones creativas le gustaría poder darle a esta herramienta generativa de fotografías?

**Segmento objetivo 2: El Usuario Profesional**

**Preguntas Generales**

-   ¿Cuál es su nombre, edad, ocupación y estado civil?
-   ¿En qué distrito reside actualmente?
-   ¿Qué tecnología suele usar en su día a día?
-   ¿Para usted aprender a utilizar aplicaciones nuevas es sencillo o tiene alguna dificultad?
-   ¿Cuáles son sus aplicaciones, páginas web y marcas favoritas? ¿Por qué?
-   ¿Se considera introvertido o extrovertido?
-   ¿Cuáles son sus dispositivos preferidos?

**Preguntas Específicas**

-   En su campo profesional ¿para qué propósitos o situaciones necesita disponer de fotografías de calidad de sí mismo con mayor frecuencia?
-   ¿Alguna vez ha ido a un estudio fotográfico?
-   Desde su perspectiva, ¿cuáles son los factores más importantes a la hora de generar una fotografía profesional de uno mismo (calidad, rapidez, costo, personalización, etc.)?
-   Al necesitar una fotografía profesional, ¿cuáles son los mayores desafíos o dificultades que enfrenta actualmente que le gustaría poder solucionar?
-   ¿Ha considerado utilizar aplicaciones con inteligencia artificial para generar fotografías profesionales de sí mismo? ¿Qué potenciales ventajas o desventajas ve en esta opción?
-   Si se lanzará una aplicación que le permitiera generar fotografías profesionales de alta calidad de forma rápida y económica, ¿qué factores evaluaría para decidir adoptarla en su flujo de trabajo? (costo, número de imágenes)
-   Pensando en la eficiencia y practicidad, ¿qué integraciones con otras herramientas profesionales o formatos de exportación serían más útiles para usted?
-   Si esta aplicación ofreciera funciones Premium diseñadas para profesionales, ¿Qué característica consideraría que valdrían la pena en una suscripción de paga?

### Registro de entrevistas

**Registro: El Usuario Entusiasta**

| **Nombre:** Jhosaim Pocohuanca                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Enlace**: <https://drive.google.com/file/d/1v_CU3N_JF18di4BTKxF_6VdHV7ZePOpa/view?usp=sharing>  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Se realizó la entrevista a Ricardo Pocón Capineda, estudiante de 21 años de ingeniería de software en la UPC y soltero. Es del distrito de San Sebastián, Cusco. En su día a día utiliza una computadora con Windows, una laptop con Linux y un iPhone con iOS. Encuentra que aprender nuevas aplicaciones depende de qué tan intuitivas sean. Sus aplicaciones, páginas web y marcas favoritas son Amazon, Spotify, Apple e Intel. Se considera una persona ni introvertida ni extrovertida. Su dispositivo preferido es la laptop por su portabilidad. Le atrae la idea de poder generar fotos creativas y divertidas de sí mismo sin un fotógrafo profesional, especialmente para probar nuevos looks como cortes de pelo o cambios de apariencia. Piensa utilizarlas unas 5 veces por semana, principalmente para probar nuevos estilos y para su perfil de LinkedIn. No ha utilizado antes aplicaciones para generar fotos con IA. Le gustaría poder personalizar fondos, vestuario, peinados, accesorios, etc. Para que use regularmente una app así, debería ser muy intuitiva, de alta calidad y con un precio accesible. No compartiría mucho las fotos generadas, salvo tal vez en Instagram. También le interesa poder explorar fondos de otras épocas o lugares. |                                                                                                   |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692622/vh8v8kaddplcolosayze.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                                                                                   |
| **Nombre:** Jhan Antonio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | **Enlace**:  ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692644/vfhebgxou8jyzrxj5cui.jpg)   |
| Jhan nos habla que él es una persona que le encanta tomar fotografías. Le parece novedosa la idea de poder reunir muchas fotos y poder usar la inteligencia artificial para mejorar sus fotografías le es muy atractivo. Además en base a su experiencia nos comenta que le puede ayudar a hacer publicidad debido a que utilizamos inteligencia artificial.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                                                                                   |
| ![](media/5897411e55fba8033196b2856231162d.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                                                   |

**Registro: El Usuario Profesional**

| **Nombre:** Alvaro Cabrera                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | **Enlace**:  <https://drive.google.com/file/d/1Iz49R_kA-m7uzAQTfxXL8CX3TZOnqMd-/view?usp=sharing>  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Se realizó la entrevista a Alvaro Cabrera Campos, es un profesional de 23 años usuario de iPhone residente en Santa Anita. Está muy interesado en usar inteligencia artificial para generar fotos profesionales y retratos de estudio de sí mismo, principalmente para utilizar como imagen de perfil en LinkedIn y otras plataformas laborales. Valoraría una app que permita personalizar al máximo los retratos generados con fondos de oficina, vestuario formal, iluminación profesional, etc. y que logre un realismo inmejorable. Pagaría por una suscripción si la app es de alta calidad y le permite tener generaciones ilimitadas |                                                                                                    |
| **![](media/d4d596b897a331e81fe6ca5b72f96d03.jpeg)**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                    |

| **Nombre:** David Cordoba                                                                                                                                                                                  | **Enlace**:  <https://www.youtube.com/watch?v=Zm5ciTzJTxg>  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| El fotógrafo opina que el mayor desafio que enfrenta al tomar fotos es que a veces es necesario agregar o quitar cosas de ellas por lo cual el uso de inteligencia artificial le parece una opción viable. |                                                             |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692739/d3gmt9wjq8wyfk6yp3jc.jpg)                                                                                                                                                            |                                                             |

| **Nombre:** Danixa FLores                                                                                                                                                                         | **Enlace**:  <https://drive.google.com/file/d/1EN1ncBXH79UkLREH8i2PZgYxwNa3-Q1Q/view?usp=drive_link>  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Ella piensa que la aplicacion PictoAI es una herramienta muy util debido a que la mayoria de estudios fotograficos el precio es muy elevado, por ende seria una buena solucion para fotos rapidas |                                                                                                       |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692766/pvlbbty4a0oju3ffpetr.jpg)                                                                                                                                                   |                                                                                                       |

| **Nombre:** Gustavo                                                                                                                                                                                                                                                                   | **Enlace**: <https://drive.google.com/file/d/1rjtnvejk31DPXnCZELcnKRxDEF612F2R/view?usp=drive_link> |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| El comento que de manera profesional, la la aplicación con IA para mejorar las fotos le saldría muy ultil para usarlo de manera personal, ya que son funcionalidades que en otros sitios web loa encuentras de paga, aparte con fotos limitadas y pocos metodos de exportar la imagen |                                                                                                     |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692981/s3sr9jkypvlkljxeifmv.jpg)                                                                                                                                                                                                                                       |                                                                                                     |

| **Nombre**  Elias Torres Espinosa                                                                                                                                                                                                                                                                                                                                                                                                     | **Enlace**: <https://drive.google.com/drive/folders/1bUI90SjTQY4KaIax1zctGiQV4MSee1ka>  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| El piensa que es una herramienta muy fundamental porque facilita todo, ya que el es un joven que está trabajando y no cuenta con tiempo, por lo cual le pareció genial la aplicación web, porque así podría personalizar mejor su LinkedIn en vez de estar desplazándose a un centro de estudios fotográficos, siente que sería más fácil subir tus fotos a la aplicación y esta te devuelvas imágenes profesionales y personalizadas |                                                                                         |
| ![](https://res.cloudinary.com/daassyisd/image/upload/v1714692981/s3sr9jkypvlkljxeifmv.jpg)                                                                                                                                                                                                                                                                                                                                                                                       |                                                                                         |

## Needfinding

### User Personas

![Interfaz de usuario gráfica, Aplicación Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714701488/gz9yqdyurbq5dmgbt4r9.jpg)

![](https://res.cloudinary.com/daassyisd/image/upload/v1714701568/hq2mptlgrrvy4qetmhdf.jpg)

### User Task Matrix

| Tarea                                                                      | Usuario Entusiasta   | Usuario Profesional  |
|----------------------------------------------------------------------------|----------------------|----------------------|
|                                                                            | Frecuencia           | Frecuencia           |
| Generar imágenes para probar nuevo look (corte de pelo, color, accesorios) | 4-5 veces por semana | 1 vez cada 2 semanas |
| Crear fotos de perfil profesional para LinkedIn                            | Ocasionalmente       | Ocasionalmente       |
| Explorar cómo se vería en diferentes escenarios (lugares, épocas)          | Ocasionalmente       | Ocasionalmente       |

### Empathy Mapping

**Segmento objetivo 1:** El usuario profesional

![Diagrama, Escala de tiempo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714701625/nctaynkudlor7l1ytovv.jpg)

**Segmento Objetivo 2:** El usuario entusiasta

![Escala de tiempo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714701690/vmbwxgorwletmzmg9lew.jpg)

### As-is Scenario Mapping

**Segmento objetivo 1:** El usuario profesional

![Escala de tiempo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702035/ofr7opkbysatz9gvbrhu.jpg)

**Segmento Objetivo 2:** El usuario entusiasta

![Diagrama, Calendario Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702057/dpfacsyspbd6kpcxensi.jpg)

## Ubiquitous Language

El desarrollo del lenguaje ubicuo permitirá establecer una terminología común y precisa para comunicarse de manera efectiva con los diferentes stakeholders involucrados en este proyecto, como desarrolladores, diseñadores, expertos en negocios y usuarios finales.

**Entidades:**

-   **Usuario**: Persona que utiliza la plataforma para generar fotos de retratos.
-   **Retrato**: Imagen generada por la plataforma que representa a una persona.
-   **Configuración**: Conjunto de opciones y preferencias seleccionadas por el usuario para personalizar el retrato.
-   **Sesión**: Instancia de uso de la plataforma por parte de un usuario.
-   **Colección**: Conjunto de retratos generados por un usuario.

**Eventos**

-   **Inicio de Sesión**: Acción realizada por un usuario para acceder a la plataforma.
-   **Generación de Retrato**: Proceso de creación de una nueva imagen de retrato por parte de la plataforma.
-   **Personalización de Configuración**: Acción realizada por el usuario para ajustar las opciones y preferencias de generación del retrato.
-   **Guardado de Retrato**: Acción realizada por el usuario para almacenar un retrato generado en su colección.
-   **Cierre de Sesión**: Acción realizada por el usuario para finalizar su uso de la plataforma.

**Acciones**

-   **Iniciar Sesión**: Acción realizada por el usuario para comenzar una nueva sesión en la plataforma.
-   **Generar Retrato**: Acción realizada por el usuario para solicitar la generación de un nuevo retrato.
-   **Configurar Opciones**: Acción realizada por el usuario para ajustar las preferencias de generación del retrato.
-   **Guardar Retrato:** Acción realizada por el usuario para almacenar un retrato generado en su colección.
-   **Cerrar Sesión:** Acción realizada por el usuario para finalizar su uso de la plataforma.

**Objetos de Valor**

-   Créditos: Unidad de valor utilizada por el usuario para acceder a las funcionalidades de la plataforma.
-   Plan de Suscripción: Conjunto de opciones y beneficios ofrecidos al usuario a cambio de una tarifa periódica.

# Capítulo III: Requirements Specification

## To-Be Scenario Mapping

| **Steps**                                                     | **Doing**                                                                          | **Thinking**                                                           | **Feeling** |
|---------------------------------------------------------------|------------------------------------------------------------------------------------|------------------------------------------------------------------------|-------------|
| Busca información sobre fotografías con AI                    | Realiza una búsqueda de programas online sobre herramientas de edición fotográfica | Me alegra encontrar una plataforma de edición gratuita y fácil de usar | Alegre      |
| Necesita herramientas para editar fotografías fáciles de usar | Ingresa a nuestra aplicación                                                       | Un sitio muy intuitivo y eficiente                                     | Seguro      |
| Se registra en PictoAI                                        | Se registra en PictoAI para mejorar sus fotografías                                | ¿Valdrá la pena este servicio?                                         | Satisfecho  |
| Obtiene la información deseada                                | Mejorar mis fotografías                                                            | ¿Cómo puedo seguir usando esta aplicación?                             | Motivado    |

| **Steps**                                   | **Doing**                                                                        | **Thinking**                               | **Feeling**            |
|---------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------|------------------------|
| Descubrimiento e interés                    | El profesional se cuestiona si podría mejorar sus fotografías                    | ¿Cómo será capaz de apoyar mi trabajo?     | Curiosidad             |
| Necesita herramienta profesional de edición | El profesional ve que en PictoAI puede ofrecerse herramientas nunca antes vistas | ¿Será esta mi oportunidad?                 | Emoción y Anticipación |
| Adquiere la suscripción                     | Escoge templates premium gracias a su suscripción                                | Los resultados superaron mis expectativas  | Entusiasmo             |

## User Stories

| Epic ID | Titulo                                  | Descripcion                                                                                                                                           |
|---------|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP01    | Autenticación y Acceso a la Aplicación  | Como usuario, deseo poder registrarme y autenticarme en la aplicación, para acceder a las funcionalidades y servicios disponibles.                    |
| EP02    | Suscripción y Planes Premium            | Como usuario, deseo tener la opción de suscribirme a planes premium para acceder a funcionalidades avanzadas de la aplicación.                        |
| EP03    | Edición de Fotos con IA                 | Como usuario, deseo poder utilizar la inteligencia artificial de Stable Diffusion para editar y mejorar las fotos que subo a la aplicación.           |
| EP04    | Análisis y Seguimiento de Métricas      | Como usuario, deseo tener acceso a métricas y estadísticas sobre el uso de la aplicación y el rendimiento de la IA, para tomar decisiones informadas. |

| Story ID  | Título                                 | Descripción                                                                                                                          | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Relacionado con |
|-----------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|
| US001     | Registro de usuario                    | Como usuario deseo poder registrarme en la aplicación                                                                                | Escenario: Registro de cuenta exitoso. Dado que un usuario tiene una cuenta de correo electrónico. Cuando el usuario completa el proceso de registro. Entonces, la aplicación confirma el registro exitoso. Escenario: Registro erróneo de cuenta. Dado que un usuario tiene una cuenta de correo electrónico. Cuando el usuario completa el proceso de registro con información incorrecta o faltante. Entonces, la aplicación muestra un mensaje de error relacionado con la información ingresada.                                                                                                                 | EP01            |
| US002     | Cerrar sesión de usuario               | Como usuario deseo poder cerrar sesión en el dispositivo para proteger mi cuenta                                                     | Escenario: Cierre de Sesión Exitoso. Dado que el usuario ha iniciado sesión en la aplicación. Cuando el usuario desee cerrar su sesión y selecciona la opción correspondiente para cerrar sesión. Entonces la aplicación cierra la sesión del usuario y lo redirige a la pantalla de inicio de sesión. Escenario: Cierre de Sesión Fallido. Dado que el usuario ha iniciado sesión en la aplicación. Cuando el usuario desee cerrar su sesión y selecciona la opción correspondiente para cerrar sesión. Entonces la aplicación muestra un mensaje de error.                                                          | EP01            |
| US003     | Actualización de información de perfil | Como usuario, deseo poder actualizar mi información de perfil en la aplicación para mantenerla precisa y actualizada.                | Escenario: Acceso a la configuración de perfil. Dado que un usuario desea actualizar su información de perfil. Cuando el usuario accede a la configuración de la cuenta. Entonces la aplicación muestra una serie de opciones, incluida la opción "Perfil". Escenario: Actualización de datos de perfil. Dado que el usuario está en la sección de configuración de perfil. Cuando el usuario edita y actualiza la información de su perfil. Entonces la aplicación guarda los cambios realizados.                                                                                                                    | EP01            |
| US004     | Seleccionar un plan                    | Como usuario de la aplicación de fotografías, deseo poder actualizar mi plan de suscripción para acceder a funcionalidades premium.  | Escenario: Selección de nuevo plan de suscripción. Dado que el usuario está en la sección de configuración de suscripción. Cuando el usuario selecciona la opción para actualizar su plan de suscripción. Entonces la aplicación muestra una lista de los diferentes planes disponibles, cada uno con sus respectivas funcionalidades y precios. Escenario: Confirmación de la actualización de suscripción. Dado que el usuario ha seleccionado un nuevo plan de suscripción. Cuando el usuario confirma la actualización seleccionando el nuevo plan. Entonces la aplicación procede con la actualización del plan. | EP01            |
| US005     | Gestión de suscripción                 | Como usuario suscrito, deseo poder administrar mi suscripción a la aplicación, incluyendo la posibilidad de cancelarla o renovarla.  | Escenario: Renovación de suscripción exitosa. Dado que un usuario tiene una suscripción activa. Cuando el usuario selecciona la opción de renovar su suscripción. Entonces, la aplicación confirma la renovación y mantiene las funcionalidades premium habilitadas. Escenario: Cancelación de suscripción exitosa. Dado que un usuario tiene una suscripción activa. Cuando el usuario selecciona la opción de cancelar su suscripción. Entonces, la aplicación confirma la cancelación y desactiva las funcionalidades premium.                                                                                     | EP02            |

## Impact Mapping

![Diagrama Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702118/rzwo4pxw5lubi0ndtpv0.jpg)

## Product Backlog

| ID - HU | TÍTULO                                            | (Importancia, precedencia) | TIPO | ESTIMACIÓN | (Story points) | SPRINT |
|---------|---------------------------------------------------|----------------------------|------|------------|----------------|--------|
| US001   | Registro de usuario                               | (Alta, Baja)               | RF   | 3          | 2              | 1      |
| US002   | Cerrar sesión de usuario                          | (Media, Baja)              | RF   | 2          | 2              | 1      |
| US003   | Actualización de información de perfil de usuario | (Alta, Media)              | RF   | 5          | 3              | 2      |
| US005   | Usuario selecciona un plan                        | (Alta, Alta)               | RF   | 8          | 5              | 3      |
| US006   | Subir fotografías por unidad y por lotes          | (Alta, Media)              | RF   | 8          | 5              | 4      |
| US007   | Realizar ediciones rápidas a las fotografías      | (Media, Alta)              | RF   | 5          | 4              | 4      |
| US008   | Explorar galería de fotografías                   | (Alta, Baja)               | RF   | 5          | 4              | 4      |
| US009   | Descargar fotografías                             | (Media, Baja)              | RF   | 3          | 3              | 5      |
| US010   | Compartir fotografías                             | (Alta, Media)              | RF   | 5          | 4              | 5      |

# Capítulo IV: Strategic-Level Software Design

## Strategic-Level Attribute-Driven Design

### Design Purpose

El propósito del diseño de la solución de generación de fotos de personas mediante inteligencia artificial es brindar una alternativa innovadora y accesible para satisfacer la necesidad de contar con fotografías profesionales de calidad, especialmente en el ámbito laboral y profesional.

El diseño de la solución se enfoca en ofrecer una experiencia de usuario intuitiva y satisfactoria, permitiendo a los usuarios personalizar y generar retratos según sus preferencias y necesidades específicas. Además, se contempla la implementación de funcionalidades adicionales, como la posibilidad de guardar y gestionar colecciones de retratos generados. En resumen, nuestra solución se enfoca en brindar una alternativa innovadora, accesible y satisfactoria para la generación de fotos de personas mediante inteligencia artificial, abordando las necesidades de diversos segmentos objetivo y alineándose con los objetivos de negocio del startup.

### Attribute-Driven Design Inputs

**Primary Functionality (Primary User Stories)**

Se seleccionó los user stories con mayor relevancia para llevar a cabo esta solución.

| Epic / User Story ID | Tiutulo                                      | Criterios de Aceptacion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | relacionado con (Epic ID) |
|----------------------|----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US006                | Subir fotografías por unidad y por lotes     | **Escenario**: Subir fotos **Dado** que el profesional se encuentra en la pantalla de inicio **Cuando** le de clic o toque el ítem “subir por lotes”. **Entonces** podrá ver las fotografías que tenga en su galería  **Escenario**: Editar fotografías. **Dado** que el usuario entusiasta se encuentra en la pantalla de edición **Cuando** selecciona una fotografía para editar **Entonces** podrá acceder a herramientas básicas de edición, como las herramientas                                                                                                                                      | EP02                      |
| US007                | Realizar ediciones rápidas a las fotografías | **Escenario**: Realizar ediciones rápidas **Dado** que el usuario básico se encuentra en la pantalla de inicio **Cuando** selecciona la opción de edición rápida. **Escenario**: Aplicar ajustes **Dado** que el usuario básico está visualizando una fotografía en la pantalla de edición rápida **Cuando** ajusta los niveles de la imagen **Entonces** puede ver en tiempo real cómo estos cambios afectan la apariencia                                                                                                                                                                                  | EP03                      |
| US008                | Explorar galería de fotografías              | **Escenario**: Explorar galería **Dado** que el usuario se encuentra en la pantalla principal de la aplicación **Cuando** selecciona la opción de "Explorar galería" **Entonces** la aplicación muestra una lista de imágenes disponibles para visualización. **Escenario**: Visualizar detalles de la fotografía **Dado** que el usuario está navegando por la galería de fotografías. **Cuando** selecciona una imagen específica **Entonces** la aplicación muestra los detalles de la imagen, como su tamaño, fecha de carga **y** opciones para descargar o compartir                                   | EP03                      |
| US009                | Galería de fotos editadas                    | **Escenario**: Acceso a la galería de fotos. **Dado** que un usuario tiene una cuenta en la aplicación y ha editado fotos. **Cuando** el usuario accede a la sección de galería. **Entonces**, la aplicación muestra todas las fotos editadas por el usuario                                                                                                                                                                                                                                                                                                                                                 | EP01                      |
| US010                | Descargar fotografías                        | **Escenario**: Descargar fotografía individual **Dado** que el usuario ha seleccionado una imagen específica en la galería. **Cuando** selecciona la opción de descarga. **Entonces** la aplicación descarga la imagen **y** la guarda en el dispositivo del usuario.   **Escenario**: Descargar lote de fotografías **Dado** que el usuario desea descargar varias imágenes a la vez. **Cuando** selecciona la opción para descargar un lote de fotografías. **Entonces** la aplicación descarga todas las imágenes seleccionadas **y** las guarda en una carpeta específica en el dispositivo del usuario. | EP03                      |
| US011                | Compartir fotografías                        | **Escenario**: Compartir en redes sociales **Dado** que el usuario ha seleccionado una imagen para compartir **Cuando** selecciona la opción de compartir en redes sociales **Entonces** la aplicación muestra una lista de redes sociales disponibles para compartir la imagen                                                                                                                                                                                                                                                                                                                              | EP04                      |
| US012                | Guardar fotografías favoritas                | **Escenario**: Marcar fotografía como favorita **Dado** que el usuario está viendo una fotografía en la galería. **Cuando** el usuario selecciona la opción de "Agregar a Favoritos". **Entonces** la aplicación guarda la fotografía en la sección de Favoritos.   **Escenario**: Ver fotografías favoritas **Dado** que el usuario ha marcado varias fotografías como favoritas. **Cuando** el usuario accede a la sección de Favoritos. **Entonces** la aplicación muestra una lista de todas las fotografías que el usuario ha marcado como favoritas.                                                   | EP02                      |
| US014                | Exportación de fotografías                   | **Escenario**: Exportar fotografías **Dado** que el usuario desea exportar sus fotografías. **Cuando** el usuario selecciona la opción de "Exportar", **entonces** la aplicación permite al usuario seleccionar las fotografías a exportar y elegir el formato y destino.                                                                                                                                                                                                                                                                                                                                    | EP03                      |

### Architectural Drivers Backlog

| **Driver ID** | **Título de Driver**                 | **Descripción**                                                                                                                                                                         | **Importancia para Stakeholders (High, Medium, Slow)** | **Impacto en Architecture Technical Complexity** **(High, Medium, Slow)** |
|---------------|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|---------------------------------------------------------------------------|
| D1            | Autenticación y Acceso Seguro        | El sistema debe proporcionar mecanismos de autenticación y autorización seguros para proteger el acceso a la aplicación y a las funcionalidades premium.                                | Alta                                                   | Alta                                                                      |
| D2            | Escalabilidad y Rendimiento          | El sistema debe ser capaz de manejar un gran volumen de usuarios y operaciones de procesamiento de imágenes de manera eficiente, garantizando un rendimiento óptimo.                    | Alta                                                   | Alta                                                                      |
| D3            | Integración con Stable Diffusion     | El sistema debe integrarse de manera efectiva con la herramienta Stable Diffusion para la generación y edición de imágenes utilizando inteligencia artificial.                          | Alta                                                   | Media                                                                     |
| D4            | Gestión de Suscripciones             | El sistema debe permitir a los usuarios suscribirse a planes premium, actualizar o cancelar sus suscripciones de manera sencilla y segura.                                              | Alta                                                   | Media                                                                     |
| DR5           | Experiencia de Usuario Intuitiva     | El sistema debe ofrecer una interfaz de usuario intuitiva y fácil de usar, que facilite la interacción con las funcionalidades de procesamiento de imágenes y gestión de suscripciones. | Media                                                  | Media                                                                     |
| D6            | Almacenamiento y Gestión de Imágenes | El sistema debe contar con un sistema de almacenamiento y gestión de imágenes eficiente, que permita el acceso, la descarga y la compartición de imágenes de manera rápida y segura.    | Media                                                  | Media                                                                     |

### Architectural Design Decisions

| **Driver ID** | **Título de Driver**                       | **Factory Method**                                                                                  | **Decorator**                                                            | **Singleton**                                                                                                               |                                                                                           |                                                                                                                                    |                                                                                                      |
|---------------|--------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
|               |                                            | **Pro**                                                                                             | **Con**                                                                  | **Pro**                                                                                                                     | **Con**                                                                                   | **Pro**                                                                                                                            | **Con**                                                                                              |
| D1            | Autenticación y Acceso Seguro              | Permite crear objetos de autenticación y autorización de manera flexible y extensible               | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de seguridad y autorización a objetos existentes de manera modular.                  | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de autenticación y autorización, facilitando su gestión y control.              | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |
| D2            | Integración con Stable Diffusion           | Permite crear objetos de integración con Stable Diffusion de manera flexible y extensible.          | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de integración con Stable Diffusion a objetos existentes de manera modular.          | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de integración con Stable Diffusion, facilitando su gestión y control.          | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |
| D3            | Gestión de Suscripciones y Planes Premium  | Permite crear objetos de gestión de suscripciones y planes premium de manera flexible y extensible. | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de gestión de suscripciones y planes premium a objetos existentes de manera modular. | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de gestión de suscripciones y planes premium, facilitando su gestión y control. | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |
| D4            | Procesamiento y Escalabilidad de Imágenes  | Permite crear objetos de procesamiento y escalabilidad de imágenes de manera flexible y extensible. | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de procesamiento y escalabilidad de imágenes a objetos existentes de manera modular. | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de procesamiento y escalabilidad de imágenes, facilitando su gestión y control. | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |
| DR5           | Experiencia de Usuario Intuitiva           | Permite crear objetos de interfaz de usuario de manera flexible y extensible.                       | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de interfaz de usuario a objetos existentes de manera modular.                       | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de interfaz de usuario, facilitando su gestión y control.                       | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |
| D6            | Almacenamiento y Gestión de Imágenes       | Permite crear objetos de almacenamiento y gestión de imágenes de manera flexible y extensible.      | Puede agregar complejidad innecesaria si no se implementa correctamente. | Facilita la adición de funcionalidades de almacenamiento y gestión de imágenes a objetos existentes de manera modular.      | Puede conducir a un diseño más complejo y difícil de mantener si se abusa de este patrón. | Garantiza que solo exista una instancia del objeto de almacenamiento y gestión de imágenes, facilitando su gestión y control.      | Puede dificultar la implementación de pruebas unitarias y puede ser un anti-patrón en algunos casos. |

### Quality Attribute Scenario Refinements

| **Refinamiento de Escenarios de Atributos de Calidad**                                                                                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actividades**                                                                                                                                                                                                                                                                                     |
| -Clarificación de requisitos                                                                                                                                                                                                                                                                        |
| -Especificaciones detallada                                                                                                                                                                                                                                                                         |
| -Evaluación de impacto                                                                                                                                                                                                                                                                              |
| -Priorización                                                                                                                                                                                                                                                                                       |
| **Descripción**                                                                                                                                                                                                                                                                                     |
| Revisión de los escenarios para garantizar la precisión y claridad de los requisitos. Detalle de cada escenario, describiendo contexto, condiciones, acciones y resultados. Finalmente análisis del impacto en el diseño de arquitectura de software y priorización según importancia y criticidad. |
| **Objetivo**                                                                                                                                                                                                                                                                                        |
| Asegurar que los escenarios de atributos de calidad estén claramente definidos, sean específicos y medibles, y aborden todas las dimensiones de los atributos de calidad.                                                                                                                           |
| **Resultado Esperado**                                                                                                                                                                                                                                                                              |
| Comprensión clara y detallada de los escenarios de atributos de calidad para guiar el diseño y desarollo del software, para complir las espectativas de calidad del usuario y negocio                                                                                                               |

## Strategic-Level Domain-Driven Design

### EventStorming

![Un letrero de color blanco Descripción generada automáticamente con confianza baja](media/990bd9e8e780204557672598e8b18237.png)

![Diagrama Descripción generada automáticamente](media/02b181e019fc68bbe5711dad61bf1069.png)

![Gráfico, Gráfico en cascada Descripción generada automáticamente](media/07e7381246e1f8b0bf883b30dff15495.png)

### Candidate Context Discovery

![Diagrama Descripción generada automáticamente](media/34d18d26f6395f048583b527dbb62402.png)

![Diagrama Descripción generada automáticamente](media/729150ae817f275d8a372e7f92387c8c.png)

![Diagrama Descripción generada automáticamente](media/4232e126edef61969a2d7482a5f8b3f2.png)

### Domain Message Flows Modeling

![Diagrama Descripción generada automáticamente](media/0b79704b46b4670fdfba8bb1ae4bcaf0.png)

![Texto Descripción generada automáticamente con confianza baja](media/f9a4c3d26ed5e4394fb1c47c22374d57.png)

### Context Mapping

**Bounded Context identificados:**

1.  Generación de Fotos por IA: Encargado de procesar las fotos de entrada proporcionadas por los usuarios y utilizar modelos de inteligencia artificial para generar nuevas imágenes según las especificaciones dadas.
2.  Gestión de Usuarios: Responsable de manejar el registro de usuarios, la autenticación, la gestión de perfiles y la configuración de preferencias de usuario.
3.  Almacenamiento de Fotos: Este "bounded context" se ocupará del almacenamiento y la gestión de las fotos de los usuarios.
4.  Interfaz de Usuario: Este contexto estaría enfocado en proporcionar una interfaz de usuario intuitiva y fácil de usar para que los usuarios ingresen fotos, especifiquen características y visualicen las fotos generadas.
5.  Acceso a Modelos de IA en Stable Diffusion: Encargado de la interacción con el API
6.  Gestión de Integración con Stable Diffusion: Responsable de la conexión y comunicación con el API

![Diagrama Descripción generada automáticamente](media/2a08ca316b97d925fa72f54357be263c.png)

**Relaciones:**

-   "Generación de Fotos por IA" se comunica con "Integración con Modelos de IA" para enviar fotos de entrada y recibir fotos generadas.
-   "Generación de Fotos por IA" y "Almacenamiento de Fotos" comparten información sobre las fotos generadas y almacenadas.
-   "Interfaz de Usuario" interactúa con "Almacenamiento de Fotos" para mostrar las fotos almacenadas y permitir a los usuarios cargar nuevas fotos.

## Software Architecture

### Software Architecture System Landscape Diagram

Este diagrama muestra una vista panorámica de todo el sistema, incluyendo sus componentes principales y cómo se interconectan. Es útil para comprender la estructura general del sistema y las relaciones entre sus partes

![Diagrama Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702510/yplhwpajesblsziyfyv9.jpg)

### Software Architecture Context Level Diagrams

Estos diagramas proporcionan una vista de alto nivel de las interacciones entre el sistema y sus entornos externos, como otros sistemas, usuarios.

![Diagrama Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702564/oqlfa0dvhts3kkmxblbp.jpg)

### Software Architecture Container Level Diagrams

Estos diagramas muestran la estructura interna del sistema, dividiéndolo en contenedores o módulos principales y describiendo las relaciones entre ellos. Ayudan a visualizar cómo se organiza el software en componentes lógicos y cómo se comunican entre sí.

![Diagrama Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714702583/wb5rrmd0tetonpqndeg3.jpg)

### Software Architecture Deployment Diagrams

Estos diagramas representan la configuración física del sistema, mostrando cómo se distribuyen los contenedores y sus instancias en diferentes nodos de hardware o entornos de ejecución.

![Interfaz de usuario gráfica Descripción generada automáticamente con confianza baja](https://res.cloudinary.com/daassyisd/image/upload/v1714702600/inibydsvy3jww8dhhwmp.jpg)
# Capítulo V: Tactical-Level Software ![Interfaz de usuario gráfica Descripción generada automáticamente con confianza baja](media/b083affb6155b5203b7a589180585271.png)Design.

## 5.1. Bounded Context: PhotoRepository

### 5.1.1. Domain Layer.

Esta capa representa el corazón del modelo de dominio de PictoAI, incluyendo las entidades, objetos de valor, y agregados. Estos son críticos para reflejar las reglas de negocio y el comportamiento de la aplicación.

![](media/c2c090354aef621d229c5e2e384fbdee.png)

### 5.1.2. Interface Layer.

En esta capa se manejan las interacciones externas con el sistema, gestiona la interacción entre el usuario y el sistema, facilitando las operaciones a través de interfaces gráficas o API.

*![](media/8a08a337cf8a51b26109dee5c99caeac.png)*

*![Diagrama Descripción generada automáticamente](media/bc8514cfbe85bdda664bd715a88e2c5a.png)*

### 5.1.3. Application Layer.

La Application Layer juega un papel crucial en la integración de la interfaz de usuario con las operaciones de dominio, asegurando que las acciones de los usuarios se traduzcan efectivamente en cambios significativos en el sistema.

*Command Handlers*

*Métodos:*

handle(EditPhotoCommand): Este método recibe un comando de edición de foto, que incluye especificaciones de qué ediciones aplicar y a qué foto donde se describe cómo desea que la imagen quede. El manejador valida el comando, asegura que la foto existe y aplica las ediciones necesarias llamando a métodos específicos en la capa de dominio.

*Event Handlers*

*Métodos:* handle(PhotoEditedEvent): Este método es llamado cuando un evento de edición de foto es emitido por la capa de dominio. Puede realizar varias acciones, dependiendo de las necesidades del negocio, como registrar la edición en un sistema de análisis, actualizar la interfaz del usuario para reflejar los cambios, o preparar la imagen para exportación.

![Diagrama Descripción generada automáticamente](media/15c509752c681f057dea3993fdea28bc.png)

### 5.1.4. Infrastructure Layer.

La Capa de Infraestructura de nuestro proyecto de generación de fotos con IA es la fundación tecnológica que soporta todas las operaciones de nuestra aplicación. En esta capa, las clases y componentes se encargan de la comunicación con servicios externos, tales como bases de datos para almacenar información persistente, sistemas de mensajería para la gestión de colas y procesamiento asincrónico, y servicios de correo electrónico para la interacción con los usuarios.

*Componentes Clave*

-   Usuario: Clase central que representa a los usuarios finales, manejando la identidad y acciones que pueden realizar dentro del sistema.
-   Foto: Clase que encapsula los datos de las imágenes y su metainformación, permitiendo operaciones de procesamiento y gestión.
-   Sesión de Fotos: Gestiona el conjunto de imágenes que un usuario puede manejar en una sesión activa, facilitando operaciones como subir, editar y organizar fotos.
-   Repositorio de Fotos: Implementa la lógica de acceso y manipulación de los datos de fotos, comunicándose con la base de datos.

*Conexiones Externas*

-   Bases de Datos (Bases de Datos): Almacena y recupera la información persistente de los usuarios y las fotos.
-   Sistemas de Mensajería (Mensajería): Proporciona la infraestructura para enviar y recibir mensajes asincrónicos, facilitando tareas como la confirmación de acciones o la ejecución de trabajos en segundo plano.
-   Servicios de Correo (Correo): Permite enviar notificaciones y comunicaciones a los usuarios, como confirmaciones de registro o notificaciones de cambios en sus fotos.

![Diagrama Descripción generada automáticamente](media/a9fa0e5e7f1678bd37aece1f7131f3c9.png)

El diagrama muestra de manera simplificada cómo las clases definidas interactúan con los servicios externos:

-   Los Usuarios se autentican y realizan acciones que requieren interactuar con Bases de Datos para guardar o consultar información.
-   Los cambios en Fotos pueden desencadenar eventos que son manejados por los Sistemas de Mensajería, permitiendo procesos como la generación de miniaturas o la indexación para búsquedas.
-   Sesiones de Fotos mantienen el estado temporal de las interacciones del usuario, con un posible almacenamiento en caché para mejorar el rendimiento.

### 5.1.6. Bounded Context Software Architecture Component Level Diagrams.

### 5.1.7. Bounded Context Software Architecture Code Level Diagrams.

![Diagrama Descripción generada automáticamente](media/e1e19925c954a16735afe733d49e41eb.png)

5.1.7.1. Bounded Context Domain Layer Class Diagrams.

![Diagrama Descripción generada automáticamente](media/246adb768cfe03b2bdf61554d0c58c59.png)

# Capítulo VI: Solution UX Design.

## 6.1. Style Guidelines.

### 6.1.1. General Style Guidelines.

*Branding:*

Logotipo: Uso del logotipo con espacio adecuado alrededor para garantizar visibilidad.

Paleta de Colores: Colores primarios y secundarios de la marca que evocan el tono de comunicación.

Imaginería: Estilo de fotografías e ilustraciones que reflejan la personalidad de la marca.

*Tipografía:*

Fuente Principal: Para títulos y encabezados, que sea legible y alinee con la identidad de marca.

Fuente Secundaria: Para cuerpo de texto, asegurando legibilidad en diferentes tamaños y dispositivos.

Jerarquía: Uso consistente de tamaños de fuente para establecer una clara jerarquía visual.

*Colores:*

Uso de Color: Para llamar la atención sobre elementos importantes y guiar al usuario a través de la interfaz.

Contraste: Suficiente contraste entre el texto y el fondo para la accesibilidad y la legibilidad.

*Espaciado:*

Padding y Margins: Definir espaciado estándar para crear diseños limpios y organizados.

Alineación: Uso de una cuadrícula para mantener consistencia en el diseño.

*Tono de Comunicación:*

Voz de la Marca: Divertido/Serio, Formal/Casual, Respetuoso/Irreverente, Entusiasta/Sereno.

Lenguaje Aplicado: Elegir un lenguaje que refuerce la voz de la marca y conecte con la audiencia.

### 6.1.2. Web, Mobile & Devices Style Guidelines.

*Interfaces Web Responsivas:*

-   Adaptabilidad: Diseños que se ajustan a diferentes tamaños de pantalla, desde móviles hasta escritorios.
-   Navegación: Menús y botones que son fáciles de usar en cualquier dispositivo.

*Interfaces Nativas para Móviles:*

-   Tamaño de Toque: Áreas de interacción que se adaptan al tamaño del dedo.
-   Gestos: Implementación de gestos naturales para la interacción con la aplicación.

*Consistencia:*

-   Elementos de UI: Mantener una consistencia visual y de interacción a través de todas las plataformas.
-   Patrones de Diseño: Seguir patrones de diseño conocidos para mejorar la usabilidad.

*Feedback Visual:*

-   Animaciones: Uso de animaciones sutiles para ofrecer retroalimentación y mejorar la experiencia del usuario.
-   Estado de los Elementos: Diseños claros para indicar el estado activo, inactivo o interactuable de los elementos de UI.



 ## 6.2. Information Architecture
 ### 6.2.2. Labeling Systems.
 **Encabezados (headings):**  Estas etiquetas son cruciales para guiar a los usuarios a través de la plataforma, facilitando la comprensión inmediata de las secciones de generación y edición de imágenes.

- **Etiquetas textuales:** Utilizadas para señalar características específicas de la plataforma, como "Crear retrato", "Editar imagen", y "Ver galería".

-  **Etiquetas icónicas (iconic labels):** El empleo de iconos claros para funciones como subir una imagen, ajustar configuraciones de edición o descargar imágenes, generalmente acompañados de texto para evitar confusiones.

Estos dos tipos de etiquetas se hacen visibles en la barra de navegación de nuestro prototipo.
### 6.2.3. SEO Tags and Meta Tags.

Las etiquetas meta juegan un papel crucial al incrementar la visibilidad online de una página mediante la optimización para motores de búsqueda. Aunque no son visibles directamente para los visitantes de la página, los navegadores y los motores de búsqueda las utilizan para interpretar y clasificar el contenido de los sitios web. Estas etiquetas facilitan la interpretación de los contenidos de los archivos HTML y son fundamentales para una gestión eficiente del mismo. Así, las etiquetas meta no solo ayudan a organizar la información de forma más efectiva, sino que también son determinantes para posicionar mejor la página en los resultados de búsqueda, lo que atrae a más visitantes al sitio.

 - **Titulo:** Esta etiqueta se cuenta entre las más importantes y suele ubicarse antes que cualquier otra etiqueta meta.
  
       ``` <title>Crea retratos realistas con nuestra herramienta de IA</title> ```


- **Codificación de caracteres:** Esta etiqueta ayudará a que muestre correctamente los caracteres especiales de nuestra pagina. 
  
      ``` <meta charset="utf-8"/> ```

- **Descripcion:** Esta meta etiqueta nos sirve para proporcionar un resumen del contenido de la página web.
  
      ``` <meta name="description" content="Transforma tus fotos en obras de arte con nuestra avanzada herramienta de inteligencia artificial. Crea, edita y personaliza imágenes como nunca antes."/> ```

- **Palabras Clave:** En esta etiqueta se pone las palabras claves relacionadas con el tema o contenido de la página web.

        ``` <meta name="keywords" content="inteligencia artificial, edición de fotos, generación de imágenes, retratos IA"/>  ```

- **Autor y Derechos de Autor:** Se utiliza para registrar la información del autor de la página web y la propiedad y derechos de autor.

       ``` <meta name="author" content="PictoAI" /><meta name="copyright" content="Copyright 2024 PictoAI"/> ```

  ### 6.2.4. Searching Systems.

    Los usuarios pueden introducir términos para buscar tipos específicos de plantillas o estilos de edición, con resultados que aparecen de forma instantánea.

  ### 6.2.5. Navigation Systems.
  - **Landing Page:** 
  
    Enlaces directos a las funcionalidades clave como "Inicio", "Nosotros" y "Crea tu retrato con IA". Botones y links en la página principal conducirán a los usuarios directamente a las secciones deseadas, mejorando la experiencia de usuario y facilitando el acceso a las herramientas. Asimismo, se implementaran otros botones para facilitar la navegacion al usuario.
  ### 6.3. Landing Page UI Design.
  ### 6.3.1. Landing Page Wireframe.
  
  ![Captura de pantalla 2024-04-28 164006](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/bec06a15-dd53-46af-bac8-d7f1c0910c23)
  
  ### 6.3.2. Landing Page Mock-up.
  
  Esta sección presenta y explica los Mock-ups del Landing Page, tanto en su versión para Desktop Web Browser como Mobile Web Browser. 
  
  **Desktop Web Browser**

  En esta sección, se muestra como se ve la landing page en navegadores web.

  ![Captura de pantalla 2024-04-27 234535](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/395e9f05-269f-45f6-981e-3fc1c5fa47f1)

  **Mobile Web Browser**

  En esta sección, se muestra como se ve la landing page en dispositivos móviles, para tablets y celulares.

  ![Captura de pantalla 2024-04-27 234717](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/d65b5205-da34-45f5-af01-c1048569064a)
  
  ### 6.4. Applications UX/UI Design.

  #### 6.4.1. Applications Wireframes.

  ![Captura de pantalla 2024-04-28 173842](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/498240e9-4ce6-4766-b2da-1bc246a4945d)
  ![Captura de pantalla 2024-04-28 173856](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/845dd76a-5a9f-4f46-96be-313798074a6b)
  ![Captura de pantalla 2024-04-28 173912](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/d13ad618-73c9-408d-8b97-481ff3741998)
  ![Captura de pantalla 2024-05-03 083453](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/eb60f848-f911-483b-a759-7d665aa2e827)
  ![Captura de pantalla 2024-05-03 083510](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/034d247d-f3aa-4b86-a625-deab655021a1)
  ![Captura de pantalla 2024-05-03 083531](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/6ea2b1d3-601d-410a-b8c2-14c7ddae5b53)


  #### 6.4.2. Applications Wireflow Diagrams.

  ![Captura de pantalla 2024-05-03 094709](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/111524705/978aafcb-9fe4-4a2b-ad34-a5b9d3c3875c)
  # 7.1 Software Configuration Management
  ### 6.4.2. Applications Mock-ups
  ![mcp 1](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/540ddae5-e398-4f75-a220-c3413893edec)
  ![mck 2](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/cf845ca3-7f41-4379-abd1-8fd1605d539d)
  ![mck 3](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/6658823f-939e-4489-b6e8-9d4d89aec267)
  
  ![mck 4](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/50476f9d-0c7b-4c28-892d-2d134966094f)
  ![cmk 5](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/5ae2b30f-f2e0-46ac-a370-8553adcd0ae1)
  ![mck 6](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/e236dd37-fca5-4678-920d-07abec02d00e)
  
  ![mck 7](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/0659f6dc-1754-4c22-ab54-f2f93d693c1d)

  ### 6.4.3. Applications User Flow Diagrams.

  
1. **User Goal**: Registro de usuario en la aplicación móvil.

   **User Persona**: Juan Pérez, 30 años, usuario habitual de aplicaciones móviles para gestionar sus tareas diarias.

   ### **Flujos**:
     - **Happy Path**:
       1. El usuario abre la aplicación y selecciona "Registrarse".
       2. Introduce sus datos personales (nombre, correo electrónico, contraseña).
       3. Confirma los datos y selecciona "Enviar".
       4. Recibe una confirmación de registro exitoso y es redirigido a la pantalla principal de la aplicación.
  
          ![aaaa](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/71df9f70-573e-4b08-914b-87231af1b287)

        **Unhappy Path**:
       1. El usuario abre la aplicación y selecciona "Registrarse".
       2. Introduce sus datos personales, pero comete un error en la dirección de correo electrónico.
       3. Recibe un mensaje de error indicando que la dirección de correo electrónico es inválida.
       4. Corrige la dirección de correo electrónico y vuelve a intentar registrarse.
       5. Completa el registro correctamente.

      **User Persona**: Laura Martínez, 35 años, gerente de proyectos en una empresa tecnológica.

     ### **Flujos**:
     - **Happy Path**:
       1. El usuario profesional abre la aplicación y selecciona "Registrarse".
       2. Introduce sus datos profesionales 
       3. Sube un documento de verificación profesional.
       4. Confirma los datos y selecciona "Registrarse".
       5. Recibe un mensaje de éxito en el registro y es redirigido al panel de control profesional.
      
        ![aaaa](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/329399fd-cd42-4fda-8941-ef7b54187b27)

     
        **Unhappy Path**:
       1. El usuario abre la aplicación y selecciona "Registrarse".
       2. Introduce sus datos personales, pero comete un error en la dirección de correo electrónico.
       3. Recibe un mensaje de error indicando que la dirección de correo electrónico es inválida.
       4. Corrige la dirección de correo electrónico y vuelve a intentar registrarse.
       5. Completa el registro correctamente.     
  
    
          
  ### 6.5. Applications Prototyping

  Para el prototipo se utilizo figma:
  Link: [Professional User Flow Design on Figma](https://www.figma.com/design/T5SUxWQSfjQem0eSIFw2iv/Untitled?node-id=0-1&t=sdqJQr0qNip4fuCW-1)

  


  

## 7.1.1 Software Development Environment Configuration

**Descripción del entorno de Desarrollo**  

### Backend - Java con Spring Boot
- Lenguaje y Framework: Java 21, Spring Boot.
- IDE: IntelliJ IDEA.
- Build Tool: Maven.
- Base de Datos: MySQL
- Deploy: Railway.app

### Frontend - TypeScript, JavaScript, y CSS
- Lenguajes: TypeScript, JavaScript, HTML5, CSS3.
- Frameworks y Librerías: React.js.
- IDE: Visual Studio Code.
- Package Manager: npm/yarn.
- Deploy: Vercel

### Móvil - Dart con Flutter
- Lenguaje y Framework: Dart, Flutter.
- IDE: Android Studio
- Emuladores: Android Emulator
- Deploy: (Pendiente)

**Descripción del entorno de Desarrollo**  

### Backend
- Maven: Archivo `pom.xml` para gestionar dependencias.
![1](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/4cd9aa74-fee0-4706-82d6-32353377b789)

### Frontend
- `package.json` para gestionar dependencias de JavaScript y TypeScript.
![2](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/5f2667a7-9955-4a85-94d9-88e09d0e835b)

### Móvil
- Archivo `pubspec.yaml` para gestionar dependencias de Flutter.
  
![3](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/522eb585-8d60-4ae8-a9be-78355bb00302)

## 7.1.2 Source Code Management

**Repositorio de Código Fuente**
- Plataforma: GitHub
- URL del Repositorio: Se debe incluir la URL del repositorio de GitHub correspondiente al proyecto. Ejemplo:
- Backend: [https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/PictoAI-BackEnd](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/PictoAI-BackEnd)
- Frontend: [https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/picto.ia-web-app](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/picto.ia-web-app)
- Móvil: [https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/PICTOIA_MOVIL](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/PICTOIA_MOVIL)

**Herramientas de Control de Versiones**
- Git: Se hizo uso de esta herramienta para el control del proyecto y utilizando la plataforma GitHub para almacenarlo.

**Estructura del Repositorio**
- Organización del Código: Se crearon 4 repositorios para que se distribuyen de la siguiente forma:
![4](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/fe760319-5e83-416d-abe1-58268be11665)

  - Main Branch: `main`
    - Rama principal contiene el código listo para producción.
  - Development Branch: `develop`
    - Rama de desarrollo donde se integran las nuevas características y correcciones de errores antes de ser lanzadas a producción.
  - Feature Branches: `feature/*`
    - Ramas para el desarrollo de nuevas características. Cada nueva característica se desarrolla en una rama separada.

**Integración Continua y Deploy Automático**
- Para gestionar el código fuente de manera eficiente y segura se utilizan las siguientes herramientas y prácticas:
  - Integración Continua (CI): GitHub Actions
  - Pipelines:
    - Backend: Compilación, pruebas unitarias, análisis estático, despliegue en Railway.app.
    - Frontend: Compilación, pruebas unitarias, análisis estático, despliegue en Vercel.
    - Móvil: Compilación, pruebas unitarias, generación de APK/IPA.

## 7.1.3 Source Code Style Guide & Conventions

**BackEnd**

### Estructura del Proyecto
- En el proyecto backend de PictoAI utilizando Spring Boot se sigue un patrón de diseño de arquitectura en capas. Este patrón divide la aplicación en capas con responsabilidades específicas promoviendo la separación de preocupaciones y facilitando el mantenimiento y la escalabilidad del sistema. A continuación se describe la estructura del proyecto y el propósito de los diferentes componentes.
    - Patrón de Diseño Utilizado: Arquitectura en Capas
    - Controller Layer: Maneja las solicitudes HTTP, realiza la validación inicial y delega las llamadas al servicio adecuado.
    - Service Layer: Contiene la lógica de negocio principal y se comunica con la capa de repositorios para acceder a los datos.
    - Repository Layer: Maneja la interacción con la base de datos proporcionando métodos para realizar operaciones CRUD.
    - Model Layer: Define las entidades de datos que representan las tablas de la base de datos.
    - DTO Layer: Define los objetos de transferencia de datos que se utilizan para encapsular los datos enviados entre las capas.

### Nomenclatura y Convenciones
- Nombres de las clases: Se utiliza PascalCase.
- Nombre de los métodos: Se utiliza camelCase.
- Constantes: Se utiliza UPPPER_SNAKE_CASE.

**FrontEnd**

### Estructura del Proyecto
- El proyecto frontend de PictoAI utiliza Next.js, un framework basado en React. La estructura del proyecto está organizada de manera que facilita el desarrollo, la colaboración y el mantenimiento. A continuación se describe la estructura del proyecto y el propósito de los diferentes componentes.
    - Patrón de Diseño Utilizado: Component-Based Architecture
    - Pages: Define las rutas de la aplicación donde cada archivo en el directorio pages representa una ruta.
    - Components: Contiene componentes reutilizables que se pueden utilizar en diferentes partes de la aplicación.
    - Services: Maneja las llamadas a las API y la lógica de negocio del frontend.
    - Styles: Contiene los archivos de estilo globales y específicos de componentes.

### Nomenclatura y Convenciones
- Nombres de las clases: Se utiliza PascalCase.
- Nombre de los métodos: Se utiliza camelCase.
- Constantes: Se utiliza UPPER_SNAKE_CASE.

**Móvil**

### Estructura del Proyecto
- El proyecto móvil de PictoAI está desarrollado en Dart utilizando el framework Flutter. La estructura del proyecto está diseñada para ser modular y mantener una clara separación de responsabilidades, facilitando el desarrollo y mantenimiento. A continuación se describe la estructura del proyecto y el propósito de los diferentes componentes.
- Patrón de Diseño Utilizado: Component-Based Architecture
- Screens: Define las diferentes pantallas de la aplicación.
- Widgets: Contiene widgets reutilizables que se pueden utilizar en diferentes partes de la aplicación.
- Services: Maneja las llamadas a las API y la lógica de negocio del frontend.
- Assets: Contiene recursos estáticos como imágenes y fuentes.

### Nomenclatura y Convenciones
- Nombres de las clases: Se utiliza PascalCase.
- Nombre de los métodos: Se utiliza camelCase.
- Constantes: Se utiliza UPPER_SNAKE_CASE.

**Referencias para Estilo y Convenciones**
- Para todos los lenguajes se aplicarán las convenciones de nomenclatura en inglés. Además se adoptarán convenciones estándar para codificación:
- Java: [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
- TypeScript: [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html)
- Dart: [Effective Dart](https://dart.dev/guides/language/effective-dart)
- Gherkin (para archivos .feature): [Gherkin Conventions for Readable Specifications](https://cucumber.io/docs/gherkin/reference/)

## 7.1.4 Software Deployment Configuration

### Backend
- Servidor de Aplicaciones: Railway.app se utiliza para el despliegue.
- Archivo de Configuración (`application.properties`)

**Pasos para el Despliegue:**
1. Conectar el repositorio de GitHub a Railway.app.
2. Configurar las variables de entorno necesarias como `SPRING_DATASOURCE_URL`, `SPRING_DATASOURCE_USERNAME`, y `SPRING_DATASOURCE_PASSWORD`.
3. Railway.app se encargará de desplegar automáticamente la aplicación basándose en el archivo `pom.xml` y las configuraciones proporcionadas.
4. Railway.app permite la configuración de bases de datos directamente desde su plataforma, facilitando la integración y el despliegue.

### Frontend

**Pasos para el Despliegue:**
1. Conectar el repositorio de GitHub a Vercel.
2. Seleccionar el framework Next.js en la configuración de Vercel.
3. Establecer las variables de entorno necesarias en el panel de control de Vercel.
4. Vercel se encargará del despliegue continuo basándose en los cambios realizados en el repositorio.

# 7.2 Solution Implementation

## 7.2.1 Sprint #1

### 7.2.1.1 Sprint Planning

| Item                    | Details                                           |
|-------------------------|---------------------------------------------------|
| **Date**                | 30/05/2024                                        |
| **Time**                | 10:00 p.m                                         |
| **Location**            | Sala de conferencias virtual de Google Meet       |
| **Prepared By**         | Josef Romero                                      |
| **Attendees** (to planning meeting) | Richar Romero, Angel Chuco, Frank Alva, Lino Quenta |

**Sprint n – 1 Review Summary**
- Durante el Sprint anterior (Sprint 0) se completó la configuración inicial del entorno de desarrollo, la instalación de herramientas necesarias y la creación del repositorio en GitHub. Se realizaron reuniones de familiarización y entrenamiento con las tecnologías que se utilizarán en el proyecto.

**Sprint n – 1 Retrospective Summary**
- El equipo consideró que el proceso de configuración del entorno fue exitoso, aunque se identificaron algunas áreas de mejora en la documentación de instalación y configuración de herramientas. Se sugirió mejorar la claridad de los pasos en la documentación y establecer puntos de control para asegurarse de que todas las herramientas estén correctamente configuradas.

**Sprint Goal & User Stories**

| Sprint n Goal           | Desarrollar la funcionalidad básica de autenticación y registro de usuarios así como la funcionalidad para subir y descargar fotografías. |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint n Velocity**   | El equipo estima completar 48 horas de trabajo en este sprint.                                                                                  |
| **Sum of Story Points** | 48 puntos de historia                                                                                                                           |

**User Stories para Sprint 1**

| ID - HU | TÍTULO                          | (Importancia precedencia) | TIPO | ESTIMACIÓN (Story points) | SPRINT |
|---------|----------------------------------|----------------------------|------|---------------------------|--------|
| US001   | Registro de usuario              | (Alta Baja)                | RF   | 3                         | 1      |
| US002   | Cerrar sesión de usuario         | (Media Baja)               | RF   | 2                         | 1      |
| US004   | Seleccionar un plan              | (Alta Alta)                | RF   | 5                         | 1      |
| US005   | Gestión de suscripción           | (Alta Alta)                | RF   | 8                         | 1      |
| US008   | Explorar galería de fotografías  | (Media Alta)               | RF   | 5                         | 1      |
| US009   | Descargar fotografías            | (Media Baja)               | RF   | 4                         | 1      |
| US010   | Compartir fotografías            | (Alta Media)               | RF   | 5                         | 1      |

### 7.2.1.2 Sprint Backlog #1

**Introducción**
- El objetivo principal del Sprint #1 es implementar las funcionalidades básicas de la aplicación de gestión de fotografías, incluyendo el registro de usuario, cierre de sesión, selección de plan, gestión de suscripción, exploración de galería de fotos y descarga de fotografías. A continuación se presenta un screenshot del Board en Trello junto con el URL público del Board.
  - URL: [https://trello.com/b/iS0ztjoS](https://trello.com/b/iS0ztjoS)
    ![5](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/a83b7b7c-bdf5-43cf-b4c8-115a9b5fe236)


**User Stories Asignadas al Sprint #1**

| User Story | Work-Item / Task          | Id  | Title                      | Description                                | Estimation (Hours) | Assigned To                | Status (To-do / In-Process / To-Review / Done) |
|------------|---------------------------|-----|----------------------------|--------------------------------------------|--------------------|----------------------------|-----------------------------------------------|
| US001      | Registro de usuario       | T001| Crear formulario de registro | Implementar formulario de registro en la interfaz | 8                  | Josef Cesar Romero Florida | To-do                                       |
|            |                           | T002| Validar datos de registro  | Añadir validación de datos para el registro | 4                  | Richar Varoni Romero Cacha | To-do                                       |
|            |                           | T003| Conectar API de registro   | Integrar backend con el formulario de registro | 6                  | Ángel Gustavo Chuco Michel | To-do                                       |
| US002      | Cerrar sesión de usuario  | T004| Crear botón de cerrar sesión | Añadir botón de cierre de sesión en la interfaz | 4                  | Frank Yamil Alva Cordova   | To-do                                       |
|            |                           | T005| Implementar lógica de sesión | Implementar la lógica para cerrar sesión   | 6                  | Lino Abraham Quenta Leon   | To-do                                       |
| US004      | Seleccionar un plan       | T006| Crear interfaz de selección de plan | Implementar la interfaz para la selección de planes | 6                  | Josef Cesar Romero Florida | To-do                                       |
|            |                           | T007| Conectar API de planes     | Integrar backend con la funcionalidad de selección de planes | 6                  | Richar Varoni Romero Cacha | To-do                                       |
| US005      | Gestión de suscripción    | T008| Crear interfaz de gestión de suscripción | Implementar la interfaz para la gestión de suscripciones | 8                  | Ángel Gustavo Chuco Michel | To-do                                       |
|            |                           | T009| Conectar API de suscripciones | Integrar backend con la funcionalidad de gestión de suscripciones | 6                  | Frank Yamil Alva Cordova   | To-do                                       |
| US008      | Explorar galería de fotos | T010| Crear interfaz de exploración de galería | Implementar la interfaz para explorar la galería de fotos | 6                  | Lino Abraham Quenta Leon   | To-do                                       |
|            |                           | T011| Conectar API de galería    | Integrar backend con la funcionalidad de exploración de la galería | 6                  | Josef Cesar Romero Florida | To-do                                       |
| US009      | Galería de fotos editadas | T012| Crear interfaz de galería de fotos editadas | Implementar la interfaz para la galería de fotos editadas | 6                  | Richar Varoni Romero Cacha | To-do                                       |
|            |                           | T013| Conectar API de galería editada | Integrar backend con la funcionalidad de galería de fotos editadas | 6                  | Ángel Gustavo Chuco Michel | To-do                                       |
| US010      | Descargar fotografías     | T014| Crear interfaz de descarga | Implementar la interfaz para la descarga de fotografías | 8                  | Frank Yamil Alva Cordova   | To-do                                       |
|            |                           | T015| Conectar API de descarga   | Integrar backend con la funcionalidad de descarga | 6                  | Lino Abraham Quenta Leon   | To-do                                       |

### 7.2.1.3 Development Evidence for Sprint Review
- Durante el Sprint 1 se realizaron avances significativos en el desarrollo de las diferentes partes del proyecto PictoIA. Los commits reflejan las implementaciones y correcciones en las áreas del backend, frontend y la aplicación móvil. A continuación se presenta la tabla con los commits relevantes de cada repositorio.

**Tabla de Commits**

| Repository          | Branch       | Commit Id | Commit Message                          | Commit Message Body                                              | Committed on (Date) |
|---------------------|--------------|-----------|-----------------------------------------|------------------------------------------------------------------|---------------------|
| pictoai-backend     | feature/auth | 14ca4e3   | feat: obtiene imágenes del SD           | Implementación de la funcionalidad para obtener imágenes del almacenamiento local | 4/06/2023           |
| pictoai-backend     | main         | 2f9d1b6   | fix                                     | Corrección de errores menores relacionados con la autenticación de usuarios | 3/06/2023           |
| pictoai-web-app     | main         | 7bdc72a   | Merge pull request #1 from PictoAI-Crea-fotos-con-IA-en-segundos/feature/auth | Fusionando cambios de autenticación en la rama principal | 4/06/2023           |
| pictoai-web-app     | feature/connection | 3ac57f1   | feat: connection-to-sd                  | Implementación de la conexión con el almacenamiento local        | 4/06/2023           |
| pictoai-web-app     | main         | 8cd45b2   | feat: update properties                 | Actualización de propiedades de configuración                    | 1/06/2023           |

### 7.2.1.4 Testing Suite Evidence for Sprint Review

| Repository          | Branch       | Commit Id | Commit Message                          | Commit Message Body                                              | Commited on (Date) |
|---------------------|--------------|-----------|-----------------------------------------|------------------------------------------------------------------|--------------------|
| backend             | feature/tests| 7c9d5e3   | test: Add unit tests for AuthController | Added unit tests for login and registration endpoints in AuthController to verify functionality. | 5/06/2024          |
| frontend            | feature/tests| b1a2f8c   | test: Implement integration tests for User Profile | Implemented integration tests to ensure user profile updates and fetch operations work correctly. | 6/06/2024          |

### 7.2.1.5 Execution Evidence for Sprint Review
- En este Sprint hemos logrado implementar y probar varias funcionalidades clave de la aplicación. Hemos completado las User Stories US001, US002, US004, US005, US008, US009, US010, cubriendo la creación y gestión de usuarios, la selección y gestión de planes, la exploración de la galería de fotos y la descarga de imágenes. Además, se han corregido errores menores y mejorado la interfaz de usuario.

**FrontEnd**
  ![6](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/63de5db9-97bc-4736-a1bc-7307d346e769)

- Inicio de sesión
  ![7](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/298165b5-2dc0-4864-aa37-adf859b0b17e)

- Registro
  ![8](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/674ce508-70ba-4b88-ab03-63a0f1d2445c)

- Elección de plan 
  ![9](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/a8680b71-09d0-47a3-8d4e-6814b7b35977)

**Backend**

- Generación de token
  ![10](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/09a23950-6089-4a9e-b6bf-d4379f1834fe)

- Generación de imagen 
  ![11](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/bf2a8b59-1e67-4ab5-9143-1fed94419d18)

**Móvil**
- Main
  ![12](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/71d46d47-d87e-4a1a-a9ef-32bb9d2db33e)

- Profile
  ![13](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/d0f9bbd9-691f-4acb-a628-22f5a0cce5e8)

- Generar Imagen
  ![14](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/f79a571e-62df-47da-b5e1-52f786e0024c)

- Favoritos 
  ![15](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/eac6aa7e-cc13-41a9-8227-771307baac9d)

### 7.2.1.6 Services Documentation Evidence for Sprint Review  
- En este Sprint se han documentado y desarrollado los siguientes endpoints para los Web Services del proyecto utilizando OpenAPI para asegurar una documentación clara y accesible. A continuación se presenta una tabla con la relación de endpoints desarrollados, indicando las acciones implementadas y proporcionando los enlaces a la documentación correspondiente. Además, se incluye una explicación de las acciones soportadas y ejemplos de interacción.

| Endpoint            | Acción       | Método HTTP | Parámetros                            | Ejemplo de Respuesta                                        |
|---------------------|--------------|-------------|---------------------------------------|-------------------------------------------------------------|
| /api/users/register | Registro     | POST        | { "username": "string", "password": "string" } | { "id": 1, "username": "usuario1", "status": "registered" } |
| /api/users/login    | Login        | POST        | { "username": "string", "password": "string" } | { "token": "jwt_token_string", "username": "usuario1" }     |
| /api/photos/upload  | Subir Fotos  | POST        | multipart/form-data                   | { "id": 10, "url": "http://server.com/photos/10.jpg", "status": "uploaded" } |
| /api/photos/edit/{id} | Editar Fotos | PUT        | { "id": "int", "edits": "object" }    | { "id": 10, "url": "http://server.com/photos/10_edited.jpg", "status": "edited" } |
| /api/photos/{id}    | Ver Foto     | GET         | { "id": "int" }                       | { "id": 10, "url": "http://server.com/photos/10.jpg", "created_at": "2023-06-05T12:00:00Z" } |

### 7.2.1.7 Software Deployment Evidence for Sprint Review
- Durante este Sprint se han realizado varias actividades relacionadas con el despliegue de las diferentes partes de nuestra aplicación. A continuación se detallan los procesos realizados, las herramientas utilizadas y las configuraciones establecidas para asegurar el correcto funcionamiento del backend, frontend y la aplicación móvil.

**Procesos Realizados**

**Backend**
- Plataforma: Railway
- Configuración de Cuenta: Se creó una cuenta en Railway y se vinculó con el repositorio de GitHub del proyecto.
- Se configuró la base de datos MySQL en Railway.

**Despliegue:**
- Configuración del archivo `application.properties` para apuntar a la base de datos desplegada en Railway.
- Automatización del despliegue continuo mediante el pipeline CI/CD de Railway.
- Verificación del correcto funcionamiento de los endpoints desplegados.

**Frontend**
- Plataforma: Vercel
- Configuración de Cuenta: Se creó una cuenta en Vercel y se vinculó con el repositorio de GitHub del proyecto.

**Despliegue:**
- Configuración del proyecto Next.js para despliegue en Vercel.
- Automatización del despliegue continuo mediante el pipeline CI/CD de Vercel.
- Verificación de la correcta visualización y funcionalidad de la interfaz web desplegada.

**Aplicación Móvil**
- Plataforma: Android Studio
- Configuración de Emuladores: Configuración de emuladores de Android para pruebas.

**Despliegue:**
- Preparación del entorno de desarrollo en Android Studio.
- Generación de archivos APK para pruebas internas.
- Verificación de la correcta ejecución de la aplicación en diferentes dispositivos.

**Capturas**
- **BackEnd**
![20](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/488f63fc-46a8-4340-8cd3-59121922c3ac)

- **FrontEnd**
  
![21](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/14784d22-a5e5-430f-814e-39da5dacb69c)


- **Móvil**
![22](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/abb5a035-a2d2-4d45-a540-9bda86a11a5e)

### 7.2.1.8 Team Collaboration Insights for Sprint Review
- Durante este Sprint el equipo ha colaborado de manera efectiva en las diferentes tareas y funcionalidades asignadas. A continuación se presenta un resumen de las actividades de colaboración y los analíticos de commits en GitHub realizados por los miembros del equipo:

**Colaboración y Comunicación**
- Herramientas de colaboración: Se utilizó Google Meet para la comunicación instantánea y Trello para la gestión de tareas y el seguimiento del Sprint Backlog.
- Par de programación: Se implementó la técnica de par de programación en varias tareas críticas para fomentar el aprendizaje y reducir errores.

**Commits (pide evidencia de que todos participamos en los repos)**

**Principales contribuciones:**
- Josef Cesar Romero Florida: Implementación de la funcionalidad de obtención de imágenes desde el almacenamiento del dispositivo.
- Richar Varoni Romero Cacha: Corrección de errores y commits iniciales de configuración del proyecto.
- Ángel Gustavo Chuco Michel: Implementación de conexiones adicionales y actualizaciones de propiedades.
- Frank Yamil Alva Cordova: Integración y pruebas de funciones de la aplicación móvil.
- Lino Abraham Quenta Leon: Desarrollo de funcionalidades adicionales y mejoras en la interfaz de usuario.
![18](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/bf042785-b6ad-4825-87f6-43ead5794ddd)
![19](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/4498487b-cad9-4a04-9752-45f4d5ac19b6)
![20](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/8fea1794-54d9-4b49-a019-3541334e1e83)

# 7.3 Validation Interviews

## 7.3.1 Diseño de entrevistas
Para este apartado se dividieron las preguntas en 5 secciones para el usuario entusiastas y 6 para el profesional buscando así obtener una retroalimentación adecuada para cada apartando.

### Preguntas para el Usuario Entusiasta
**Registro y Inicio de Sesión:**
- ¿Fue fácil para ti registrarte en la aplicación? ¿Qué parte del proceso encontraste más sencilla o más complicada?
- ¿Qué opinas de la opción de iniciar sesión con Google/GitHub? ¿La utilizaste? ¿Por qué?

**Elección de Planes:**
- ¿Qué te parece la oferta de los diferentes planes (Gratis, Pro, Empresarial)? ¿Cuál elegirías y por qué?
- ¿Encontraste claras las diferencias entre cada plan?

**Exploración y Generación de Imágenes:**
- ¿Cómo fue tu experiencia explorando la galería de imágenes? ¿Pudiste encontrar fácilmente lo que buscabas?
- ¿Qué te pareció la funcionalidad de generar imágenes con IA? ¿La encontraste útil y fácil de usar?
- ¿Qué tipos de imágenes generaste? ¿Cómo evaluarías la calidad de las imágenes generadas?

**Interacción con la App Móvil:**
- ¿Qué te pareció la navegación en la aplicación móvil? ¿Fue intuitiva?
- ¿Usaste la funcionalidad de subir fotos por lotes? ¿Cómo fue tu experiencia?
- ¿Qué opinas de las herramientas básicas de edición en la app móvil? ¿Las encontraste adecuadas para tus necesidades?

**Usabilidad y Diseño:**
- ¿Cómo describirías la apariencia y el diseño de la aplicación? ¿Fue atractivo y fácil de entender?
- ¿Qué mejorarías en términos de usabilidad y diseño?

### Preguntas para el Usuario Profesional
**Registro y Inicio de Sesión:**
- ¿Tuviste algún problema al registrarte o iniciar sesión en la aplicación?
- ¿Qué opinas de la seguridad del proceso de registro e inicio de sesión?

**Elección de Planes:**
- ¿Cuál de los planes (Gratis, Pro, Empresarial) te parece más adecuado para tus necesidades profesionales?
- ¿Qué funcionalidades adicionales te gustaría ver en los planes de pago?

**Exploración y Generación de Imágenes:**
- ¿Cómo fue tu experiencia explorando la galería de imágenes y utilizando la función de búsqueda?
- ¿Cómo evaluarías la calidad y la personalización de las imágenes generadas por la IA en términos de uso profesional?
- ¿Qué tipos de proyectos podrías realizar con las imágenes generadas por la IA?

**Interacción con la App Móvil:**
- ¿Qué tan fácil fue para ti usar la aplicación móvil para tus necesidades profesionales?
- ¿Qué opinas de la funcionalidad de subir fotos por lotes en términos de eficiencia para proyectos grandes?
- ¿Las herramientas de edición básicas en la app móvil cumplen con tus expectativas de calidad profesional?

**Usabilidad y Diseño:**
- ¿Cómo describirías la apariencia y el diseño de la aplicación en términos de profesionalismo?
- ¿Qué mejorarías en términos de usabilidad y diseño para hacer la aplicación más adecuada para profesionales?

**Integraciones y Exportación:**
- ¿Te gustaría ver alguna integración específica (por ejemplo, con Adobe Photoshop, Lightroom, etc.)?
- ¿Qué tan importante es para ti la funcionalidad de exportar imágenes en formatos profesionales?

## 7.3.2 Registro de Entrevistas

### Entrevistas Usuario Entusiasta
**Entrevista 1:**
- URL: [https://www.youtube.com/watch?v=7t5MDzijHx4](https://www.youtube.com/watch?v=7t5MDzijHx4)
![en 1](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/910bfcea-c7de-41a9-a616-d2e3d9fb1681)

**Resumen:**
En el video, el cliente expresa que la aplicación le parece muy fácil de usar, especialmente en los procesos de iniciar sesión y registrarse, sin encontrar dificultades significativas. Destaca la opción intuitiva de iniciar sesión con una cuenta de Google. En cuanto a los planes y precios, se muestra satisfecho con las opciones ofrecidas, prefiriendo inicialmente el plan básico y considerando un posible upgrade en el futuro. Al probar la generación de imágenes, el cliente encuentra que los resultados cumplen con sus expectativas y aprecia la calidad de las imágenes generadas, así como la funcionalidad de agregar fondos a sus fotos. También valora positivamente la función de agregar imágenes a favoritos para facilitar su acceso. En general, considera que la aplicación móvil es correcta, original y entretenida, y sugiere como mejora la posibilidad de crear pequeñas animaciones o GIFs a partir de las imágenes generadas.

**Entrevista 2:**
- URL: [https://drive.google.com/file/d/1SSnxj55udGbJuOagI30QUYRHJ8_rfOuL/view](https://drive.google.com/file/d/1SSnxj55udGbJuOagI30QUYRHJ8_rfOuL/view)
![en2](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/5e3530cf-2a80-42b6-94a4-395a3cdc7eca)

**Resumen:**
En el video, Leonel Alfaro comparte su experiencia utilizando la aplicación Big to Agile. Leonel destaca que el proceso de registro e inicio de sesión es muy intuitivo y fácil de usar. Utilizó su cuenta de Google, lo cual encontró conveniente.
Sobre los planes ofrecidos, considera que los precios son razonables. Empezó con el plan gratuito y luego se cambió al plan pro debido a su experiencia satisfactoria.
Leonel quedó impresionado con la funcionalidad de generación de imágenes, valorando la calidad y precisión de las imágenes generadas. Describió la interfaz de la aplicación como moderna y clara, y apreció la facilidad de navegación. En general, su experiencia con Big to Agile fue muy positiva.

**Entrevista 3:**
- URL: [https://www.youtube.com/watch?v=qrtojmZB9xI](https://www.youtube.com/watch?v=qrtojmZB9xI)
![en4](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/bab566d6-fddc-401b-ad73-25f081442bb3)

**Resumen:**
En el video se habla sobre la experiencia de un cliente, quien es un estudiante, con la aplicación. El cliente menciona que el proceso de registro e inicio de sesión le pareció fácil e intuitivo, destacando la opción de iniciar sesión con Google como la más conveniente. Al explorar los diferentes planes ofrecidos, considera que el plan pro es el más adecuado para usos académicos, mientras que utilizaría el plan gratuito para diversión. En cuanto a la galería de imágenes y la generación de imágenes con inteligencia artificial, el cliente la encuentra útil y fácil de usar, valorando positivamente la calidad de las imágenes generadas. Además, encuentra intuitiva la barra de menús y menciona que la función de guardar en favoritos es útil para acceder rápidamente a imágenes frecuentes. Aunque no llegó a utilizar la función de subir fotos por lotes, le parece interesante. Finalmente, describe el diseño de la aplicación como atractivo, aunque sugiere que los colores podrían ser más suaves.

### Entrevistas Usuario Profesional
**Entrevista 1:**
- URL: [https://www.youtube.com/watch?v=PyFTTX_CbeA](https://www.youtube.com/watch?v=PyFTTX_CbeA)
![en4](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/47e781f3-3c02-4edb-8449-79e16046bc19)

**Resumen:**
En el video se habla sobre la experiencia de una usuaria profesional, contadora pública de Puno, con la aplicación. La usuaria encuentra la aplicación muy interesante, especialmente útil para generar y editar imágenes para su CV y LinkedIn. Considera que el proceso de registro e inicio de sesión es sencillo y accesible, destacando la importancia de contar con imágenes profesionales en sus documentos. En cuanto a los planes, menciona que comenzaría con el plan básico y consideraría un upgrade dependiendo de sus necesidades. La usuaria encuentra la generación de imágenes con inteligencia artificial muy útil, generando principalmente imágenes para su CV con fondo blanco, y valora positivamente la calidad de las imágenes. Respecto a la interfaz de usuario, la considera atractiva y fácil de usar, aunque sugiere algunos cambios en el tamaño de las letras para mejorar la visibilidad. En general, la usuaria encuentra la aplicación sencilla y accesible de utilizar.
**Entrevista 2:**
- URL: [https://www.youtube.com/watch?v=E9dwS9rgGAU](https://www.youtube.com/watch?v=E9dwS9rgGAU)
![en6](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/64944330-5559-4ced-981c-141e95b40f96)

**Resumen:**
En el video se habla sobre la experiencia de un usuario profesional, Gustavo Siancas, fotógrafo, con la plataforma Picto. El usuario destaca que la aplicación es interesante y útil para generar y mejorar fotografías con inteligencia artificial, especialmente para CVs y LinkedIn. Gustavo no tuvo problemas al registrarse o iniciar sesión y se siente seguro con el proceso de registro. Considera adecuado el plan empresarial y recomienda el plan Pro para pequeños fotógrafos. Valora la calidad y personalización de las imágenes generadas, aunque menciona que a veces la IA no cumple completamente con las expectativas. Sugiere que se añadan proyectos generados por la IA en la página de inicio y una integración con Photoshop para mejorar la funcionalidad de exportación. En general, encuentra la aplicación atractiva y profesional, con la combinación de colores adecuada, y considera importante la funcionalidad de exportar imágenes para su trabajo profesional.

**Entrevista 3:**
- URL:[Video en SharePoint](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201910655_upc_edu_pe/EZBGSt0V7FlPtUJAohi3-YgBd-OWrxKLzu8-jCOAPTGBSA?e=eSfQ8d&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

  ![aaaaaaa2](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/560be759-ad89-4fea-8a4c-2e48bb461205)

**Resumen:**
En el video se habla sobre la experiencia de un usuario entusiasta, Luciano Ruiz Blas, con la aplicación Big to Agile. Luciano encontró el proceso de registro e inicio de sesión muy intuitivo y sin dificultades, siguiendo los estándares comunes. Usó su cuenta de GitHub para iniciar sesión, lo cual le resultó cómodo. Respecto a los planes ofrecidos (gratis, pro y empresarial), considera que los precios son justos y claros. Inicialmente, optó por el plan gratuito para probar la aplicación y luego eligió el plan pro, que satisface sus necesidades. Al probar la funcionalidad de generar imágenes, Luciano la encontró muy útil y fácil de usar, similar a un buscador que proporciona imágenes de alta calidad. Valora positivamente el diseño de la aplicación, describiéndolo como atractivo y fácil de entender, aunque sugiere pequeñas mejoras en el diseño. En general, su experiencia con la aplicación fue positiva y satisfactoria.

## 7.3.3 Evaluación según Heurísticas
Esta sección contiene el proceso de evaluación de las sesiones de validación basado en heurísticas, considerando heurísticas de usabilidad, arquitectura de información e inclusive diseño de la experiencia propuesta. Para esto, la sección debe contener la estructura del formato para evaluaciones de heurísticas indicado en el Anexo D. Formato para Evaluación de User Experience según Heurísticas.
####Proceso de Evaluación.

1. **Selección de Heurísticas**:
   - Heurísticas de Nielsen: visibilidad del estado del sistema, correspondencia entre el sistema y el mundo real, control del usuario, consistencia, prevención de errores, reconocimiento en lugar del recuerdo, flexibilidad y eficiencia de uso, diseño estético y minimalista, ayuda y documentación.

2. **Reclutamiento de Evaluadores**:
   - De 3 a 5 evaluadores con experiencia en usabilidad y diseño de interfaces.

3. **Briefing**:
   - Sesión de introducción con guion de tareas específicas para los evaluadores.

4. **Evaluación Individual**:
   - Cada evaluador identifica problemas de usabilidad y anota:
     - Descripción del problema.
     - Heurística violada.
     - Gravedad del problema (leve, moderado, grave, crítico).
     - Sugerencias para solucionar el problema.

5. **Reunión de Consenso**:
   - Discusión y priorización de problemas según su impacto.

6. **Informe de Evaluación**:
   - Resumen de problemas, heurísticas violadas, gravedad y recomendaciones.

#### 3. Resultados de la Evaluación

- **Problema 1**:
  - **Descripción**: El botón de "Enviar" no es visible en la pantalla de registro.
  - **Heurística Violada**: Visibilidad del estado del sistema.
  - **Gravedad**: Crítico.
  - **Recomendación**: Reubicar el botón en una posición más visible o cambiar su color para que destaque más.

- **Problema 2**:
  - **Descripción**: No hay retroalimentación cuando se envía un formulario.
  - **Heurística Violada**: Visibilidad del estado del sistema.
  - **Gravedad**: Grave.
  - **Recomendación**: Agregar un mensaje de confirmación o una animación que indique que el formulario se ha enviado correctamente.
  - 
## 7.4. Video About-the-Product
Link: [YouTube Video](https://youtu.be/9y2EqP8bJX4)

[Video on SharePoint](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201910655_upc_edu_pe/EdTz1pZgaXdHjxMDs8mo6GMBjIvwnyTAD2StWq3ciOXk9g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=GNXLeB)

![prduct](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/6f7613fb-fd5a-442f-8513-b793dcd81693)

### Conclusiones y recomendaciones

En esta sección, el equipo enuncia las conclusiones sobre el trabajo, incluyendo los resultados a los que ha llegado en relación a los Problem Statements especificados, los assumptions realizados frente al comportamiento real de los segmentos, los Hypotheses Statements establecidos y los criterios de éxito especificados en el proceso de Lean UX, en contraste con los resultados obtenidos en el ciclo de vida. Igualmente, incluye recomendaciones sobre los siguientes pasos en relación a Roadmap de los productos digitales que forman parte del alcance del modelo de negocio digital.

#### Conclusiones

1. **Problem Statements**:
   - **Resultado**: Se identificaron y abordaron correctamente los problemas clave de usabilidad y eficiencia en el sistema, cumpliendo con los objetivos planteados en los Problem Statements.
   
2. **Assumptions y comportamiento real**:
   - **Observación**: Las assumptions iniciales sobre el comportamiento de los usuarios fueron en gran parte precisas, aunque algunos segmentos mostraron diferencias significativas en sus interacciones, lo que requirió ajustes en el diseño.

3. **Hypotheses Statements**:
   - **Evaluación**: Las hipótesis planteadas fueron validadas a través de pruebas y retroalimentación de los usuarios, confirmando que las mejoras propuestas eran efectivas para mejorar la usabilidad y satisfacción del usuario.

4. **Criterios de éxito**:
   - **Cumplimiento**: Los criterios de éxito definidos se alcanzaron en su mayoría, con mejoras notables en la experiencia del usuario y la eficiencia operativa del sistema.

#### Recomendaciones

1. **Mejoras Continuas**:
   - **Sugerencia**: Implementar un ciclo continuo de retroalimentación y mejora basado en las evaluaciones heurísticas y la retroalimentación de los usuarios para mantener y mejorar la calidad del sistema.

2. **Roadmap de Productos Digitales**:
   - **Próximos pasos**: Definir y priorizar las siguientes fases de desarrollo en el roadmap del producto, enfocándose en las áreas de mayor impacto identificadas durante el proceso de evaluación.

3. **Adopción de Lean UX**:
   - **Recomendación**: Continuar utilizando el enfoque Lean UX para futuros desarrollos, asegurando que las soluciones se alineen con las necesidades reales de los usuarios y los objetivos de negocio.

4. **Monitoreo y Análisis**:
   - **Estrategia**: Establecer métricas claras y herramientas de monitoreo para evaluar continuamente el desempeño del sistema y la satisfacción del usuario, permitiendo ajustes rápidos y efectivos.

## Video About-the-Team.
Link: [Video on SharePoint](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201910655_upc_edu_pe/ERuYsP1xrCJKjPcsGULj78UBN9n5YNUCEzmJVOggTCWHXQ?e=i1zlfl&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

![about the team](https://github.com/PictoAI-Crea-fotos-con-IA-en-segundos/Informe-Trabajo-/assets/56949276/85928341-7e4e-429b-b5c2-5f5d9a3fdbc1)

### Bibliografía

1. Nielsen, J. (1994). *Usability Engineering*. Academic Press.
2. Norman, D. A. (2013). *The Design of Everyday Things: Revised and Expanded Edition*. Basic Books.
3. Shneiderman, B., Plaisant, C., Cohen, M., Jacobs, S., Elmqvist, N., & Diakopoulos, N. (2017). *Designing the User Interface: Strategies for Effective Human-Computer Interaction* (6th ed.). Pearson.
4. International Organization for Standardization. (2018). *ISO 9241-11:2018 Ergonomics of human-system interaction – Part 11: Usability: Definitions and concepts*. ISO.
5. Krug, S. (2014). *Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability* (3rd ed.). New Riders.
6. Tullis, T., & Albert, B. (2013). *Measuring the User Experience: Collecting, Analyzing, and Presenting Usability Metrics* (2nd ed.). Morgan Kaufmann.
7. Benyon, D. (2014). *Designing Interactive Systems: A Comprehensive Guide to HCI, UX, and Interaction Design* (3rd ed.). Pearson.
8. ISO/IEC 25010. (2011). *Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – System and software quality models*. ISO/IEC.
9. Holtzblatt, K., & Beyer, H. (2017). *Contextual Design: Design for Life* (2nd ed.). Morgan Kaufmann.
10. Garrett, J. J. (2011). *The Elements of User Experience: User-Centered Design for the Web and Beyond* (2nd ed.). New Riders.

  # Anexo
[Video-Trabajo-Parcial](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201910655_upc_edu_pe/EV5FVST-UNhMs1xvbvul0EsBwaugmjjlN6v8xq5TNrkbXQ?e=7ogAKe)
