# Introducción_a_Python_Archivos

## Ejercicios introductorios de Python en Raspberry PI 4 MODEL B


Como parte de las actividades del taller de IoT, se continua trabajando con la programación en lenguaje Python, para controlar una tarjeta Raspberry pi 4, facilitada por el taller para realizar las prácticas en el curso.

## Material necesario

- ![Rasberry PI 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)
- Sensor ultrasónico ![HC-SR04](https://datasheet4u.com/datasheet-pdf/ETC1/HC-SR04/pdf.php?id=1380138)

## Software necesario

Python 3

## Instrucciones

Para está práctica se deben de cumplir los siguientes puntos:

1. Leer la información colocada en la plataforma de Codigo IoT, referente a la programación básica de Python para el manejo de archivos. [Manejo de Archivos](https://edu.codigoiot.com/mod/lesson/view.php?id=2024&pageid=2569&startlastseen=no)
2.  Armar el circuito mostrado en la figura 1.

  **Figura 1.** *Conexión del sensor HC-SR04 a Raspberry PI 4*.
  
  ![Circuito](https://github.com/OmarAbundis/Introduccion_a_Python_Archivos/blob/main/Imagenes/Diagrama_UltraSonico.PNG)
  
3. Analizar el programa de control y escribirlo en un entorno de programación. [Programa](https://github.com/OmarAbundis/Introduccion_a_Python_Archivos/blob/main/Programas/Archivos_ultraSonico.py).

4. Observar su funcionamiento.

## Resultados

El circuito y el programa funcionaron satisfactoriamente, una vez que se modificó el programa de referencia de la plataforma de Código de IoT y teniendo cuidado del identado que exige el lenguaje de programación Python.

En la figura 2, se muestra corriendo el programa en **Thonny**, que viene por defecto en la Raspberry. En la parte final se muestran los resultados de las mediciones registradas por el sensor HC-SR04.

**Figura 3.** *Código funcionando.*

![Thonny](https://github.com/OmarAbundis/Introduccion_a_Python_Archivos/blob/main/Imagenes/Thonny_Ultrasonico.PNG)

Para corroborar en la figura 4, se muestra evidencia del programa ejecutado desde la consola de la Raspberry.

**Figura 4.** *Ejecución desde Consola de Raspberry.*

![Consola](https://github.com/OmarAbundis/Introduccion_a_Python_Archivos/blob/main/Imagenes/UltraSonico_Consola.PNG)

Y para finalizar en la figura 5, se muestra la evidencia del archivo que se genera automáticamente en .TXT, registrando las mediciones obtenidas.

**Figura 5.** *Archivo de Registro de Medidas.*

![Archivo](https://github.com/OmarAbundis/Introduccion_a_Python_Archivos/blob/main/Imagenes/Archivo_UltraSonico.PNG)

[Vídeo de funcionamiento](https://youtu.be/ez1xVBdXycA)

## Créditos

Dra. Paloma Vilchis, desarrolladora del contenido de la presente práctica.
Prof. Hugo Vargas.
  
  

