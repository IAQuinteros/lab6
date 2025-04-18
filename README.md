LAB-06
Creación de vistas básicas para los modelos

En esta evaluación, agregará vistas básicas a su aplicación Whats New utilizando Ruby on Rails.

Instrucciones
Trabaje en el mismo repositorio que la última sesión de laboratorio para que pueda tener el código que ya generó para los modelos.

1. Crea vistas para tus modelos
Usando los modelos creados en lab-05, ahora implementará el índice básico y mostrará vistas para cada uno.

Debe crear vistas para los siguientes modelos:

User
Chat
Message
1.1 Vistas de índice
Para cada modelo, cree una vista que:index

Enumera todos los registros del modelo
Muestra los valores de todos los atributos en formato de tabla
Incluye un enlace para ver cada registro individual ( ver)show
1.2 Mostrar vistas
Para cada modelo, cree una vista que:show

Muestra todos los valores de atributo de una sola instancia
Incluye un enlace para volver a la vista de índice
💡 Ejemplo: En , muestra el nombre completo y el correo electrónico del usuario.app/views/users/show.html.erb

Puede utilizar HTML sin formato y Ruby incrustado (). No se espera que utilices CSS ni ningún marco de frontend en este punto..html.erb

2. Añade una barra de navegación
Con Bootstrap, agregue una barra de navegación en la parte superior de la página. Esto debe mostrarse en todas las páginas de la aplicación, para ello se deben utilizar rails parciales
