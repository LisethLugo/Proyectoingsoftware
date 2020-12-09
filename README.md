# PROYECTO FINAL DE INGENIERÍA DE SOFTWARE 

Este  programa realiza el ajuste de  poligonales topográficas  cerradas y abiertas 

## LECTURA DE DATOS 
la lectura de datos se realiza desde un archivo plano con un formato pre-definido .

>El tipo de poligonal se ingresa por pantalla 

> La ruta del archivo con las mediciones de la poligonal  se digita en pantalla 

## VALIDACIONES 
El programa valida el archivo con las mediciones cumple con el formato que el programa lee 

## AJUSTES 

### Poligonal cerrada
Si la poligonal es cerrada los posibles métodos de ajuste seran: 

-Método de brujula
-Método de transito

>Se solicitara por pantalla al usuario las coordenadas de los puntos de la linea de referencia 

### Poligonal abierta 
Si la poligonal es abierta el método de ajuste sera **Crandall**

>Se solicitara por pantalla al usuario las coordenadas de los puntos de la linea de referncia de incio y fin

## SALIDA
Los resultados  de los cálculos y los ajustes  se guardan en un archivo plano en la misma ruta del archivo de entrada

## GRAFICAS 
La Poligonal se dibuja a través de uno de los siguientes métodos: 

-Un archivo  **Geojson** o **json**
-En consola a través de una librería gráfica 
-En un archivo CAD a través de  una librería externa 

[Universidad distrital](https://www.udistrital.edu.co)
