# 🌐 Laboratorios - Redes de Datos (CIT-2114)

El objetivo es documentar y presentar el trabajo práctico realizado a lo largo del semestre, abarcando desde el análisis de paquetes hasta la configuración de protocolos de enrutamiento complejos.

---

## 🔬 Laboratorios Realizados

Aquí encontrarás un resumen de cada laboratorio, los temas cubiertos y las tecnologías utilizadas.

### **Laboratorio 1: Captura y Análisis de Paquetes con Wireshark**
Este laboratorio se centró en el uso de **Wireshark** como herramienta fundamental para el análisis de redes. Se realizaron capturas de tráfico para estudiar el comportamiento de los protocolos más comunes.

-   **Temas cubiertos:**
    -   Identificación de elementos y configuración de una red LAN/WLAN.
    -   Captura y análisis de paquetes **ICMP** (Ping).
    -   Análisis de TPDUs (Segmentos **TCP** y Datagramas **UDP**).
    -   Diferencias y análisis de paquetes **HTTP** y **HTTPS**.

### **Laboratorio 2: Análisis del Funcionamiento del Protocolo ARP**
El objetivo fue comprender a fondo el Protocolo de Resolución de Direcciones (**ARP**). Se utilizó tanto la línea de comandos como herramientas de simulación para observar su funcionamiento en una red local.

-   **Temas cubiertos:**
    -   Uso del comando `arp` para gestionar la caché de direcciones.
    -   Captura de mensajes **ARP Request** (Broadcast) y **ARP Reply** (Unicast) con Wireshark.
    -   Simulación del protocolo ARP en **Cisco Packet Tracer** para visualizar el proceso de resolución de direcciones MAC.

### **Laboratorio 3: Configuración y Análisis del Protocolo Spanning Tree (STP)**
Este laboratorio exploró el Protocolo Spanning Tree (**STP**) como mecanismo para prevenir bucles en redes con enlaces redundantes. Se analizaron sus estados y su impacto en la topología de la red.

-   **Temas cubiertos:**
    -   Simulación de **tormentas de broadcast** al deshabilitar STP.
    -   Elección del **Root Bridge** y estados de los puertos (Designated, Root, Blocking).
    -   Análisis de convergencia de la red ante fallos de enlace.
    -   Comparación del rendimiento y tiempos de convergencia entre **STP** y **Rapid Spanning Tree Protocol (RSTP)**.

### **Laboratorio 4: Routing Estático y Dinámico**
El último laboratorio se enfocó en la configuración y verificación de rutas estáticas y dinámicas, implementando algunos de los protocolos de enrutamiento más importantes en la industria.

-   **Temas cubiertos:**
    -   Configuración de **rutas estáticas** y rutas por defecto en **Cisco Packet Tracer**.
    -   Implementación de protocolos de enrutamiento dinámico:
        -   **RIPv2** (Protocolo de Información de Enrutamiento).
        -   **EIGRP** (Protocolo de Enrutamiento de Gateway Interior Mejorado).
        -   **OSPF** (Abrir la Ruta Más Corta Primero).
    -   Análisis de tablas de enrutamiento y convergencia de la red ante fallos.

---

## 🛠️ Herramientas Utilizadas

-   **Cisco Packet Tracer:** Para el diseño, simulación y configuración de topologías de red.
-   **Wireshark:** Para la captura y análisis detallado de paquetes de red.
-   **Línea de Comandos (CMD/Terminal):** Para la ejecución de comandos de red como `ping`, `ipconfig` y `arp`.

---

## 👨‍💻 Autores

Este trabajo fue realizado en colaboración por:

-   Paula Villarroel
-   Ezequiel Morales
-   Dylan Barahona
