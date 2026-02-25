<img width="1168" height="705" alt="VLAN_DHCP_Centralizado" src="https://github.com/user-attachments/assets/f97e2f57-0002-4b9a-b547-958b931bbb12" />

🖧 Proyecto Cisco Packet Tracer – Segmentación de Red con VLANs y DHCP Centralizado

📌 Descripción del Proyecto

Este proyecto simula una infraestructura de red empresarial con:

Un DataCenter principal

Servidor DHCP centralizado

Segmentación mediante VLANs

Interconexión de múltiples switches

Comunicación entre redes mediante Router

Conectividad inalámbrica en una VLAN específica

Pruebas de conectividad realizadas (Ping y Tracert)

El objetivo es implementar una red segmentada, escalable y organizada, aplicando conceptos de:

VLAN

Enrutamiento inter-VLAN

DHCP

Trunking

Access Points

Pruebas de conectividad



🌐 Segmentación por VLAN

Se implementaron 3 VLANs:

VLAN A	192.168.10.8.


VLAN B	192.168.10.16.


VLAN C	192.168.10.24.


🔌 Distribución de Dispositivos

🔹 Switch0

4 PCs conectadas

2 en VLAN A

2 en VLAN B


🔹 Switch2

2 PCs conectadas

1 en VLAN A

1 en VLAN B

Conectado a Switch0

Conectado a Switch1

🔹 Switch1

3 PCs conectadas

1 en VLAN A

1 en VLAN B

1 en VLAN C

1 Access Point

El Access Point provee conexión inalámbrica a:

2 PCs en VLAN C


🧪 Pruebas Realizadas

Se realizaron pruebas de conectividad:

✅ ping entre dispositivos de distintas VLANs

✅ tracert para verificar el recorrido de paquetes

✅ Verificación de asignación IP vía DHCP

✅ Comunicación entre switches mediante enlaces trunk

Resultados:

✔️ Conectividad correcta

✔️ Asignación dinámica funcional

✔️ Segmentación implementada correctamente

🛠 Tecnologías y Conceptos Aplicados

VLAN (802.1Q)

Trunking

DHCP Server

Router-on-a-Stick (Inter-VLAN)

Switching

Wireless Networking

Pruebas de conectividad

🎯 Objetivos del Proyecto

Implementar segmentación lógica de red

Centralizar asignación de direcciones IP

Permitir comunicación controlada entre VLANs

Simular infraestructura empresarial escalable

Practicar configuración en Cisco Packet Tracer
