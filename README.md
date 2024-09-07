![upc logo](images/upc_logo.png)

**Universidad Peruana de Ciencias Aplicadas**

**Ingeniería de Software \- Grupo 5 (WX51)**

**Desarrollo de Aplicaciones Open Source** 

# INFORME DEL TRABAJO FINAL

**Profesor:** Alberto Wilmer Sanchez Seña

**Startup:** Innova Source

**Grupo:** 5

**Producto:** Sabores Cercanos

**Integrantes:**

* **Maria Jose Pezo Castilla \- u20221c590**  
* **Max Anthony Paitan Pumacahua \- U201314454**  
* **Dalila Victoria Torres Sanchez \- U20221F734**  
* **Fiorella Angela Vilca Valverde \- U20211E417**  
* **Rafael Alberto Cuya Villegas \- u201913495**

*****
*****

# **TABLA DE CONTENIDOS**

**Carátula**

**Registro de Versiones del Informe**

**Project Report Collaboration Insights**

**Contenido**

**Tabla de contenidos**

**Student Outcome**

**Capítulo I: Introducción**

**1.1. Startup Profile**

**1.1.1. Descripción de la Startup**

**1.1.2. Perfiles de integrantes del equipo**

**1.2. Solution Profile**

**1.2.1 Antecedentes y problemática**

**1.2.2 Lean UX Process.**

**1.2.2.1. Lean UX Problem Statements.**

**1.2.2.2. Lean UX Assumptions.**

**1.2.2.3. Lean UX Hypothesis Statements.**

**1.2.2.4. Lean UX Canvas.**

**1.3. Segmentos objetivo.**

**Capítulo II: Requirements Elicitation & Analysis**

**2.1. Competidores.**

**2.1.1. Análisis competitivo.**

**2.1.2. Estrategias y tácticas frente a competidores.**

**2.2. Entrevistas.**

**2.2.1. Diseño de entrevistas.**

**2.2.2. Registro de entrevistas.**

**2.2.3. Análisis de entrevistas.**

**2.3. Needfinding.**

**2.3.1. User Personas.**

**2.3.2. User Task Matrix.**

**2.3.3. User Journey Mapping.**

**2.3.4. Empathy Mapping.**

**2.3.5. As-is Scenario Mapping.**

**2.4. Ubiquitous Language.**

**Capítulo III: Requirements Specification**

**3.1. To-Be Scenario Mapping.**

**3.2. User Stories.**

**3.3. Impact Mapping.**

**3.4. Product Backlog.**

**Capítulo IV: Product Design**

**4.1. Style Guidelines.**

**4.1.1. General Style Guidelines.**

**4.1.2. Web Style Guidelines.**

**4.2. Information Architecture.**

**4.2.1. Organization Systems.**

**4.2.2. Labeling Systems.**

**4.2.3. SEO Tags and Meta Tags**

**4.2.4. Searching Systems.**

**4.2.5. Navigation Systems.**

**4.3. Landing Page UI Design.**

**4.3.1. Landing Page Wireframe.**

**4.3.2. Landing Page Mock-up.**

**4.4. Web Applications UX/UI Design.**

**4.4.1. Web Applications Wireframes.**

**4.4.2. Web Applications Wireflow Diagrams.**

**4.4.2. Web Applications Mock-ups.**

**4.4.3. Web Applications User Flow Diagrams.**

**4.5. Web Applications Prototyping.**

**4.6. Domain-Driven Software Architecture.**

**4.6.1. Software Architecture Context Diagram.**

**4.6.2. Software Architecture Container Diagrams.**

**4.6.3. Software Architecture Components Diagrams.**

**4.7. Software Object-Oriented Design.**

**4.7.1. Class Diagrams.**

**4.7.2. Class Dictionary.**

**4.8. Database Design.**

**4.8.1. Database Diagram.**

**Capítulo V: Product Implementation, Validation & Deployment**

