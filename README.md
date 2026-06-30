Active Directory Lab - TechSolutions S.L.
🚀 Badges del proyecto

Aquí tienes una cabecera estilo GitHub profesional:

🟦 Windows Server 2022: Windows Server 2022
🟨 Active Directory: Active Directory
🟩 DNS Service: DNS
🟧 DHCP Service: DHCP
🟪 GPO Policies: Group Policy
🟫 File Server: File Server
⚙️ Virtualization: VirtualBox
📌 Descripción del proyecto

Este proyecto simula un entorno empresarial real basado en Windows Server 2022, diseñado para recrear una infraestructura de red corporativa completa.

Incluye la implementación de servicios esenciales como:

Active Directory Domain Services (AD DS)
DNS integrado
DHCP para asignación automática de IPs
Servidor de archivos con permisos NTFS
Políticas de seguridad centralizadas mediante GPO

El objetivo es replicar un entorno real de administración de sistemas en empresa.

🏢 Empresa simulada

TechSolutions S.L. es una empresa ficticia creada para estructurar el laboratorio como un entorno corporativo real, con departamentos, usuarios y políticas diferenciadas.

🎯 Objetivos del laboratorio
Implementación de un dominio corporativo
Administración centralizada de usuarios y grupos
Diseño de estructura organizativa (OU)
Configuración de servicios de red empresariales
Aplicación de políticas de seguridad (GPO)
Control de accesos a recursos compartidos
🧱 Arquitectura del sistema
Red interna: 192.168.10.0/24

┌──────────────────────────────────────┐
│ Windows Server 2022 (TS-DC01)        │
│ Domain Controller                    │
│ AD DS | DNS | DHCP | File Server     │
│ GPO Management                       │
└───────────────┬──────────────────────┘
                │
                ▼
┌──────────────────────────────────────┐
│ Windows Client (TS-CLI01)            │
│ Unido al dominio                     │
└──────────────────────────────────────┘
⚙️ Tecnologías utilizadas
Windows Server 2022
Active Directory Domain Services
DNS Server
DHCP Server
Group Policy Objects (GPO)
Windows 10 / 11 Client
NTFS Permissions
VirtualBox
🏗️ Estructura del dominio

Dominio: techsolutions.local

Departamentos:
IT
Recursos Humanos
Finanzas
Dirección
Usuarios:
Laura Gómez
Miguel Ruiz
Ana Torres
David Martín
Marta López
Carlos Sánchez
Sergio Romero
Elena Díaz
🔐 Políticas de grupo (GPO)
Bloqueo de Panel de control
Restricción de CMD
Políticas de contraseñas seguras
Mensaje corporativo de inicio de sesión
Restricciones de configuración de usuario
🧪 Evidencias del laboratorio

Las capturas están organizadas en la carpeta:

screenshots/
Flujo del proyecto:
01_server_manager.png → Configuración inicial del servidor
02_active_directory.png → Active Directory configurado
03_usuarios_ou.png → Usuarios y OU creadas
04_cliente_dominio.png → Cliente unido al dominio
05_gpo.png → Configuración de GPO
gpo_funcionando.png → Validación de políticas
06_dhcp.png → Configuración DHCP
07_carpetas_compartidas.png → File Server
comprobacion_dns_cliente.png → Validación DNS desde cliente
📊 Resultado final

Se ha implementado una infraestructura corporativa funcional que simula un entorno empresarial real.

Este proyecto demuestra habilidades en:

Administración de sistemas Windows Server
Gestión de infraestructura de red
Active Directory y administración de identidades
Seguridad mediante políticas de grupo
Servicios de red corporativos (DNS/DHCP)
Control de acceso a recursos compartidos
🚀 Mejoras futuras
Múltiples controladores de dominio (redundancia)
Segmentación de red (VLANs)
Automatización con PowerShell
Auditoría avanzada de seguridad
Backup de Active Directory
Integración con Linux clients
👤 Autor

Cristina Calle
Proyecto personal orientado a administración de sistemas y entornos Windows Server.
