# Introducción

- Feature-Driven Development metodología ágil 1997
- No cubre todo el proceso solo las fases de diseño e implementación
- Muchas iteraciones cortas con entregas frecuentes de trabajo tangible en todos los pasos
- Características -> HU de Scrum, las valora el cliente
- Metodología para equipos grandes, comunicación importante, muchas veces mediante documentación

# Procesos

5 fases, se itera sobre las 2 últimas

## Desarrollar el modelo global

- Se crean equipos interdisciplinares (desarrolladores, expertos en el dominio, programadores) que, guiados por un arquitecto jefe, componen un modelo del dominio.
- Después de ser revisados se elige un modelo (o combinación de varios) 
- Así el equipo tendrá una visión general del proyecto
- En esta etapa el arquitecto jefe y los programadores jefes crearán una lista informal de las características a realizar

## Construir la lista de características

- A partir del modelo y la lista de características, se agrupan en áreas de dominio (major list sets)
- Esta lista se divide en subcojuntos según la funcionalidad. Cada característica se prioriza y se dividen las más complejas en otras más pequeñas.
- Como salida se obtiene la lista de característica (Revisada por los clientes para su aprobación y validación)

## PLanificando por características

- Se ordena la lista de características según la prioridad y la dependencia entre las características
- El gestor del proyecto, desarrollador y programador jefe establecen hitos y diseñan un cronograma de diseño y construcción.
- El gestor de desarrollo y el jefe del producto verifican el plan teniendo en cuenta al equipo
- De esta etapa se obtiene un plan de desarrollo con fecha de finalización de cada conjunto de características. De cada característica se indica el programador jefe asignado y las fechas de inicio y fin. Para cada clase se indica el programador encargado

## Diseñando por características

- (estas 2 etapas duran entre un par de días y 2 semanas como máximo) Varios equipos trabajan simultáneamente en su propio conjunto de características

- El programador jefe (a partir de la documentación anterior) selecciona las siguientes características a realizar (de las que tenga asignadaS)
- Identifica los class owners involucrados en el desarrollo de esas características y contacta con expertos en el dominio si es necesario
- Se trabaja en el diseño técnico y en la infraestructura (escribir clases, determinar métodos y hacer diagramas de secuencia)
- Los class owner actualizan la descripción de sus clases en base al diagrama de secuencia
- El equipo revisa y verifica el diseño
- Salida: diagrama de secuencia detallado, diagrama de class actualizado, descripción de clases y métodos, notas significativas para el diseño

## Construyendo por característica
- El propietario de clase implementa los métodos de las clases correspondientes a cada característica y realiza las pruebas de unidad de cada clase
- El equipo de característica revisa el código
- ...

# Roles
Tres tipos: clave, de apoyo y adicionales. Un rol puede ser tomado por varias personas y varias personas pueden tener varios roles. Nos centramos en los clave:

# Conclusiones
- Este método minimiza la complejidad del sistema (al dividirla en problemas pequeños)
- Compronsión profunda del software a desarrollar
- Como se va documentando todo se puede llevar un seguimiento del progreso y los resultados
- Comunicación fácil, fomenta la creatividad e innovación
- Compilaciones regulares -> minimizan los errores
- Calidad -> gracias a las pruebas del código, estándares utilizados para codificar,...
