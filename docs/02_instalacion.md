# 02 - Plan de instalación del sistema

## Objetivo

Definir la configuración previa a la instalación de Windows Server 2022 para el laboratorio de Active Directory.

---

## Red del laboratorio

- Red: 192.168.10.0/24  
- Gateway: 192.168.10.1  
- DNS inicial: 192.168.10.10  

---

## Servidor

- Nombre: TS-DC01  
- Sistema operativo: Windows Server 2022 (Desktop Experience)  
- Rol futuro: Controlador de dominio  

### Configuración de red prevista

- IP: 192.168.10.10  
- Máscara: 255.255.255.0  
- Gateway: 192.168.10.1  
- DNS: 127.0.0.1 (temporal durante instalación)  

---

## Cliente

- Nombre: TS-CLI01  
- Sistema operativo: Windows 11  
- Configuración: DHCP  

---

## Roles previstos

- Active Directory Domain Services (AD DS)  
- DNS  
- DHCP (opcional)  
- File Server  

---

## Objetivo de esta fase

Preparar la infraestructura base sobre la que se construirá el dominio empresarial TechSolutions S.L.

## Configuración inicial del servidor

Una vez instalado el sistema operativo, se han realizado las siguientes configuraciones:

### Cambios realizados

- Nombre del equipo cambiado a TS-DC01
- Configuración de red estática aplicada

### Configuración de red

- IP: 192.168.10.10
- Máscara: 255.255.255.0
- Gateway: 192.168.10.1
- DNS: 192.168.10.10

---

## Estado actual

El servidor está preparado para la instalación de Active Directory Domain Services (AD DS).