#  Proyecto Boochan: La Trilogía de Infraestructura

Bienvenido al repositorio central del **Proyecto Boochan**. Este ecosistema recoge la evolución de una infraestructura IT completa, desde entornos locales complejos hasta implementaciones avanzadas en la nube (Microsoft Azure), combinando sistemas Linux y Windows.

---

##  Boochan 1: El Origen (On-Premise)
*Infraestructura integral escalable en 9 fases.*

Este proyecto representa la base de la administración de sistemas local, centrada en la seguridad, el control de tráfico y la gestión de servicios esenciales.

###  Fases del Despliegue:
1. **Topología de Red:** Diseño de subredes y segmentación.
2. **Virtualización:** Configuración del entorno base (Hyper-V/VirtualBox).
3. **Servidor Gateway (Ubuntu):** Configuración de Netplan y enrutamiento.
4. **Seguridad Perimetral (Firewall):** Reglas de IPTables y filtrado de paquetes.
5. **Proxy de Red (Squid):** Control de acceso web y caché de red.
6. **Servicios Core (DHCP/DNS):** Automatización de direccionamiento.
7. **Controlador de Dominio:** Gestión de identidades y GPOs.
8. **Almacenamiento y Backup:** Configuración de cuotas y copias de seguridad.
9. **Clientes y Conectividad:** Integración final de puestos de trabajo.

---

##  Boochan 2: Híbrido en la Nube (Azure)
*Interoperabilidad Linux-Windows en entornos Cloud.*

En esta segunda iteración, trasladamos la infraestructura a **Microsoft Azure**, enfocándonos en la conectividad entre sistemas heterogéneos.

* **Arquitectura:** Despliegue de una VNet con múltiples subredes.
* **Servidor Maestro (Ubuntu):** Actuando como nodo central de servicios en la nube.
* **Clientes Windows:** Integración de máquinas virtuales Windows 10/11 conectadas al nodo Linux.
* **Gestión:** Implementación de reglas de Network Security Groups (NSG) y acceso mediante SSH/RDP seguro.

---

##  Boochan 3: Enterprise Cloud (Azure)
*Ecosistema Windows Server nativo en Azure.*

La culminación del proyecto se centra en un entorno puramente empresarial bajo tecnología Microsoft, maximizando la eficiencia de las herramientas de Azure.

* **Servidor:** Windows Server 2022 en Azure como controlador de dominio principal.
* **Gestión de Identidades:** Active Directory Domain Services (AD DS) en la nube.
* **Clientes:** Despliegue automatizado de máquinas cliente Windows.
* **Optimización:** Uso de Azure Bastion para conexiones seguras y gestión de discos administrados para alta disponibilidad.

---


## Autor

* **Iker Martinez Gomez** - [boochanspace](https://github.com/boochanspace)
* **Héctor Manzanaro Romero**
* **Jorge Lozano Cervilla**

---
*Este proyecto fue desarrollado con fines educativos para demostrar habilidades en Administración de Sistemas, Redes y Cloud Computing.*
