# Objetivos de la clase de Ingeniería de Software

- Formar competencias para diseñar, desarrollar y gestionar proyectos de software
de calidad.
- Aplicación de metodologías, modelos de proceso y técnicas de ingeniería de
software.

## ¿Por qué es importante aprender Ingeniería de Software?

- Desarrollo de software con calidad profesional.
- Reducción.

# Contenido General del Curso

- Introducción a la Ingeniería de Software.
- Modelos de Proceso de Desarrollo.
- Ingeniería de Requerimientos.
- Diseño e Implementación de Software.
- Pruebas y Mantenimiento.
- Herramientas CASE.

# Criterios de evaluación

- Actividades 25%.
- Tareas 15.
- Examen 20.
- Lectura 15s.
Proyecto final 25
- Asistencia y participación en clase.

Entrega puntual de trabajos y lecturas.

Bibliografía base: Sommerville I (2015). Ingeniería de Software, 10a ed. Pressman. R.

# Conceptos básicos de Ingeniería de Software

Ingeniería de Software: Disciplina de desarrollo sistemático de software.
Objetivo: construir software confiable, eficiente, mantenible.

## ¿Por qué es necesario aplicar ingeniería al software?

- El software es complejo y creciente.
- El software tiene impacto crítico.
- El software cambia constantemente.
- Permite gestionar recursos limitados.
- Calidad, seguridad y confiabilidad.
- Colaboración de equipos multidisplinarios.

Conjunto de programas, datos y documentación.
Componentes: código fuente, documentación, manuales.
Ejemplo: Sistemas bancarios, apps móviles.

# Dominios de Aplicación de Software

- Sistemas embebidos.
- Aplicaciones empresariales.
- Software científico.
- Sistemas de tiempo real.

# Software Heredado y Web/Apps

Software heredado: antiguo pero crítico.
Web/Apps: modernas, dinámicas y móviles.
Ejemplo: Sistemas COBOL en bancos vs. apps de delivery.

El software heredado (*legacy software*) son sistemas antiguos que siguen siendo
utilizados porque:

- son sistemas antiguos que siguen siendo utilizados porque
- son críticos para la operación,
- son costosos o arriesgados de reemplazar,
- nadie conoce completamente su funcionamiento.

### ¿Qué harías si heredaras un sistema crítico que nadie entiende, pero que no puede detenerse?

| Reto                  | Explicación | Ejemplo |
| --------------------- | ------------ | ------- |
| Tecnología Obsoleta  | Lenguajes, plataformas o hardware ya no soportados. | Sistemas COBOL en bancos |
| Falta de documentación | No existen especificaciones completas o están desactualizadas. | Código difícil de entender para nuevos ingenieros |
| Conocimiento limitado | Los desarrolladores originales ya no están disponibles. | Dificultad para hacer modificaciones seguras |
| Alta dependencia operativa | El sistema es crítico y no puede faltar. | Sistema de control de tráfico aéreo |
| Mantenimiento costoso | Cada cambio requiere esfuerzo extra. | Cambios pequeños implican mucho trabajo |
| Compatibilidad | No es compatible con nuevas plataformas o normativas. | Integración con servicios web modernos |
| Riesgo de seguridad | Vulnerabilidades no parchadas | Falta de cifrado moderno o controles de acceso actuales |

# Historia de la Ingeniería de Software

