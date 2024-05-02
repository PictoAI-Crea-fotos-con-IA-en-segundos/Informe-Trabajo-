**UNIVERSIDAD PERUANA**

**DE CIENCIAS APLICADAS**

![Logotipo Descripción generada automáticamente](media/7943e8dd4ed8f5002ac097150ab79dbe.png)

**SI728 Arquitecturas De Software Emergentes**

Informe del trabajo TB1P

**Profesor:** Royer Edelwer Rojas Malasquez

**Startup:** LooGood

**Producto:** PictoAI

**Integrantes:**

Josef Cesar Romero Florida (U201910655)

Richar Varoni Romero Cacha (U20201B428)

Ángel Gustavo Chuco Michel (U20201B193)

Frank Alva Cordova (U202113432)

Lino Abraham Quenta Leon (U20211F978)

**Abril, 25 de 2024**

Contenido

[Capítulo I: Introducción](#_Toc165013622)

[Startup Profile](#startup-profile)

[Descripción de Startup](#descripción-de-startup)

[Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)

[Solution Profile](#solution-profile)

[Antecedentes y Problemática](#antecedentes-y-problemática)

[Lean UX Process](#lean-ux-process)

[Segmento Objetivo](#segmento-objetivo)

[Segmento Objetivo 1: El Usuario Entusiasta](#segmento-objetivo-1-el-usuario-entusiasta)

[Segmento Objetivo 2: El Usuario Profesional](#segmento-objetivo-2-el-usuario-profesional)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

[Competidores](#competidores)

[Análisis competitivo](#análisis-competitivo)

[Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)

[Entrevistas](#entrevistas)

[Diseño de entrevistas.](#diseño-de-entrevistas)

[Registro de entrevistas](#registro-de-entrevistas)

[Needfinding](#needfinding)

[User Personas](#user-personas)

[User Task Matrix](#user-task-matrix)

[Empathy Mapping](#empathy-mapping)

[As-is Scenario Mapping](#as-is-scenario-mapping)

[Ubiquitous Language](#ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

[To-Be Scenario Mapping](#to-be-scenario-mapping)

[User Stories](#user-stories)

[Impact Mapping](#impact-mapping)

[Product Backlog](#product-backlog)

[Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)

[Strategic-Level Attribute-Driven Design](#strategic-level-attribute-driven-design)

[Design Purpose](#design-purpose)

[Attribute-Driven Design Inputs](#attribute-driven-design-inputs)

[Architectural Drivers Backlog](#architectural-drivers-backlog)

[Architectural Design Decisions](#architectural-design-decisions)

[Quality Attribute Scenario Refinements](#quality-attribute-scenario-refinements)

[Strategic-Level Domain-Driven Design](#strategic-level-domain-driven-design)

[EventStorming](#eventstorming)

[Candidate Context Discovery](#candidate-context-discovery)

[Domain Message Flows Modeling](#domain-message-flows-modeling)

[Context Mapping](#context-mapping)

[Software Architecture](#software-architecture)

[Software Architecture System Landscape Diagram](#software-architecture-system-landscape-diagram)

[Software Architecture Context Level Diagrams](#software-architecture-context-level-diagrams)

[Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams)

[Software Architecture Deployment Diagrams](#software-architecture-deployment-diagrams)

# Capítulo I: Introducción

## Startup Profile

### Descripción de Startup

El startup se enfoca en desarrollar una solución de generación de fotos de personas mediante inteligencia artificial con la herramienta Stable Diffusion. Nuestra plataforma utiliza algoritmos avanzados de procesamiento de imágenes para crear retratos realistas y personalizados. Nuestro objetivo es ofrecer una experiencia única y satisfactoria para nuestros usuarios, ya sean entusiastas de la fotografía o profesionales que buscan herramientas innovadoras para su trabajo

### Perfiles de integrantes del equipo

| ![](media/548cdfee6f2643527c29792a81e53db8.png)  | Soy Ángel Gustavo Chuco Michel, tengo 24 años, estudió la carrera de Ingeniería de Software, soy una persona amante de la tecnología y las nuevas tendencias. Considero que tengo aptitudes positivas en el trabajo en equipo y me gusta participar constantemente con mis compañeros.                                                                                                                                                                                                                |
|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](media/d5c50f124d793c16169095b309ffc7a5.png)  | Soy Frank Alva Cordova, tengo 21 años, estudio la carrera de Ingenieria de Software, soy una persona responsable y entusiasta.  Puedo aportar mis conocimientos en desarrollo web y móvil para alcanzar los objetivos planteados. Considero que puedo aportar con el grupo con los conocimientos adquiridos en el curso.                                                                                                                                                                              |
| ![](media/3533042993f9c7fdada23f0848d8881a.png)  | Romero Florida, Josef Ingeniería de SoftwareTengo 21 años y soy originario de Lima. Mi formación escolar fue en el colegio Nuestra Señora del Sagrado Corazón. Actualmente, me encuentro cursando la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, una elección motivada por mi pasión hacia la tecnología. Creo firmemente en la llegada de la Inteligencia General Artificial (AGI) y siempre busco oportunidades para incrementar mi conocimiento en el campo |
| ![](media/6fe0eacbc27dc240e0597d84a431357b.jpeg) | Soy Lino abraham quenta leon, 20 año soy estudiante de la universidad peruana de ciencias aplicadas, actualmente curso el 8 ciclo de la carrera de ingeniería de software, me considero una persona super creativa, me gustas el diseño y la programación web, además de gestionar proyectos, con habilidades blandas ya definidas, además que siempre busco mejorar cada vez más.                                                                                                                    |
| ![](media/83088aac5fa69098862900e9c314902b.png)  | Soy Richar Romero, Tengo 22 años, entre mis principales habilidades se encuentra la capacidad de guardar información, la empatía, el ser resiliente y tengo conocimiento en los lenguajes de C++, C\#, python,JS,Kotlin y en frameworks como vue y angular.                                                                                                                                                                                                                                           |

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

1.  ![](media/712233085ad8d148db3e4134cf3b6827.jpeg)**Lean UX Canvas**

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
-   ¿Se considera introvertido o extrovertido?
-   ¿Cuáles son sus dispositivos preferidos?

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
| ![](media/2f6ca3c6124ff95dcc31ad800d73e2dd.jpeg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                                                                                   |
| **Nombre:** Jhan Antonio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | **Enlace**: <https://drive.google.com/file/d/1N8BaEtO9HeqBmQFKUM04A2mrJ2urq80-/view?usp=sharing>  |
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
| ![](media/578aa7150fc6bd4b41cedb2e8b72f507.png)                                                                                                                                                            |                                                             |

| **Nombre:** Danixa FLores                                                                                                                                                                         | **Enlace**:  <https://drive.google.com/file/d/1EN1ncBXH79UkLREH8i2PZgYxwNa3-Q1Q/view?usp=drive_link>  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Ella piensa que la aplicacion PictoAI es una herramienta muy util debido a que la mayoria de estudios fotograficos el precio es muy elevado, por ende seria una buena solucion para fotos rapidas |                                                                                                       |
| ![](media/a94d94a7f378e3c98fcc34bec02c4e7c.png)                                                                                                                                                   |                                                                                                       |

| **Nombre:** Gustavo                                                                                                                                                                                                                                                                   | **Enlace**: <https://drive.google.com/file/d/1rjtnvejk31DPXnCZELcnKRxDEF612F2R/view?usp=drive_link> |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| El comento que de manera profesional, la la aplicación con IA para mejorar las fotos le saldría muy ultil para usarlo de manera personal, ya que son funcionalidades que en otros sitios web loa encuentras de paga, aparte con fotos limitadas y pocos metodos de exportar la imagen |                                                                                                     |
| ![](media/644107f3717130bae0d9b2c66bc498bd.png)                                                                                                                                                                                                                                       |                                                                                                     |

| **Nombre**  Elias Torres Espinosa                                                                                                                                                                                                                                                                                                                                                                                                     | **Enlace**: <https://drive.google.com/drive/folders/1bUI90SjTQY4KaIax1zctGiQV4MSee1ka>  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| El piensa que es una herramienta muy fundamental porque facilita todo, ya que el es un joven que está trabajando y no cuenta con tiempo, por lo cual le pareció genial la aplicación web, porque así podría personalizar mejor su LinkedIn en vez de estar desplazándose a un centro de estudios fotográficos, siente que sería más fácil subir tus fotos a la aplicación y esta te devuelvas imágenes profesionales y personalizadas |                                                                                         |
| ![](media/644107f3717130bae0d9b2c66bc498bd.png)                                                                                                                                                                                                                                                                                                                                                                                       |                                                                                         |

## Needfinding

### User Personas

![Interfaz de usuario gráfica, Aplicación Descripción generada automáticamente](media/aea34c97ee427eef8309f63826e27b91.png)

![](media/f754ecdb067e4b91ef28b72d7ceabd75.png)

### User Task Matrix

| Tarea                                                                      | Usuario Entusiasta   | Usuario Profesional  |
|----------------------------------------------------------------------------|----------------------|----------------------|
|                                                                            | Frecuencia           | Frecuencia           |
| Generar imágenes para probar nuevo look (corte de pelo, color, accesorios) | 4-5 veces por semana | 1 vez cada 2 semanas |
| Crear fotos de perfil profesional para LinkedIn                            | Ocasionalmente       | Ocasionalmente       |
| Explorar cómo se vería en diferentes escenarios (lugares, épocas)          | Ocasionalmente       | Ocasionalmente       |

### Empathy Mapping

**Segmento objetivo 1:** El usuario profesional

![Diagrama, Escala de tiempo Descripción generada automáticamente](media/0baca919e98c55580860fe9427663eef.jpeg)

**Segmento Objetivo 2:** El usuario entusiasta

![Escala de tiempo Descripción generada automáticamente](media/8206b5cb94835a8eb2e7b28ce89b89eb.jpeg)

### As-is Scenario Mapping

**Segmento objetivo 1:** El usuario profesional

![Escala de tiempo Descripción generada automáticamente](media/40271077924664e3815a6744428ce37a.jpeg)

**Segmento Objetivo 2:** El usuario entusiasta

![Diagrama, Calendario Descripción generada automáticamente](media/77796ea35e7cacb1a8e1be551a9d11d4.jpeg)

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

![Diagrama Descripción generada automáticamente](media/a9510b546e66b211433e386d05e786be.jpeg)

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

![Diagrama Descripción generada automáticamente](media/83e4069b19988313d7abfb60600afcc0.png)

### Software Architecture Context Level Diagrams

Estos diagramas proporcionan una vista de alto nivel de las interacciones entre el sistema y sus entornos externos, como otros sistemas, usuarios.

![Diagrama Descripción generada automáticamente](media/3425e588cb7a2f13e277c741961a9bdb.png)

### Software Architecture Container Level Diagrams

Estos diagramas muestran la estructura interna del sistema, dividiéndolo en contenedores o módulos principales y describiendo las relaciones entre ellos. Ayudan a visualizar cómo se organiza el software en componentes lógicos y cómo se comunican entre sí.

![Diagrama Descripción generada automáticamente](media/f79f431d58a441b4b8a54dedf32845c0.png)

### Software Architecture Deployment Diagrams

Estos diagramas representan la configuración física del sistema, mostrando cómo se distribuyen los contenedores y sus instancias en diferentes nodos de hardware o entornos de ejecución.

![Interfaz de usuario gráfica Descripción generada automáticamente con confianza baja](media/b083affb6155b5203b7a589180585271.png)
