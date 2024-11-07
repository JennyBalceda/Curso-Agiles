### Repaso

---


### *4 valores Ágiles:*   
- Software que funcione **SOBRE** documentación excesiva -> ***Es más importante el trabajo hecho***      
    - Trabajo hecho = **Valor** (+ Ingresos, Evita Perdida de egresos, Baja Costos, Evita sobre Costos)

- Responder al cambio **SOBRE** seguimiento a un plan -> ***Es mas importnate la habilidad***
    - **Cynefin:** Según sea la situación, haré un trabajo predictivo, ágil, teórico o voy a reaccionar al trabajo caótico

- Individuos e interacciones **SOBRE** procesos y herramientas -> ***Formar Equipos***
    - Voy a obtener **4 fases de Equipos (Tuckman)**, para auto organizarlos y resolver problemas (1 - Reglas, 2 - Capacitación, 3 - Liderar y temas de control, 4 - Empoderarlos)
    - ¿Para qué formar equipos? -> Para generar ideas, generar las mejores ideas

- Colaboración con el cliente **SOBRE** Negociación de contrato -> ***Confianza***
    - Comunicación efectiva, Lenguaje Corporal, Tono de Voz y la Retroalimentación = Para generar ideas
    - Las ideas pueden ser de 3 maneras:
        - Design Thinking 
        - Escribe en Silencio, Round Robin y Free For All (Generación genérica de ideas, para la Fase 4)
        - Solucionar Problemas (Poda del Árbol, Lancha RÁpida y Recuerda el Futuro)

---

### Lean Startup y Lean Inception

> Un Proyecto tiene 5 fases

***Fases de un Proyecto:***
1. **Inicio:**
    - Proyecto Predictivo (PMBOOK V6, termina en la entrega del Project Charter o Acta de Constitución) 
    - Proyecto Ágil (Termina en la entrega del MVP - Tiene su Charter Agil con Lean Startup o Lean Inception)
        - ***Lean Startup:*** Tienen 3 fases  
            1. **Crear un MVP:** Empatizar con el cliente para poder identificar los requerimientos, luego identificar como las funcionalidades mas importantes son necesarias para el MVP 
                - (¿Cómo sé que una funcionalidad es buena para el MVP? -> Que tanto valor aporta) 
                - (MVP -> Es el software que por lo menos tienen un componente de valor, + Ingresos, Evita Perdida de egresos, Baja Costos, Evita sobre Costos)
                - ¿Cómo conocer al cliente del MVP? Puedo conocerlo con un Estudio de Mercado -> Design Thinking (conocer +) -> Crear Funcionaldiades de Valor -> Priorizarlas con MoSCoW

            2. **Medir:** Poner KPI's -> Percepción del usuario (si lo compra o no lo hace, si te retroalimenta) = Como se comparta mi producto MVP ante el usuario

            3. **Aprende:** En base a los KPI's APRENDEMOS si se aumentan (+) Funcionalidades o si se retiran (-) Funcionaldiades
        
        - ***Lean Inception:*** Tenmos 5 guías
            1. Alcance
            2. Primeras Funcionalidades
            3. Parte Técnica
            4. Usabilidad
            5. MVP


2. **Planeación** 
    - Herramientas de Scrum:
        - Sprint Planning: Reunión en el cual el equipo se reune para planificar el trabajo de un mes, se define el alcance, tiempo y costo del primer o último sprint, el equipo se auto organiza para planificar lo que el Product Owner les entrega del Backlog
    - Herramientas de Kanban:
        - Crear el Tablero
    
3. **Ejecución:**
    - Herramientas de Scrum:
        - El Sprint que tiene un TimeBox
    - Herramientas de Kanban: 
        - Ejecutar el Tablero (Crear las tarjetas de avance a lo largo del tiempo)

4. **Control:**
    - Herramientas de Scrum:
        - Daily: Es una reunión de 15 minutos para 3 cuestiones
        - Sprint Review
    - Herramientas de Kanban:
        - Subir o Bajar el WIP (Trabajo en proceso)
        - TC (Gestionar el tiempo de ciclo)
            -   En cuanto tiempo debería hacer ese trabajo en base a la velocidad de mi equipo

5. **Manteminiento - Cierre - Mejora**
    - Herramientas de Scrum:
        - Sprint Retrospective
    - Herramientas de Kanban:
        - TOC (La teoria de las restricciones)
 
 > *Herramientas != Métodos (Example: Daily vs Scrum)*

