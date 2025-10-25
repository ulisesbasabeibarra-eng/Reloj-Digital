# Reloj Digital

[![Sin-titulo.png](https://i.postimg.cc/15RT8fYV/Sin-titulo.png)](https://postimg.cc/QVPSPxDj)
## Authors

- [@Ulises Basabe](https://github.com/ulisesbasabeibarra-eng)
- [@Facundo Dominguez](https://github.com/facundodominguez1)
- [@Ramiro Trejo](https://github.com/RamiiTrejo)
- [@Rodrigo Benitez](https://github.com/rodrigobenitez17)
- [@Maximo Paez]()



## DESCRIPCIÓN

Un reloj digital sin utilizar un microcontrolador o web para establecer el tiempo. Utilizando solamente electronica discreta como el lm555, cuyo componente debe de estar en modo astable para general pulsos electronicos que estableceran gracias a los integrados 74LS47 y 74LS90 que los displays de 7 segmentos marquen una hora determinada. Un total de 6 displays para marcar los segundos, minutos y horas.
## Informe

[Reloj Digital](https://docs.google.com/document/d/12YXhhFJf7GPLBze2eZ5sYaiuNMOwRFxj9prBwNTrKLU/edit?pli=1&tab=t.0#heading=h.a97jr9uy2bgi)
. Este enlace lleva a un documento de google en el que se encuentra más informacion sobre este projecto junto con imagenes explicativas y vistas previas.
## Funcionamiento
El funcionamiento de este reloj se basa en el circuito integrado LM555, configurado como oscilador astable, que genera una serie de pulsos eléctricos aproximadamente de 1 Hz por  segundo. Estos pulsos son enviados al 74LS90, que actúa como contador decimal y convierte los pulsos en una salida binaria. Después, esta señal binaria pasa al 74LS47, que la decodifica y la transforma en señales para encender los segmentos correspondientes del display de 7 segmentos, mostrando así los números de forma digital. 

El potenciómetro permite ajustar la frecuencia del LM555, aumentando o disminuyendo la velocidad con que se generan los pulsos que llegan al 74LS90 (Es decir, la velocidad con que se cambian los números en el display).

El LED conectado al circuito también parpadea al ritmo de los pulsos, sirviendo como indicador visual de la frecuencia del contador. En este caso, se ha optado por utilizar una resistencia fija de 3,9 kΩ, de modo que el temporizador genere un pulso cada segundo aproximadamente, obteniendo así una base de tiempo estable para el reloj.

Los botones conectados uno a los displays de los segundos y otro conectado a los minutos. Su funcion es que una vez al ser pulsados, este pulso contara tambien como si fuera un pulso del LM555, es decir, una vez que se pulsa el numero del display pasara al siguiente respectivamente, funcionando como un reloj manual y esta para setiar el reloj a la hora exacta al de la hora actual.

(La alimentacion vendria mediante un cable conectado a un transformador el cual iria conectado a un toma corriente)
## Modelo 3D
En este projecto se utilizo Autodesk, programa el cual estoy mas acostumbrado a utilizar ademas de ser muy utilizadas a la hora de hacer diseños 3D, gracias a que este ofrece una amplia gama de software como AutoCAD, Fusion 360, Inventor y 3ds Max, utilizados en sectores como la ingeniería, la arquitectura, el entretenimiento y el diseño de productos.

El modelo 3D esta compuesto por dos partes principales: El piso y El cuerpo. 

El piso o la inferior, es un rectangulo compuesto por cuatro agujeros, uno en cada esquina, por donde se ingresarian los tornillos los cuales unirian las dos piezas. Además de tener otros cuatro agujeros más con un desnivel para ubicar la placa y mantenerla en el lugar y dejando un muy pequeño espacio entre los dos para las patas o sobresalientes de los componentes de la misma.

[![piso.png](https://i.postimg.cc/j2MdpcXf/piso.png)](https://postimg.cc/0KJsmph5)

El Cuepo tambien consta con los mismos huecos para tener mas rigidez en la uniones de estas tres partes (placa, piso, cuerpo).Tambien consta con un agujero en un costado para permitir la salida del cable de alimentación.

[![cuerpo.png](https://i.postimg.cc/26PPVZSJ/cuerpo.png)](https://postimg.cc/34FLqWpC)

Además tiene 6 agujeros rectangulares para permitir la vista de los displays de 7 segmento, con una pequeña separacion entre cada uno y otra entre cada grupo de dos, para formar los segundos, minutos y horas, cuyos grupos abajo les sigue sus respectivo unidad marcada como un corte en el cuerpo. Tambien, más abajo tiene dos agueros donde irian ubicados los botones. Los displays y los botones deberan ir adheridos con silicona para que mantengan su lugar.

[![cuerpo.png](https://i.postimg.cc/j2SJnL3h/cuerpo.png)](https://postimg.cc/LYGsr6pq)

En la carpeta carcasa, se encontran los archivos de estas pieza 3D en diferentes tipos de archivos desde .stl, donde se podran mandar a imprimir directamente, .fusion, asta .step. 
## Desmontaje de la carcasa
[![desamblage.png](https://i.postimg.cc/nc8M49Qy/desamblage.png)](https://a360.co/3W90Zk7)
