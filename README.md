# -ProtoServo-..-
Instrumento de Evaluación Unidad III

### Integrantes
- Quintana Romero Gael
- Ramirez Ramirez Lizeth
  
### Grupo
GDS0541

## Nombre del personaje
ProtoServo

## Materiales utilizados
| Nombre del componente | Descripción | Cantidad | Precio total |
|-|-|-|-|
|ESP32|El ESP32 es un microcontrolador de bajo costo y bajo consumo de energía que se utiliza comúnmente en proyectos de Internet de las cosas (IoT) y desarrollo de hardware.|2|$280.00|
|Cables Dupont|Los cables Dupont son un tipo de cable utilizado comúnmente en electrónica y robótica para conectar componentes y dispositivos. Estos cables suelen tener conectores de tipo macho y hembra que se acoplan fácilmente, lo que facilita la conexión y desconexión de componentes en prototipos y proyectos.|Muchos|$100.00|
|Tira leds|Una tira de LEDs es una cinta flexible con diodos emisores de luz, ideal para iluminación decorativa, funcional y personalizada.|99 leds|$100.00|
|Servomotor |Es un tipo de motor eléctrico que se utiliza para controlar con precisión la posición, la velocidad y la aceleración de un sistema mecánico.  | 5 | $250|
|Protoboard |Es una herramienta simple que se usa en proyectos de robótica que permite conectar fácilmente componentes electrónicos entre sí, sin necesidad de realizar una soldadura. | 3 | $105 |
| Buzzer | Un zumbador (en inglés buzzer) es un transductor electroacústico que produce un sonido o zumbido continuo o intermitente de un mismo tono (generalmente agudo).| 2 | $20.0 |
| Sendor de movimiento | Un sensor de presencia o sensor de movimiento es un dispositivo electrónico que pone en funcionamiento un sistema (encendido o apagado) cuando detecta movimiento en el área o ambiente en el que está instalado. | 1 | $50.0 |
| Sensor de Temperatura  | Un sensor de temperatura mide cambios térmicos, convirtiéndolos en señales eléctricas, para monitorear y controlar procesos en diversos sistemas.  | 1 | $30 |
| Botones | Los botones son interruptores simples utilizados para activar o desactivar circuitos, permitiendo control manual en dispositivos electrónicos o mecánicos.| 3 | $15 |
| Palitos de madera | Los palitos de madera los usamos para hacer las estructuras de los cuerpor de los reyes magos | Muchos | $30.0 |
| Tela Fieltro | El fieltro es una tela flexible y suave, ideal para forrar figuras de cartón como el ciervo, proporcionando acabado elegante. | 1 m  | $30.0 | 
| Escarcha | La escarcha es un material decorativo brillante que oculta cables, ofreciendo un acabado estético en proyectos creativos o festivos. | 1 m | $20.0 | 
| Cartón | El cartón es un material rígido y liviano, ideal para construir la estructura del ciervo por su facilidad de manipulación. | 1.5 m^2 | $0 |
| cartulina (1), esferas(15), pompones(12), listón(1), escarcha(1), estrella(1) | Un arbolito de Navidad puede fabricarse con materiales reciclados como cartón o madera, diseñado para sostener luces LED decorativas | Estanbre,  | $30.0 | 
| Papel lustre | El papel lustre es un material brillante y colorido, ideal para forrar regalos, decoraciones artesanales y proyectos escolares creativos. | 3 pliegos | $12.0 |
| kola loka, resistol liquido, resistol de barra, silicon de pistola, aguja y cobre | Los usamos para pegar/unir los  materiales | Varios | $100 | 
| Papel lustre dorado | Forrar la base de madera con la que sostienen los prototipos | .75 | $12.0 |
| Madera | madera que servirá para tener una base donde se sontendrán los componentes | 50*40 | $80 |


## Software utlizado 
| Nombre de Software | Versión | Tipo |
|-|-|-|
| Arduino | Reciente | Editor |
|Thonny| Reciente | Editor |
| Node red | Reciente | Conexión WiFi |

## Dibujo del prototipo a desarrollar 
- Coloca el dibujo a mano de la propuesta de prototipo a realizar.
![Dibujo resyes magos](https://github.com/dalisoto/Personaje/blob/main/Dibujo%20reyes%20magos.jpg?raw=true)
![Prototipo de proyecto](https://github.com/dalisoto/Personaje/assets/139840896/694815de-58d4-4101-8534-eb34bfeb3dda)

## Imagenes del proyecto final 
![Reyes_magos](https://github.com/dalisoto/Personaje/blob/main/Reyes_magos.jpg?raw=true)
![componentes](https://github.com/dalisoto/Personaje/blob/main/componentes.jpg?raw=true)




## Comunicación 
Describir el protocolo de comunicación que tendrá el dispositivo (Como interactua el usuario con el prototipo):
El proyecto tendrá un sensor de movimiento que al detectar movimiento este se actuará, activando una alarma buzzer que sonará una pequeña canción navideña, también moviendo el servo lo que hará que se mueva a mano de un personaje, esto hará que abrá una cajita en secuencia. Tendrá muchos leds los cuales se prenderán y apagaran. 

## Arquitectura 
Coloca una imgane donde coloques los sensores, los actuadores, el microcontrolador, base de datos (sqlite o mysql). 

## Código python
Para descargar el código de micropython descargue la carpeta comprimida en zip, "Reyes Magos.zip"

Imagenes del código de la placa 1
![img1p1](https://github.com/dalisoto/Personaje/blob/main/img1p2.jpg?raw=true)
![img1p1](https://github.com/dalisoto/Personaje/blob/main/img2p2.jpg?raw=true)
![img1p1](https://github.com/dalisoto/Personaje/blob/main/img3p2.jpg?raw=true)

Imagenes del código de la placa 2
![img1p2](https://github.com/dalisoto/Personaje/blob/main/img1p1.jpg?raw=true)
![img2p2](https://github.com/dalisoto/Personaje/blob/main/img2p1.jpg?raw=true)
![img3p2](https://github.com/dalisoto/Personaje/blob/main/img3p1.jpg?raw=true)
## Enlace a drive para ver el video del funcionamiento del proyecto
No se pudo subir a git debido al tamaño del video.
https://drive.google.com/file/d/1xSZzrpQzt4ZiSIcFHwVN-keGWmTJNXBT/view?usp=sharing

## Imagen de flujo de Node Red
![NodeRed](https://github.com/dalisoto/Personaje/blob/main/NodeRedimg.png?raw=true)
Para ver el código vaya al archivo "Reyes Magos (2).json "
