NOMBRE Y APELLIDOS: Pablo Soriano Jiménez

CURSO: 2ºDAM 

EMAIL: psorjim856@g.educaand.es

TÍTULO DEL PROYECTO: Eusol’s Stock

OBJETIVOS DEL PROYECTO:

El objetivo general del proyecto es crear una aplicación que funcione tanto en móvil como en escritorio, y que permita gestionar el stock de la empresa de mi padre de una forma más profesional y útil. Actualmente, la gestión se realiza mediante un Excel que a veces presenta problemas, y una aplicación de facturación que solo es compatible hasta Windows 7.

FINALIDAD DEL PROYECTO:

La aplicación permitirá gestionar el stock tanto desde un PC en el almacén como desde los móviles de los trabajadores. Además, permitirá crear pedidos con su correspondiente factura para su impresión. En estos pedidos, se podrá especificar el modelo y la cantidad de sombreros, al seleccionar dicha cantidad, se mostrará automáticamente la cantidad disponible de sombreros, así como el IVA correspondiente. Cabe mencionar que en el caso de la empresa de mi padre, cada cliente tiene un tipo de IVA distinto.

Además de la ventana de gestión de pedidos, la aplicación contará con una ventana para gestionar las compras y otra para gestionar el stock en sí. Esto permitirá que, en caso de querer regalar existencias, se puede hacer manualmente sin necesidad de crear un pedido.

FUNCIONALIDADES DEL PROYECTO O APLICACIÓN:

La aplicación, tanto en su versión móvil como en la de escritorio, contará con una página principal que permitirá acceder a los distintos modos de la aplicación. Estos modos serán tres:

  1. Compra: El modo "Compra" permitirá añadir una compra de productos de la empresa, tanto nuevos como existentes. En caso de que ya existan, se sumará la cantidad comprada al stock actual. Sin embargo, si se trata de un producto nuevo, permitirá añadirlo con sus datos correspondientes: ID, nombre, breve descripción y una imagen del producto.

  2. Venta: El modo "Venta" permitirá gestionar una venta. Podrás elegir los productos que desees vender y su cantidad. Mientras escribas la cantidad, se mostrará en pantalla la cantidad disponible en ese momento. Después, al marcar una casilla, se podrá crear una factura para el pedido. Al marcar esta casilla, aparecerán nuevos campos para rellenar, como el nombre del cliente, el IVA aplicado, la fecha de facturación, entre otros.

  3. Stock: El modo "Stock" permitirá una gestión más detallada del stock. Esto incluirá la capacidad de eliminar o añadir existencias de manera puntual por motivos como productos defectuosos, devoluciones o eliminación de productos del inventario.

REQUISITOS MÍNIMOS (HARDWARE Y SOFTWARE) NECESARIOS:

En cuanto a los requisitos, es crucial que la aplicación pueda funcionar tanto en los móviles de los dos trabajadores principales de la empresa como en un ordenador con Windows 10, equipado con un procesador Intel Core i5 de quinta generación y al menos 8GB de RAM.

HERRAMIENTAS DE DESARROLLO:

La aplicación la desarrollaré basada en lenguaje de programación Java, tanto para la aplicación móvil como para la aplicación de escritorio. Para la versión móvil trabajaré con Android Studio, cuya parte visual la trabajaré con XML. 

Para la versión de escritorio tengo mis dudas, sé que para trabajar el código lo haré con IntelliJ, pero lo que no sé es si hacer la parte visual con JPanel o conectarlo con un entorno visual web como Angular. Seguramente optaré por la primera opción, pero no descarto la segunda idea. 

Ambas aplicaciones estarán conectadas a la misma base de datos, la cual crearé con SQLite y trabajaré sobre ella con DBeaver.

También trabajaré con Git para controlar las versiones del proyecto.

TEMPORIZACIÓN EN LA REALIZACIÓN:

No tengo todavía claro cómo organizarme el tiempo. Tengo en total 53 días, sin contar con los fines de semana, y tengo que saber gestionarlo dentro de las fases de realización del proyecto:

  1. Planificación: En este apartado, planificaré mejor el proyecto. Me haré un esquema de cómo quiero que el proyecto esté estructurado. No debería llevarme más de 2 días.

  2. Creación del proyecto desktop: Me centraré primero en la creación del proyecto para escritorio, incluyendo su apartado gráfico. Esto incluirá sus tres apartados y la funcionalidad de estos, excluyendo la funcionalidad de la base de datos.

  3. Creación del proyecto móvil: A continuación, me centraré en la creación del proyecto para móvil, incluyendo su apartado gráfico. Esto incluirá sus tres apartados y la funcionalidad de estos, excluyendo la funcionalidad de la base de datos.
  
  4. Creación de la base de datos: En este punto, crearé la base de datos, la cual tendrá 4 columnas: ID, Nombre, Breve descripción y Foto.
  
  5. Conexión con la BD: Crearé la conexión de ambas partes del proyecto con la base de datos creada anteriormente y terminaré de completar la funcionalidad de los apartados que necesitaban la base de datos para funcionar.
  
  6. Pruebas: Haré pruebas con productos inventados para verificar que todo funcione como debe. Probaré que ambas aplicaciones estén conectadas a la misma base de datos y que los movimientos que haga desde la aplicación den resultados.
  
  7. Corrección de errores: Corregiré los errores encontrados durante las pruebas anteriores.
  
  8. Detalles finales: Esta parte se enfocará principalmente en añadir detalles estéticos a la aplicación. Es posible que incluso esta parte sea innecesaria.
  
  9. Pruebas finales: Estas pruebas se realizarán con los errores corregidos y con los detalles finales implementados. Las llevaré a cabo junto a mi padre, ya que quiero simular situaciones reales de su empresa.
  
  10. Documentación: Dedicaré un tiempo a documentar todo el proyecto. Creo que es necesario asignar un tiempo específico para ello, además de ir completándolo conforme voy avanzando en el proyecto.
  
  11. Pruebas reales: No realizaré estas pruebas yo mismo. Proporcionaré la aplicación a la empresa para que ellos mismos puedan probarla con situaciones reales. Con estos resultados, podré determinar que la aplicación estará terminada.
