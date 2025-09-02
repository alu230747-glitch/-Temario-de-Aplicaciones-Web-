# -Temario-de-Aplicaciones-Web-
Comprender los fundamentos del desarrollo de aplicaciones web.
1.-Introducción al desarrollo web

*Historia y evolución del desarrollo web
-La historia del desarrollo web comenzó a principios de la década de 1990, cuando Tim Berners-Lee creó el primer navegador web y software de servidor. Inicialmente, las páginas web eran simples y estáticas, compuestas de código HTML (lenguaje de marcado de hipertexto). Estas páginas contenían texto, hipervínculos y formato básico. Se utilizaban principalmente para compartir información y presentaban poca interactividad.

*Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
-Las aplicaciones web estáticas muestran contenido fijo y predefinido, cargando páginas HTML completas. 
-Las aplicaciones web dinámicas generan contenido personalizado en tiempo real usando bases de datos para responder a los usuarios. 
-Las Aplicaciones de Página Única (SPA) son un tipo de aplicación dinámica que carga una sola página HTML y actualiza el contenido sin recargarla, ofreciendo una experiencia fluida. 
-Las Aplicaciones Web Progresivas (PWA) son aplicaciones web que combinan lo mejor de las aplicaciones web y nativas, permitiendo instalación, funcionamiento sin conexión y notificaciones push. 

2.Arquitectura de aplicaciones web

*Cliente-Servidor
-La arquitectura cliente-servidor es un modelo fundamental para las aplicaciones web donde un componente (el cliente) solicita servicios o datos, y otro (el servidor) los procesa y proporciona una respuesta a través de una red, como Internet. El cliente suele ser un navegador web o una aplicación móvil que interactúa con el usuario, mientras que el servidor se encarga del almacenamiento, el procesamiento de datos y la lógica de negocio.

*Arquitectura de tres capas (presentación, lógica, datos)
-La arquitectura de tres capas (o "three-tier") es un modelo de diseño de software que divide una aplicación en tres niveles lógicos y físicos distintos para mejorar el mantenimiento, la escalabilidad y la modularidad. Estos niveles son: la Capa de Presentación, que maneja la interacción con el usuario; la Capa de Lógica de Negocio, que contiene el procesamiento de datos y las reglas de la aplicación; y la Capa de Datos, que se encarga del almacenamiento y la gestión de la información. 

-1. Capa de Presentación (o Interfaz de Usuario):
Función: Es la interfaz con la que el usuario interactúa directamente. 
Responsabilidades: Muestra la información al usuario, recibe sus solicitudes y las envía a la siguiente capa para su procesamiento. 
Ejemplos: Vistas web, interfaces de consola, aplicaciones móviles o de escritorio. 

-2. Capa de Lógica de Negocio (o de Aplicación):
Función: Es el corazón de la aplicación, donde se procesan los datos y se aplican las reglas del negocio. 
Responsabilidades: Realiza cálculos, valida datos y ejecuta las tareas para las que fue creada la aplicación. 
Ventajas: Oculta el acceso a datos de la capa de presentación y puede ser escalada o modificada sin afectar las otras capas. 

-3. Capa de Datos (o de Persistencia):
Función: Se encarga del almacenamiento y la gestión de los datos de la aplicación. 
Responsabilidades: Se comunica con bases de datos u otros sistemas de persistencia para obtener y guardar información. 
Ejemplos: Servidores de bases de datos que almacenan los datos. 

*REST y API-first design
-¿Qué es REST?
Estilo arquitectónico:
REST (Representational State Transfer) es un estilo arquitectónico que define cómo deben interactuar los componentes de un sistema web. 
Basado en recursos:
Las APIs REST se centran en recursos, los cuales tienen un identificador único (URI) y se pueden manipular usando métodos HTTP estándar como GET, POST, PUT y DELETE. 
Independencia cliente-servidor:
Los principios de REST promueven una separación clara entre el cliente y el servidor, lo que aumenta la flexibilidad y la escalabilidad. 
Sin estado (Stateless):
Cada solicitud del cliente al servidor debe ser independiente, conteniendo toda la información necesaria para ser procesada sin depender de peticiones anteriores. 

