# Práctica N° 1
### SISTEMA EMPRESARIALES
### 1) explique que son los sistemas empresariales
> son los procesos empresariales en torno a la logística y servicio al cliente: compras, aprovisionamiento, producción, almacenamiento, preparación, distribución y postventa. 
### 2) Describa cuales son las características más importantes de una aplicación empresarial
> Es evidente que hoy en día existen miles de aplicaciones que utilizamos de forma diaria para poder llevar a cabo nuestras tareas. Al ser tantas los expertos en el sector realizan una clasificación de estos programas dividiéndolos en cuatro categorías distintas y en cada una las aplicaciones presentan sus propias características.

> En el primer punto nos encontramos con las aplicaciones de negocios. Aquí uno de los programas más utilizados son los procesadores de palabras. Gracias a ellos podemos escribir textos, borrarlos, revisar la ortografía, hacer cambios en la escritura, modificar el tipo de letra... entre otras muchas cosas. También pertenecen a este grupo las hojas de cálculo, que son procesadores de números para crear plantillas en donde poder realizar fórmulas, hacer operaciones e incluso se pueden incluir textos. Después tenemos las bases de datos, que es una herramienta fundamental para poder tener controlada toda la información que hemos guardado en el ordenador y consultarla rápidamente cuando lo necesitemos. Finalmente la última aplicación de negocios a la que nos vamos a referir son los graficadores, que sirven para crear tablas, gráficas y todo tipo de ilustraciones.

> Por otro lado, el siguiente grupo de la clasificación son las aplicaciones personales. Se refieren a todos los programas que utilizamos fuera del ámbito de trabajo. Podemos así tener nuestra propia agenda de direcciones, un blog de notas personal, un calendario para consultar las fechas más relevantes o el correo electrónico para mandar y recibir mensajes.

> A las aplicaciones de negocio y personales les siguen las de entretenimiento. En este grupo nos encontraremos todos los programas que sirven para el ocio y la diversión, como es el caso de los videojuegos o los simuladores. Aunque también dentro de este tipo de aplicaciones están las educativas. Finalmente el último grupo al que tenemos que hacer referencia son las aplicaciones de utilería. Estas son aquellas que nos van a ayudar a mejorar el mantenimiento de nuestro ordenador y tenerlo siempre actualizado con las últimas versiones de los programas más técnicos.

> Todos los ordenadores que utilizamos en la actualidad están compuestos por el hardware y el software. Mientras que el primero se refiere a la parte física del ordenador, el segundo se centra en la parte lógica de la misma. Por este motivo tenemos que tenerlo en cuenta para incluir estas aplicaciones en nuestro ordenador. En cualquier caso, cada software de aplicación está desarrollado atendiendo a las características principales que tenga un sistema operativo específico, así a la hora de utilizar alguna de estas aplicaciones debemos hacerlo con el sistema adecuado, ya que no todos los software son compatibles.

> En definitiva los software de aplicación son los programas que nos ayudan a llevar a cabo diferentes tipos de tareas. Cada uno de ellos está programado para ofrecer sus servicios dentro de un campo o sector más concreto y basándose en los diferentes sistemas informáticos que existen en el mercado.
### 3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta

#### Bancos

#### Tigo

#### Entel

#### Viva

#### Aduana

>la caida del sistema de estas empresar causaria grandes perdidas tanto a la empresa como al pais, poer eso es aconsejable hacer >aplicaciones de mision critica para cada una de ellas.

### 4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
> La escala horizontal significa que la escala agregando más máquinas a su grupo de recursos, mientras que la escala vertical significa que la escala agregando más potencia (CPU, RAM) a una máquina existente.
Una manera fácil de recordar esto es pensar en una máquina en un rack de servidores, agregamos más máquinas en dirección horizontal y agregamos más recursos a una máquina en dirección vertical.
> En un mundo de base de datos, la escala horizontal a menudo se basa en la partición de los datos, es decir, cada nodo contiene solo una parte de los datos, en la escala vertical los datos residen en un solo nodo y la escala se realiza a través de varios núcleos, es decir, distribuyendo la carga entre Recursos de CPU y RAM de esa máquina.

> Con la escala horizontal, a menudo es más fácil escalar dinámicamente agregando más máquinas al grupo existente. La escala vertical a menudo se limita a la capacidad de una sola máquina, escalar más allá de esa capacidad a menudo implica tiempo de inactividad y viene con un límite superior.

> Un buen ejemplo de escala horizontal es Cassandra, MongoDB … y un buen ejemplo de escala vertical es MySQL – Amazon RDS (la versión en nube de MySQL). Proporciona una manera fácil de escalar verticalmente al cambiar de máquinas pequeñas a máquinas más grandes. Este proceso a menudo implica el tiempo de inactividad.
### 5) Que es un servidor Web y que es un servidor de aplicaciones
> Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente es renderizado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se usa el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador

>En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.
>Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negociación y de acceso a los datos de las aplicaciones. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.

### 6) Con un gráfico explique cómo funciona el protocolo HTTP
![PROTOCOLO HTTP](https://images-blogger-opensocial.googleusercontent.com/gadgets/proxy?url=http%3A%2F%2Froble.pntic.mec.es%2Fjprp0006%2Ftecnologia%2Fbachillerato_tic%2Funidad01_navegadores%2Fimagenes_navegador_buscador%2Fcliente_servidor.jpg&container=blogger&gadget=a&rewriteMime=image%2F*)

### 7) Explique los elementos importantes de REQUEST en HTTP
> HTTP define un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs. Cada uno de ellos implementan una semántica diferente, pero algunas características similares son compartidas por un grupo de ellos: ej. un request method puede ser safe, idempotent, o cacheable.

##### GET
>El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

##### HEAD
>El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

##### POST
>El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios >en el servidor.

##### PUT
>El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.

##### DELETE
>El método DELETE borra un recurso en específico.

##### CONNECT
>El método CONNECT establece un túnel hacia el servidor identificado por el recurso.

##### OPTIONS
>El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.

##### TRACE
>El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.

##### PATCH
>El método PATCH  es utilizado para aplicar modificaciones parciales a un recurso.
### 8) Explique los elementos importantes de RESPONSE en HTTP
>response.buffer Sirve para interferir en el proceso buffering
>Responce.CacheControl Permite a los servidores guardar un acopia en la cache
>Responce.Flush Provoca el envío inmediato al cliente del contenido del buffer de salida
>Responce.End Detiene el proceso de la pagina ASP
>Responce.Clear Vacía el contenido del buffer de salida

### 9) Describa con un gráfico la arquitectura Java EE
![Arquitectura JAVA](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)

### 10) Explique cuáles son los contenedores, componentes y servicios de Java EE
>Contenedores: Son la interface entre un componente y el bajo nivel, es especifico para la plataforma , antes de que se pueda ejecutar >el componente web

>Componentes: Aplicaciones cliente (Web, Applets, Aplicaciones de escritorio), Componentes web (Servlet, JavaServerPages, >JavaServerFaces), Componentes de negocio (Enterprice JavaBeans)

>Servicios: WSDL, SOAP, JAX-WS , JAXB, WS-POLICY

### 11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.
>HttpServlet: init(ServletConfig config), getServletConfig(), service(ServletRequest req,ServletResponse res), destroy()
>HttpServletRequest: getHeader(String name), getCookies(), getSession(), setAttribute(String name, Object value)
>HttpServletResponse: addCookie(), addHeader(), addIntHeader(), contaisHeader(), encodeRedirectURL(), encodeURL(), sendError(), >sendRedirect(), setStatus()
