# Sistema de Gestión de Turnos Online para Autogestión de Pacientes

## Descripción del proyecto

El presente proyecto consiste en el análisis, diseño y planificación de un Sistema de Gestión de Turnos Online para la Clínica Odontológica de Gualeguaychú, una organización dedicada a la prestación de servicios de salud bucodental.

La propuesta surge a partir de la necesidad de optimizar la gestión de turnos, actualmente realizada principalmente de forma manual, mediante la incorporación de una plataforma web que permita a los pacientes autogestionar sus reservas.

El proyecto se desarrolla en el marco del Trabajo Práctico Integrador y Progresivo (TPI) de la asignatura Organización Empresarial, correspondiente a la Tecnicatura Universitaria en Programación de la Universidad Tecnológica Nacional (UTN).

## Objetivo del sistema

Facilitar la gestión de turnos odontológicos mediante una plataforma web, mejorando la accesibilidad para los pacientes, reduciendo la carga administrativa del personal de Secretaría y favoreciendo una organización más eficiente de las agendas profesionales.

## Funcionalidades propuestas

- Registro e inicio de sesión de pacientes.
- Selección de profesional, especialidad y tipo de atención.
- Consulta de fechas y horarios disponibles.
- Solicitud y confirmación de turnos online.
- Validación de disponibilidad para evitar reservas simultáneas.
- Consulta y cancelación de turnos por parte de los pacientes.
- Administración de la disponibilidad de los profesionales.

Algunas prestaciones requieren coordinación directa con Secretaría y no permiten la reserva online.

## Alcance del modelado BPMN

Se modeló el proceso de solicitud y reserva de turnos online mediante la notación BPMN 2.0.

El diagrama representa la interacción entre el paciente y el Sistema de Gestión de Turnos, contemplando el registro, la autenticación, la selección de atención, la consulta de disponibilidad y la confirmación de la reserva.

También se incluyeron situaciones excepcionales, como errores de autenticación, falta de horarios disponibles y cambios en la disponibilidad antes de confirmar una reserva.

## Documentación BPMN

El proceso de solicitud y reserva de turnos online fue modelado utilizando la notación BPMN 2.0 mediante la herramienta draw.io.

Se encuentran disponibles los siguientes archivos:

- [Visualizar diagrama BPMN (PNG)](./bpmn-reserva-turnos.png)
- [Acceder al archivo BPMN editable (draw.io)](./bpmn-reserva-turnos.drawio)

El archivo editable permite examinar las actividades, los participantes, las compuertas de decisión y los flujos de comunicación que componen el proceso.

El diagrama también se encuentra incorporado en la documentación del Trabajo Práctico Integrador y Progresivo.

## Organización del proyecto

**Institución:** Universidad Tecnológica Nacional (UTN)

**Carrera:** Tecnicatura Universitaria en Programación

**Asignatura:** Organización Empresarial

**Comisión:** N.º 7

**Organización analizada:** Clínica Odontológica de Gualeguaychú

**Integrante:** María Constanza Maetta

**Modalidad:** Trabajo individual

## Gestión y documentación

El repositorio utiliza Git y GitHub para registrar y organizar las modificaciones de la documentación técnica mediante ramas de trabajo, commits descriptivos y Pull Requests.

La planificación y el seguimiento de las actividades del proyecto se realizarán mediante un tablero ágil de GitHub Projects.

## Estado del proyecto

Proyecto académico en etapa de análisis, modelado y planificación. Las funcionalidades descritas corresponden al sistema propuesto y no implican que el software se encuentre implementado.

## Declaración de uso de inteligencia artificial

Durante la elaboración del proyecto se utilizó ChatGPT (OpenAI) como herramienta de apoyo para organizar y revisar el modelado del proceso BPMN, analizar alternativas de representación y verificar la coherencia de las actividades y decisiones.

Las propuestas generadas fueron evaluadas críticamente y modificadas cuando resultaron innecesarias o inconsistentes. Entre las correcciones realizadas se destacan la eliminación de compuertas redundantes, la simplificación de actividades, la revisión de los flujos de mensaje y la delimitación del alcance del proceso online.

Las decisiones finales sobre el diseño, la documentación y la adecuación al funcionamiento de la clínica se realizaron mediante criterio propio. La asistencia de IA no sustituye la responsabilidad sobre la coherencia y exactitud del proyecto.

### Ejemplos de consultas a la IA y evaluación crítica

Durante el desarrollo del trabajo se realizaron distintas consultas a ChatGPT para analizar alternativas y resolver dificultades. A continuación, se presentan ejemplos resumidos de esas interacciones y las decisiones adoptadas.

**1. Modelado del proceso BPMN**

- **Consulta realizada (resumida):** ¿Cómo representar mediante BPMN 2.0 el proceso de solicitud y reserva de turnos, incluyendo el registro de pacientes, la autenticación, la selección de horarios y las situaciones excepcionales?
- **Aporte de la IA:** Propuestas para organizar los participantes, las actividades, las compuertas XOR y los flujos de comunicación.
- **Intervención humana:** Se revisó el diagrama de forma progresiva, identificando conexiones incorrectas, actividades redundantes y decisiones que podían simplificarse.

**2. Simplificación de la consulta de disponibilidad**

- **Consulta realizada (resumida):** ¿Es necesario incorporar actividades intermedias como «Preparar horarios disponibles» y «Preparar aviso de falta de disponibilidad», o pueden simplificarse?
- **Aporte de la IA:** Análisis de las alternativas de representación del flujo.
- **Intervención humana:** Se decidió eliminar las actividades innecesarias y utilizar acciones más directas, como «Enviar horarios disponibles», para mejorar la claridad del proceso.

**3. Organización del backlog ágil**

- **Consulta realizada (resumida):** ¿Cómo organizar las historias de usuario y las tareas del proyecto en GitHub Projects, utilizando los estados Por hacer, En progreso y Listo?
- **Aporte de la IA:** Orientación para redactar historias de usuario, establecer criterios de aceptación y organizar el tablero Kanban.
- **Intervención humana:** Se decidió mantener las funcionalidades del software en estado pendiente, diferenciándolas de las tareas de análisis y documentación efectivamente realizadas.

**Conclusión de las interacciones**

Las respuestas generadas por la IA fueron utilizadas como propuestas iniciales y no como soluciones definitivas. Se aplicó criterio propio para verificar su coherencia con la organización analizada, corregir errores de representación y asegurar que la documentación reflejara el estado real del proyecto.
