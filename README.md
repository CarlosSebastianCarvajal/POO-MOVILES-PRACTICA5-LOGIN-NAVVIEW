# POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW
Desarrollo de una aplicación nativa Android que permite simular un Login de Usuario y que al ingresar las credenciales, muestre una Interfaz Gráfica de Usuario (NavigationView), cuya Imagen y Nombre de usuario sean dinámicos y las opciones del Menú del  NavigationView sean dinámicas según el perfil o tipo del usuario que ha ingresado

DETALLES DE LA APLICACIÓN:

Para las pruebas de la aplicación se utilizo una base de datos no relacional  utilizada anteriormente en un proyecto distinto (utilice esta base de datos dado que ya contenia algunos datos de usuario y con tipos o perfiles de usuario distintos y estaba disponible como una API REST).
Los datos estan disponibles en: https://smart-meter-project-35c6b-default-rtdb.firebaseio.com/Usuarios.json

Se utilizo Volley para obtener los datos.

CAPTURAS DE FUNCIONAMIENTO DE LA APLICACIÓN:


Al Abrir la aplicación Nos muestra la siguiente pantalla (Activity), la cual contiene un inicio de sesion para el usuario:

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642173871.png)

En la siguiente imagen se muestra el ingreso de datos (Usuario y contraseña) de un usuario de tipo administrador (Proveedor de un servicio)

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642173900.png)

Al presionar iniciar sesion y si los datos correctos no redirige a la ¨pantalla principal¨ aunque esta vacia dado que no se ha cargado ningun fragment:

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642173908.png)

Al presionar el boton de Menú se puede apreciar La imagen y nombre del usuario logeado, además de su lista de opciones disponibles:

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642173928.png)

Se ingresó datos de otro usuario, en este caso de tipo Consumidor:

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642174332.png)

Se aprecia tambien que se muestra la imagen yh nombre del usuario, sin embargo para este usuario se ha cambiado dinamicamente la lista de opciones del usuario:

![alt text](https://github.com/CarlosSebastianCarvajal/POO-MOVILES-PRACTICA5-LOGIN-NAVVIEW/blob/main/capturas/Screenshot_1642174364.png)



