Propuesta del sistema “MercaDito Libre”
Fundamentos de Ingeniería de Software.


 Elaborado por “Equipo Ternurin”

•	Aguilera Rico Abril Gisel
•	Álvarez Rodríguez America Aurora
•	Fierro Luevanos Ruben Joel
•	Martínez Ortiz Marco Antonio
•	Sáenz González Diego Arath


Fecha de entrega:
08 de marzo del 2026



Contenido

1.	Descripción general del sistema.	3
a.	Nombre.	3
b.	Problema que soluciona al sistema.	3
c.	Usuarios principales.	3
d.	Objetivo general.	3
2.	Procesos (de la aplicación)	3
a.	Proceso de desarrollo.	3
i.	Metodología de desarrollo elegida	3
ii.	Justificación	3
b.	Actividades principales.	4
i.	Análisis.	4
ii.	Diseño.	4
iii.	Desarrollo.	4
iv.	Pruebas.	4
v.	Entregas.	5
c.	Flujo de trabajo (en un diagrama de flujo).	5
d.	Control de calidad.	6
i.	¿Como evitarán errores?	6
ii.  ¿Qué practicas utilizaran?	6
3.	Proyecto.	7
a.	Definición del proyecto.	7
i.	Alcance.	7
ii.	Entregable.	8
b.	Planificación básica (en Jira).	8
i.	Cronograma (6 semanas simuladas).	8
ii.	Fases.	10
c.	Recursos.	10
i.	Humanos.	10
ii.	Técnicos.	10
d.	Riesgos identificados	11
e.	Métricas del proyecto.	12
i.	Tiempos	12
ii.	Costo estimado	12
iii.	Indicadores del avance	12
5. Producto.	12
a.	Funcionalidades principales.	12
c.	Características del software.	13

 
1.	Descripción general del sistema.
a.	Nombre.
El nombre de nuestro sistema es MercaDito Libre.
b.	Problema que soluciona al sistema.
El comercio estudiantil en la UACJ se apoya actualmente en grupos de Facebook que, al ser informales, resultan muy desorganizados. El problema principal es la saturación de información: las ventas se mezclan con noticias y avisos, obligando al usuario a navegar por publicaciones irrelevantes para encontrar lo que busca.
Además, no existe un control de stock, los alumnos pierden tiempo preguntando por la disponibilidad de productos que ya se agotaron. Nuestro sistema soluciona esto mediante categorías específicas y la opción de deshabilitar productos en tiempo real, optimizando el tiempo de toda la comunidad. 
c.	Usuarios principales.
El sistema está diseñado específicamente para los estudiantes de la UACJ. Se enfoca tanto en los alumnos que buscan emprender dentro de los institutos como en aquellos que necesitan localizar artículos o alimentos de manera rápida entre clases.
d.	Objetivo general.
Desarrollar una plataforma digital de comercio estudiantil categorizada para la comunidad de la UACJ, con el fin de optimizar la búsqueda de artículos y alimentos, eliminando la saturación de información propia de redes sociales informales.
2.	Procesos (de la aplicación)
a.	Proceso de desarrollo.

i.	Metodología de desarrollo elegida
Como principales metodologías de desarrollo, hemos decidido seleccionar Ágil – SCRUM.

ii.	Justificación
Hemos seleccionado la metodología SCRUM debido a que el proyecto tiene un cronograma de ejecución corto y requiere de una entrega de valor incremental. Al trabajar con con Jira, esta metodología permite una integración natural para gestionar procesos y dividir el trabajo en sprints de dos semanas.
b.	Actividades principales.
i.	Análisis. 
Para asegurar el éxito de MercaDito Libre, el proceso se dividirá en las siguientes fases operativas:
•	Levantamiento de requerimientos: Identificación de las necesidades críticas de los estudiantes (vendedores y compradores).
•	Historias de Usuario: Creación de tickets en Jira que describan las funciones desde la perspectiva del alumno.
•	Definición de reglas de negocio: Establecer los criterios para las categorías y el flujo de validación de usuarios de la UACJ.
ii.	Diseño. 
•	Arquitectura de datos: Diseño del modelo entidad-relación para la base de datos (usuarios, productos, categorías).
•	Diseño de interfaz (UI/UX): Creación de prototipos enfocados en la navegación rápida y la facilidad de uso en dispositivos móviles.
•	Definición de API: Especificación de los puntos de enlace (endpoints) que conectarán el frontend con el servidor.

