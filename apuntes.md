# Objetivos de la clase de Ingeniería de Software

- Formar competencias para diseñar, desarrollar y gestionar proyectos de software
de calidad.
- Aplicación de metodologías, modelos de proceso y técnicas de ingeniería de
software.

## ¿Por qué es importante aprender Ingeniería de Software?

- Desarrollo de software con calidad profesional.
- Reducción.

## Contenido General del Curso

- Introducción a la Ingeniería de Software.
- Modelos de Proceso de Desarrollo.
- Ingeniería de Requerimientos.
- Diseño e Implementación de Software.
- Pruebas y Mantenimiento.
- Herramientas CASE.

## Criterios de evaluación
| Criterios de evaluación | |
|---|---|
| Actividades | 25% |
| Tareas | 15% |
| Examen | 20% |
| Lecturas | 15% |
| Proyecto final | 25% |
| Asistencia y participación en clase | |
| Entrega puntual de trabajos y lecturas | |

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
a) Herramientas.
b) Capacitación.
c) Costos legales. (x)
d) Ambientes.

2.- ¿Cuál es un beneficio de las pruebas tempranas?
a) Menos usuarios beta.
b) Menos fallas de hardware.
c) Prevención de defectos. (x)
d) Más personal.

3.- ¿Qué provocó la pérdida del Mars Climate Orbiter?
a Malware.
b Error lógico.
c Unidades erróneas. (x)
d Memoria.

4.- ¿Qué afirmación es falsa?
a) Automatización posible.
b) Probar eleva costos. (x)
c) Errores costosos.
d) Pruebas mejoran entregan.

5.- ¿Qué herramienta ofrece?
x) Automatización.

### ¿Qué porcentaje de los proyectos de software fallan por problemas en los requerimientos?

Diversos estudios han señalado que entre el 60% y el 80% de los proyectos de software fallan total o parcialmente debido a problemas relacionados con los requerimientos.

- Requerimientos incompletos o cambiantes sin control.
- Falta de entendimiento claro entre usuarios y desarrolladores.
- Documentación ambigua o contradictoria.
- Ausencia de validación constante con el cliente.

### ¿Por qué sigue habiendo software defectuoso a pesar de tantos avances tecnológicos y metodológicos?

- Requerimientos mal definidos.
- Pruebas insuficientes o mal planificadas.
- Mala gestión de confiruación y versiones.
- Presión de entrega y fechas políticas.
- Falta de cultura de calidad.

## Puntos importantes para prevenir el deterioro de la calidad
- Involucrar a los usuarios desde el levantamiento de requerimientos.
- Implementar pruebas automatizadas y estrategias de prueba continua.
- Adoptar herramientas de integración y entrega continua (CI/CD).
- Formar una cultura de mejora continua y revisiones cruzada.
- Establecer políticas de control de versiones y configuración.

### Considera...
que la calidad no es una fase, es una cultura.
- Cada práctica contribuye a construir software robusto, mantenible y alineado con las necesidades del usuario.

## Ejemplos visuales de buenas prácticas
- Pipeline CI/CD con Jenkins y GitHub Actions.
- Matriz de pruebas automatizadas (unitarias, integración, UI).
- Flujo de revisión de código con `pull requests`.
- Tablera Kanban para gestión ágil.

## ¿Qué tan seguro estás de que tu software funciona correctamente... sin haberlo probado?

## Pruebas
Las pruebas intentan demostrar que un programa hace lo que se intenta que haga, así como descubrir defectos en el programa antes de usarlo.
- Validación: Se ocupa de controlar si el producto satisface los requerimientos del usuario.
- Verificación: Implica comprobar que el software cumpla con su funcionalidad y con los requerimientos no funcionales establecidos.

### Conceptos
Una prueba de software es todo proceso orientado a comprobar la calidad del software mediante la identificación de fallos en el mismo.
Un caso de pruebas es un conjunto de entradas, condiciones de ejecución y resultados esperados que han sido desarrollados para un objetivo particular.

### Etapas de las pruebas
Las pruebas se realizan en cuantro etapas:
- Prueba de unidades (prueba de métodos y clases).
- Prueba de integración o de subsistemas.
- Prueba de sistema.
- Prueba de validación (o de aceptación).

### Ejemplo - Windows 10 Update (2020)
- Fallos por pryebas insuficientes de compatibilidad.
- Causó pérdidad de archivos personales en algunas actualizaciones.
- Generó mala prensa y pérdida de confianza.

### Importancia de una buena estrategia de pruebas
- Las pruebas deben cubrir desde los más pequeño (función) hasta lo más grande (todo el sistema).
- No basta con probar una vez.


### ¿Confías lo suficiente en tu código como para que lo usen miles de personas sin que falle?

### Pruebas por conocimiento del código
- Caja blanca: conoce la lógica del software
- Caja negra: se enfoca en entradas y salidas sin concoer el código
- Caja gris: combina ambos enfoques para mayor cobertura

La caja blanca usa herramientas con o combertura de flujo, ejecuta pruebas que abarquen cada rama del código y su técnica usada es el análisis del flujo de control

La caja negra emplea las técnicas partición de equivalencia, valores límites.

La caja gris se suele emplear en la integración de frontend y backend o validación de API's con conocimiento parcial del backend.

## Pruebas por niveles
1.- Pruebas unitarias
2.- Pruebas de integración
3.- Pruebas funcionales
4.- Pruebas de rendimiento
5.- Pruebas de aceptación
6.- Pruebas de instalación

