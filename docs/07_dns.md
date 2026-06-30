# 07 - Servicio DNS

## Objetivo

Verificar el correcto funcionamiento del servicio DNS integrado con Active Directory.

---

## Configuración

El servicio DNS fue instalado automáticamente durante la promoción del servidor a controlador de dominio.

---

## Zona DNS

- Zona de búsqueda directa: techsolutions.local

---

## Comprobaciones realizadas

- Resolución del nombre TS-DC01 mediante `nslookup`.
- Resolución del dominio `techsolutions.local`.
- Verificación de la zona DNS desde el administrador de DNS.

---

## Resultado

El servicio DNS resuelve correctamente los nombres del dominio y permite la comunicación entre los equipos del laboratorio.