**5.1. Software Configuration Management.**

**5.1.1. Software Development Environment Configuration.**

**5.1.2. Source Code Management.**

**5.1.3. Source Code Style Guide & Conventions.**

**5.1.4. Software Deployment Configuration.**

**5.2. Landing Page, Services & Applications Implementation.**

**5.2.1. Sprint 1**

**5.2.1.1. Sprint Planning 1.**

**5.2.1.2. Sprint Backlog 1.**

**5.2.1.3. Development Evidence for Sprint Review.**

**5.2.1.4. Testing Suite Evidence for Sprint Review.**

**5.2.1.5. Execution Evidence for Sprint Review.**

**5.2.1.6. Services Documentation Evidence for Sprint Review.**

**5.2.1.7. Software Deployment Evidence for Sprint Review.**

**5.2.1.8. Team Collaboration Insights during Sprint.**

**5.3. Validation Interviews.**

**5.3.1. Diseño de Entrevistas.**

**5.3.2. Registro de Entrevistas.**

**5.3.3. Evaluaciones según heurísticas.**

**5.4. Video About-the-Product.**

**Conclusiones**

- **Conclusiones y recomendaciones.**  
- **Video About-the-Team.**

**Bibliografía**  
**Anexos**

*****
*****

# Capítulo 1: Introducción

## **1.1. Startup Profile**

El término Startup se utiliza para describir pequeñas y medianas empresas que ingresan al mercado con ideas vinculadas al mundo tecnológico, con notables perspectivas de desarrollo. Una Startup se distingue por ser un negocio escalable, con gran potencial de crecimiento y con una veloz y efectiva expansión. Por otro lado, las Startups surgen con la finalidad de resolver con claridad un problema social de gran relevancia, de una forma simple e innovadora.

### **1.1.1. Descripción de la Startup**

#### **Descripción de la empresa:**

"Sabores Cercanos" es una plataforma web diseñada para conectar a cocineros caseros con universitarios y profesionales que carecen de tiempo para cocinar. La plataforma permite a los cocineros ofrecer sus servicios de comida, incluyendo menús personalizados, precios, ubicaciones, y ofertas especiales. Los consumidores pueden buscar, seleccionar y pedir comida casera de cocineros locales, basándose en sus preferencias alimenticias y restricciones dietéticas. Además, "Sabores Cercanos" promueve una comunidad culinaria activa donde se pueden compartir y descubrir recetas, fomentando la interacción entre cocineros y consumidores.

La propuesta de valor de "Sabores Cercanos" se centra en proporcionar comida casera de calidad, personalizada y a precios asequibles, mientras que ofrece a los cocineros una vía para generar ingresos adicionales de forma flexible. A través de una interfaz intuitiva y procesos eficientes, "Sabores Cercanos" crea un ecosistema donde la pasión por la cocina y la necesidad de comidas prácticas y saludables se encuentran.

##### **Misión:**

La misión de "Sabores Cercanos" es transformar la forma en que las personas acceden a la comida casera, conectando a cocineros apasionados con consumidores que buscan opciones de alimentación saludable y conveniente. Aspiramos a empoderar a los cocineros caseros, brindándoles la oportunidad de monetizar sus habilidades culinarias, mientras mejoramos la calidad de vida de nuestros consumidores a través de alimentos nutritivos y sabrosos. Fomentamos una comunidad en la que compartir la pasión por la cocina se convierte en una experiencia enriquecedora para todos.

##### **Visión:**

Nuestra visión es ser la plataforma líder en conectar cocineros caseros y consumidores en América Latina, reconocida por ofrecer calidad, confianza y una experiencia gastronómica única. Queremos crear un movimiento que celebre la comida casera y las tradiciones culinarias locales, mientras promovemos estilos de vida saludables y sostenibles. Buscamos establecer un estándar en la economía colaborativa del sector alimentario, donde la comida casera se convierta en una opción accesible y preferida para todos, y donde cada cocinero tenga la oportunidad de compartir su talento y mejorar su vida.