iii.	Desarrollo.
•	Configuración del entorno: Preparación del repositorio en GitHub y definición de la estrategia de ramas.
•	Implementación de Sprints: Codificación de los módulos de autenticación, catálogo de productos y panel de administración de stock.
•	Revisiones de código: Uso de Pull Requests en GitHub para asegurar que el código subido por cada integrante cumpla con los estándares del equipo.

iv.	Pruebas. 
•	Pruebas unitarias: Verificación de funciones individuales (ej. el cambio de estado de un producto de "disponible" a "agotado").
•	Pruebas de integración: Asegurar que el frontend se comunique correctamente con la base de datos.
•	Pruebas de usuario: Sesiones de prueba con alumnos reales para evaluar la facilidad de navegación y la claridad de las categorías.

v.	Entregas.
•	Despliegue: Carga del sistema en el entorno de producción o infraestructura elegida.
•	Documentación técnica: Finalización del manual de usuario y documentación del código en el README del repositorio.
•	Cierre del proyecto: Presentación de los resultados finales y revisión de métricas en Jira.

c.	Flujo de trabajo (en un diagrama de flujo).

 Imagenes/Diagrama.jpg



El flujo de trabajo del sistema MercaDito Libre describe las etapas principales que sigue el desarrollo y funcionamiento de la plataforma. El proceso inicia con el levantamiento de requerimientos, donde se identifican las necesidades de los estudiantes que utilizarán la plataforma. Posteriormente, se realiza el análisis y diseño del sistema.
Una vez finalizada la etapa de diseño, se procede al desarrollo del sistema, el cual se implementa mediante la metodología ágil SCRUM en ciclos de trabajo llamados sprints. Durante esta fase se desarrollan los módulos principales como la información de productos y el control de disponibilidad de estos.
Posteriormente se realizan pruebas del sistema, incluyendo pruebas con usuarios, con el objetivo de verificar el correcto funcionamiento de la plataforma y detectar posibles errores.
Finalmente, cuando el sistema cumple con los requisitos establecidos, se realiza el despliegue del sistema y el proceso concluye con la presentación final del proyecto.

d.	Control de calidad.

i.	¿Como evitarán errores?
Para reducir la aparición de errores durante el desarrollo del sistema MercaDito Libre, el equipo aplicará diferentes mecanismos de control de calidad a lo largo de todo el ciclo de desarrollo. Entre ellos se encuentran las revisiones periódicas del código, la implementación de pruebas unitarias e integración, y la validación de funcionalidades mediante pruebas con usuarios reales.
Además, el uso de herramientas como GitHub permitirá llevar un control de versiones del proyecto, evitando conflictos en el código y permitiendo identificar cambios realizados por cada integrante del equipo.

ii.  ¿Qué practicas utilizaran?
El equipo implementará diversas prácticas de desarrollo para garantizar la calidad del software, entre las cuales destacan:
•	Control de versiones con GitHub, para mantener un historial de cambios y facilitar el trabajo colaborativo.
•	Pruebas continuas del sistema, incluyendo pruebas unitarias y de integración.
•	Documentación del proyecto, mediante comentarios en el código para facilitar el mantenimiento del sistema.
Estas prácticas permiten mejorar la organización del proyecto, reducir errores y asegurar que el sistema final cumpla con los requerimientos establecidos.
3.	Proyecto.
a.	Definición del proyecto.
i.	Alcance.
El proyecto consiste en el diseño de un sistema llamado MercaDito Libre, el cual se enfoca exclusivamente en estudiantes de la Universidad Autónoma de Ciudad Juárez (UACJ), que permitirá la compra, venta e intercambio de productos dentro de la comunidad universitaria. 

El sistema buscara mejorar la organización del comercio estudiantil que actualmente se realiza principalmente en grupos de Facebook donde la información suele mezclarse con publicaciones irrelevantes y no hay un control claro sobre la disponibilidad de productos ni sobre la identidad de los usuarios. 
 
