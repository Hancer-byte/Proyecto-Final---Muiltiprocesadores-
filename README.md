# - Proyecto Final Muiltiprocesadores -
## Jorge Martínez Hernández
## 1. Introducción 
Este proyecto final consta de distintas partes, las cuales integran gran parte de las actividades realizadas durante el semestre.
EL principal punto a observar durante este prouecto es analizar la rapidez y efectividad en el procesamiento de mi equipo comparado con el de un compañero y un servicio en linea. (Google Cloud), permitiendo hacer una comparativa dependiendo las especificaciones de los mismos. 

Este proceso es de suma importancia ya que van ligados a como trabajan los equipos nuevos en el mercado, sus cualidades y las mejoras que se podrian realizar a nuestros equipos.

## GOOGLE CLOUD
Es un servivio en linea que se podria decir que ofrece la mejor tecnología hoy en día, se cree que utiliza el mayor sistema de datos por fibra óptica del todo el mundo  
### Pasos para cerear cuenta 
Uno de los pasos principales es tener una cuenta de gmail y una tarjeta bancaria para poder activar la cuenta en Google Cloud, esto permitira tener un saldo gratis.
#### Paso 1
En nuestro primer paso daremos click en el boton de "PRUEBA GRATIS"

[![1.png](https://i.postimg.cc/rphGC27B/1.png)](https://postimg.cc/McQjqN65)
##### Imagen 1 Paso 1/3 para crear cuenta Google Cloud

#### Paso 2
Posteriormente se abre una nueva página donde se nos pedirá llenar un dar de cosas y marcar una casilla como se muestra en la imagen 2 de este apartado

[![2.png](https://i.postimg.cc/JnGNpdLG/2.png)](https://postimg.cc/ftQSLCkN)
##### Imagen 2 Paso 2/3 para crear cuenta Google Cloud

#### Paso 3
En esta tercera y ultima parte se solicitarán datos del creador de la cuenta asi como datos de la cuenta bancaria (solo es para corroborrar que no es un bot), posteriormente solo damos "ACEPTAR Y CONTINUAR) y habremos completado con exito la creacion de nuestro servivio en linea.

[![3.png](https://i.postimg.cc/Ss3W37SV/3.png)](https://postimg.cc/JD3DBXBB)
##### Imagen 3 Paso 3/3 para crear cuenta Google Cloud

## MÁQUINA VIRTUAL
### Pasos para cerear Maquina Virtual
La imagenes siguientes muestran los campos que utilice para la configuración de la máquina virtual con las especificaciones solicitadas, la capacidad y el sistema operativo.

[![1-1.png](https://i.postimg.cc/CKQRvhJV/1-1.png)](https://postimg.cc/DW1f0KtC)
##### Imagen 1.1 Paso 1/3 para crear Máquina Virtual

[![1-2.png](https://i.postimg.cc/1XxfQvLC/1-2.png)](https://postimg.cc/Pp4tbQfY)
##### Imagen 1.2 Paso 2/3 para crear Máquina Virtual

[![1-3.png](https://i.postimg.cc/tJh7ChbX/1-3.png)](https://postimg.cc/fSRM8SkF)
##### Imagen 1.3 Paso 3/3 para crear Máquina Virtual

## 2. Desarrollo


### Especificaciones Laptop utilizada Vs. Máquina Virtual 

[![2-1.png](https://i.postimg.cc/ZnCtwmfX/2-1.png)](https://postimg.cc/N2qz03vx)
##### Imagen 2.1 Especificaciones de Laptop usada para compración


[![2-2.png](https://i.postimg.cc/Fz8tq68z/2-2.png)](https://postimg.cc/zHCPHxJY)
##### Imagen 2.1 Especificaciones de Máquina Virtual usada para compración

### Comparación en los tiempos de ejecución 

#### Actividad 1.3 PROCESADORES MÚLTIPLES EN ACCIÓN
Para la Actividad 1.3 se solicito realizar lo siguiente:

Se ejecutó el código de muestra ("Procesadores multiples en accion") con 15 threads. 

[![a1-3.png](https://i.postimg.cc/G2Mxx8SJ/a1-3.png)](https://postimg.cc/WFkZ23Vh)
##### Imagen 2.2 Comparación de tiempos en  la Actividad 1.3

En esta ejecución se puede observar que los tiempos son completamente distitos, mostrando mayor velocidad en la máquina virtual y la asignacion de threads.

#### Actividad 1.4 ÁREA BAJO LA CURVA
Para la Actividad 1.4 se solicito realizar lo siguiente:

En esta actividad se busca encontrar el mejor tiempo usando un programa usando el concepto paralelización, previamente se busco el numero de pasos para encontrar el valor mas preciso para pi. Dándonos cuenta de que con 10*e^9 es el numero mas optimo y en un tiempo adecuado.

En mi caso el numero optimo de threads utilizados fue 900( cabe mencionar que esto se relaizo en en CMD de mi dispositivo) 
[![a1-41.png](https://i.postimg.cc/x10B07bX/a1-41.png)](https://postimg.cc/mt5mjmj4)
##### Imagen 2.3 Determinación del numero optimo de threads para esta actividad

A continuacion se mostrará la comparativa entre mi dispositivo y la máquina virtual.

[![a1-4.png](https://i.postimg.cc/hP8HRghF/a1-4.png)](https://postimg.cc/gnJM3Cv4)
##### Imagen 2.4 Comparación de tiempos en  la Actividad 1.4

Claramente en esta actividad la diferinecia de tiempo en muy distinta y en este caso el tiempo de CMD de mi lap fue mucho mas rápido, sin embargo los parametros se tomaron de la misma, talvez por eso el mejor tiempo es por ello.

#### Actividad 1.5 VELOCIDAD (RAM-DISCO DURO- CACHE)

#### RAM
Velocidad de lecto-escritura de la memoria RAM de su equipo mediante threads en comparación con la cache

[![a1-5RAM.png](https://i.postimg.cc/cC8RQsgF/a1-5RAM.png)](https://postimg.cc/zH8HNYkh)
##### Imagen 2.5 Comparación de tiempos en  la Actividad 1.5
#### DISCO DURO
Velocidad de lecto-escritura del disco duro de su equipo mediante threads en comparación con la cache

[![a1-5DD.png](https://i.postimg.cc/gJjq2yYF/a1-5DD.png)](https://postimg.cc/CByfvqBm)
##### Imagen 2.6 Comparación de tiempos en  la Actividad 1.5

#### OPERACIóN MATEMÁTICA
La operación matemática(exponencial, potencia, trigonométrica, etc.) más lenta en comparación con la suma.

[![a1-5Math.png](https://i.postimg.cc/hjY8zJjJ/a1-5Math.png)](https://postimg.cc/G8kT6mvr)
##### Imagen 2.7 Comparación de tiempos en  la Actividad 1.5

#### Actividad 2.1 ESCALA DE GRISES - ROTACIÓN (Horizontal/Vertical)

Para esta actividad se solicitó cambiar una imagen a color en escala de grises además de a)invertir con respecto a la horizontal y b) vertical de la imagen.

Las Imágenes que utilicé para esta actividad son las siguientes:

[![1.jpg](https://i.postimg.cc/65cT58Qt/1.jpg)](https://postimg.cc/mtcTm2M5)
##### Imagen 2.8 Dimensiones  425 X 302 (Imagen en formato normal)

[![f4.jpg](https://i.postimg.cc/bvX77TjJ/f4.jpg)](https://postimg.cc/Bjg7D2b9)
##### Imagen 2.9 Dimensiones  3000 X 2076 (Imagen en gran formato)


[![a2-12.png](https://i.postimg.cc/V6hpFB4m/a2-12.png)](https://postimg.cc/R6cgStjD)
##### Imagen 2.10 Comparación de tiempos en  la Actividad 2.1 con imagen normal

[![a2-11.png](https://i.postimg.cc/26ygvXQ0/a2-11.png)](https://postimg.cc/gX9MbsBh)
##### Imagen 2.10 Comparación de tiempos en  la Actividad 2.1 con imagen en gran  formato

[![1-1.png](https://i.postimg.cc/13gkfdKM/1-1.png)](https://postimg.cc/gxWS7NQ6)
##### Imagen 2.11 Resultado de la imagen convertida a escala de grises (imagen Normal)

[![2.png](https://i.postimg.cc/6qHvs5jh/2.png)](https://postimg.cc/H8yxXHCJ)
##### Imagen 2.12 Resultado de la imagen convertida a escala de grises (imagen en gran formato)

[![1-1.png](https://i.postimg.cc/05GP2BC7/1-1.png)](https://postimg.cc/fkb685pb)
##### Imagen 2.13 Resultado de la imagen convertida a escala de grises y rotada verticalmente (imagen Normal)

[![1-2.png](https://i.postimg.cc/28zmq7HM/1-2.png)](https://postimg.cc/QVnvw1ZJ)
##### Imagen 2.14 Resultado de la imagen convertida a escala de grisesy rotada verticalmente (imagen en gran formato)

[![horizontal1.png](https://i.postimg.cc/SKt3KWX0/horizontal1.png)](https://postimg.cc/SXCDTY7V)
##### Imagen 2.15 Resultado de la imagen convertida a escala de grises y rotada horizontalmente (imagen Normal)

[![horizontal2.png](https://i.postimg.cc/524RqPLd/horizontal2.png)](https://postimg.cc/LnWDm3xN)
##### Imagen 2.16 Resultado de la imagen convertida a escala de grisesy rotada horizontalmente (imagen en gran formato)

Como se pueden dar cuenta en el tiempo de ambos servicios el tamaño de la imagen es una base fundamental.

#### Actividad 2.2 Bluerring y rotación
Para la realización de esta actividad utilice las imagenes de la activdad anterior.(Imagen 2.8 y 2.9)

[![a2-21.png](https://i.postimg.cc/ZRs5mTyb/a2-21.png)](https://postimg.cc/LYfpBFTw)
##### Imagen 2.17 Comparación de tiempos en  la Actividad 2.2 con imagen normal

[![a2-22.png](https://i.postimg.cc/2yPjq2wg/a2-22.png)](https://postimg.cc/K3Dhw7C5)
##### Imagen 2.18 Comparación de tiempos en  la Actividad 2.1 con imagen en gran formato


[![gif.gif](https://i.postimg.cc/9F1SmJmf/gif.gif)](https://postimg.cc/N59bb8rh)
##### Imagen 2.19 Imagen normal con efecto blur y rotación 

[![gif1.gif](https://i.postimg.cc/63sbjP0M/gif1.gif)](https://postimg.cc/Ty9chCBb)
##### Imagen 2.19 Imagen en gran formato con efecto blur y rotación 