### **1.1.2. Perfiles de integrantes del equipo**

####  Nombre: Cuya Villegas, Rafael Alberto | U201913495

> Soy Rafael Cuya de la carrera de Ingeniería de Software, soy una persona responsable y perseverante, me gusta hacer deporte en especial jugar fútbol.
>
> [Imagen]

---

## **1.2. Solution Profile**

### **1.2.1 Antecedentes y problemática**

En el siguiente apartado, nos encargamos de investigar en detalle el problema en sí mismo. El objetivo es determinar las causas del problema que se deben abordar.

**What?**

* ¿Qué problema hay?  
  Muchas personas, especialmente universitarios y profesionales, no tienen tiempo para cocinar debido a sus horarios ocupados. Esto los lleva a depender de comida rápida o de baja calidad, afectando su salud y bienestar. Por otro lado, hay muchas personas que disfrutan cocinar y buscan una manera de generar ingresos adicionales desde casa, monetizando su habilidad culinaria sin tener que invertir en un restaurante completo o un negocio de catering.

**When?**

* ¿Cuándo sucede el problema?  
  El problema es continuo. Ocurre diariamente cuando los consumidores enfrentan la necesidad de comer mientras equilibran otras responsabilidades, como el trabajo o los estudios. El problema se intensifica durante las horas pico de almuerzo y cena, cuando el tiempo es limitado.  
* ¿Cuándo el cliente necesita el programa?  
  Los consumidores necesitan la plataforma durante sus horarios de comida, especialmente durante el almuerzo y la cena. Los cocineros necesitan la plataforma para poder planificar y gestionar sus servicios de manera eficiente, incluyendo la publicación de menús y la preparación de pedidos.

**Where?**

* ¿Dónde el cliente usara el producto?  
  La aplicación se usará principalmente en entornos urbanos, donde hay una alta concentración de profesionales y estudiantes. Los consumidores usarán la aplicación desde sus teléfonos móviles o computadoras para hacer pedidos mientras están en casa, en la oficina o en el campus.


**Why?**

* Debido a la necesidad de ofrecer una solución que conecte a personas que valoran la comida casera con cocineros que desean generar ingresos adicionales. Los consumidores buscan opciones de comida que se adapten a sus preferencias y restricciones alimenticias, mientras que los cocineros buscan una plataforma que les permita monetizar su pasión de manera flexible y accesible. Este problema afecta tanto a la salud de los consumidores como a la economía de los cocineros caseros, quienes podrían beneficiarse de una fuente adicional de ingresos.

**Who?**

* *Consumidores:* Universitarios y profesionales que no tienen tiempo para cocinar pero desean opciones saludables y personalizadas.  
* *Proveedores:* Cocineros caseros que buscan una manera de monetizar su habilidad culinaria y generar ingresos adicionales desde sus hogares.

**How?**

* "Sabores Cercanos" propone una plataforma web que conecta a cocineros caseros con consumidores que buscan opciones de comida casera y personalizada. Esto permite a los cocineros caseros ofrecer sus servicios de comida directamente a los consumidores, quienes pueden buscar, seleccionar y personalizar sus pedidos de manera fácil y eficiente. La plataforma también fomenta una comunidad activa donde se comparten recetas y se promueve la interacción culinaria.

Los principales puntos del funcionamiento son:

