Memoria\_Tecnica\_SI\_Sanchez.md  
 Alumno: VÍCTOR SÁNCHEZ COLORADO  
 Ciclo: DAW  
 Fecha: 15 de mayo de 2026  
---

Índice

[**1\. Análisis de Necesidades	1**](#1.-análisis-de-necesidades)

[**2\. Conclusión	1**](#2.-conclusión)

[**3\. Referencias	2**](#3.-referencias)

[**Commit final recomendado	2**](#commit-final-recomendado)

---

# 1\. Análisis de Necesidades {#1.-análisis-de-necesidades}

La empresa necesitaba una forma más segura y sencilla de acceder a sus servidores remotos. Antes de esta solución, cada usuario debía conectarse directamente mediante SSH o RDP, lo que obligaba a abrir varios puertos en el firewall y aumentaba los riesgos de seguridad.  
Para resolver este problema, se ha implementado una infraestructura basada en Apache Guacamole y Docker. Guacamole permite acceder a los servidores desde un navegador web sin instalar programas adicionales. Además, Docker facilita la creación y gestión de contenedores aislados, haciendo que cada servicio funcione de forma independiente.  
La principal ventaja de esta solución es la centralización del acceso remoto en un único punto. Esto mejora la seguridad y simplifica la administración de los sistemas. Asimismo, el uso de contenedores permite desplegar servicios rápidamente y facilita las tareas de mantenimiento.  
Otra ventaja importante es el ahorro económico, ya que todas las herramientas utilizadas son software libre y cuentan con licencias open source. Esto reduce costes de licencias y ofrece mayor flexibilidad para futuras ampliaciones de la infraestructura.  
En conclusión, la combinación de Docker y Apache Guacamole proporciona una solución segura, moderna y fácil de administrar para el acceso remoto empresarial.  
---

# 

# 

# 2\. Conclusión {#2.-conclusión}

La solución implementada mejora la seguridad y la organización de la infraestructura de la empresa. Además, Docker permite trabajar de forma más flexible y Apache Guacamole facilita el acceso remoto desde cualquier navegador.  
---

# 

# 3\. Referencias {#3.-referencias}

* [https://guacamole.apache.org/](https://guacamole.apache.org/)  
* [https://www.docker.com/](https://www.docker.com/)  
* [https://www.postgresql.org/](https://www.postgresql.org/)

---

# Commit final recomendado {#commit-final-recomendado}

git add .  
git commit \-m "feat: Sprint 1 completado \- UD07"  
git push origin main  