---
### Kanban

Tablero Kanban se divide en 2 partes (Inferior y superior)   

***PLANIFICACIÓN:***   
- Superior (Planeado):  
    **Crear tablero:**
    - Poner proceso de desarrollo de software
    - ¿Cómo crear columnas? -> Si los procesos usan la misma información y herramientas, es bueno crearles una columna común
        - Cada columna puede ser de una o más actividades
        - Cada columna debe tener los mismos tipos de Técnicos, Herramientas e Información
        - Cada columna tendrá un Cartel con la información de que se hace en ella -> Encima va el WIP (Work In Progress - Cantidad de trabajo que deben hacer)
- Inferior (Real):  
    **Crear las tarjetas de HU:**
    - Tarjeta de HU: Actividad, % de avance, recursos usados, los desperdicios (hay 7), checklist de la tarea
        - Desperdicios: Hay 7 y son cualquier cosa que te haga perder dinero y perder tiempo   
   
***EJECUCIÓN:***
- Cuello de Botella
    - Cada columna tiene su propio WIP, donde comienzan a fluir las tarjetas y de pronto comienzan a congestionarse de tarjetas
    - ¿Cómo te das cuenta? -> Algunas tareas debieron haber ido hechas en un margen de un tiempo asignado, pero pasa el tiempo y las tarjetas no fluyen, fluyen pocas
    - *Te das cuenta cuando empiezas a desfasarte del cronograma*
- Bajar el WIP
    - Disminuir las HU por columna, al disminuir hará que el tiempo sobre y el tiempo sobrante se dedica a solucionar el problema
- TOC (Gestionar el tiempo de ciclo)
    - Secuencia de pasos (5) para el cuello de botella
    - Es la solución que se hace luego de bajar el WIP (usar el tiempo sobrante y dedicarlo a solucionar el problema)
    - Eliminación de los cuellos de botella
    - Hacer que el trabajo se mantenga fluido
    - Tiene 5 partes:
        1. Encontrar el cuello de botella
        2. Buscar una causa raíz para solucionar el problema
        3. Bajar el WIP para enconreae la mejor solución a ese problema
        4. Una vez solucionado levantas el WIP
        5. Volver o pasar a otra columna con Cuello de Botella

Servicios Kanban:
- Cada servicio podría ser una columna
- Idenficar los servicios es esencial en Kanba, entender tu negocio
- Está relacionado al negocio
- Es bueno dividir el trabajo en servicios porque me centro en las necesidades del cliente y me ayuda a gestionar mejor el trabajo
- Evoluciona en base a las politicas del cliente y el negocio
- Negocio = Conjunto de servicios
    - Desarrollo de funcionalidades:
    - Resolución de errores o incidencias:
    - Pruebas y control de calidad:
    - Mantenimiento y actualizaciones:
    - Gestión de requisitos y prioridades:
    - Diseño de interfaz de usuario:
    - Implementación de pruebas y automatización:
    - Despliegue y puesta en producción:
    - Gestión de la configuración:
    - Soporte y atención al cliente:


Tiempo 1:38


   
>- Sube WIP = aprender mas 
>- Baja el WIP para solucionar problemas
> - Kanban + usado > Scrum en el mundo real (según Ivan)
> - Kanban solo tiene 2 filas, pero si varias columnas

> - Cada columna Kanban sería lo equivalente a un Sprint
> - Cada Sprint tiene una cantidad de trabajo por hacer y a esa cantidad se le llama WIP
> - Si el Kanban se convierte en una secuencia de Sprint se convierte en un **Roadmap**
> - Cada columna representa un Sprint = Roadmap

> - Tiempo de Ciclo = Time Box -> cuanto demora todo el kanban o una columna 
>   - TimeBox (en Scrum) -> Está pre establecido
>   - TimeBox (en Kanban) -> No está preestablecido, se define por el Gerente del Proyecto
>       - Es un dato porque ya tiene un tiempo total del proyecto y lo que hace para los time box es dividir tiempo
>       - La velocidad no es un dato que tengamos, tenemos que averiguar
>       - Se usa Planning Poker para ver o medir la habilidad del equipo
>       - Tiempo = WIP (Carga de trabajo) entre Velocidad del equipo
