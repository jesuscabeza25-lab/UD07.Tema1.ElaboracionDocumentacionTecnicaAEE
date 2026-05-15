

# *La Memoria Técnica (Estructura Ofimática)* {#la-memoria-técnica-(estructura-ofimática)}

Nombre: Jesús Cabeza Carballar  
Ciclo: Sistemas Informáticos  
Fecha: 15/05/2026

**Índice**

[**La Memoria Técnica (Estructura Ofimática)	1**](#la-memoria-técnica-\(estructura-ofimática\))

[**ANEXO I: Plantilla y Ejemplo de Análisis de Necesidades	3**](#anexo-i:-plantilla-y-ejemplo-de-análisis-de-necesidades)

[1\. Análisis de Necesidades	3](#1.-análisis-de-necesidades)

[1.1. Contexto y Problemática Actual	3](#1.1.-contexto-y-problemática-actual)

[1.2. Solución Propuesta: Infraestructura Híbrida Docker-Guacamole	3](#1.2.-solución-propuesta:-infraestructura-híbrida-docker-guacamole)

[1.3. Justificación Técnica y Beneficios (TCO)	3](#1.3.-justificación-técnica-y-beneficios-\(tco\))

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# ANEXO I: Plantilla y Ejemplo de Análisis de Necesidades {#anexo-i:-plantilla-y-ejemplo-de-análisis-de-necesidades}

## 1\. Análisis de Necesidades {#1.-análisis-de-necesidades}

### 1.1. Contexto y Problemática Actual {#1.1.-contexto-y-problemática-actual}

La gestión de servidores en entornos remotos suele presentar vulnerabilidades debido a la descentralización de los accesos. El uso de conexiones directas (RDP o SSH) obliga a abrir múltiples puertos en el firewall corporativo, lo que aumenta la superficie de ataque y expone la infraestructura a incursiones externas. Asimismo, la falta de una herramienta centralizada dificulta la auditoría y obliga al personal técnico a depender de clientes pesados en sus máquinas locales.

### 1.2. Solución Propuesta: Infraestructura Híbrida Docker-Guacamole {#1.2.-solución-propuesta:-infraestructura-híbrida-docker-guacamole}

Se propone el despliegue de **Apache Guacamole** mediante contenedores **Docker**. Esta solución actúa como un gateway web que traduce protocolos de escritorio remoto a HTML5, eliminando la necesidad de software adicional en el cliente. Gracias a Docker, los servicios (PostgreSQL, Guacamole y SSH) operan de forma aislada y estanca, permitiendo un despliegue rápido y seguro con un único punto de entrada vía navegador.

### 

### 1.3. Justificación Técnica y Beneficios (TCO) {#1.3.-justificación-técnica-y-beneficios-(tco)}

La implementación reduce el Coste Total de Propiedad (TCO) al utilizar software de código abierto, eliminando gastos en licencias propietarias. Los principales beneficios incluyen:

* **Seguridad:** Cierre de puertos críticos y centralización de la autenticación.  
* **Eficiencia:** Menor consumo de recursos gracias a la arquitectura de contenedores.  
* **Disponibilidad:** Facilidad para la recuperación ante desastres (DRP) mediante la 


  
**Buenos ejemplos**:

* Drake, J. M. (2008). **Análisis de requisitos y especificación de una aplicación** \[en línea\] Disponible en: https://www.ctr.unican.es/asignaturas/ingenieria\_software\_4\_f/doc/m3\_08\_especificacion-2011.pdf  
* García Notario, D. (2015). **Análisis de requisitos en el desarrollo del software**  \[en línea\] Disponible en: https://e-archivo.uc3m.es/rest/api/core/bitstreams/a66b0a2d-fa7c-483f-ac5e-1476ff2da8eb/content

