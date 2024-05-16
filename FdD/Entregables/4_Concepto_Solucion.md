
## Propuesta de Solución

Nuestro sistema automatizado de gestión de residuos se basa en un mapa de nodos interconectados, donde cada nodo representa un mini contenedor de basura equipado con potenciómetros para medir el nivel de llenado. Estos están conectados a un Arduino que procesa la información de llenado de cada contenedor y determina la ruta más eficiente utilizando el algoritmo de Dijkstra. Un vehículo seguidor de línea, equipado con sensores para detectar y seguir las líneas marcadas en el suelo, realizará la recolección. El sistema prioriza los contenedores más llenos, optimizando la ruta de recolección para maximizar la eficiencia y minimizar el tránsito innecesario.

## Caja Negra

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/caja_negra.png" width="820px"></p>

Figura 1: Diagrama de Caja Negra del proyecto. Elaboración propia.

## Caja Negra definiciones
<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/definicion_entrada_salida.png" width="820px"></p>

Figura 2: Definición de Entradas y Salidas. Elaboración propia.

## Esquema de Funciones

<p align="center"><img src ="https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/esquema_funciones.png" width="820px"></p>
Figura 3: Esquema de Funciones del proyecto. Elaboración propia.

## Definición de funciones

+ *Transformar*: alimentarse de la fuente de energía elegida para el encendido del prototipo y su debida conexión con el software para así poner en marcha sus funciones.
+ *Traducir*: captar la información obtenida por los sensores basado en las condiciones del contenedor y señalarlas en distintos rangos de capacidad de llenado.
+ *Procesar*: analiza y procesa la información traducida de los contenedores, e identifica las características puestos en la ruta con el fin de generar una ruta óptima de recojo.
+ *Almacenar*: guarda la información procesada para obtener una respuesta rápida acerca de la información actualizada entre el software optimizador con las rutas dadas según los datos de los tachos prioritarios.
+ *Transmitir*: poder enviar las señales entre el programa que ya previamente va a formar la ruta y el SP32 usado para el robot.
+ *Visualizar*: es el resultado que se da a través de la conexión entre el software y el prototipo, generando un mapa que pueda estar indicado en una aplicativo que pueda ser usado por el público objetivo.

## Matriz Morfológica

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/Matriz_Morfologica.png)

Figura 5: Matriz Morfológica del proyecto. Elaboración propia.

## Tabla de Valoración

![](https://github.com/ArnySalazar/FdD/blob/main/FdD2024-1/Imagenes/I_E_4/Tabla_valoracion.png)

Figura 6: Tabla de Valoración del proyecto. Elaboración propia.

## Conclusión del Concepto de Solución

El concepto de solución con flechas de color azul fue elegido principalmente por su funcionalidad adecuada en relación con la inversión realizada. Además, tiene una buena compatibilidad con las herramientas que vamos a utilizar, como el software de mapeo, el prototipo que seguirá las rutas en los puntos clave y la aplicación que utilizará el público objetivo. Para empezar, estamos optando por una fuente de energía accesible, económica y versátil, que también es utilizada por nuestro curso durante algunos de nuestros talleres de electrónica. Continuamos con el sensor elegido, el infrarrojo TCRT5000, que cumplirá la función de seguidor de línea. Dado que trabajaremos con software, también necesitaremos una placa microcontroladora como Arduino, que podremos implementar fácilmente con el código propuesto. Nuestra solución complementa equipos que puedan trabajar bien entre sí y sean ajustables para una conexión adecuada.
