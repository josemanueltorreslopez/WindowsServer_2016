# WindowsServer_2016
## Ejercicio Windows Server 2016
### Explicacion de la Empresa

En esta empresa estara el equipo administrador y otro de ayudante de administracion que entre ambos gestionaran todo.
Por otra parte Gestion se encargara de la gestion de los vienes de la empresa.
Y la parte de Contabilidad sera aquella que se dedique a las finanzas dentro de la empresa.
Gestion y Contabilidad tendra cada uno dos usuarios y dos equipos a los que no podran acceder desde el equipo del otro y solo en horario laboral podran acceder. 
Por otra parte administracion sera un ordenador de ayuda para el equipo administrador.

### Preparación
Lo primero que debemos hacer es ver y configurar el nombre del equipo para que se pueda visualizar correctamente.

![Imagen Nombre Equipo](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Nombre%20Equipo.JPG)

El proceso a seguir seria el siguiente.

![Imagen Proceso](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Proceso.JPG)

Y aquí seria donde le pondriamos nombre al equipo.

![Imagen Proceso1](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Proceso1.JPG)

Ahora pondremos estatica la ip de nuestro servidor ya que no nos interesa que este en dhcp.

![Imagen IpStatic](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/IpStatic.JPG)
![Imagen IpStatic2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/IpStatic2.JPG)

### Instalacion del Active Directory
Ahora empezaremos con la instalación del Active Directory, y lo primero es agregar su rol.

![Imagen RolAD](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/RolAD.JPG)
![Imagen RolAD2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/RolAD2.JPG)

Una vez termine de instalarse lo cerramos y nos aparecera en la banderita una señar de atencion. Le daremos y debremos seguir los siguientes pasos, para darle un dominio a nuestro Active Directory.

![Imagen RolAD2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Dominio.JPG)
![Imagen RolAD2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Dominio2.JPG)

Y ya terminamos de instalar el Rol de Active Directory.

![Imagen FinInstalacion](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/FinInstalacion.JPG)
![Imagen FinInstalacion2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/FinInstalacion2.JPG)

### Instalacion DHCP
Para hacer que nuestro servidor sea tambien servidor de DHCP deberemos instalarle el rol correspondiente.

![Imagen RolDHCP](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/RolDHCP.JPG)
![Imagen RolDHCP2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/RolDHCP2.JPG)

Nos saltara un aviso en el que deberemos configurar el DHCP

![Imagen ConfiguracionDHCP](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ConfiguracionDHCP.JPG)

Una vez terminado de configurar deberemos irnos a la parte de herramientas y buscar el DHCP.

![Imagen Herramientas](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Herramientas.JPG)

Y en el menu que nos sale deberemos crear un nuevo ambito.

![Imagen Ambito](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Ambito.JPG)
![Imagen Ambito2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Ambito1.JPG)
![Imagen Ambito3](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Ambito2.JPG)

En esta seccion es donde daremos el rango de Ips que repartira nuestro servidor.

### Creacion de Usuarios

Para crear usuarios tendremos que irnos a las herramientas.

![Imagen HerramientasUsu](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/HerramientasUsu.JPG)

En este menu crearemos las Unidades Organizativas de nuestra empresa.

![Imagen UnidadOrganizativa](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/UnidadOrganizativa.JPG)
![Imagen UnidadOrganizativa1](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/UnidadOrganizativa1.JPG)


Una vez creadas nuestras Unidades Organizativas dentro de ellas introduciremos Usuarios y Equipos.
Con el click derecho sobre nuestra Unidad Organizativa podemos darle a nuevo y nos saldran diversas opciones, las que nos interesan son las de equipo y usuario.

![Imagen CreacionUsuario](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/CreacionUsuario.JPG)
![Imagen CreacionEquipo](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/CreacionEquipo.JPG)

Y se nos quedan asi nuestras Unidades Organizativas.

![Imagen Contabilidad](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Contabilidad.JPG)
![Imagen Administracion](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Administracion.JPG)
![Imagen Gestion](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Gestion.JPG)

Ahora daremos a los usuarios las restricciones de hora y equipo.

![Imagen Restricciones](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Restricciones.JPG)
![Imagen Hora](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Hora.JPG)
![Imagen Equipo](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/Equipo.JPG)

Y por ultimo añadimos la impresora.

![Imagen Impresora](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/impresora.png)
![Imagen Impresora2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/impresora2.png)

### Comprobacion
Una vez creados los usuarios y los equipos debemos comprobar desde otro Windows si funciona correctamente.
Bien una vez iniciada la sesion en el otro Windows deberemos cambiar el nombre del equipo y el dominio.

![Imagen ConexionUsu](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ConexionUsu.PNG)
![Imagen ConexionUsu2](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ConexcionUsu2.PNG)
![Imagen ConexionUsu3](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ConexionUsu3.PNG)
![Imagen ConexionUsu4](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ConexionUsu4.PNG)

En este usuario deberia haber problemas por la hora al conectarse.

![Imagen ConexionUsu4](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/RestriccionTiempo.PNG)

Le quitamos las restricciones para poder entrar al usuario o probamos con otro y ya solo nos queda asegurarnos de que usuario es y si recibe una Ip de nuestro servidor.

![Imagen ComprobacionUsuario](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ComprobacionUsu.PNG)
![Imagen ComprobacionDHCP](https://github.com/josemanueltorreslopez/WindowsServer_2016/blob/master/ComprobacionClienteDHCP.PNG)
