# Active Directory Lab - TechSolutions S.L.

## Descripción del proyecto

Este proyecto simula un entorno empresarial completo basado en Windows Server 2022, con el objetivo de recrear una infraestructura de red corporativa realista orientada a la administración de sistemas. Cuenta con un cliente conectado al dominio Windows 10

Incluye la implementación de servicios fundamentales como Active Directory, DNS, DHCP y servidor de archivos, además de la gestión de usuarios, grupos, políticas de seguridad y permisos.

El objetivo principal es desarrollar habilidades prácticas en administración de sistemas Windows y entornos corporativos.

---

## Empresa simulada

TechSolutions S.L. es una empresa ficticia dedicada al desarrollo de software y soporte tecnológico. Todo el entorno del laboratorio se ha diseñado bajo esta estructura organizativa para simular un entorno real de producción.

---

## Objetivo del laboratorio

Diseñar e implementar una infraestructura completa que incluya:

- Controlador de dominio
- Gestión de usuarios y grupos
- Unidades organizativas (OU)
- Políticas de grupo (GPO)
- Servicio DNS integrado con Active Directory
- Servicio DHCP para asignación automática de direcciones IP
- Servidor de archivos con permisos por departamento
- Cliente Windows unido al dominio

---

## Arquitectura del sistema

Cliente Windows 10 (TS-CLI01)  
│  
Red interna: 192.168.10.0/24  
│  
Servidor Windows Server 2022 (TS-DC01)  
- Active Directory Domain Services  
- DNS  
- DHCP  
- File Server  
- Group Policy Objects (GPO)  

---

## Tecnologías utilizadas

- Windows Server 2022  
- Active Directory Domain Services (AD DS)  
- DNS Server  
- DHCP Server  
- Windows 11 Pro  
- Group Policy Objects (GPO)  
- NTFS Permissions  
- Virtualización (VirtualBox)

---

## Estructura del dominio

Dominio: techsolutions.local

Departamentos implementados:

- IT  
- Recursos Humanos  
- Finanzas  
- Dirección  

Usuarios creados:

- Laura Gómez  
- Miguel Ruiz  
- Ana Torres  
- David Martín  
- Marta López  
- Carlos Sánchez  
- Sergio Romero  
- Elena Díaz  

---

## Políticas de grupo (GPO)

Se han implementado políticas de seguridad y configuración centralizada, incluyendo:

- Restricción de acceso al Panel de control  
- Bloqueo de consola CMD  
- Políticas de contraseñas seguras  
- Mensaje de bienvenida corporativo  
- Restricciones de configuración de usuario  

---

## Servicios implementados

### Active Directory
- Creación de dominio corporativo
- Gestión de usuarios, grupos y OU
- Estructura organizativa empresarial

### DNS
- Resolución de nombres internos
- Integración con Active Directory

### DHCP
- Asignación automática de direcciones IP
- Configuración de red centralizada para clientes

### File Server
- Carpetas compartidas por departamento
- Control de acceso mediante permisos NTFS

---

## Evidencias

Las capturas del proyecto se encuentran en la carpeta:

screenshots/

Incluyen la configuración del servidor, Active Directory, GPOs, DHCP, DNS y validación del cliente unido al dominio.

---

## Resultado final

Se ha implementado una infraestructura completa de red empresarial simulada, replicando un entorno real de administración de sistemas Windows.

El proyecto demuestra competencias en:

- Administración de sistemas Windows Server  
- Servicios de red empresariales  
- Gestión de identidades (Active Directory)  
- Seguridad mediante políticas de grupo  
- Control de acceso a recursos compartidos  

---

## Autor

Cristina Calle  
Proyecto de laboratorio personal orientado al desarrollo profesional en administración de sistemas.