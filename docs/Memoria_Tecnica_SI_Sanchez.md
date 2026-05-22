# 1. Análisis de Necesidades 

La empresa necesitaba una forma más segura y sencilla de acceder a sus servidores remotos. Antes de esta solución, cada usuario debía conectarse directamente mediante SSH o RDP, lo que obligaba a abrir varios puertos en el firewall y aumentaba los riesgos de seguridad.  
Para resolver este problema, se ha implementado una infraestructura basada en Apache Guacamole y Docker. Guacamole permite acceder a los servidores desde un navegador web sin instalar programas adicionales. Además, Docker facilita la creación y gestión de contenedores aislados, haciendo que cada servicio funcione de forma independiente.  
La principal ventaja de esta solución es la centralización del acceso remoto en un único punto. Esto mejora la seguridad y simplifica la administración de los sistemas. Asimismo, el uso de contenedores permite desplegar servicios rápidamente y facilita las tareas de mantenimiento.  
Otra ventaja importante es el ahorro económico, ya que todas las herramientas utilizadas son software libre y cuentan con licencias open source. Esto reduce costes de licencias y ofrece mayor flexibilidad para futuras ampliaciones de la infraestructura.  
En conclusión, la combinación de Docker y Apache Guacamole proporciona una solución segura, moderna y fácil de administrar para el acceso remoto empresarial.  

## Conclusión

La solución implementada mejora la seguridad y la organización de la infraestructura de la empresa. Además, Docker permite trabajar de forma más flexible y Apache Guacamole facilita el acceso remoto desde cualquier navegador.  


## Referencias 

* [https://guacamole.apache.org/](https://guacamole.apache.org/)  
* [https://www.docker.com/](https://www.docker.com/)  
* [https://www.postgresql.org/](https://www.postgresql.org/)

## Commit final recomendado

git add .  
git commit -m "feat: Sprint 1 completado - UD07"  
git push origin main  


# 2. Estimación de Costes de Infraestructura
Esta seria la tabla de TCO

<img width="985" height="274" alt="image" src="https://github.com/user-attachments/assets/96e07e79-e9e5-4144-a9a9-5a0bf4813f93" />

# 3. Estrategia de Despliegue y Comunicación

Para el despliegue de la aplicación se utilizará SFTP (SSH File Transfer Protocol) para transferir archivos desde el entorno local al servidor de producción. SFTP funciona sobre SSH, lo que permite cifrar toda la comunicación entre cliente y servidor, evitando que usuarios no autorizados puedan interceptar credenciales o información sensible durante la transferencia.

Se descarta el uso del protocolo FTP tradicional debido a que transmite los datos en texto plano, generando riesgos de seguridad. El uso de SFTP proporciona autenticación segura mediante usuario y contraseña o claves SSH, además de facilitar procesos automatizados de despliegue y mantenimiento.

El proyecto utiliza Docker Compose para gestionar y desplegar los servicios necesarios de forma organizada y reproducible, facilitando la administración de la infraestructura.

Para la comunicación entre los miembros del equipo se utilizará Discord o Microsoft Teams. Estas herramientas permitirán compartir incidencias técnicas, coordinar tareas y recibir alertas automáticas en caso de fallos o caídas del servidor.


