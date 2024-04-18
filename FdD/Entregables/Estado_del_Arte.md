# **Estado del Arte**
## Contexto Científico
<h3 align="center"> Artículo 1: Modelo de optimización de rutas de recogida de residuos para vincular el ahorro de costes y reducción de emisiones para alcanzar objetivos de desarrollo sostenible </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule1_img1.png" width="520px"></p>

**Figura 1:** Portada del primer artículo consultado. Fue extraído de: “Waste  collection route optimisation model for linking cost saving and emission reduction to achieve sustainable development goals” y elaborado por M.A. Hannana, R.A. Begumb, Ali Q. Al-Shetwic, P.J. Kera, M.A. Al Mamund, Aini Hussaind, Hassan Basrie, T.M.I. Mahlia (1). 

Este artículo propone un modelo de optimización de rutas de recolección de residuos sólidos con el fin de mejorar la eficiencia de recolección y su vinculación con los objetivos de desarrollo sostenible (SDGs). Describen un modelo de programación lineal entera mixta (MILP) y se formulan modelos matemáticos que tienen en cuenta variables como la capacidad de los vehículos de recolección, la distancia entre contenedores y la cantidad de residuos recolectados.; que utiliza dos enfoques: optimización de ruta fija (FRO) con datos estáticos y optimización de ruta variable (VRO) con datos en tiempo real. Además, se calcula el consumo de combustible y las emisiones de carbono asociadas a la recolección de residuos, con el objetivo de reducir los costos y el impacto ambiental de esta actividad. Utilizó datos de simulación para generar eficiencia en la recolección, reducción de costos y emisiones. Sus resultados muestran que VRO mejoró la eficiencia de recolección en un 26.08%, logrando ahorros de costos del 44.44% y una reducción de emisiones de carbono del 17.60% al considerar un nivel mínimo de llenado del 70%.  (1).

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule1_img2.png" width="600px"></p>

**Tabla 1:** Reducción de emisiones de CO2 para VRO y FRO. La tabla muestra que al aplicar el sistema desarrollado, los efectos ambientales disminuirán debido a la menor distancia recorrida y menos tiempo de permanencia en la carretera que en la condición actual, lo que eventualmente conduce a una reducción de las emisiones. Fue extraído de: “Waste  collection route optimisation model for linking cost saving and emission reduction to achieve sustainable development goals” y elaborado por M.A. Hannana, R.A. Begumb, Ali Q. Al-Shetwic, P.J. Kera, M.A. Al Mamund, Aini Hussaind, Hassan Basrie, T.M.I. Mahlia (1). 

<h3 align="center"> Artículo 2: Una solución de IoT para el seguimiento de la carga de flotas de camiones de basura </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img1.png" width="520px"></p>

**Figura 2:** Portada del segundo artículo consultado. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J (2). 

Este artículo trata sobre el desafío de gestionar eficientemente la recolección de residuos sólidos en áreas urbanas, proponiendo una solución basada en Internet de las Cosas (IoT). Cuyo objetivo es monitorear la ubicación y la carga de los camiones de recolección en tiempo real para optimizar dinámicamente las rutas de recolección. Se utiliza tecnología IoT para medir la carga del camión y determinar su posición, enviando estos datos a una solución de computación en la nube. La implementación se probó con éxito en el campo, utilizando una flota real en operaciones diarias. La solución mejora la eficiencia operativa, reduce costos y evita problemas como multas por sobrepeso. Tiene Azure como plataforma de nube pública, aprovechando servicios como Azure IoT Hub y Time Series Insights para el procesamiento de datos y generación de insights. Además, se detalla la arquitectura del sistema, incluyendo componentes de borde como microcontroladores ESP32 y sensores de peso y posición (2). 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img2.png" width="600px"></p>

**Figura 3:** Descripción General de la Arquitectura completa del sistema implementado. La solución actual se basa en Azure IoT, donde todos los dispositivos son administrados por Azure IoT Hub y los mensajes se enrutan a servicios de Time Series Insights o alarmas basadas en propiedades generadas por una pequeña inteligencia incrustada en el código del dispositivo. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J (2). 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule2_img3.png" width="600px"></p>

**Figura 4:** Componentes de Hardware. Muestra que cada camión cuenta con un dispositivo que incluye un microcontrolador ESP32, módulos de comunicación GSM y GPS, así como conexiones a transceptores CAN, módulos RS485 y SDCard para almacenar datos sin procesar como respaldo, junto con un LED RGB para indicar el estado del módulo. Fue extraído de: “An IoT solution for load monitoring and tracking of garbage-truck fleets” y elaborado por Maia, J., & Yudi, J (2). 

<h3 align="center"> Artículo 3: Recolección de Residuos Sólidos como servicio mediante solución IoT para Ciudades Inteligentes </h3>

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img1.png" width="520px"></p>

**Figura 5:** Portada del tercer artículo consultado. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. (3).

Este artículo propone un sistema eficiente basado en IoT (Internet de las Cosas) para la gestión de residuos sólidos en ciudades inteligentes. Este sistema permite monitorear los contenedores de basura, programar dinámicamente y optimizar las rutas de los camiones recolectores de basura. Los contenedores están equipados con dispositivos integrados de bajo costo, a través de un prototipo de hardware con sensores ultrasonidos (HC-SR04) para medir el nivel de basura en los contenedores, los módulos GPS (EM-506 GPS receiver) para obtener la ubicación en tiempo real de los contenedores, y los módulos Wi-Fi (ESP8266) para la conexión a la red y la transmisión de datos a la nube. Además,utiliza un algoritmo de ruta más corta para calcular las rutas óptimas. La información recopilada se visualiza mediante una aplicación móvil y una plataforma web, lo que facilita el seguimiento y control por parte de los conductores de los camiones de recolección y las autoridades municipales. La integración de tecnologías como ThingSpeak para el almacenamiento en la nube y Google Maps API para la planificación de rutas contribuye a una gestión más inteligente y eficiente de los residuos, mejorando la utilización de recursos y la recolección de datos en tiempo real. (3)

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img2.png" width="520px"></p>

**Figura 6:** Sistema propuesto y Patrón de transmisión. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. (3). 

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_3/cc_articule3_img3.png" width="520px"></p>

**Figura 7:** Diagrama de circuito del sistema integrado y Estadísticas de la plataforma ThingSpeak IoT. Fue extraído de: “Solid Waste Collection as a Service using IoT-Solution for Smart Cities” y elaborado por Chaudhari, S. S., & Bhole, V. Y. (3). 

## CONTEXTO COMERCIAL







