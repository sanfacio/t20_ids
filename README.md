# Actividad de integración: *Software Rescue Challenge — CampusGo*

## Objetivo

Al terminar, cada equipo habrá propuesto una primera versión viable de un plan para rescatar un proyecto de software: aclarará necesidades, priorizará trabajo, definirá una solución inicial, acordará cómo asegurar calidad y explicará sus decisiones. El énfasis está en la comunicación, la escucha y la construcción conjunta, no en encontrar una única respuesta correcta.

## Entregables

Cada equipo prepara una sola hoja, diapositiva o tablero con:

1. Sus tres preguntas o supuestos principales.
2. De 4 a 6 historias de usuario y criterios de aceptación de las dos prioritarias.
3. La priorización y el alcance del primer incremento.
4. Un boceto de la solución inicial.
5. Acuerdos de calidad, entrega y colaboración.
6. Los ajustes realizados ante el cambio inesperado.

## Escenario: Proyecto CampusGo

La universidad desea lanzar **CampusGo**, una aplicación para estudiantes que permita:

- Consultar horarios de clase.
- Recibir notificaciones sobre cambios de salón.
- Consultar eventos universitarios.
- Reportar problemas en las instalaciones.
- Consultar información de profesores.

El equipo que inició el proyecto solicita ayuda porque, tras varias semanas, han aparecido estos problemas:

- Las personas usuarias no tienen claridad sobre todas las funcionalidades necesarias.
- Usuarios y desarrollo interpretan los requerimientos de forma distinta.
- El código está repartido en computadoras personales y no existe una estrategia clara de control de versiones.
- No se han acordado pruebas, criterios de aceptación ni responsables de calidad.
- Hay presión por mostrar una versión útil en pocas semanas.

La dirección pide al equipo entregar una propuesta inicial para un primer incremento funcional, sin intentar construir toda la aplicación.

## Roles del equipo

Asignen un rol por persona. Los roles ayudan a distribuir la participación; todas las decisiones deben ser acordadas por el equipo.

| Rol | Responsabilidad durante la actividad |
| --- | --- |
| Facilitador/a ágil | Cuida los tiempos, reparte la participación y ayuda a resolver desacuerdos. |
| Representante de usuarios | Formula necesidades, dudas y criterios de aceptación desde la perspectiva de estudiantes y personal universitario. |
| Diseñador/a técnico/a | Propone una solución simple: componentes, datos principales, integraciones y decisiones técnicas iniciales. |
| Responsable de calidad y entrega | Identifica riesgos, pruebas, seguridad básica y una forma de colaborar con control de versiones e integración continua. |

> Sugerencia: roten la voz de quien presenta en cada etapa para que todas las personas participen.

## Desarrollo paso a paso

### 1. Comprender el reto — 10 minutos

Lean el escenario y conversen sobre las personas involucradas: estudiantes, docentes, coordinación académica y mantenimiento. Anoten dudas y supuestos. Elijan las **tres preguntas** que más necesitan resolver antes de desarrollar CampusGo.

### 2. Convertir necesidades en historias — 15 minutos

El representante de usuarios guía la redacción de entre **4 y 6 historias de usuario** con el formato:

> Como **[tipo de usuario]**, quiero **[necesidad]** para **[beneficio]**.

Para las dos historias más importantes, agreguen de dos a tres criterios de aceptación comprobables. Eviten soluciones técnicas en la redacción; primero describan el valor para la persona usuaria.

### 3. Priorizar el primer incremento — 10 minutos

Ordenen las historias con las etiquetas **Ahora**, **Después** y **Más adelante**. Seleccionen un alcance pequeño que sí pueda ser una primera versión útil. Expliquen brevemente qué valor aporta y qué decidieron dejar fuera por ahora.

### 4. Diseñar una solución inicial — 15 minutos

El diseñador técnico dirige un boceto sencillo de la solución. Puede ser un diagrama en papel o digital que muestre:

- Pantallas o puntos de interacción principales.
- Datos mínimos que se deben guardar o consultar.
- Componentes o servicios relevantes.
- Una integración necesaria, si aplica (por ejemplo, el sistema institucional de horarios).

No se espera una arquitectura perfecta: busquen una solución comprensible, evolutiva y alineada con el alcance elegido.

### 5. Acordar calidad y forma de trabajo — 15 minutos

El responsable de calidad y entrega conduce estos acuerdos:

- Dos pruebas que el equipo ejecutaría antes de liberar la versión.
- Un riesgo de seguridad o privacidad y una medida básica de mitigación.
- Una definición breve de “terminado” para una historia.
- Una forma de usar control de versiones: repositorio compartido, ramas cortas, revisión entre pares e integración frecuente.
- Una práctica de automatización que implementarían primero, como ejecutar pruebas al integrar cambios.

### 6. Cambio inesperado: responder en conjunto — 10 minutos

Conversen y ajusten su propuesta. Anoten:

1. Qué historia, criterio de aceptación o prioridad cambia.
2. Qué dato, integración, riesgo o prueba nueva aparece.
3. Qué decisión tomarían para entregar valor sin comprometer la privacidad ni prometer información incorrecta.

### 7. Compartir y reflexionar — 15 minutos


