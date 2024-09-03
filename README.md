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