* Registro y Perfil del Usuario: Cocineros y consumidores se registran y crean perfiles detallados que facilitan la oferta y búsqueda de servicios.  
* Publicación y Gestión de Servicios de Comida: Los cocineros publican menús, precios y promociones, con opciones para personalizar según las necesidades dietéticas de los usuarios.  
* Búsqueda y Selección de Servicios: Los consumidores utilizan filtros avanzados para encontrar opciones que se ajusten a sus preferencias y ubicación.  
* Pedidos y Personalización: Los consumidores realizan pedidos personalizados con especificación de fecha y hora de entrega o recogida.  
* Pagos y Gestión de Pedidos: La plataforma procesa pagos y gestiona el estado de los pedidos, asegurando un servicio eficiente.  
* Entrega o Recogida: Dependiendo del acuerdo, los cocineros entregan la comida o los consumidores la recogen, con opciones de rastreo en tiempo real.  
* Sistema de Revisión y Feedback: Consumidores y cocineros pueden dejar reseñas y calificaciones para mejorar la calidad del servicio.  
* Recetas de Cocina y Comunidad: Los cocineros pueden compartir recetas, creando una comunidad culinaria activa que enriquece la experiencia del usuario.

**How much?**

* Los costos para los cocineros caseros incluyen los insumos para preparar las comidas y una comisión por transacción que cobra la plataforma. Para los consumidores, los costos están relacionados con el precio de los menús seleccionados, que se establecen de manera competitiva para asegurar que sean accesibles en comparación con otras opciones de comida rápida o a domicilio.

### **1.2.2 Lean UX Process.**  
	  
#### **1.2.2.1. Lean UX Problem Statements.**  
	  
Sabores Cercanos es una plataforma web diseñada para conectar a cocineros caseros con universitarios y profesionales que carecen de tiempo para cocinar. La propuesta de valor se centra en proporcionar comida casera de calidad, personalizada y a precios accesibles, al mismo tiempo que ofrece a los cocineros una oportunidad de generar ingresos adicionales de forma flexible.

Hemos observado un factor crítico que afecta a los universitarios y profesionales ocupados y cocineros caseros.

**Problema:**  
La falta de acceso a opciones de comida casera y saludable afecta la calidad de vida de universitarios y profesionales ocupados, quienes a menudo dependen de opciones rápidas y menos nutritivas debido a sus limitados horarios. Al mismo tiempo, muchos cocineros caseros no tienen una manera efectiva de monetizar sus habilidades culinarias sin tener que invertir en un restaurante o negocio de catering.

**Pregunta central:**  
¿Cómo podemos mejorar la accesibilidad a comida casera y personalizada para los consumidores, al mismo tiempo que facilitamos a los cocineros caseros la monetización de sus habilidades culinarias de manera eficiente y flexible?

#### **1.2.2.2. Lean UX Assumptions.**

**Business Outcomes**

* Incremento en la cantidad de cocineros caseros registrados en la plataforma.  
* Aumento en el número de pedidos diarios realizados a través de la plataforma.  
* Mejora en la retención y satisfacción tanto de cocineros como de consumidores, reflejada en altas calificaciones y feedback positivo.  
* Generación de ingresos estables a través de comisiones por transacción y el establecimiento de suscripciones premium.

**User Benefits**

* Para los consumidores: Acceso a comida casera de calidad, adaptada a sus preferencias dietéticas, y la conveniencia de recibirla en su hogar o recogerla.  
* Para los cocineros: Una manera accesible y flexible de monetizar sus habilidades culinarias sin necesidad de grandes inversiones.  
* Creación de una comunidad culinaria donde se comparten y descubren recetas, enriqueciendo la experiencia de los usuarios.

**User & Customers**