En el proyecto se contemplará el diseño de las siguientes funcionalidades principales:
 
·	Inventario: Permitirá a los vendedores actualizar la disponibilidad de sus productos en tiempo real, evitando que los estudiantes pierdan tiempo preguntando por artículos que ya no se encuentran disponibles. 
·	Sistema de categorías: El sistema contara con categorías organizadas que faciliten la búsqueda de productos como libros, ropa, artículos escolares como calculadoras, alimentos, servicios y otros artículos que sean de interés para los estudiantes. 
·	Clasificación por institutos: Se permitirá filtrar productos según los institutos de la universidad (ICSA, IIT, IADA, ICB y CU) para facilitar encontrar vendedores cercanos dentro del campus y coordinar entregas de manera más práctica.
·	Validación institucional: El acceso a la plataforma estará restringido únicamente a miembros de la comunidad universitaria mediante la validación de matrícula o correo electrónico de la UACJ, lo que permitirá garantizar que los usuarios pertenecen realmente a la universidad
 
El sistema no permitirá los pagos dentro de la plataforma, estos se llevarán únicamente físicamente de persona a persona ya sea por efectivo o transferencia.

ii.	Entregable.
Para la propuesta del sistema MercaDito Libre se generarán los siguientes entregables:
·	Primera parte del documento: donde se incluye la descripción general del sistema, los procesos del desarrollo y la planificación del proyecto
·	Segunda entrega del documento: donde se incluye la definición de los roles de las personas, responsabilidades, etc. Para el producto cuales son las funciones principales del sistema, los requisitos, características y criterios de calidad. También incluye la tecnología, donde se especificarán las herramientas, lenguajes y plataformas que se utilizarían para el desarrollo del sistema.
·	Documento final: Se entregará el documento completo que integre la primera y segunda parte, presentando la propuesta del sistema MercaDito Libre.

b.	Planificación básica (en Jira).
i.	Cronograma (6 semanas simuladas).
La planificación del proyecto se organizó mediante la herramienta de gestión de proyectos Jira, donde se registraron las tareas correspondientes a cada fase del desarrollo del sistema y se estructuró un cronograma simulado de seis semanas.
   Imagenes/Planificación1.jpg
   Imagenes/Planificación2.jpg
   Imagenes/Planificación3.jpg
   Imagenes/Planificación4.jpg


 
ii.	Fases.
El proyecto se divide en las siguientes fases principales:
1.	Análisis: Se identifican los problemas actuales del comercio estudiantil y se definen los requisitos del sistema.
2.	Diseño: Se define la estructura del sistema, sus módulos principales y la organización de los productos dentro de la plataforma.
3.	Desarrollo (simulado): Se plantea la implementación de las funcionalidades principales del sistema.
4.	Pruebas: Se revisan las funcionalidades del sistema con el objetivo de detectar posibles errores o mejoras.
5.	Entrega: Se prepara la documentación final del proyecto y la presentación de la propuesta del sistema.

c.	Recursos.

i.	Humanos.

Para el desarrollo de la propuesta del sistema MercaDito Libre se contará con un equipo de trabajo conformado por cinco integrantes. Cada miembro del equipo participará en diferentes actividades del proyecto:
·	Project Manager: un responsable de la planificación estratégica, gestión del tablero en Jira y cumplimiento del cronograma de 6 semanas.
·	Diseñadores UI/UX: dos diseñadores encargados del diseño visual de la plataforma, la creación de prototipos en Figma y de asegurar que la navegación sea intuitiva para los estudiantes.
·	Desarrolladores de Software: dos desarrolladores responsables de la arquitectura técnica, la lógica del control de stock y la gestión del repositorio en GitHub.

