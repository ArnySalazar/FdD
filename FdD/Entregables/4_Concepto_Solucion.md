
## Propuesta de Solución

Nuestro sistema automatizado de gestión de residuos se basa en un mapa de nodos interconectados, donde cada nodo representa un mini contenedor de basura equipado con potenciómetros para medir el nivel de llenado. Estos potenciómetros están conectados a un ESP32, alimentado por una batería de litio y un regulador LM2595, que transmite la información a un sistema central. Un aplicativo móvil recibe estos datos y, utilizando un algoritmo que calcula la ruta óptima basada en una fórmula, determina la ruta más eficiente considerando la capacidad del camión recolector. El sistema prioriza los contenedores más llenos, optimizando la recolección para maximizar la eficiencia y minimizar el tránsito innecesario.

## Caja Negra

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/caja_negra_1.png" width="820px"></p>

**Figura 1:** Diagrama de Caja Negra del proyecto. Elaboración propia.

## Caja Negra definiciones
<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/definicion_entrada_salida_1.png" width="820px"></p>

**Figura 2:** Definición de Entradas y Salidas. Elaboración propia.

## Esquema de Funciones

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/esquema_funciones_1.png" width="820px"></p>

**Figura 3:** Esquema de Funciones del proyecto. Elaboración propia.

## Definición de funciones

+ *Recibe:* Recolecta toda la información de los tachos con sensores ya establecidos en diversos puntos del distrito. En el proyecto los datos recibidos son de los potenciómetros de cada tacho.
+ *Almacenar:* Los datos son almacenados en una base de datos.
+ *Ordena:* Clasifica los datos según el nivel de llenado y la prioridad de recolección, preparando la información para el cálculo de ruta.
+ *Procesa:* Nuestro software procesaría y daría la ruta más óptima de recolección según nuestro algoritmo, utilizando la fórmula y tomando en cuenta la capacidad del camión.
+ *Transmitir:* Daría la orden al camión compactador sobre la ruta que debe seguir.
+ *Visualizar:* El usuario podrá visualizar la ruta optimizada y así el estado actual de cada contenedor mediante la app ya implementada.
+ *Notifica o Alerta:* Genera alertas y notificaciones sobre los contenedores que requieren atención inmediata.

## Matriz Morfológica

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/Matriz_Morfologica.png)

**Figura 4:** Matriz Morfológica del proyecto. Elaboración propia.

## Tabla de Valoración

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/t_valoracion.png)

**Figura 5:** Tabla de Valoración del proyecto. Elaboración propia.

## Conclusión del Concepto de Solución

El concepto de solución con flechas de color rojo fue elegido principalmente por su funcionalidad adecuada en relación con la inversión realizada. Además, tiene una buena compatibilidad con las herramientas que vamos a utilizar, como el software de mapeo, el prototipo que seguirá las rutas en los puntos clave y la aplicación que utilizará el público objetivo. Para empezar, estamos optando por una fuente de energía accesible, económica y versátil, que también es utilizada por nuestro curso durante algunos de nuestros talleres de electrónica. Continuamos con el sensor elegido, . Dado que trabajaremos con software, también necesitaremos una placa microcontroladora como Arduino, que podremos implementar fácilmente con el código propuesto. Nuestra solución complementa equipos que puedan trabajar bien entre sí y sean ajustables para una conexión adecuada.
