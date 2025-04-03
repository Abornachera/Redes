# **Documentación de la Red VLAN**

## **1. Descripción General**
Este documento describe la topología de red basada en VLANs implementada en Cisco Packet Tracer. La red se encuentra segmentada en cuatro VLANs distintas para mejorar la organización, la seguridad y la eficiencia del tráfico de datos.

## **2. Segmentación en VLANs**
La red está dividida en las siguientes VLANs:

| VLAN ID | Nombre  | Rango de IP  |
|---------|---------|--------------|
| 22      | VLAN22  | 100.0.0.0/8  |
| 33      | VLAN33  | 101.0.0.0/8  |
| 44      | VLAN44  | 102.0.0.0/8  |

Cada VLAN agrupa un conjunto específico de PCs, permitiendo la segmentación y el control del tráfico de datos en la red.

## **3. Topología y Conectividad**

- Se utiliza una arquitectura jerárquica con switches conectados entre sí.
- Se han configurado enlaces troncales (trunk) entre los switches para permitir la comunicación entre VLANs a través de un router o un switch de capa 3.
- Cada PC está asignado a una VLAN específica.