1. *¿Quién(es) es el usuario?*  
* Cocineros caseros (amateur) que desean generar ingresos adicionales ofreciendo sus servicios de comida.  
* Universitarios y profesionales ocupados que buscan opciones de comida casera y saludable.  
2. *¿Dónde encaja nuestro producto en su trabajo o vida?*  
* Para los consumidores, encaja en sus rutinas diarias, especialmente durante horarios de comida como almuerzos y cenas, cuando necesitan opciones rápidas, saludables y convenientes.  
* Para los cocineros, encaja como una oportunidad para generar ingresos desde casa en horarios flexibles, permitiéndoles seguir su pasión por la cocina.  
3. *¿Qué problemas tiene nuestro producto que resolver?*  
* La falta de tiempo y acceso a comida saludable para consumidores ocupados.  
* La falta de oportunidades accesibles para que los cocineros caseros moneticen sus habilidades sin grandes inversiones.  
4. *¿Cuándo y cómo es nuestro producto usado?*  
* El producto es usado diariamente por los consumidores para pedir comida, especialmente durante horas de almuerzo y cena.  
* Los cocineros usan la plataforma para gestionar sus menús, pedidos y entregas en cualquier momento del día, según su disponibilidad.  
5. *¿Qué características son importantes?*  
* Registro y creación de perfiles detallados para cocineros y consumidores.  
* Publicación y gestión de menús, incluyendo personalización según necesidades dietéticas.  
* Búsqueda avanzada y filtros para los consumidores.  
* Sistema de pagos seguro y eficiente.  
* Sistema de calificaciones y feedback para mejorar la experiencia de usuario.  
6. *¿Cómo debe verse nuestro producto y cómo debe comportarse?*  
* El producto debe tener una interfaz intuitiva y atractiva, fácil de navegar tanto para cocineros como para consumidores.  
* Debe comportarse de manera rápida y responsiva, permitiendo a los usuarios completar sus tareas sin fricciones.  
* Debe ser confiable y seguro, especialmente en el manejo de pagos y datos personales.

**¿Qué es lo que brinda mi producto?**  
1.	Creemos que nuestros clientes necesitan:

* Los consumidores necesitan acceso a opciones de comida saludable y personalizada de manera conveniente.  
* Los cocineros necesitan una plataforma que les permita monetizar su pasión por la cocina de forma accesible y flexible.

2.	Estas necesidades se pueden resolver con:

* Una plataforma web que conecte a cocineros caseros con los consumidores, facilitando la búsqueda, pedido y entrega de comida casera.

3.	Nuestros clientes son o serán:

* Universitarios y profesionales ocupados que valoran la comida saludable pero no tienen tiempo para cocinar.  
* Cocineros caseros que desean generar ingresos adicionales ofreciendo sus servicios de comida.

4.	El valor \#1 que un cliente quiere de nuestro servicio es:

* Para los consumidores: Comida casera de calidad y personalizada, disponible de manera rápida y conveniente.  
* Para los cocineros: Una oportunidad para monetizar sus habilidades culinarias sin complicaciones.

5.	El cliente también puede obtener estos beneficios adicionales:

* Participación en una comunidad culinaria activa donde pueden descubrir y compartir recetas.  
* Para los cocineros, la posibilidad de construir una reputación y expandir su base de clientes a través de buenas calificaciones y feedback.

6.	Vamos a adquirir la mayoría de mis clientes a través de:

* Marketing digital dirigido a universitarios y profesionales, utilizando redes sociales, anuncios en línea y colaboraciones con influencers culinarios.  
* Para los cocineros, mediante campañas que resalten la oportunidad de generar ingresos adicionales desde casa.

7.	Haremos dinero a través de:

* Comisiones por transacción en cada pedido realizado a través de la plataforma.  
* Posibles suscripciones premium para acceso a características avanzadas o exclusivas.  
* Posibilidad de mostrar publicidad relacionada con el giro comercial de negocio

8.	Nuestra competencia principal en el mercado será:

* Servicios de entrega de comida como UberEats o Rappi, que ofrecen opciones rápidas aunque menos personalizadas y caseras.  
* Empresas de comida como Manzana Verde o LifeCafé.  
* Otros marketplaces de comida casera que puedan surgir.

9.	Los venceremos debido a:

* Un enfoque en comida casera de alta calidad y personalizada, además de una fuerte comunidad culinaria que fomente la interacción y el intercambio de recetas.

10.	Nuestro mayor riesgo de producto es...

* La falta de adopción de la plataforma por parte de cocineros caseros debido a posibles barreras tecnológicas o falta de confianza en la monetización.

11.	Resolveremos esto a través de:

