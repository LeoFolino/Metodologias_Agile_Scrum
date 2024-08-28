## Índice

1. [Organizaciones Tradicionales y Agiles](#organizaciones-tradicionales-y-agiles)  
     - [Organizaciones Tradicionales](#organizaciones-tradicionales)  
       - [Ventajas Del Modelo Tradicional](#ventajas-del-modelo-tradicional)  
       - [Desventajas del modelo tradicional](#desventajas-del-modelo-tradicional)  
     - [Organizaciones Agiles](#organizaciones-agiles)  
       - [Ventajas del modelo Agil](#ventajas-del-modelo-agil)  
       - [Desventajas del modelo Agil](#desventajas-del-modelo-agil)  
  - [Comparacion entre ambas metodologias](#comparacion-entre-ambas-metodologias)  
  
  
2. [Evolucion de metodos de desarrollo de software](#evolucion-de-metodos-de-desarrollo-de-software)  
   - [La crisis del software](#la-crisis-del-software)  
   - [Metodologias tradicionales](#metodologias-tradicionales)  
   - [Metodologias Agiles](#metodologias-agiles)  
     - [Aspectos claves de las Metodologias Agiles](#aspectos-claves-de-las-metodologias-agiles)  
     - [Que modelo es el que mas conviene?](#que-modelo-es-el-que-mas-conviene)  
        - [Comparacion entre Metodos Tradicionales y Metodos Agiles](#comparacion-entre-metodos-tradicionales-y-metodos-agiles)  
      - [Valores y Principios de la Agilidad](#valores-y-principios-de-la-agilidad)  
        - [Valores Agiles](#valores-agiles)  
        - [El Manifiesto Agil](#el-manifiesto-agil)  
        - [Principios Agiles](#principios-agiles)  
  - [Reflexion](#reflexiones)  

3. [Cultura Agil](#cultura-agil)  
   - [Caracteristicas de Cultura Agil](#caracteristicas-de-cultura-agil)  
   - [Diferencia entre Agilidad y Velocidad](#diferencia-entre-agilidad-y-velocidad)  
   - [Resultados de las organizaciones agiles](#resultados-de-las-organizaciones-agiles)  
   - [Introduccion a las metodologias agiles](#introduiccion-a-las-metodologias-agiles)
     - [Herramientas de planificacion y seguimiento](#herramientas-de-planificacion-y-seguimiento)
     - [Herramientas de comunicacion y colaboracion](#herramientas-de-comunicacion-y-colaboracion)
     - [Herramientas de integracion y despliegue continuo](#herramientas-de-integracion-y-despliegue-continuo)
     - [Herramientas de monitoreo y feedback](#herramientas-de-monitoreo-y-feedback)
   - [Reflexion](#reflexion)  

4. [Marcos de Trabajo Agiles](#marcos-de-trabajo-agiles)  
   - [Lean](#lean)  
     - [Introduccion](#introduccion-a-lean)  
     - [Los 5 principios de Lean en el desarrollo de software](#los-5-principios-de-lean-en-el-desarrollo-de-software)  
     - [Desafios y criticas a Lean y Agile](#desafios-y-criticas-a-lean-y-agile)  
     - [Caso de estudio: Lean en el desarrollo de software](#caso-de-estudio-lean-en-el-desarrollo-de-software)
     - [Lean Startup](#lean-startup)  
       - [Enfoque en el cliente](#enfoque-en-el-cliente)  
       - [Desarrollo iterativo](#desarrollo-iterativo)  
       - [Validacion de Hipotesis](#validacion-de-hipotesis)  
       - [Producto minimo viable (MVP)](#producto-minimo-viable-mvp)  
       - [Aprendizaje Validado](#aprendizaje-validado)  
       - [Pivotar o Preservar](#pivotar-o-preservar)  
     - [Desafios la implementacion de Lean Startup](#desafios-la-implementacion-de-lean-startup)  
     - [Ventajas en adoptar Lean Startup](#ventajas-en-adoptar-lean-startup)  
     - [Diferencias con enfoques tradicionales](#diferencias-de-lean-startup-con-enfoques-tradicionales)  
   - [Kanban](#kanban)  
     - [Introduccion a Kanban](#introduccion-a-kanban)  
       - [Principios clave de Kanban](#principios-clave-de-kanban)  
       - [Ventajas de Kanban](#ventajas-de-kanban)  
       - [Desventajas de Kanban](#desventajas-de-kanban)  
     - [WIP, DOR y DOD](#wip-dor-y-dod)  
       - [Work In Progress (WIP)](#work-in-progress-wip)  
       - [Definition Of Ready (DOR)](#definition-of-ready-dor)  
       - [Definition Of Done (DOD)](#definition-of-done-dod)  
       - [Implementacion de WIP, DOR y DOD](#implementacion-de-wip-dor-y-dod)  
       - [Beneficios de implementar WIP, DOR y DOD](#beneficios-de-implementar-wip-dor-y-dod)  
     - [Herramientas de Tablero Kanban](#herramientas-de-tablero-kanban)  
       - [Columnas del Tablero Kanban](#columnas-del-tablero-kanban)  
       - [Tablero Digital Kanban](#tablero-digital-kanban)  
   - [Scrum](#scrum)  
     - [La Guia de Scrum](#la-guia-de-scrum)  
     - [Valores (Scrum)](#valores-scrum)  
     - [Pilares de Scrum](#pilares-de-scrum)  
     - [Los Roles en Scrum](#los-roles-en-scrum)  
       - [Scrum Master](#scrum-master)  
       - [Product Owner](#product-owner)  
       - [Equipo de Desarrollo](#equipo-de-desarrollo)  
     - [Integracion de los Roles en Scrum](#integracion-de-los-roles-en-scrum)  
     - [Los Eventos en Scrum](#los-eventos-en-scrum).  
       - [Sprint](#sprint)  
       - [Sprint Planning](#sprint-planning)  
       - [Daily Scrum](#daily-scrum)  
       - [Sprint Review](#sprint-review)  
       - [Sprint Retrospective](#sprint-retrospective)  
     - [Los Artefactos en Scrum](#los-artefactos-en-scrum)  
       - [Product Backlog](#product-backlog)  
       - [Sprint Backlog](#sprint-backlog)  
       - [Incremento](#incremento)  
  
5. [User Stories](#user-stories)
   - [Definicion y caracteristicas de las User Stories]
   - [Diferencia entrre requerimientos tradicionales y User Stories]
   - [Caso de Aplicacion]
   - [Criterios de Aceptacion]
   - [Como definir criterios de aceptacion de calidad]
   - [Roadmap & User Story Mapping]
   - [El Roadmap]
   - [El User Story Mapping]

# Organizaciones Tradicionales y Agiles
### Organizaciones Tradicionales:

![EsquemaDeOrganizacionTradicional](/capturas/1.jpg)

SE HACE LO QUE DICE EL JEFE

#### Ventajas del modelo tradicional
- Estructura clara y procesos definidos
- Estructura jerarquica
- Direccion y control

#### Desventajas del modelo tradicional
- Estructura rigida
- Obstaculo para la innovacion y adaptabilidad

[Volver al índice](#índice)

### Organizaciones Agiles

![EsquemaDeOrganizacionAgil](/capturas/2.jpg)

Estructura plana, con menos niveles jerarquicos y mas redes de equipos interconectados

#### Ventajas del modelo Agil
- Rapida adaptacion
- Estructura flexible
- Toma de decisiones descentralizada

#### Desventajas del modelo Agil
- Dificultad para instaurar una vision de equipo
- Falta de procesos definidos

## Comparacion entre ambas metodologias:

_Las organizaciones tradicionales son preferidas en entornos estables y predecibles donde la eficiencia es critica.
En cambio las organizaciones agiles son preferidas ante entornos dinamicos y cambiantes._

>"Las organizaciones no se transforman, son las personas que se transforman para cambiar las organizaciones"  

[Volver al índice](#índice)  

---

# Evolucion de metodos de desarrollo de software

#### La crisis del software
- Retrasos
- Presupuestos mal calculados
- Entregas incompletas
- Usuarios y clientes insatisfechos

Durante los 60 se presento la **crisis del software**. *En respuesta a esta crisis, surgen:*
- Nuevas metodologias de desarrollo
- Herramientas y tecnicas
- Desarrollo de software estructurado
- Programacion orientada a objetos (POO)
- Metodologias agiles
- Educacion y formacion para proveer mayor personal calificado

[Volver al índice](#índice)

## Metodologias tradicionales

- ### Modelo en Cascada:
  #### Estructura lineal y secuencial:
  - Secuencialidad
  - Documentacion extensa
  - Poca flexibilidad
  - Previsibilidad
  - Facil de entender

![ModeloCascada](/capturas/3.jpg)
  1.  Requerimientos
  2.  Diseño
  3.  Desarrollo
  4.  Pruebas
  5.  Implementacion
  6.  Mantenimiento

[Volver al índice](#índice)

- ### Metodologias Agiles:
  #### Conjunto de practicas de desarrollo de software que priorizan la flexibilidad y entrega continua de valor
  - Scrum(Divide el desarrollo en sprints o iteraciones cortas)
  - Kanban(Centrado en el flujo y limitacion de trabajo en progreso)
  - Lean(Eliminar desperdicios y entregar valor de manera eficiente)

#### Aspectos claves de las Metodologias Agiles:
  - Flexibilidad y adaptabilidad
  - Colaboracion
  - Entrega continua de valor
  - Iteracciones
  - Descentralizacion de la toma de decisiones
  - Feedback y mejora continua
  
## Que modelo es el que mas conviene?
*Aspectos a considerar: Depende de*
- Cuan estable y cambiante son los requisitos
- Las caracteristicas del equipo
- Disponibilidad de las partes interesadas
- Importancia que se le de a las entregas tempranas

## Comparacion entre Metodos Tradicionales y Metodos Agiles:
*Los metodos tradicionales buscan definir todo desde el principio no dando lugar a cambios, mientras que los metodos agiles aceptan el cambio y promueven una evolucion continua*

![AlineacionDeRasgosDeProyectosYMetodologias](/capturas/5.jpg)
![AlineacionDeRasgosDeProyectosYMetodologias2](/capturas/6.jpg)

[Volver al índice](#índice)

# Valores y Principios de la Agilidad:

### Valores Agiles:
El manifiesto Agil (Creado en 2001) fue elaborado por un grupo de expertos en desarrollo de software con el fin de discutir el enfoque de gestion mas adaptable y enfocado en las personas. **Centrado en las realidades cambiantes del entorno y reconocer que la flexibilidad, la comunicacion y colaboracion son las claves para el exito**
Estos valores no solo ofrecen una guia para la creacion de software, sino que tambien **apunta a un cambio cultural en las organizaciones**, reflejan un cambio a una mayor agilidad en todas las areas de una empresa.

#### El Manifiesto Agil:
1. Individuos e interacciones sobre procesos y herramientas. (Resalta la importancia de las personas y sus interacciones en el equipo. En lugar de depender estrictamente de un software de gestion de proyectos, se fomenta la comunicacion directa, reuniones y sesiones de trabajo colaborativo. Esto no significa descartar las herramientas, sino usarla como apoyo para las interacciones humanas).
2. Software funcional sobre documentacion exhaustiva. (El enfoque esta en producir software que funcione y aporte valor real en lugar dedicar esfuerzo excesivo a la documentacion detallada que luego queda desactualizada)
3. Colaboracion con el cliente sobre negociacion de contratos. (Prioriza trabajar mano a mano con el cliente. Ej: Equipo de desarrollo en constante contacto con el cliente presentando el progreso para asi alinear cambios, correcciones y ajustes del proyecto.)
4. Responder al cambio sobre seguir un plan.(Fomenta la adaptabilidad y capacidad de responder a cambios inesperados.)

### Principios Agiles:
>Van a ofrecer una guia practica para implementar valores. Tienen en cuenta la entrega continua y adaptabilidad hasta la importancia en la comunicacion y mejora continua.
   1. Satisfacer al cliente mediante entregas tempranas y continuas de software valioso. (Centrarse en comprender y satisfacer las necesidades del cliente por medio de entregas frecuentes [versiones menores])
   2. Bienvenidos los cambios en los requisitos, incluso en etapas tardias de desarrollo.
   3. Entregar software funcionando frecuentemente entre dos semanas a dos meses. (Crear un ciclo de feedback corto)
   4. Los profesionales del negocio y los desarrolladores deben trabajar juntos diariamente a lo largo del proyecto. (Hace foco en la comunicacion entre los equipos)
   5. Construir proyectos alrededor de individuos motivados, dandoles el entorno y apoyo que necesitan. (Se enfoca en el capital humano como el punto mas alto)
   6. El metodo mas eficiente y efectivo de transmitir informacion es la conversacion cara a cara. (Enfoca en que la comunicacion directa construye un equipo mas conectado y agil para llegar a un consenso)
   7. Software funcionando como la principal medida de progreso. (Que cada incremento de software añada un incremento de valor para el usuario)
   8. Los procesos agiles promueben un desarrollo sostenible. (Equilibrio entre la vida laboral y personal)
   9. La atencion continua a la excelencia tecnica y al buen diseño mejora la agilidad. (Equipo buscando mejor calidad de codigo, bien documentado y construido con practicas solidas)
   10. La simplicidad es esencial. (Destaca la importancia de la eficiencia descartando trabajo innecesario)
   11. Los mejores arquitectos, requisitos, y diseños emergen de equipos auto-organizados. (Se reconoce el valor de la autonomia y auto-organizacion del equipo)
   12. A intervalos regulares, el equipo reflexiona sobre como ser mas efectivo y ajusta su comportamiento en consecuencia. (La mejora continaua es el nucleo de este principio)

## Reflexiones:
  >Adoptar la agilidad es mas que seguir reglas, es transformar nuestra forma de trabajar y pensar, fomentando la adaptabilidad, colaboracion , entrega, reflexion y mejora continua.

[Volver al índice](#índice)

---
## Cultura Agil:

>Una cultura agil no se limita solo a una serie de practicas o metodos, cuando hablamos de una cultura agil nos referimos a una filosofia que se encuentra en cada aspecto y area de una organizacion.
>Una cultura agil se caracteriza por poner enfgasis en la flexibilidad y adaptacion, las interacciones humanas, la comunicacion y la colaboracion.

### Caracteristicas de Cultura Agil:
  1. Flexibilidad y adaptabilidad.
  2. Colaboracion y comunicacion.
  3. Empoderamiento y autonomia del equipo.
  4. Iteraciones y mejora continua.
  5. Foco en el cliente.

### Diferencia entre Agilidad y Velocidad:
![EsquemaVelozAgil](/capturas/7.jpg)
>Ser agil no es ser rapido. Mientras la velocidad aplica a cuan rapido se puede finalizar el proyecto, la agilidad es la velocidad en la que finalizamos el proyecto sumado a la flexibilidad que tiene el equipo de adaptarse a todos los obstaculos y cambios que se generen en el transcurso del mismo. Ej: Una empresa que actualiza su software en base a las tendencias actuales, es una empresa que demuestra agilidad.

### Resultados de las organizaciones agiles:
  1. Mayor satisfaccion del cliente.
  2. Mejora en la calidad del producto.
  3. Eficiencia operativa mejorada.
  4. Mayor motivacion y satisfaccion del equipo.

>La cultura agil trasciende metodos y herramientas. Es un viaje hacia la excelencia operativa, la innovacion continua y el exito compartido.

[Volver al índice](#índice)

## Introduiccion a las metodologias agiles  

Las herramientas ágiles facilitan:
  - La planificación y seguimiento de proyectos.
  - Refuerzan los principios de colaboración, transparencia y adaptabilidad.
  - Y maximizan la eficiencia y efectividad del trabajo del equipo.

#### Herramientas de planificacion y seguimiento:  
  
>Es software o sistemas diseñados para ayudar en la organización, programación, y seguimiento del progreso de proyectos o tareas. Algunas de las herramientas más populares para la gestión de proyectos ágiles son JIRA y Trello  
![JiraTrello](/capturas/8.jpg)  

#### Herramientas de comunicacion y colaboracion:  
  
>Las herramientas de comunicación y colaboración son plataformas y software diseñados para facilitar la interacción, el trabajo en equipo y el intercambio de información entre individuos y grupos. Como por ejemplo Microsoft Teams y Slack
![TeamSlack](/capturas/9.jpg)  

#### Herramientas de integracion y despliegue continuo:  
  
>Las herramientas integración y despliegue continuo son fundamentales en el desarrollo de software moderno. Permitiendo automatizar partes del proceso de desarrollo para mejorar la eficiencia, calidad y velocidad de entrega. Algunas de las herramientas más populares en este ámbito son Jenkins y Git
![JenkinsGitHub](/capturas/10.jpg)  

#### Herramientas de monitoreo y feedback:  
  
>Las herramientas de monitoreo y retroalimentación son esenciales para la gestión de proyectos. Estas herramientas ayudan a las organizaciones y a los equipos a rastrear el rendimiento, obtener información valiosa y mejorar continuamente sus procesos y productos.

### Reflexion:
> Las herramientas ágiles potencian los marcos de trabajo, transformando la colaboración, eficiencia y transparencia en pilares de un cultura ágil efectiva.  
  
[Volver al índice](#índice)
  
---
  
# Marcos de Trabajo Agiles:  
  
## Lean  

#### Introduccion a Lean:  
El metodo lean con origen en la manufactura se adapto con exito al ambito del desarrollo de software permitiendo gestionar proyectos agiles y crear sistemas eficientes y centrados en el usuario, impulsando innovaciones y mejoras continuas

Parte del desarrollo de sistema de Toyota:
![lean](/capturas/11.jpg)  
  
Los principios de lean se convirtieron en una fuente de inspiracion para poder afrontar los desafios en el desarrollo de software.
  - Just in time
  - Mejora contina y adaptabilidad
  - Eficiencia del equipo
  - Eliminacion de desperdicios
  - Entregar valor al cliente

#### Los 5 principios de Lean en el desarrollo de software:

![11](/capturas/12.jpg)

#### Desafios y criticas a Lean y Agile

![#](/capturas/13.jpg)

### Caso de estudio: Lean en el desarrollo de software

>Esta historia trata sobre la empresa SoftTech que sufre retrasos en entregas, presupuestos sobrepasados y desconexion entre lo que producia el equipo y lo que el cliente necesita  
>Lo primero que realizaron a traves de encuestas, reuniones de feedback y analisis de datos, comprendieron que es lo que el cliente queria o necesitaba  
>Lo siguiente fue el mapeo de la cadena de valor, desgloso su proceso de desarrollo de software en etapas individuales para detectar cuales son las etapas que no agregaban valor. Al eliminar o simplificar estas etapas lograron acortar los tiempos.  
>Crearon un flujo continuo de software, CI-CD.  
>Implementaron el sistema pull. En lugar de tener un plan rigido, empezaron a trabajar en etapas mas cortas y recolectar rapidamente informacion de los clientes.  

[Volver al índice](#índice)

### Lean Startup

Lean Startup es una metodologia que transformo el mundo del emprendimiento y el desarrollo de productos digitales:  
**El enfoque es *"aprender rapido fallando rapido"***  
>Lo que difiere Lean startup de Lean Manufacturing, es que Lean Startup se enfoca en experimentacion y adaptacion, y Lean Manufacturing se enfoca en la eficiencia del proceso  
![#](/capturas/14.jpg)

  

#### Caracteristicas:
##### Enfoque en el cliente
Lean Startup pone al cliente en el centro de todo el proceso de desarrollo. No se desarrolla en lo que creemos que quieren, sino en lo que quieren mediante feedback en las primeras etapas del desarrollo.

  
##### Desarrollo iterativo:
Desarrollar una version inicial del producto, medir y aprender de los resultados para luego hacer los ajustes y modificaciones necesarios.

##### Validacion de Hipotesis:
Al principio del proceso de desarrollo se formulan una serie de hipotesis. Luego se diseñan experimentos para validar o invalidar estas hipotesis.

##### Producto minimo viable (MVP):
MVP es la version mas simplificada de un producto que permite recopilar la maxima cantidad de aprendizaje validado sobre los clientes con el menor esfuerzo. El objetivo no es desarrollar un producto fin al sino aprender sobre lo que los clientes realmente quieren y necesitan.

##### Aprendizaje Validado:
El objetivo principal no es simplemente hacer dinero, o servir a los clientes. Sino aprender como construir un negocio sostenible y viable.

##### Pivotar o Preservar:
Pivotar es hacer cambios significativos, y Preservar es mantener lo realizado y mejorar u optimizar el producto actual.

#### Desafios la implementacion de Lean Startup:
   - Cambio cultural y resistencia organizacional.
   - Manejo de la incertudimbre y la ambiguedad.
   - Desafios de implementacion practica.
   - Gestion de expectativas y metricas de exito.
   - Enfoque en el aprendizaje vs resultados inmediatos.

#### Ventajas en adoptar Lean Startup:
   - Enfoque en el cliente.
   - Agilidad y adaptabilidad.
   - Optimizacion de recursos.
   - Innovacion y diferenciacion en el mercado.
   - Reduccion de riesgos.

#### Diferencias de Lean Startup con enfoques tradicionales:
![#](/capturas/15.jpg)  
  
[Volver al índice](#índice)

## Kanban

### Introduccion a Kanban:
>Enfocado en transformar la gestion de proyectos con eficiencia, adaptabilidad y vision.  
  
>El origen y la filosofia de Kanban
[#](/capturas/16.jpg)  

##### Principios clave de Kanban:
- Visualizar el trabajo.
- Limitar el trabajo en progreso.
- Gestionar el flujo de trabajo.
- Mejora continua.

##### Ventajas de Kanban:
- Mejora la visibilidad.
- Flexibilidad.
- Eficiencia en el flujo de trabajo.
- Mejora continua.
- Moral del equipo.

##### Desventajas de Kanban:
- Resistencia al cambio.
- Menos efectivo en proyectos estructurados.
- Gestion del tablero.
- Proyectos grandes o distribuidos.
- Falta de planificacion a largo plazo.

### WIP, DOR y DOD:
>Wip -> Work in Progress | DOR --> Definition of Ready | DOD --> Definition of Done

#### Work In Progress (WIP):
- Es la cantidad de tareas en curso en un momento dado.
- Previene la sobre carga y mejora la eficiencia.
- Reduce el estres y mejora la moral del equipo.
- Varia segun el tamaño y capacidad del equipo, complejidad de las tareas y caracteristicas del proyecto.

#### Definition Of Ready (DOR):
- Establece criterios para determinar cuando una tarea esta listo para ser trabajada.
- Actua como un acuerdo entre todo el equipo.
- Asegura la comprension y calidad de requisitos y expectativas, herramientas u otros.
- Los criterios tomados deben ser realistas, medibles y comprensibles.
- Previene retrasos y malos entendidos.

#### Definition Of Done (DOD):
- Establece criterios para determinar cuando una tarea esta completamente finalizada.
- Actua como un acuerdo entre todo el equipo.
- Debe reflejar las necesidades del proyecto y capacidades del equipo.
- Evita el avance de trabajo incompleto o de baja calidad.

#### Implementacion de WIP, DOR y DOD:
- Es importante la determinacion de los criterios y sus significados.
- Se debe educar y motivar al equipo sobre su importancia y beneficios.
- El uso de herramientas digitales puede colaborar en la aceptacion y aplicacion de esos conceptos.
- Permiten mejorar la gestion y promover una cultura de trabajo organizada.

#### Beneficios de implementar WIP, DOR y DOD:
- Mejora en la comunicacion y colaboracion.
- Cultura de mejora continua.
- Mejora en la ejecucion de proyectos.
- Mejora en la dinamica y satisfaccion del equipo.

#### Desafios comunes de implementar WIP, DOR y DOD:
- Resistencia al cambio.
- Mantener criterios realistas y alcanzables.
- Asegurar una aplicacion consistente.
- Integracion con otros procesos y herramientas de uso.

### Herramientas de Tablero Kanban:

#### Columnas del Tablero Kanban:
>![#](/capturas/17.jpg)
>Es crucial que podamos entender el porque detras de la eficacia de kanban.
>Factores criticos para el exito: configuracion del tablero, definicion de criterios y adaptacion de herramientas.
>Es importante conocer los desafios y beneficios que puede proporcionar su implementacion.

#### Tablero Digital Kanban:
>![#](/capturas/18.jpg)  

[Volver al índice](#índice)

## Scrum:
Marco de trabajo que transformo el desarrollo de software en el mundo:
Es una filosofia de colaboracion y eficiencia, que se basa en una comprension profunda de sus valores y pilares.

#### La Guia de Scrum:
>Establece de manera clara y concisa los principios fundamentales, roles, eventos y artefactos de scrum.
>Es un recurso indispensable para quien este implementando o trabajando con scrum.

#### Valores (Scrum):
- Compromiso: Va mas alla de simplemente cumplir tareas, es un compromiso con los objetivos del equipo y proyecto
- Coraje: Valentia de enfrentar desafios, hablar abiertamente y de hacer lo correcto incluso cuando es muy dificil
- Enfoque: Se deben concentrar en el sprint y los objetivos del equipo
- Apertura: Abierto siempre a nuevas ideas, a los cambios, y colaboracion efectiva dentro del equipo
- Respeto: Hacia los compañeros del equipo como profesionales y personas

#### Pilares de Scrum:
- Transparencia: Todos los aspectos del trabajo del equipo deben ser visibles a quienes son los responsables de los resultados
- Inspeccion: Los equipos deben inspeccionar regularmente su progreso hacia los objetivos definidos.
- Adaptacion: Realizar ajustes tan pronto como sean posibles, cuando se detectan desviaciones indeseadas.

### Los Roles en Scrum:
>En Scrum cada rol tiene responsabilidades unicas que son esenciales para el exito del equipo y proyecto.
>Son partes fundamentales del marco de trabajo Scrum.
>Cada rol contribuye al proceso agil y los hace esenciales para el proyecto.

#### Scrum Master:
- Facilitador: Ayuda a moderar y organizar las reuniones, asegurando que sean productivas y se mantengan dentro del marco de trabajo Scrum(Sprint, Dailys).
- Mentor: Guiar al equipo para la comprension y aplicacion de los principios de Scrum, y ayuda los integrantes a mejorar sus habilidades dentro del marco de trabajo agil. Debe empoderar y motivar.
- Elimina Obstaculos: Debe buscar solventar rapidamente los inconvenientes para no generar retrasos en el proyecto.
- Intermediario: Media entre el equipo y el resto de la organizacion.
- Corazon del equipo

#### Product Owner:
Es el principal tomador de decisiones para con el producto:
- Visionario: Debe entender las necesidades del mercado, los usuarios, y la empresa.
- Gestor del Backlog: Identificar y priorizar los elementos del backlog, asegurando que se prioricen las tareas mas importantes y valiosas.
- Comunicador.
- Decisor: Toma decisiones oportunas sobre caracteristicas a desarrollar y el orden.
- Clave para el exito: Vision estrategica, habilidades de gestion y comunicacion efectiva.

#### Equipo de Desarrollo:
- Autoorganizacion: El equipo toma decisiones en conjunto sobre como abordar los problemas y resolverlos.
- Colaboracion y Comunicacion.
- Compromiso.
- Flexibilidad y Adaptabilidad.
- Impulsa la Innovacion.

[Volver al índice](#índice)

### Integracion de los Roles en Scrum:
- Sinergia entre los roles.
- Comunicacion Efectiva.
- Responsabilidad compartida.
- Adaptacion y mejora continua.

### Los eventos en Scrum:
>En Scrum cada evento esta diseñado con un proposito especifico.
>Sirven como puntos de control y oportunidades de ajuste.
>No solo son reuniones sino que son momentos estrategicos.
>Son la columna vertebral del proceso scrum.

#### Sprint
>![#](/capturas/19.jpg)
>Es el corazon de Scrum.
>Establece un ciclo de tiempo durante el cual se crea un producto o se mejora.
>Dura de una a cuatro semanas.
>Es importante que los objetivos del sprint sean claros y alcanzables.

#### Sprint Planning:
>![#](/capturas/20.jpg)
>Establece la direccion y los objetivos para el sprint.
>En este evento el Product Owner presenta los elementos del product backlog y sus prioridades.
>El objetivo es seleccionar que items del backlog pasaran a formar parte del sprint backlog.

#### Daily Scrum:
>Reunion todos los dias.
>No deberia durar mas de 15'.
>En este evento cada miembro del equipo comparte su progreso, identifica posibles obstaculos y planifica las acciones del dia.
>Esta reunion ayuda a detectar problemas rapidamente.

#### Sprint Review:
>Se realiza al final del sprint.
>En este evento se recopila el feedback de los stakeholders.
>Se inspecciona el incremento y determina futuras adaptaciones.
>Incluye a stakeholders, clientes o usuarios finales.
>El equipo presenta lo que ha completado en el sprint.

#### Sprint Retrospective:
>Se realiza luego del Sprint Review.
>En este evento se reflexiona acerca del sprint y se planifican las mejoras para el proximo.
>El objetivo es identificar que funciono bien, que podria mejorarse y comop se pueden implementar esos cambios para el proximo sprint.
>Aqui el equipo discute y propone aspectos de mejora del proceso.

### Los Artefactos en Scrum:
Sirven como punto de control y oportunidades de ajuste, son momentos estrategicos y la columna vertebral del proceso Scrum.

#### Product Backlog:
![#](/capturas/21.jpg)
>Gestionado por el Product Owner.
>Priorizacion y Refinamiento.
>Transparencia y Comunicacion.
>Adaptacion.

#### Sprint Backlog:
![#](/capturas/22.jpg)
>Colaboracion y Autoorganizacion.
>Transparencia y Adaptabilidad
>Monitoreo del progreso

#### Incremento:
![#](/capturas/23.jpg)
>Definicion y Proposito
>Calidad y Cumplimiento
>Transparencia y Feedback
>Evolucion continua

[Volver al índice](#índice)

---

## User Stories
Las User Stories son una tecnica fundamental para ayudar a comprender y entregar exactamente lo que nuestros usuarios necesitan

#### Definicion y caracteristicas de las User Stories:
Una User Story es una descripcion narrada que captura una caracteristica deseada por el usuario en pocas oraciones, siempre resaltando el valor que proporciona (INVEST)
![#](/capturas/24.jpg)

#### Diferencia entrre requerimientos tradicionales y User Stories:
- Las User Stories son breves y se centran en la experiencia y necesidades del usuario
- Son conversacionales y colaborativas, diseñadas para evolucionar a traves de la retroalimentacion y las iteraciones
- Las User Stories invitan al equipo a explirar y definir conjuntamente como se puede satisfacer mejor la necesidad del usuario
![#](/capturas/25.jpg)  
![#](/capturas/26.jpg)

#### Caso de Aplicacion:
>Imaginemos el caso de una empresa de tecnología que enfrentaba dificultades en la gestión de expectativas de sus clientes.
>Al adoptar User Stories, el equipo comenzó a redactar historias que representaban las necesidades de los usuarios finales en escenarios reales, facilitando así la identificación de funcionalidades clave y la priorización de tareas.

### Criterios de Aceptacion
>Son un componente fundamental que transforma un User Story de una simple declaracion de necesidad a una guia precisa para la creacion de valor.
>Don condiciones especificas que un software o funcion debe cumplir para ser aceptados por los usuarios.

#### Como definir criterios de aceptacion de calidad
>Para definir criterios de aceptacion efectivos, cada US debe ser acompañada de indicadores claros y cuantificables. Incluyendo aspectos de usabilidad, rendimiento y conformidad.
>Un buen criterio de aceptacion cumple con el criterio SMART.
![#](/capturas/27.jpg)

Ejemplo:
- El usuario debe poder añadir o editar fechas limite en cada tarea individualmente.
- La fecha limite seleccionada debe mostrarse claramente en la interfaz de la tarea.
- El sistema permite seleccionar las fechas dentro del rango de un año desde la fecha actual.
- Las fechas limite establecidas deben ser sincronizadas y visibles en todas las plataformas donde se utilice la app.
- El usuario recibe una notificacion de recordatorio 24hs antes de la fecha limite.

[Volver al índice](#índice)

### Roadmap & User Story Mapping:

> Estas herramientas son vitales en la transformacion de una vision de proyecto en una realidad palpable y ejecutable.
>El roadmap proporciona una vision estrategica, mientras que el User Story Mapping nos adentra en el corazon de la planificacion del proyecto.

#### El Roadmap:
>Es un mapa de ruta estrategico que proporciona una vision panoramica de donde queremos ir con el proyecto.

#### El User Story Mapping:
>Es una herramienta tactica que ayuda a los equipos a desglosar y priorizar el trabajo de desarrollo en segmentos manejables, asegurando que cada paso del proceso este alineado con las necesidades y expectativas del usuario.

Ventajas:
- Aporta claridad al proceso.
- Permite visualizar el proyecto desde la perspectiva del usuario.
- Ayuda a priorizar tareas.
- Facilita la planificacion.

>El Product Owner es el responsable de asegurar que las historias reflejen las necesidades del usuario y se alineen con la vision del producto.
>Trabaja estrechamente con el equipo y clientes para priorizar y organizar las historias.

[Volver al índice](#índice)

### Tecnicas de Estimacion:

  - Planning Poker: Tecnica Ludica y colaborativa para estimar el esfuerzo o complejidad de las tareas del proyecto, por medio del usi de cartas con diferentes valores.
  ![#](/capturas/28.jpg)
  - Story Points: Unidad de medida abstracta que se utiliza para estimar la complejidad de una historia de usuario. En lugar de estimar el tiempo, se estima el esfuerzo relativo
  ![#](/capturas/29.jpg)
  - T-Shirt: Son una unidad de medida abstracta que se utiliza para estimar la complejidad de una historia de usuario. En lugar de estimar el tiempo, se estima el esfuerzo relativo.
  ![#](/capturas/30.jpg)

#### Importancia de la estimacion:

  - Falicita la planificacion.
  - Comunicacion y transparencia.
  - Adaptacion y flexibilidad.
  - Mejora continua.

### Tecnicas de Priorizacion:

  - MoSCoW: Se destaca por su simplicidad y eficacia. Su nombre es un acronimo de cuatro categorias prioritarias: Must have (Debe tener), Should have (Deberia tener), Could have (Podria tener), Won't have this time(No tendra esta vez). Esto ayuda a enfocar en lo realmente importante.
  ![#](/capturas/31.jpg)
  - Matriz de Eisenhower: Hace uso de una matriz la cual divide las tareas en 4 cuadrantes basados en su urgencia e importancia, ayudando a identificar lo que debe hacerse de inmediato y lo que puede delegarse o posponerse.
  ![#](/capturas/32.jpg)
  - Basada en el Valor: Implica evaluar cada tarea o historia de usuario en terminos de su retorno de inversion y el valor que aporta al cliente o usuario final
  ![#](/capturas/33.jpg)

#### Importancia de la Priorizacion:

  - Maximiza el valor entregado.
  - Gestion de recursos.
  - Facilita la toma de decisiones.
  - Respuesta a los cambios.

## Metricas en los Proyectos Agiles:

>La priorizacion es esencian en la agilidad ya que guia a los equipos en la toma de decisiones sobre que trabajar primero para maximizar el valor entregado

  - La velocidad del equipo: Se calcula sumando los Story points de todas las historias completadas en un sprint. Esta metrica varia entre los equipos.
  - Burndown chart: Es uno de los graficos que muestra el trabajo restasnte en el eje vertical frente al tiempo en el eje horizontal. Un grafico ideal muestra una linea descendiente constante hacia cero indicando que el trabajo se esta completando en un ritmo regular
  - Lead Time y Cycle Time: Mientras que el Lead Time mide el tiempo total desde la concepcion hasta la entrega, el Cycle Time se centra en el tiempo de produccion activa.
  - Throughput: Se refiere al numero de tareas o historias completadas en un periodo de tiempo determinado.
  - Indice de Satisfaccion del cliente: Esta metrica se obtiene a traves de encuestas y feedback del cliente.

### Importancia de las metricas:
  - Facilita la toma de decisiones
  - Mejora continua y adaptabilidad
  - Optimiza la planificacion
  - Orientacion al cliente