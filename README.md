# WindowsServer_2016
## Ejercicio Windows Server 2016
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