ii.	Técnicos.
Para el desarrollo de la propuesta del sistema se utilizarán herramientas tecnológicas que facilitarán la planificación, documentación y organización del proyecto de MercaDito Libre.
·	Software de Gestión: utilizaremos Jira para el seguimiento de las 6 semanas de cronograma.
·	Plataformas de Colaboración: usaremos GitHub para el control de versiones del desarrollo de MercaDito Libre y Google Docs para la elaboración del documento del proyecto.
·	Herramientas de Diseño: usaremos Figma para hacer prototipos de la interfaz de usuario del sistema.
·	Hardware: se ocuparán estaciones de trabajo con laptops o PC con acceso a la red de la UACJ para pruebas de conectividad y bases de datos locales como MySQL/XAMPP para simular el inventario.
·	Comunicación: Utilizaremos la plataforma de Microsoft Teams para hacer reuniones y ver el avance de las actividades, corrección de errores, etc.


d.	Riesgos identificados

Bajo uso por parte de los estudiantes: Existe el riesgo de que pocos alumnos utilicen la aplicación al inicio.
•	Mitigación: Lanzar una campaña de marketing dentro del campus y ofrecer incentivos iniciales para los primeros usuarios registrados.
Acceso de personas externas no autorizadas o creación de cuentas falsas que generen desconfianza en la plataforma.
•	Mitigación:  Implementar un módulo de autenticación institucional que valide la matrícula del estudiante contra la base de datos de la UACJ. Esto asegura que solo alumnos activos puedan registrarse y publicar artículos, creando un entorno cerrado y seguro. Además, se incluirá un sistema de reporte de usuarios dentro de la app para que la comunidad misma pueda señalar comportamientos sospechosos, aumentando el control social sobre la plataforma.

Retrasos en el desarrollo: El equipo podría no cumplir con el cronograma de 6 semanas.
•	Mitigación: Utilizar la metodología Scrum con sprints semanales y reuniones de seguimiento constantes en Microsoft Teams para ajustar tareas en tiempo real.
Errores técnicos o fallas en el servidor: Problemas con la base de datos o conectividad a la red de la universidad.
•	Mitigación: Realizar pruebas de carga en entornos locales (XAMPP) y mantener un repositorio de versiones actualizado constantemente en GitHub para revertir cambios si es necesario.
Falta de comunicación entre el equipo: Que los cambios de diseño o lógica no sean compartidos.
•	Mitigación: Centrar toda la gestión y comunicación en el tablero de Jira y Microsoft Teams, manteniendo los prototipos de Figma accesibles para todo el equipo en todo momento.

e.	Métricas del proyecto.
i.	Tiempos
 El proyecto se mide estrictamente sobre un cronograma de 6 semanas. El éxito se define por la entrega de los hitos establecidos al final de cada sprint semanal.

ii.	Costo estimado
 Al tratarse de un proyecto académico interno, el costo se mide en horas. Se estima un esfuerzo total basado en los 5 integrantes del equipo dedicando tiempo a diseño, desarrollo y gestión durante las 6 semanas.

iii.	Indicadores del avance
	Estado de GitHub: Número de commits y funcionalidades integradas al repositorio principal.
	Cumplimiento de prototipos: Porcentaje de pantallas de la interfaz validadas en Figma y aprobadas por el equipo.

6. Tecnologia

a. Lenguaje elegido

Para el desarrollo del sistema MercaDito Libre se propone utilizar JavaScript como lenguaje principal de programación, ya que permite desarrollar tanto el frontend como el backend del sistema utilizando tecnologías modernas de desarrollo web.

En el lado del cliente se utilizará JavaScript junto con HTML y CSS para construir la interfaz del sistema, permitiendo que los estudiantes puedan navegar fácilmente por las categorías de productos, publicar artículos y gestionar su inventario desde cualquier navegador o dispositivo móvil.

Para el lado del servidor se propone utilizar Node.js, lo que permitirá gestionar la lógica del sistema, como el registro de usuarios, autenticación mediante correo institucional, manejo de inventario y comunicación con la base de datos.

b. Herramientas

Durante el desarrollo del sistema se utilizarán diferentes herramientas tecnológicas que permitirán organizar el trabajo del equipo, diseñar la interfaz y gestionar el proyecto de manera eficiente.

Entre las principales herramientas se encuentran:

Jira:
Se utilizará para la gestión del proyecto y la organización de tareas mediante un tablero de trabajo basado en la metodología Scrum. En esta herramienta se registrarán las historias de usuario, sprints y el seguimiento del progreso del equipo.

