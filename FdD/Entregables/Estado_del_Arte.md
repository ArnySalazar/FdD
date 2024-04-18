# **Estado del Arte**
## Contexto Científico
<h3 align="center"> Artículo 1: Modelo de optimización de rutas de recogida de residuos para vincular el ahorro de costes y reducción de emisiones para alcanzar objetivos de desarrollo sostenible </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule1_img1.png" width="520px"></p>

**Figura 1:** Portada del primer artículo consultado. Fue extraído de: “Waste  collection route optimisation model for linking cost saving and emission reduction to achieve sustainable development goals” y elaborado por M.A. Hannana, R.A. Begumb, Ali Q. Al-Shetwic, P.J. Kera, M.A. Al Mamund, Aini Hussaind, Hassan Basrie, T.M.I. Mahlia 1. [[1]](https://www.sciencedirect.com/science/article/abs/pii/S2210670720306144) 

Este artículo propone un modelo de optimización de rutas de recolección de residuos sólidos con el fin de mejorar la eficiencia de recolección y su vinculación con los objetivos de desarrollo sostenible (SDGs). Describen un modelo de programación lineal entera mixta (MILP) y se formulan modelos matemáticos que tienen en cuenta variables como la capacidad de los vehículos de recolección, la distancia entre contenedores y la cantidad de residuos recolectados.; que utiliza dos enfoques: optimización de ruta fija (FRO) con datos estáticos y optimización de ruta variable (VRO) con datos en tiempo real. Además, se calcula el consumo de combustible y las emisiones de carbono asociadas a la recolección de residuos, con el objetivo de reducir los costos y el impacto ambiental de esta actividad. Utilizó datos de simulación para generar eficiencia en la recolección, reducción de costos y emisiones. Sus resultados muestran que VRO mejoró la eficiencia de recolección en un 26.08%, logrando ahorros de costos del 44.44% y una reducción de emisiones de carbono del 17.60% al considerar un nivel mínimo de llenado del 70%. [[1]](https://www.sciencedirect.com/science/article/abs/pii/S2210670720306144) 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule1_img2.png" width="600px"></p>

**Tabla 1:** Reducción de emisiones de CO2 para VRO y FRO. La tabla muestra que al aplicar el sistema desarrollado, los efectos ambientales disminuirán debido a la menor distancia recorrida y menos tiempo de permanencia en la carretera que en la condición actual, lo que eventualmente conduce a una reducción de las emisiones. Fue extraído de: “Waste  collection route optimisation model for linking cost saving and emission reduction to achieve sustainable development goals” y elaborado por M.A. Hannana, R.A. Begumb, Ali Q. Al-Shetwic, P.J. Kera, M.A. Al Mamund, Aini Hussaind, Hassan Basrie, T.M.I. Mahlia [[1]](https://www.sciencedirect.com/science/article/abs/pii/S2210670720306144)  

<h3 align="center"> Artículo 2: Una solución de IoT para el seguimiento de la carga de flotas de camiones de basura </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img1.png" width="520px"></p>

**Figura 2:** Portada del segundo artículo consultado. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J [[2]](https://ieeexplore.ieee.org/document/9274699) 

Este artículo trata sobre el desafío de gestionar eficientemente la recolección de residuos sólidos en áreas urbanas, proponiendo una solución basada en Internet de las Cosas (IoT). Cuyo objetivo es monitorear la ubicación y la carga de los camiones de recolección en tiempo real para optimizar dinámicamente las rutas de recolección. Se utiliza tecnología IoT para medir la carga del camión y determinar su posición, enviando estos datos a una solución de computación en la nube. La implementación se probó con éxito en el campo, utilizando una flota real en operaciones diarias. La solución mejora la eficiencia operativa, reduce costos y evita problemas como multas por sobrepeso. Tiene Azure como plataforma de nube pública, aprovechando servicios como Azure IoT Hub y Time Series Insights para el procesamiento de datos y generación de insights. Además, se detalla la arquitectura del sistema, incluyendo componentes de borde como microcontroladores ESP32 y sensores de peso y posición [[2]](https://ieeexplore.ieee.org/document/9274699) 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img2.png" width="600px"></p>

**Figura 3:** Descripción General de la Arquitectura completa del sistema implementado. La solución actual se basa en Azure IoT, donde todos los dispositivos son administrados por Azure IoT Hub y los mensajes se enrutan a servicios de Time Series Insights o alarmas basadas en propiedades generadas por una pequeña inteligencia incrustada en el código del dispositivo. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J [[2]](https://ieeexplore.ieee.org/document/9274699) 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img3.png" width="600px"></p>

**Figura 4:** Componentes de Hardware. Muestra que cada camión cuenta con un dispositivo que incluye un microcontrolador ESP32, módulos de comunicación GSM y GPS, así como conexiones a transceptores CAN, módulos RS485 y SDCard para almacenar datos sin procesar como respaldo, junto con un LED RGB para indicar el estado del módulo. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J [[2]](https://ieeexplore.ieee.org/document/9274699) 

<h3 align="center"> Artículo 3: Recolección de Residuos Sólidos como servicio mediante solución IoT para Ciudades Inteligentes </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img1.png" width="520px"></p>

**Figura 5:** Portada del tercer artículo consultado. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. [[3]](https://ieeexplore.ieee.org/abstract/document/8537326/authors#authors)

Este artículo propone un sistema eficiente basado en IoT (Internet de las Cosas) para la gestión de residuos sólidos en ciudades inteligentes. Este sistema permite monitorear los contenedores de basura, programar dinámicamente y optimizar las rutas de los camiones recolectores de basura. Los contenedores están equipados con dispositivos integrados de bajo costo, a través de un prototipo de hardware con sensores ultrasonidos (HC-SR04) para medir el nivel de basura en los contenedores, los módulos GPS (EM-506 GPS receiver) para obtener la ubicación en tiempo real de los contenedores, y los módulos Wi-Fi (ESP8266) para la conexión a la red y la transmisión de datos a la nube. Además,utiliza un algoritmo de ruta más corta para calcular las rutas óptimas. La información recopilada se visualiza mediante una aplicación móvil y una plataforma web, lo que facilita el seguimiento y control por parte de los conductores de los camiones de recolección y las autoridades municipales. La integración de tecnologías como ThingSpeak para el almacenamiento en la nube y Google Maps API para la planificación de rutas contribuye a una gestión más inteligente y eficiente de los residuos, mejorando la utilización de recursos y la recolección de datos en tiempo real. [[3]](https://ieeexplore.ieee.org/abstract/document/8537326/authors#authors)

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img2.png" width="520px"></p>

**Figura 6:** Sistema propuesto y Patrón de transmisión. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. [[3]](https://ieeexplore.ieee.org/abstract/document/8537326/authors#authors)

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img3.png" width="520px"></p>

**Figura 7:** Diagrama de circuito del sistema integrado y Estadísticas de la plataforma ThingSpeak IoT. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. [[3]](https://ieeexplore.ieee.org/abstract/document/8537326/authors#authors)

## Contexto Comercial 
<h3 align="center"> Dispositivos en el mercado con funciones relacionadas a la problemática </h3>

**1. Cerca: Sistema de Gestión de Transporte (TMS):**

Se trata de un software TMS el cual permite tener una gestión inteligente acerca de las rutas transportadoras que trabaja con diversas compañías con el fin de agilizar las rutas de entrega.

Entre sus funciones tenemos:
- Administración del transporte y gestión de flotas incluyendo costos.
- Planificación óptima de la distribución de productos y territorios con el menor costo logístico.
- Yard management en conjunto con un control de ingresos y afinación de viajes por prioridad.
- Monitoreo logístico para verificar el cumplimiento de rutas en vivo.
- Dashboards con estadísticas fácilmente configurables a cada necesidad. [](https://www.cercatechnology.com/mx/portfolio/tms/)

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cerca.png)  
**Figura 8:** Logo de la compañía. Fue extraído de 

**2. RoutingMaps: Software optimizador de rutas de recolección de residuos**

Definimos este software como un sistema que tiene la capacidad de abarcar enfoques distintos de las empresas que lo adquieren, si es que nosotros deseamos optimizar la ruta de recogida de residuos, este nos permitirá hacer un adecuado y detallado seguimiento a cada etapa; además, cuenta con mapas actualizados gracias a Google Maps, asegurando que los conductores puedan tomar el mejor camino. Finalmente, puede evaluar la ruta y mejorar su planificación, incluso asignar automáticamente los puntos de recogida de residuos. Todas estas herramientas nos dan como resultado una reducción en distancias recorridas, tiempo de recojo y por tanto, reducción en las emisiones de CO2 de parte de los vehículos. [[5]](https://www.routingmaps.com/ventajas/)

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/Tech4log-Routingmaps.png)
**Figura 9:** Logo de la compañía. Fue extraído de 

**3. miResiduo: aplicación que gestiona rutas y registra la recolección de residuos**

Esta plataforma digital, que consiste en un software de gestión de residuos en conjunto a una aplicación integrada desarrollada con el fin de capturar datos de recolección de residuos, brindando información precisa, confiable y actualizada sobre la gestión de desechos de manera eficiente. 
Algunos de los beneficios de implementar esta app en empresas recolectoras son:

- Trazabilidad de los residuos recolectados y destinados.
- Sincronización de datos recolectados en campo en el sistema web
- Emisión automática del Informe de visita realizada enviado al correo.
- Posibilidad de capturar evidencia fotográfica de cada residuo recolectado.
- Fecha y hora exactas de los registros de cada recolección;
- Mapa para comprobar la ruta ejecutada vs la programada. [[6]]([https://www.routingmaps.com/ventajas/](https://www.meuresiduo.com/blog-es/app-para-gestion-de-rutas-y-registros-de-recolecciones-de-residuos/
))

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/Logo-MeuResiduo.png)

**Figura 10:** Logo de la compañía. Fue extraído de 
![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/meuresiduo2.png)

**Figura 11:** Apariencia del aplicativo. Fue extraído de 

PATENTES
----------------------------------------------------------------------------------------------------------------------------------
**Patente N°1**

**Dispositivo, sistema y método para la monitorización, control y optimización de un servicio de recogida de residuos** (US20190019167A1).

**Inventor/es**: Edy Candel, Shlomo Akiva Ashkenazi

**Fecha de publicación**: 2019-01-17

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/patente1.png" width="600px"></p>

**Descripción**:

La gestión eficiente de residuos en flotas de camiones de basura es fundamental para los servicios de recolección. Un dispositivo de medición de residuos, equipado con cámaras de luz visible, sensores de volumen y un controlador, se despliega frente a la tolva del camión. Su función es medir el volumen de residuos en la tolva utilizando sensores. El método calcula el volumen de residuos descargados del contenedor restando la medición previa a la carga de la medición posterior. Este sistema optimiza y supervisa el funcionamiento de la flota de camiones de basura, basándose en las mediciones proporcionadas por los dispositivos de medición de residuos.

Más información.-US020190019167A120190117 (storage.googleapis.com)

**Patente N°2**

**Sistema de gestión del tráfico**(US7663505B2).

**Inventor/es**: Mark W. Publicover

**Fecha de publicación**: 2010-02-16

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/patente2.png" width="600px"></p>

**Descripción**:

Un dispositivo inteligente de control de tráfico comunica datos a los vehículos cercanos sobre su estado actual y previsto. Esto permite que los vehículos ajusten su velocidad para evitar llegar al dispositivo de control de tráfico hasta que se permita el paso, evitando paradas innecesarias y aceleraciones repetidas. Además, en otras implementaciones, el dispositivo o los sistemas de control de tráfico reciben información de los vehículos y la transmiten a otros vehículos.

Más información.-1499084960126058918-07663505 (storage.googleapis.com).

## Referencias:

[[1]](https://www.sciencedirect.com/science/article/abs/pii/S2210670720306144) Hannan, M. A., Begum, R. A., Al-Shetwi, A. Q., Ker, P. J., Al Mamun, M. A., Hussain, A., … Mahlia, T. M. I. (2020). Waste collection route optimisation model for linking cost saving and emission reduction to achieve sustainable development goals. Sustainable Cities and Society, 102393. doi:10.1016/j.scs.2020.102393

[[2]](https://ieeexplore.ieee.org/document/9274699)  Maia, J., & Yudi, J. (2020). An IoT solution for load monitoring and tracking of garbage-truck fleets. 2020 IEEE Conference on Industrial Cyberphysical Systems (ICPS). doi:10.1109/icps48405.2020.9274699

[[3]](https://ieeexplore.ieee.org/abstract/document/8537326/authors#authors) Chaudhari, S. S., & Bhole, V. Y. (2018). Solid Waste Collection as a Service using IoT-Solution for Smart Cities. 2018 International Conference on Smart City and Emerging Technology (ICSCET). doi:10.1109/icscet.2018.8537326

[4] https://www.cercatechnology.com/mx/portfolio/tms/

[5] https://www.routingmaps.com/ventajas/

[6]https://www.meuresiduo.com/blog-es/app-para-gestion-de-rutas-y-registros-de-recolecciones-de-residuos/