* Proporcionando tutoriales y soporte técnico fácil de entender para cocineros.  
* Ofreciendo incentivos y testimonios de éxito que demuestren la viabilidad de generar ingresos a través de la plataforma.

12.	¿Qué otras suposiciones tenemos? Eso, si se prueba que es falso, causará que nuestro negocio/proyecto no funcione?

* Suponemos que hay una demanda significativa de comida casera personalizada entre universitarios y profesionales ocupados. Si esta demanda es menor de lo esperado, el modelo de negocio podría no ser viable.  
* Suponemos que los cocineros caseros estarán dispuestos a adoptar la tecnología necesaria para operar en la plataforma. Si esto no es cierto, la oferta de servicios podría ser insuficiente para atraer a los consumidores.

#### **1.2.2.3. Lean UX Hypothesis Statements.**

**Hypothesis 1:**

Creemos que mejorar la visibilidad de las promociones especiales dentro de la plataforma atraerá a más usuarios a realizar pedidos con mayor frecuencia.  
Sabremos que estamos bien cuando veamos un aumento del 15% en la cantidad de pedidos realizados durante las 4 primeras semanas en las que se publican promociones especiales.

**Hypothesis 2:**

Creemos que agregar un sistema de reseñas y calificaciones mejorará la confianza de los consumidores en la calidad de la comida y aumentará la tasa de retención de usuarios.  
Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado: Feedback positivo sobre la utilidad de las reseñas y un aumento en la tasa de retención de usuarios del 20%.

**Hypothesis 3:**

Creemos que ofrecer recetas exclusivas y contenido premium para suscriptores motivará a los cocineros y usuarios a suscribirse al servicio premium.  
Sabremos que estamos bien cuando veamos un incremento del 10% en las suscripciones al contenido premium durante el primer mes de lanzamiento.

**Hypothesis 4:**

Creemos que simplificar el proceso de registro y publicación de menús para los cocineros caseros aumentará la cantidad de cocineros activos en la plataforma.  
Sabremos que estamos bien cuando veamos un incremento del 25% en el número de cocineros que publican sus menús dentro del primer mes después de la implementación de estas mejoras.

**Hypothesis 5:**

Creemos que implementar un sistema de notificaciones personalizadas que informe a los usuarios sobre nuevas ofertas o menús cercanos aumentará la frecuencia de uso de la plataforma.  
Sabremos que estamos bien cuando veamos un aumento del 20% en la cantidad de usuarios activos diarios en la plataforma después de la implementación del sistema de notificaciones.

#### **1.2.2.4. Lean UX Canvas.**