Figma:
Será utilizada para el diseño de la interfaz gráfica del sistema y la creación de prototipos de navegación. Esto permitirá visualizar cómo funcionará la aplicación antes de comenzar el desarrollo.

Visual Studio Code:
Será el editor de código principal utilizado por los desarrolladores para programar las funcionalidades del sistema.

MySQL / XAMPP:
Se utilizará para la simulación y gestión de la base de datos del sistema, permitiendo almacenar información sobre usuarios, productos, categorías y disponibilidad de inventario.



c. Control de versiones (GitHub)

Para el control de versiones del proyecto se utilizará la plataforma GitHub, la cual permitirá almacenar el repositorio del sistema MercaDito Libre y mantener un historial completo de los cambios realizados en el proyecto.

El uso de GitHub permitirá que todos los integrantes del equipo puedan colaborar en el desarrollo del proyecto de manera organizada, subiendo sus cambios mediante commits y revisiones de código. Además, se utilizará una estrategia de ramas para evitar conflictos en el desarrollo, donde las nuevas funcionalidades serán desarrolladas en ramas independientes antes de ser integradas a la rama principal.

También se utilizarán Pull Requests, los cuales permitirán revisar el código antes de integrarlo al repositorio principal, asegurando que el código cumpla con los estándares del equipo y evitando errores en el sistema.

El control de versiones mediante GitHub facilita el trabajo colaborativo, mejora la organización del proyecto y permite recuperar versiones anteriores del código en caso de errores o fallas.

5. Producto.
a.	Funcionalidades principales.
Estas son las funciones clave que permiten que el sistema cumpla con su propósito de organizar el comercio en la UACJ: 
•	Autenticación Institucional: Acceso restringido exclusivamente a estudiantes mediante la validación de matrícula o correo de la UACJ.
•	Gestión de Inventario en Tiempo Real: Panel para que el vendedor publique artículos y pueda deshabilitarlos o marcarlos como "agotados" al instante.
•	Buscador Categorizado: Filtros por tipo de producto como libros, alimentos, servicios y material escolar para evitar contenido irrelevante.
•	Clasificación por Institutos: Opción para filtrar productos según el campus (ICSA, IIT, IADA, ICB o CU) y facilitar la entrega física.
•	Sistema de Reporte Comunitario: Herramienta para señalar comportamientos sospechosos o cuentas falsas, reforzando la seguridad del entorno.
•	Perfil de Usuario Personalizado: Espacio para gestionar el historial de publicaciones activas y datos de contacto institucionales.
•	Catálogo de Favoritos: Función para guardar artículos de interés y localizarlos rápidamente sin que se pierdan en el feed.
•	Enlace de Contacto Directo: Botón para acordar puntos de entrega dentro del instituto sin exponer datos privados de forma pública.
•	Búsqueda por Palabras Clave: Motor de búsqueda para localizar artículos específicos de forma inmediata.


b.	Características del software.
MercaDito Libre se define por las siguientes cualidades técnicas y de experiencia de uso:
•	Exclusividad Universitaria: Entorno cerrado que garantiza que todos los participantes son miembros activos de la UACJ.
•	Diseño Mobile-First: Interfaz optimizada para una navegación rápida y sencilla desde dispositivos móviles entre clases.
•	Gestión de Stock Dinámica: Prioriza la visibilidad de la disponibilidad real de los productos, a diferencia de las redes sociales convencionales.
•	Interacción Híbrida: El sistema gestiona la información, pero el pago y la entrega se realizan físicamente (efectivo o transferencia).
•	Arquitectura Escalable y Ágil: Desarrollado bajo metodología SCRUM, permitiendo añadir funciones de forma incremental.
•	Navegación Intuitiva (UI/UX): Diseño enfocado en encontrar lo que se busca con el menor número de clics posibles.
•	Eficiencia en Consumo de Datos: Optimización de recursos para funcionar correctamente con el Wi-Fi universitario o datos móviles.
•	Sincronización en Tiempo Real: Los cambios en el inventario se reflejan inmediatamente para evitar desinformación sobre el stock.
