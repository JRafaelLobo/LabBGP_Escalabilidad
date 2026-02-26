# LabBGP_Escalabilidad

## 📘 Planteamiento
Este proyecto tiene como propósito **aprender e implementar BGP** en un entorno compuesto por múltiples redes.  
La práctica se realizará físicamente en el laboratorio de Redes y se utilizará **GNS3** para la simulación.

## 🧰 Dispositivos Disponibles
Los dispositivos disponibles para el laboratorio son:

- **Cisco 1900 Series**
- **Cisco 2900 Series**
- **Cisco 4321**
- **Catalyst 2960**

## 📡 Diagramas

### Diagrama IPv4
![Diagrama IPV4](https://github.com/JRafaelLobo/LabBGP_Escalabilidad/blob/master/imagenes/LAB_BGP_IPv4.png?raw=true)

### Diagrama IPv6
![Diagrama IPV6](https://github.com/JRafaelLobo/LabBGP_Escalabilidad/blob/master/imagenes/LAB_BGP_IPv6.png?raw=true)


## Limitaciones
Debido a las restricciones físicas de nuestros dispositivos —principalmente el número reducido de interfaces disponibles en los routers— se empleará un switch con VLANs para simular enlaces punto a punto.
Cada VLAN representará un “cable” independiente del diagrama original, permitiendo replicar la topología física sin necesidad de múltiples puertos por router.
De esta forma, el switch funciona únicamente como medio de transporte para las VLANs definidas, mientras que la lógica de capa 3 se mantiene igual que en la topología física original. 

### Diagrama IPV4
![Diagrama IPV4](./imagenes/DiagramaPersonalizadoIPV4.drawio.svg)
### Diagrama IPV6
![Diagrama IPV6](./imagenes/DiagramaPersonalizadoIPV6.drawio.svg)

## 📁 Estructura del Proyecto

```
.
├── Configuracion     # Configuración rápida de cada router
├── Emulacion         # Emulaciones creadas en GNS3 para el montaje físico
└── Imagenes          # Imágenes utilizadas para la documentación
```

## 👥 Autores

| Nombre |
|--------|
| **Daniel Reyes** |
| **Victor Valladares** |
| **Adrian Burgos** |
| **Jose Lobo** |
| **Ana Diaz** |
| **Lisandro Lean** |
| **Natalia Martinez** |
| **Jose Euraque** |
| **Gerardo Cano** |