Video: [Historia de la Ingeniería de Software](https://www.youtube.com/watch?v=VTyO4dAEbIg)

Video: [La Ética en la Ingeniería de Software](https://www.youtube.com/watch?v=mtyS2z3l_OU)


# Requisitos del sistema (*ingeniería de requisitos del sistema*)
## Documento de requisitos

- ¿Qué pasa con las historias del usuario?
- ¿Qué pasa con los casos de uso?

### ¿Qué es RUP?

- UML.
- Diagrama de casos de uso (representa qué hace el usuario con el sistema).

## Diagrama de casos de uso
![Ejemplo de diagrama de casos de uso](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgU9C-aeNqdEKUpDHGoPrm3SVPuAIyZm2kYgHKzL_qeIIHkHC-XTwjhB6W0f8-uyCGXrzJ-i7KNnwiemMljxNB_HhyphenhyphenaFJVJ9ejZP3LexYLjVG2MDB2rEX-Mqsj-hZaruxVOZKmnEv3ORhbe/w1200-h630-p-k-no-nu/diagrama-de-casos-de-uso-600.jpg "Diagrama de casos de uso")


Los elementos son:
- Actor
![Actor](https://c0.klipartz.com/pngpicture/878/158/gratis-png-palo-humano-uso-caso-diagrama-simbolo-computadora-iconos-actor-actor.png "Actor")
- Relaciones
![Relación](https://geometriamagicomundodelorigami.wordpress.com/wp-content/uploads/2016/12/linea-recta.jpg?w=840 "Relación")
- Casos de uso
![Caso de uso](https://images.vexels.com/media/users/3/139183/isolated/preview/e81136ff89d964e1b8e8e4f7ff63d4cf-elipse.png "Caso de uso")
- Sistema
![Límites del sistema](https://d2bzx2vuetkzse.cloudfront.net/fit-in/0x450/unshoppable_producs/817bab4c-19f1-44bd-a069-6afd6d03be18.png "Límites del sistema")


Puede haber relaciones de inclusión (obligatorias para una acción) o extensión
(opcionales).

CU=003
Nombre=Consultar asistencias
Actor=Personal académico
Precondición=Registrar usuario, Registrar asistencia
Descripción =	1.- El docente registra usuario/contraseña en el sistema
		2.- El sistema verifica que usuario/contraseña existan en el sistema
		3.- El sistema muestra cursos
		4.- El docente selecciona un curso a revisar
		5.- El docente muestra menú de consulta (por día o por fecha espefícica)
		6.- El docente selecciona tipo de consulta
		7.- El sistema muestra las asistencias de los alumnos
Excepción=	2.1.- El sistema envía un mensaje de error
		6.1.- No se seleccionó nada
		7.1.- No hubo asistencia

# ¿Qué es el diseño del sistem?
Es la fase donde se define cómo fucionará el sistema

## ¿Por qué es importante?
- Facilita la comprensión y mantenimiento del software
- Reduce errores y trabajo en etapas posteriores
- Permite la reutilización de componentenes
- Mejora la calidad del producto final

## Tipos de diseño
Diseño arquitectónico
Diseño de alto nivel (modular)
Diseño detallado (estructural)
Diseño de interfaz de usuario
Diseño de bases de datos


## Diseño arquitectónico
Define la estructura general del sistema.
Incluye patrones como MVC, cliente-servidor, microservicios.

Ejemplo: separar frontend, backend, y base de datos.

## Diseño de alto nivel (modular)

Divide el sistema en módulos o componentes.
Define responsabilidades, entradas y salidas

Ejemplo: Módulo de autenticación, módulo de pagos, etc.

## Diseño detallado

Define estructuras internas, algoritmos y clases.
Incluye diagramas de clases, estructuras de datos.

Ejemplo: Diagrama UML de clases para una app de reservas.

## Diseño de interfaz de usuario

Define la experiencia visual del usuario.
Utiliza wireframes, mockups, guías de estilo.

Ejemplo: pantalla de login con validación de campos.

## Diseño de base de datos

Define la estructura lógica de almacenamiento.
Utiliza modelos de entidad-relación, normalización.

Ejemplo: Tabla de usuarios, reservas, clases.

# Estructura de contenidos

Es la forma en que se agrupa, clasifica y jerarquiza la información.
Puede ser jerárquica, secuencial, matricial o temática.

Ejemplo:
En un sistema de biblioteca digital-
- Jerárquico -> Libros -> Categoría -> Subcategoría -> Título
- Temático -> Libros por temas


# Sistemas de navegación
Permiten al usuario desplazarse dentro del sistema o sitio.
Incluyen menús, enlaces, rutas de navegación y accesos directos.

Ejemplo:
- Migajas de pan: Inicio > Cursos > Ingeniería de Software > Unidad

# Sistemas de rotulado

Son las palabras, íconos o frases utilizadas para representar la información.
Deben ser claros, consistentes y comprensibles.

# Sistemas de búsqueda y recuperación
Mecanismos que permiten encontrar contenido específico mediante palaras clave,
filtros o categorización

En una tienda online

- Búsqueda por nombre, categoría precio
- Filtro: precio mínimo, máximo, disponibilidad, marca

# ¿Qué es el diseño de bases de datos?
Proceso de definir la estructura lógica para el almacenamiento de datos.
Incluye identificación.

## Etapas del diseño de bases de datos
- Recoleción de requerimientos.
- Modelo entidad-relación.
- Conversión al modelo relacional.
- Normalización.
- Implementación.

## Diseño Conceptual (modelo ER)
Es una representación gráfica abastracta de la información usando entidades,
atributos y relaciones.

Ejemplo:
- Entidades: Alumno, Materia, Profesor, Calificación.

## Diseño lógico

Transforma el modelo ER en tablas relacionales que se implementarán en una
base de datos (se crean tablas).

## Normalización

Proceso para eliminar redundancias y dependencias no deseadas dividiendo tablas
o reestructurándolas en formas normales (1FN, 2FN, 3FN, ...).

Si en una tabla "Alumno" hay múltiples columnas como materia_1, materia_2, etc.,
debe separarse esa información en una tabla aparte llamada inscripciones.

Evitar inconsistencias (ej. cambiar el nombre de una materia en múltiples 
columnas).

## Implementación

Traducción del diseño lógico a código SQL en un sistema de gestión de bases
de datos.

# ¿Qué es la interfaz de usuario?
## ¿Qué es la experiencia de usuario? (UX vs UI)

UX: sensación general del usuario al usar el sistema (eficacia, satisfacción).
Ejemplo: una app bancaria clara y rápida = buena UX + IU bien diseñada.

## Principios de una buena IU

- Claridad.
- Consistencia.
- Retroalimentación inmediata.
- Prevención de errores.
- Flexibilidad y eficiencia.

## Elementos clave para un buen diseño de IU

- Layout (disposición visual).
- Tipografía.
- Colores y contraste.
- Íconos y simbología.
- Fomrularios.
- Controles de navegación.

# Usabilidad

## Preguntas para guiar el diseño
- ¿Qué tareas debe realizar el usuario?
- ¿Qué contexto (dispositivo, entorno) usa?
- ¿Qué errores puede cometer y cómo prevenirlos?
- ¿El diseño es accesible e inclusivo?

# Pruebas
## Tipos de costos asociados a las pruebas
- Costos directos: personal, herramientas, tiempo.
- Costos indirectos: entrenamiento, mantenimiento, reportes.

## ¿Qué pasa si no se hacen pruebas eficientes?
- Baja confianza del cliente
- Reputación afectada.
- Costos de correción hasta 100 veces mayores.
- Riesgos legales.

## Mitos comunes
"Probar es caro" vs. "No probar es mucho más caro".

"El cliente encontrará los errores" vs. "Eso podría destruir la relación comercial".

## Herramientas y estrategias de bajo costo
- Pruebas unitarias
- Integración continua
- Pruebas basadas en riesgo

## Errores
- Error (mistake): Acción humana incorrecta que introduce defectos.
- Defecto (bug): Imperfección en código o diseño.
- Falla (failure): COmportamiento onccorrecto en ejecución.
- Problema (issue): Término general ara registrar incidentes.

## Tipos de errores
- Sintaxis: Violaciones del lenguaje.
- Lógicos: Mal razonamiento.
- Diseño: Arquitectura inadecuada.
- Integración: Problemas entre módulos.
- Configuración: Parámetros erróneos.

## Fallas comunes
- Rendimiento: Respuesta lenta o bloqueos.
- Seguridad: Vulnerabilidades explotados.
- Usabilidad: Experiencia negativa del usuario.
- Compatibilidad: Fallos en diferentes entornos.
- Concurrencia: Problemas multihilo.

## Problemas estructurales
- Falta de pruebas automatizadas.
- Casos límite no considerados.
- Código inconsistente o sin revisión.
- Ambigüedad en los requisitos
- Documentación deficiente

## Impacto económico
- Corregir en la producción cuesta 10-100 veces más.
- Daño a la reputación de la empresa.
- Pérdida de clientes.
- Posibles consecuencias legales.

## Conclusión

- Prevenir errores es más eficiente que corregirlos.
- El aseguramiento de calidad es una inversión estratégica.
- Comprender las fallas permite diseñar software con mayor eficiencia.

## Lecutras recomendadas
- 'Software Testing: Principles and Practices' - Desikan & Ramesh.
- "The Art of"

### Pregunta de reflexión
- "¿Qué pasaría con el prestigio de tu empresa si un cliente detecta un error crítico antes que tú?"

### Cuestionario
1.- ¿Cuál de los siguientes costos no está asociado a las pruebas?
a) Herramientas
b) Capacitación
c) Costos legales (x)
d) Ambientes

2.- ¿Cuál es un beneficio de las pruebas tempranas?
a) Menos usuarios beta
b) Menos fallas de hardware
c) Prevención de defectos (x)
d) Más personal

3.- ¿Qué provocó la pérdida del Mars Climate Orbiter?
a Malware
b Error lógico
c Unidades erróneas (x)
d Memoria

4.- ¿Qué afirmación es falsa?
a) Automatización posible
b) Probar eleva costos (x)
c) Errores costosos
d) Pruebas mejoran entregan.


5.- ¿Qué herramienta ofrece?
x) Automatización


###¿Qué porcentaje de los proyectos de software fallan por problemas en los requerimientos?

Entre el 60 y el 80 por ciento de los proyectos de software fallan total o parcialmente debido a problemas relacionados con los requerimientos.

- Requerimientos incompletos o cambiantes sin control.
- Falta de entendimiento claro entre usuarios y desarrolladores.
- Documentación ambigua o contradictoria.
- Ausencia de validación constante con el cliente.