-¿Qué es el diseño API-First?
Prioridad a las APIs:
Es un enfoque de desarrollo en el que las APIs se diseñan y definen como el elemento central de la aplicación desde el inicio del proyecto. 
Diseño antes que el código:
En lugar de considerar las APIs como un producto secundario, el enfoque API-First las sitúa como los pilares del software, diseñando la interfaz primero. 
Beneficios:
Este enfoque mejora la integración entre diferentes sistemas, fomenta la escalabilidad y puede acelerar el ciclo de desarrollo al definir claramente las interacciones esperadas. 
Ejemplo:
Implica definir cómo los clientes (aplicaciones móviles, sitios web) accederán a la aplicación y sus datos antes de empezar a escribir el código. 

3. -Lenguajes y tecnologías fundamentales

*HTML, CSS, JavaScript, PHP, MySQL
-1. HTML (HyperText Markup Language)
Propósito:
Es el lenguaje de marcado estándar para la creación de la estructura y el contenido de las páginas web. 
Función:
Define la organización del contenido mediante etiquetas (como párrafos, encabezados, imágenes y enlaces) para indicar al navegador qué es cada parte de la página.

-2. CSS (Cascading Style Sheets)
Propósito:
Se utiliza para definir la presentación y el estilo visual de los elementos HTML. 
Función:
Controla la apariencia de la página, como los colores, las fuentes, el diseño y el espaciado, independientemente de la estructura HTML. 

-3. JavaScript (JS)
Propósito: Aporta interactividad y dinamismo a las páginas web. 
Función: Permite crear animaciones, gestionar formularios, actualizar contenido de forma dinámica y añadir funcionalidades complejas al sitio web desde el navegador (lado del cliente). 

-4. PHP (Hypertext Preprocessor)
Propósito: Es un lenguaje de programación del lado del servidor. 
Función: Se utiliza para interactuar con bases de datos, gestionar formularios, crear sistemas de registro de usuarios y todo el contenido que se genera y se envía al navegador, haciendo que el sitio sea dinámico. 

-5. MySQL 
Propósito: Es un sistema de gestión de bases de datos relacionales.
Función: Almacena, organiza y recupera datos de manera eficiente, permitiendo que las aplicaciones web muestren contenido actualizado y gestionen información de los usuarios o del sitio.

4.-Control de versiones

*Git y GitHub
El Control de Versiones
-Qué es:

Un sistema que registra todos los cambios que se hacen en un proyecto a lo largo del tiempo, permitiendo a los usuarios volver a versiones anteriores si es necesario. 
Para qué sirve:
Historial: Mantiene un registro detallado de cada modificación, quién la hizo y cuándo. 
Recuperación: Permite restaurar el proyecto a un estado anterior en caso de errores o pérdida de información. 
Comparación: Facilita ver las diferencias entre distintas versiones del código o los archivos. 
Colaboración: Es fundamental para que varios desarrolladores puedan trabajar en un mismo proyecto. 

Git
-Qué es:

Un sistema de control de versiones distribuido (DVCS), que permite a los desarrolladores rastrear cambios en el código localmente y gestionar proyectos de forma individual o en equipo. 
Funciones principales:
Registro de cambios: Captura y almacena "snapshots" de las modificaciones del proyecto. 
Ramificaciones (Branches): Permite crear ramas independientes para trabajar en nuevas funcionalidades sin afectar la versión principal. 
Fusión de cambios: Facilita la integración de los cambios realizados por diferentes desarrolladores. 

GitHub
-Qué es:

Una plataforma web que se utiliza para alojar repositorios Git. Ofrece servicios adicionales para la gestión y colaboración de proyectos. 
Funciones principales:
Alojamiento de código: Almacena los repositorios Git en la nube, haciéndolos accesibles desde cualquier lugar. 
Colaboración: Permite a los equipos trabajar juntos en proyectos compartidos, gestionando cambios mediante mecanismos como las "pull requests". 
Gestión de proyectos: Facilita la organización de equipos, la asignación de tareas y el seguimiento de hitos. 
Open Source: Es ampliamente utilizado para proyectos de código abierto, pero también para proyectos privados y equipos individuales. 

*Flujo de trabajo con ramas (branching, merge, pull requests)
-Componentes del Flujo de Trabajo
Branch (Rama):
Es una versión paralela o un camino de desarrollo que se crea a partir de una línea de código existente. Permite trabajar en nuevas características o correcciones de errores sin afectar la estabilidad de la rama principal. 

-Commit:
Un "commit" es un registro de los cambios realizados en una rama en un momento específico. Cada commit es un punto en el historial que puede ser revisado o restaurado posteriormente. 
Merge (Fusión):
Es el proceso de combinar los cambios de una rama de desarrollo con otra rama, típicamente la rama principal. 

