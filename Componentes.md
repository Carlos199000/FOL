# Componentes de un ordenador
En esta guía se describirá los componentes de un ordenador y sus utilidades.
---
# Índice 
- [1. Componentes y utilidades](#1-componentes-y-utilidades) 
    - [Cpu o Procesador](#1-cpu-o-procesador)   
    - [Tarjeta Gráfica](#2-tarjeta-gráfica)
    - [Memoria Ram](#3-memoria-ram)
    - [Placa base](#4-placa-base)
    - [Almacenamiento](#5-almacenamiento) 
    - [Fuente de alimentación](#6-fuente-de-alimentación)
    - [Sistemas de refrigeración](#7-sistemas-de-refrigeración)
    - [Caja](#8-caja) 
- [2. ¿Como puedo saber la dirección IP de mi ordenador?](#2-como-puedo-saber-la-dirección-ip-de-mi-ordenador) 
- [3. ¿Como puedo comprobar la conexión de red?](#3-como-puedo-comprobar-la-conexión-de-red) 

## 1. Componentes y utilidades
#### 1. **Cpu o Procesador**:
 su trabajo es ejecutar los programas de manera continua y gestionar la interacción con los periféricos y el resto de los componentes del ordenador.
 
 * *Núcleos de un procesador:* Su función principal es leer, interpretar y ejecutar instrucciones y cálculos, permitiendo que la computadora realice varias acciones al mismo tiempo (multitarea y procesamiento paralelo) 

* *hilos de un procesador:* Su función principal es dividir y gestionar las tareas de forma más eficiente, permitiendo que cada núcleo físico de la CPU trabaje con más de un flujo de datos al mismo tiempo.
![CPU](https://pc-solucion.es/wp-content/uploads/2017/06/que-es-cpu.jpg)

#### 2. **Tarjeta Gráfica**: 
su trabajo es liberar al procesador de tener que mostrar y calcular los gráficos que vemos en la pantalla o el monitor.

- Puede ser: 
    - Integrada: Viene dentro del mismo procesador (CPU) o placa base. (comparte la memoria RAM del sistema)
    - Dedicada: Es un componente independiente que se instala por separado en la placa base.(cuenta con su propia memoria exclusiva llamada VRAM)

>Si se usa para ofimática que no requiera una potencia alta se recomienda la integrada por el costo.

![GPU](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/geforce-rtx-graphics-cards/geforce-rtx-2080-technical-photography-angled-004-850px.png)

#### 3. **Memoria Ram**:
 almacena de manera temporal y mientras el ordenador está encendido, todos los programas y los datos con las que el procesador ha de ejecutar.

![Memoria Ram](https://thumb.pccomponentes.com/w-530-530/articles/1093/10938281/1199-memoria-ram-kingston-32gb-2x16gb-ddr5-6000mt-s-fury-beast-expo-black.jpg)

#### 4. **Placa base**:
 Su trabajo es la intercomunicación entre los diferentes componentes que están conectados a la misma, así como de la distribución de la energía de los mismos que viene de la fuente de alimentación.

![Placa base](https://img.pccomponentes.com/pcblog/1736809200000/que-es-una-placa-base-tipos-instalar-2.jpg)

#### 5. **Almacenamiento**:
 Los dispositivos de almacenamiento permiten guardar todos los datos sin tener que mantener el ordenador encendido.
Hay que recalcar que existen tres tipos de disco duros:
1. HDD
2. SSD
3. NVMe

| Tipo               |  Velocidad         | Precio             |  Resistencia       |
|--------------------|--------------------|--------------------|--------------------|
| HDD                | Baja (150mb)       | Muy bajo           | Frágil (piezas móviles)|
| SSD SATA             | Media (550mb)      | Medio              | Alta               |
| SSD NVMe               | Muy alta (1500mb)  | Alto               | Alta               |

> Recalcar que el SSD NVMe a diferencia del SSD SATA y HDD, tiene que ser instalado en la ranura M2 de la placa (o con un adaptador de PCIe) , y el SSD y HDD pueden ser instalador por medio de USB (externo) o conectados a la placa (conector SATA).

### HHD
![HDD](https://img.pccomponentes.com/articles/5/52021/22.jpg) 
### SSD SATA
![SSD](https://m.media-amazon.com/images/I/61PmESVGGTL.jpg) 
### SSD NVMe 
![NVMe](https://thumb.pccomponentes.com/w-530-530/articles/24/245950/2.jpg) 

#### 6. **Fuente de alimentación**:
 La fuente de alimentación es la principal encargada de alimentar al sistema con energía. Dependiendo del modelo tendrá conexiones distintas, mayor o menor potencia así como sistemas de protección adicionales.

![Fuente de alimentación](https://img.pccomponentes.com/pcblog/2274/fuente-alimentacion.jpg) 

#### 7. **Sistemas de refrigeración**:
 dentro de este apartado se encuentran 3 componentes; el disipador (para la CPU), los ventiladores, y la posiblidad de refrigeración líquida.
Los sistemas de refrigeración permiten que el hardware del ordenador funcione sin ningún problema de temperatura.

### Disipador CPU
![CPU disipador](https://static.fnac-static.com/multimedia/Images/ES/MC/a7/a0/91/9543847/1541-3/tsp20240718120708/Disipador-CPU-Doble-Torre-Mars-Gaming-MCPU-XU9-TDP-400W-2x-Ventiladores-FDB-9-Heatpipes-BPH-Negro.jpg)  

### Ventiladores 
![Ventiladores](https://thumb.pccomponentes.com/w-530-530/articles/1088/10887544/1670-corsair-rs120-r-argb-pack-3-ventiladores-de-flujo-inverso-120mm-pwm-negro.jpg) 

### Refrigeración líquida
![Refrigeración líquida](https://thumb.pccomponentes.com/w-530-530/articles/1083/10834757/1272-asus-rog-strix-lc-iii-360-kit-de-refrigeracion-liquida-360mm-negro-review.jpg) 

#### 8. **Caja**:
 La caja de PC es un componente esencial de la configuración, de ella depende la protección física y la optimización para crear el mejor flujo de aire posible.
![Caja](https://m.media-amazon.com/images/I/81Jm7SYdf3L.jpg)  

## 2. ¿Como puedo saber la dirección IP de mi ordenador?

Usando el comando `ipconfig /all` en cmd se mostrará la dirección IP MAC y la dirección IPv4 tanto como la IPv6
--- 
## 3. ¿Como puedo comprobar la conexión de red?
Con los comandos en cmd
 ```
ping google.com
hostname
systeminfo
```
El comando *ping google.com* comprueba si tu ordenador puede comunicarse con otro dispositivo o servidor.

El comando *hostname* muestra el nombre que tiene asignado tu ordenador dentro de Windows.

El comando *systeminfo* muestra información detallada sobre el ordenador y su sistema operativo (p. ej. Tipo de procesador, memoria RAM, versión de Windows, Fecha de instalación del sistema).

[Lista de comandos de cmd](https://www.dos-a-la-tres.com/Aplicaciones/Programacion-de-Pol-Software/Documentos-y-Sitios-Recomendados/Manuales-de-Formacion/Manual-de-Comandos-de-CMD-Windows-11.pdf) 

## BIOS
![BIOS de una placa Asus](https://kmpic.asus.com/images/2020/08/13/d621a106-c217-4ec0-b58a-cc3feef1b879.png)

El propósito fundamental del BIOS es iniciar, y probar el hardware del sistema y cargar un gestor de arranque o un sistema operativo desde un dispositivo de almacenamiento de datos. Además, el BIOS provee una capa de abstracción para el hardware, por ejemplo, que consiste en una vía para que los programas de aplicaciones y los sistemas operativos interactúen con el teclado, el monitor y otros dispositivos de entrada/salida.


## Periféricos

- Mouse
- Pantalla
- Teclado
- Cascos

## Próximas mejoras
- Tipos de conectores
- Cómo actualizar la BIOS
- Cómo actualizar los controladores
