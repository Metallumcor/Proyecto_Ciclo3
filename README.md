# Mi stock simple APP - Desktop

Esta es una aplicación destinada a ejecución local en navegador, la cual tendrá como finalidad el control de inventarios de
una cafetería ficticia por parte de empleados y administradores. Realizada por el grupo D del programa MisionTIC 2020 como
proyecto final para la culminación del cilo 3.

## Descripción general del problema

En esta empresa los trabajadores cuentan con dos roles principales: administrador y empleado. Las funciones de acuerdo a 
cada uno de los roles son:

### Administrador

- Crear nuevos administradores y empleados. 
- Crear, visualizar, actualizar y borrar productos.

### Empleado

- Visualizar y actualizar los stocks de productos

Cada tarea tiene unas especificaciones adicionales, pero primero se hace mención de la estructura de los objetos que 
conformaran la base de datos (y tendrán conexión con el aplicativo)

### Usuario

- Identificador (Int, PK)
- Usuario (Varchar)
- Contraseña (Varchar)
- Correo (Varchar)

### Producto

- Identificador (Int, PK)
- Nombre (Varchar)
- Descripción (Varchar)
- Cantidad (Int)
- Foto (Blob)

## Breve descripción de las tareas

### Creación de usuario:

Al crear un nuevo usuario, el sistema debe enviar un correo de confirmación con las credenciales entregadas por el administrador 
a la dirección especificada. 

### CRUD de producto

Solamente los administradores tiene acceso pleno a estos métodos. En el caso de actualización y eliminación, los productos son 
seleccionados en una interfaz donde se disponen sus imagenes de manera interactiva.

En el caso de ser un empleado, este podrá acceder a una versión limitada de la interfaz del admin donde el método de actualización
solo adminta la modificación del stock

### Login

Es requerido al iniciar la plataforma. En caso de olvidar la constraseña de un usuario existente, se puede pedir que se envie un
correo devolviendo las credenciales requeridas.

## Contacto e información adicional

El control de versiones y la descripción es realizada por David Cardenas Pineda (dhcardenasp@gmail.com). Otras carácteristicas del 
aplicativo serán registradas en futuras aplicaciones.