-Pull Request:
Es una petición formal para fusionar el código de una rama de desarrollo en otra rama. En plataformas como GitHub, esto inicia un proceso de revisión de código, discusión y aprobación antes de que los cambios sean integrados en la rama principal. 

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

1.-Diseño e implementación del frontend

*Maquetación/Wireframe/Mockup
API
-El diseño e implementación del frontend es el proceso de crear la parte visible e interactiva de una aplicación web o móvil, utilizando maquetaciones (wireframes) para la estructura básica y mockups para el diseño visual detallado, antes de que los desarrolladores creen el código real. Un wireframe es un plano de baja fidelidad, mientras que un mockup es una representación más realista con colores, fuentes e imágenes, permitiendo a los equipos visualizar y refinar el diseño antes de la implementación final. 
Maquetación (Wireframing)

Qué es:
Es la etapa inicial y de baja fidelidad que se enfoca en la estructura, disposición de los elementos y la funcionalidad de la interfaz. Se conoce como el "esqueleto" de la página o aplicación. 
Para qué sirve:
Permite a los diseñadores y equipos de producto concentrarse en la arquitectura de la información y el flujo de usuario sin distracciones visuales. 
Ayuda a definir la jerarquía del contenido y la ubicación de elementos clave como menús y botones. 
Facilita la comunicación temprana de la estructura general y la funcionalidad antes de invertir en detalles visuales. 
Cómo se hace:
Se crea con un diseño simple, a menudo en blanco y negro o escala de grises, utilizando contenido de marcador de posición. Se pueden usar herramientas como Miro o software específico de wireframing. 
Mockup
Qué es:
Es una representación de alta fidelidad que muestra el aspecto visual final de un diseño, más allá de la simple estructura. 
Para qué sirve:
Presenta los elementos de diseño reales, como los colores, tipografía, imágenes y estética general. 
Permite a los interesados visualizar cómo se verá y se sentirá el producto terminado. 
Sirve para comunicar la funcionalidad y la experiencia de usuario de una manera más concreta antes del desarrollo. 
Cómo se hace:
Se utiliza un software gráfico, como Adobe XD, para crear diseños detallados que se asemejen a la versión final de la aplicación o sitio web. 
El proceso y la relación
1. Diseño de maquetación (wireframe):
Se establece la estructura básica de la interfaz y la disposición de sus elementos. 
2. Creación de mockups:
Se añaden los detalles visuales (colores, tipografías, imágenes) al wireframe para crear una representación más realista. 
3. Implementación del frontend:
Una vez que el mockup es aprobado, los desarrolladores utilizan esos diseños para codificar la interfaz de usuario real.

2.-Diseño e implementación del backend
Servidor
*Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)

-El backend de una aplicación web se diseña e implementa como el conjunto de procesos del servidor que manejan la lógica de negocio y la gestión de datos, interactuando con la base de datos (como MySQL, PostgreSQL o MongoDB) y el frontend a través de peticiones HTTP (como GET o POST) para enviar y recibir información. Este proceso implica la creación de un servidor que recibe y responde a las solicitudes, la implementación de la lógica para procesar los datos y la conexión a la base de datos elegida para almacenar y recuperar la información necesaria. 
Componentes clave
Servidor:
Es el corazón del backend, un programa que escucha y procesa las solicitudes que llegan desde el frontend. 
Peticiones y respuestas HTTP:
El frontend se comunica con el backend utilizando métodos HTTP como GET (para obtener datos), POST (para enviar datos), PUT (para actualizar) o DELETE (para borrar). El backend debe procesar estas peticiones y enviar una respuesta adecuada (generalmente en formato JSON). 
Conexión a bases de datos:
El backend se conecta a un sistema de gestión de bases de datos (SGBD) para almacenar y consultar la información. Las bases de datos más comunes son: 
MySQL y PostgreSQL: Son bases de datos relacionales que almacenan los datos en tablas estructuradas. 
MongoDB: Es una base de datos NoSQL que utiliza documentos flexibles para almacenar datos. 
Pasos para el diseño e implementación
1. Definir la arquitectura:
Elige la tecnología del servidor (por ejemplo, Node.js, Python con Flask/Django, Java con Spring) y la base de datos que mejor se adapte a las necesidades del proyecto. 
2. Crear el servidor:
Configura un servidor que pueda escuchar en un puerto específico y esté preparado para manejar las solicitudes HTTP. 
3. Implementar la lógica de negocio:
Desarrolla las funciones que procesan la información recibida, realizan cálculos, validan datos y preparan la información para la base de datos o para el frontend. 
4. Integrar la base de datos:
Escribe el código necesario para conectar el backend a la base de datos seleccionada (MySQL, PostgreSQL o MongoDB). Esto incluye la definición de los modelos de datos y las operaciones para interactuar con las tablas o colecciones. 
5. Desarrollar endpoints de la API:
Crea las URLs (endpoints) que el frontend utilizará para comunicarse con el backend, asociando a cada endpoint la función de la lógica de negocio que debe ejecutar. 
6. Manejar las peticiones y respuestas:
Asegúrate de que el servidor pueda recibir las peticiones HTTP, procesar la información y enviar respuestas claras al frontend.