| LEAN UX CANVAS |  |  |
| :---- | :---- | :---- |
| **Business problem** | **Solution Ideas** | **Business Outcomes** |
| Universitarios y profesionales ocupados no tienen tiempo para cocinar, lo que los lleva a depender de comida rápida o de baja calidad, afectando su salud. Por otro lado, cocineros caseros buscan monetizar sus habilidades culinarias sin necesidad de grandes inversiones. ¿Cómo podemos mejorar la accesibilidad a comida casera y personalizada para los consumidores, al mismo tiempo que facilitamos a los cocineros caseros la monetización de sus habilidades culinarias de manera eficiente y flexible? | - Desarrollo de una plataforma web que conecte cocineros caseros con consumidores que buscan comida casera. <br> - Funcionalidades como registro y perfil de usuarios, publicación de menús, búsqueda avanzada, personalización de pedidos, sistema de pagos seguro, y sistema de calificaciones y reseñas. <br> - Implementación de una sección para compartir y descubrir recetas de cocina dentro de la plataforma. Los cocineros pueden publicar sus recetas favoritas, permitiendo a los usuarios replicarlas en casa. Los usuarios pueden guardar sus recetas preferidas, recibir notificaciones de nuevas publicaciones, y participar en una comunidad culinaria activa | <br> - Incremento en la cantidad de cocineros caseros registrados en la plataforma. <br> - Aumento en el número de pedidos diarios realizados a través de la plataforma. <br> - Mejora en la retención y satisfacción tanto de cocineros como de consumidores, reflejada en altas calificaciones y feedback positivo. <br> - Generación de ingresos estables a través de comisiones por transacción y posibles suscripciones premium. |
| **Users & Customers** |  | **User Benefits** |
| **- Cocineros Caseros:** Personas que desean generar ingresos adicionales ofreciendo sus servicios de comida casera desde sus hogares. <br> **- Universitarios y Profesionales Ocupados:** Personas que buscan opciones de comida casera y saludable debido a su falta de tiempo para cocinar. |  | **- Para los Consumidores:** Acceso a comida casera de calidad, personalizada según sus preferencias dietéticas, y la conveniencia de recibirla en su hogar o recogerla. <br> **- Para los Cocineros:** Una manera accesible y flexible de monetizar sus habilidades culinarias sin necesidad de grandes inversiones. <br> - Creación de una comunidad culinaria donde se comparten y descubren recetas, enriqueciendo la experiencia de los usuarios. |
| **Hypothesis** | **What’s the most important thing we need to learn first** | **What’s the least amount of work we need to do learn the next most important thing** |
| **Hypothesis 1:**  Creemos que mejorar la visibilidad de las promociones especiales dentro de la plataforma atraerá a más usuarios a realizar pedidos con mayor frecuencia. Un aumento del 15% en la cantidad de pedidos realizados durante las primeras 4 semanas en las que se publican promociones especiales. <br> **Hypothesis 2:**  Creemos que agregar un sistema de reseñas y calificaciones mejorará la confianza de los consumidores en la calidad de la comida y aumentará la tasa de retención de usuarios. Un aumento en la tasa de retención de usuarios del 20% y feedback positivo sobre la utilidad de las reseñas. <br> **Hypothesis 3:**  Creemos que simplificar el proceso de registro y publicación de menús para los cocineros caseros aumentará la cantidad de cocineros activos en la plataforma. Un incremento del 25% en el número de cocineros que publican sus menús dentro del primer mes. | Conocer los patrones de comportamiento de los consumidores en relación a la demanda de comida casera. Identificar barreras potenciales que impidan que los cocineros caseros adopten la tecnología de la plataforma. | Realizar entrevistas con cocineros caseros y consumidores potenciales. Crear y probar prototipos de la plataforma con usuarios reales para validar hipótesis clave. |

## **1.3. Segmentos objetivo.**

### **Segmento Objetivo \#1: Universitarios y Profesionales Ocupados** 

Este segmento está compuesto por jóvenes de entre 20 y 40 años que residen en grandes ciudades y centros universitarios de América Latina. Representan alrededor del 60% de los usuarios de la plataforma. Son estudiantes universitarios o profesionales que, debido a sus ocupadas agendas, tienen poco tiempo para cocinar, lo que los lleva a buscar opciones de comida saludable y casera. Valoran la conveniencia y la posibilidad de personalizar sus pedidos según sus preferencias dietéticas. Este grupo prefiere opciones rápidas y asequibles, utilizando la plataforma para recibir comida en sus hogares o lugares de trabajo.

### **Segmento Objetivo \#2: Cocineros Caseros**

Este segmento incluye personas, generalmente entre 30 y 50 años, que viven en áreas urbanas y suburbanas de América Latina. Son apasionados de la cocina y buscan monetizar sus habilidades culinarias sin las complejidades de un restaurante formal. Representan aproximadamente el 40% de los usuarios de la plataforma "Sabores Cercanos". Estos cocineros, que en su mayoría son mujeres, están interesados en ofrecer comida casera de calidad y disfrutan compartiendo sus recetas con una comunidad más amplia. Buscan una fuente de ingresos adicional y flexible, que les permita trabajar desde casa y administrar su propio tiempo.