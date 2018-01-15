# The Gender Bender


Probabilistic drum trigger generator.

![the-gender-bender](https://user-images.githubusercontent.com/6823868/29998083-3386c7a6-9022-11e7-9b96-6b8f59b2f1cc.jpg)

- [Mouser project](https://www.mouser.es/ProjectManager/ProjectDetail.aspx?State=EDIT&ProjectGUID=648036c1-8d6a-4717-aa2b-a728f60b2be2)

Basado en Mutable Instruments GRIDS. 		 	 	 				
The Gender Bender mezcla 9 patrones distintos por track para crear ritmos probabilísticos con distintas densidades, que son enviados simultáneamente via trigger, midi y USB midi.

Generador de triggers probabilístico.
El nombre hace referencia a la posibilidad de mezclar géneros/ estilos dentro de un mismo patrón. 
Dispone de siete tracks con salida de trigger independiente, clock out, clock in, reset y dos cv in asignables internamente via software. Midi in y out, lector de tarjetas sd para poder guardar snapshots y estilos. 

Incorpora el algoritmo de permutación de Nicolas Collins:
https://composerprogrammer.com/research/acmethodsforbbsci.pdf

Necesita un clock, midi clock o usb clock para iniciar las secuencias.

Componentes:
Teensy 3.2
5 encoders con pulsador
Joystick Ps2 sin retorno
Pantalla Oled 1.3”
Midi in & out
Usb
MicroSD

Banana & minijack compatible

28HP

We recommend [TY TOOLS](http://neodd.com/tytools) for upload the firmware