3.-Bases de datos

 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend
¿Qué es un ORM?
ORM significa Object Relational Mapper (Mapeador objeto-relacional) por sus siglas en inglés. Antes de hablar sobre lo que es un ORM, sería mejor hablar primero de mapeo relacional de objetos como concepto.
A menos que haya trabajado exclusivamente con bases de datos NoSQL, es probable que haya escrito una buena cantidad de consultas SQL. Que por lo general, se ven así:

En desarrollo backend, CRUD se refiere a las cuatro operaciones fundamentales (Crear, Leer, Actualizar, Eliminar) con las que se manipulan datos en bases de datos y sistemas de información, como insertarlos, consultarlos, modificarlos y borrarlos. El modelado de datos define la estructura de la información y las relaciones entre entidades, mientras que la implementación CRUD desde el backend es la lógica y el código que permiten ejecutar estas operaciones de forma segura y eficiente sobre esos datos modelados. 

4.-Seguridad básica en aplicaciones web

Validación de formularios
Autenticación y autorización 
La seguridad básica en aplicaciones web incluye la validación de formularios para asegurar que los datos ingresados sean válidos y no maliciosos, la autenticación (verificar la identidad del usuario) y la autorización (determinar a qué recursos tiene acceso el usuario). Estas prácticas son esenciales para proteger la información de la aplicación y de los usuarios frente a accesos no autorizados y ataques. 
Validación de formularios
Esta medida de seguridad verifica que los datos recibidos de un formulario cumplan con las características esperadas y estén libres de contenido malicioso. 
Propósito:
Prevenir que entradas incorrectas o maliciosas afecten la aplicación y generar la confianza de que los datos de entrada son seguros y válidos. 
Cómo funciona:
Los datos de entrada deben ser filtrados y validados antes de su procesamiento para asegurar su integridad y que no contengan código perjudicial, como lo es en el caso de la validación de formularios para el inicio de sesión o el registro. 
Autenticación
Es el proceso para confirmar la identidad de un usuario antes de permitirle el acceso a un sistema o aplicación. 
Propósito: Asegurar que el usuario es quien dice ser antes de concederle acceso. 
Ejemplo: Iniciar sesión con un nombre de usuario y contraseña. 
Mejores prácticas: La autenticación multifactor (MFA), que requiere más de una forma de verificación de identidad (por ejemplo, una contraseña y un código del teléfono), añade una capa extra de seguridad. 
Autorización
Una vez que se ha autenticado un usuario, la autorización determina a qué recursos o funcionalidades de la aplicación tiene permitido acceder. 
Propósito:
Controlar el acceso a los recursos, asegurando que solo los usuarios autorizados puedan realizar ciertas acciones o ver cierta información.
Ejemplo:
Permitir o denegar el acceso a una página o a una función específica de la aplicación, según los permisos del usuario.
Relación entre los conceptos
La autenticación responde a la pregunta "¿Quién eres tú?", mientras que la autorización responde a "¿Qué puedes hacer?". 
Son procesos complementarios: la autenticación es un paso inicial para verificar la identidad del usuario, y la autorización define sus derechos y permisos dentro del sistema. 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend
La integración de frontend y backend se realiza mediante APIs (Interfaces de Programación de Aplicaciones) que actúan como intermediarios, permitiendo que la interfaz de usuario (frontend) envíe solicitudes HTTP al backend. El backend procesa estas solicitudes, interactúa con la base de datos para obtener o modificar datos y, a continuación, devuelve una respuesta HTTP con la información solicitada al frontend, que actualiza la interfaz del usuario, creando una aplicación funcional y dinámica. 
Interfaz de Usuario (Frontend)
Propósito:
Es la parte visible de la aplicación con la que el usuario interactúa directamente. 
Funciones:
Se encarga de la presentación de datos, la experiencia del usuario y de recibir las acciones del usuario, como clics en botones o entrada de datos. 
Manejo de API (Interfaces de Programación de Aplicaciones)
Rol:
Las APIs son el "puente" o intermediario que permite la comunicación entre el frontend y el backend. 
Funcionamiento:
Definen métodos y formatos de datos para que el frontend pueda solicitar servicios al backend sin conocer la implementación interna de este último. 
Tipos de Solicitudes:
El frontend usa APIs para enviar solicitudes HTTP (como GET para obtener datos o POST para enviar datos) al backend. 
Proceso de Solicitud y Respuesta de Backend
1. Solicitud del Usuario:
El usuario interactúa con el frontend (ej. al hacer clic en un botón). 
2. Envío de Solicitud:
El frontend envía una solicitud al backend a través de la API, utilizando el protocolo HTTP. 
3. Procesamiento en el Backend:
El backend recibe la solicitud, la procesa, realiza operaciones (como consultas a la base de datos) y prepara una respuesta. 
4. Respuesta al Frontend:
El backend devuelve la respuesta al frontend, que luego la utiliza para actualizar la interfaz de usuario y mostrar la información al usuario. 
Ejemplo Ilustrativo (Restaurante) 
Usuario (Frontend): Pide comida del menú.
Mesero (API): Lleva la solicitud a la cocina.
Cocina (Backend/Base de Datos): Prepara la comida (datos).
Mesero (API): Lleva la comida de vuelta al usuario.

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento
El almacenamiento en un servidor se refiere al espacio digital en un servidor donde se guardan los datos de un sitio web o aplicación, que puede ser físico o virtual. Existen varios tipos de servidores, como los compartidos, que albergan múltiples clientes en un único servidor, o los servidores dedicados, exclusivos para un solo cliente. El servicio de hosting es el alquiler de este espacio en un servidor para publicar un sitio web en Internet. Los proveedores de servicios de alojamiento, como Wix, Bluehost, o Hostinger, son empresas que ofrecen estos recursos y la infraestructura tecnológica necesaria. 
Tipos de servidores
Servidores Web: Almacenan y entregan el contenido de las páginas de internet para que los usuarios puedan acceder a ellas a través de un navegador. 
Servidores de Base de Datos: Se encargan de organizar, almacenar y transferir información a otros ordenadores mediante el uso de tablas, registros e índices. 
Servidores de Correo Electrónico: Gestionan el envío y la recepción de correos electrónicos. 
Servidores FTP (File Transfer Protocol): Permiten el envío y la gestión de archivos entre sistemas. 
Servidores en la Nube (Cloud Servers): Son servidores virtuales o físicos ubicados en la nube, ofreciendo escalabilidad y flexibilidad para distribuir el contenido en una red de servidores. 
Servicios de Hosting
El hosting es el servicio que pone a disposición los servidores y el espacio de almacenamiento para publicar un sitio web. 
Hosting Compartido:
Es la opción más asequible donde múltiples sitios web comparten los recursos de un mismo servidor. 
Hosting VPS (Servidor Privado Virtual):
Ofrece más recursos dedicados y mayor control que el hosting compartido, simulando un servidor dedicado en una infraestructura compartida. 
Hosting Dedicado:
Un servidor físico completo se alquila exclusivamente para un solo cliente, proporcionando el máximo rendimiento y control. 
Hosting en la Nube:
Utiliza una red de servidores virtualizados distribuidos en la nube, lo que permite escalar los recursos fácilmente y con alta disponibilidad. 
Proveedores de Servicios de Almacenamiento (Hosting)
Estos proveedores ofrecen los servicios de hosting mencionados anteriormente. 
Wix.com:
Una plataforma que ofrece soluciones integrales, incluyendo hosting para crear y publicar sitios web, indica la fuente original de esta respuesta. 
Hostinger:
Ofrece diversos tipos de hosting, incluyendo alojamiento web, VPS y en la nube, así como tutoriales para principiantes, según su sitio web. 
GoDaddy:
Un proveedor de servicios de hosting y dominios que ofrece planes de alojamiento compartido, VPS y dedicados, según los recursos de su página. 
Otras Plataformas:
Empresas como IBM, Lenovo, o Claro Colombia (para almacenamiento en la nube) también ofrecen servicios relacionados. 

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