## Pruebas unitarias
- Validan funciones, métodos o componentes individuales.
- Se realizan por desarrolladores.
- Verifican que una función de cálculo retorne el resultado correcto, por ejemplo.

## Pruebas de integración
- Validan la interacción entre módulos o servicios.
- Se aseguran de que los datos fluyen correctamente.

## Pruebas de sistema - funcionales
Evalúan 

## Pruebas de sistema - rendimiento
- Miden la velocidad, capacidad y estabilidad del sistema.
- Se realizan con herramientas como JMeter o Gatling.

## Pruebas de aceptación
Validan que el sistema satisface los criterios del cliente.
Se realizan junto con el usuario final.

## Pruebas de instalación
Verifican que el software se puede instalar y configurar correctamente
Se prueban rutas, pemisos dependencias y configuración,


## Clasificación de las técnicas de pruebas
|Base de clasificación|Técnicas específicas|
|---|---|
| Técnicas basadas en la intuición y experiencia | Prueba ad hoc / Pruebas por exploración |
| Técnicas basadas en la especificación | Partición de equivalencia / Análisis de valores límite / Pruebas de robustez / Tablas de decisión / Pruebas basadas en máquinas de estado finito / Pruebas basadas en especificaciones formales / Pruebas aleatorias |
| Técnicas basadas en el código  | Pruebas de cobertura basadas en flujo de control / Pruebas de cobertura basadas en flujo de datos |
| Técnicas basadas en errores  | Pruebas de conjetura de errores / Pruebas de mutación |
| Técnicas estáticas | Pruebas de sala ímpia |
| Técnicas ||


1.- Técnicas de diseño de casos de prueba
- Particiones de equivalencia.
- Divide las entradas en grupos que se comparten de forma similar.
- Reduce el número de casos sin perder efectividad.

2.- Análisis de valores límite
- Se basa en los errores que suelen ocurrir en los bordes de las entradas válidas.
- Límite inferior/superior y sus alrededores.

3.- Robustez
- Evalúan cómo responde el sistema ante entradas incorrectas o inesperadas.
- Validar que el sistema no colapse y brinde mensajes adecuados.

4.- Tablas de decisión
- Usadas cuando hay múltiples condiciones y sus combinaciones.

5.- Pruebas basadas en máquinas de estado finito.
- Se modela el sistema como una serie de estados y transiciones.
- Se verifica que las transiciones ocurran correctamente.

6.- Pruebas basadas en especificaciones formales
- Derivan casos de prueba a apartir de especificaciones matemáticas o lógicas

7.- Pruebas aleatorias
- Se generan entradas al azar dentro de un rango permitido.
- Útiles para probar robustez o encontrar errores inesperados.

### Pregunta: ¿Tus pruebas actuales están diseñadas pensando en el código o en el usuario final que lo utilizará?

Las técnicas de evaluación en Interacción HUmano-Computadora permiten analizar la efectividad, eficiencia y satisfacción del usuario en sistemas interactivos.

Se basan en principios ergonómicos, modelos de desempeño humano y métodos de evaluación cualitativos y cuantitativos.

## Métodos de evaluación

Cualitativos; Se basan en observaciones y entrevistas para comprender la experiencia de usuario.
Cuantitativos: Utilizan métricas objetivas como tiempos de respuesta y número de errores.


Los métodos cualitativos buscan comprender cómo y por qué los usuarios interactúan con un sistema.
Se enfocan en la experiencia subjetiva, percepción y comportamiento de los usuarios.
- Entrevistas en profundidad.


Los métodos cuantitativos miden la interacción con el sistema usando datos numéricos. Permiten identificar tendenecias y patrones en la experiencia del usuario.
- Tiempos de ejecución de tareas.
- Número de errores cometidos.
- Análisis de registros.

CSUQ

Confiable
Simple
Alta correlación con los resultados (.94)
19 preguntas estructuradas en 4 grupos
Uso del sistema SYSUSE-Q1 a 8
Calidad e la información
Interfaz de calidad


# Documentación
Conjunto de artefactos que describen la arquitectura, uso y mantenimiento de un sistema.

Incluye los manuales.

- Documentación técnica para desarrolladores (diagramas, UML).
- Documentación de usuario (guías, tutoriales para las personas).
- Documentación de mantenimiento (bitácoras de cambio, historial de versiones).

# Mantenimiento

## Mantenimiento correctivo
Repara errorees luego de detectar fallos.

## Mantenimiento evolutivo
Agrega funciones por solicitud del usuario o nuevas necesidades del mercado.

## Mantenimiento perfectivo
Mejora el rendimiento, eficiencia o usabilidad sin cambiar la funcionalidad básica, ya sea por decisión técnica o experiencia UX.

## Mantenimiento adaptativo
Ajusta el software a cambios en el entorno técnico y a nuevas plataformas o tecnologías.


# Formatos estandarizados de la documentación
- IEEE 829: documentación de pruebas
- ISO/IEC 12207: procesos del ciclo de vida del software
- IEEE 830: especificación de requisitos
- Control de versiones semver (v1.2.3)

## Consejos para el software de calidad
- Documentar desde el análisis
- Usar control de versiones
- Aplicar pruebas continuas (CI/CD)
- Usar comentarios significativos en el código
- Priorizar mantenimiento y escalabilidad

