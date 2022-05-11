# clase-09-proyecto-mitad-semestre

## Acerca del Proyecto
El Proyecto se trata de elaborar un "telesketch" o "pizarra magica" a través de los contenidos vistos en clases.
la elaboración conecta la placa arduino con su respectivo codigo y a través de comunicación serial se conecta al navegador por p5.serialcontrol permitiendo utilizar el navegador como "pizarra"

## Que es un Telesketch
Telesketch o Sketch es un juguete inventado en 1959 por el francés André Cassagnes (23 de septiembre de 1926 – 16 de enero de 2013) y que fue comercializado por primera vez en Estados Unidos con el nombre de Etch-A-Sketch por Ohio Art Company en 1960 y en España por Borrás. Cassagnes, quien lo llamó originalmente "la Pantalla Mágica", falleció en enero de 2013.

El Telesketch es una versión muy simplificada de un plotter. La superficie interior de la pantalla está recubierta de polvo de aluminio y partículas de estireno en la que una punta metálica móvil traza surcos, dibujando una línea negra en la pantalla gris. La punta metálica se controla por dos mandos giratorios: uno la mueve verticalmente y otro horizontalmente. Para borrar el dibujo sólo hay que ponerlo boca abajo y agitarlo para que el aluminio y el estireno vuelvan a recubrir la superficie.

## Integrantes
<p>
- Camila Flores del Rio </br>
- Paz Castro Yevenes </br>
- Diego Barahona Barahona </br>
</p>

## Comenzando el Proyecto
Debido a la complejidad del proyecto dividimos su desarrollo en las siguientes etapas 

#### I Arduino
   * Etapa_1: Evaluación y prueba del codigo [ej_01_arduino_envia_pulsador_potenciometro](https://github.com/montoyamoraga/aud5i022-2022-1/blob/main/clases/clase-08/ej_01_arduino_envia_pulsador_potenciometro/ej_01_arduino_envia_pulsador_potenciometro.ino) por [montoyamoraga](https://github.com/montoyamoraga) modificandolo en software arduino para lectura de 2 potenciometros y 3 pulsadores.</br>
   * Etapa_2: Construcción del circuito con los componentes electronicos teniendo en cuenta la facilidad de uso y lectura del circuito (orden de componentes y colores de cables)</br>
   * Etapa_3: Prueba del circuito y el codigo por medio del monitor serial de arduino. </br>
   * Etapa_4: Conexión de circuito con el codigo arduino y p5, monitor serial web.
      * Testear lectura de datos en navegador con [ejemplo p5js](https://github.com/aud5i022-2022-1/clase-08-ejemplo-p5js-texto/blob/main/sketch.js) en navegador 
#### II P5js
   * Edición de codigo [ejemplo p5js](https://github.com/aud5i022-2022-1/clase-08-ejemplo-p5js-texto/blob/main/sketch.js) para utilizar el navegador como pantalla.
#### III Processing
   * Crear versión de ejemplo p5js para processing 
   * Desarrollar archivo para utilizarlo en el pc *consultar al Instructor*
#### IV Prototipo 1
   * Establecer piezas y circuito fijo
   * Modelado 3d de Carcasa
   * Montaje

## Avances clase 10/05/2022

Tipeo y modificación del codigo [ej_01_arduino_envia_pulsador_potenciometro](https://github.com/montoyamoraga/aud5i022-2022-1/blob/main/clases/clase-08/ej_01_arduino_envia_pulsador_potenciometro/ej_01_arduino_envia_pulsador_potenciometro.ino) hecho por [montoyamoraga](https://github.com/montoyamoraga) </br>
basado en Examples/04. Comunication/Virtualcolormixer.
<p>
Construcción del circuito de prueba, el cual incluye los siguientes materiales </br>
</p>

## Lista de Materiales

Los materiales son:

* Arduino Uno
* 2 protoboard 
* 17 cables
* 2 potenciómetros
* 3 botones
* 3 resistencias 10K

## Armado de Circuito

Primero debido al poco espacio de la protoboard unimos 2 protoboards quitando un carril de GND y 5V.

![Unión de Protoboards](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img00.jpeg)

Despues de esto comenzamos a conectar un cable rojo al 5V y un cable negro al GND de nuestro Arduino Uno

![Conexión Tierra/5V al Arduino](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img00_.jpeg)

Los otros extremos de los cables los conectamos de la siguiente manera rojo(5V) al negativo de la Protoboard y el negro(GND) al positivo.

![Conexión Tierra/5V a la Protoboard](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img01.jpeg)

En el lado derecho de nuestra Protoboard agregamos 3 pulsadores 

![Agrega Pulsadores](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img02.jpeg)

Agregamos a cada pulsador en su pata izquierda su respectivo resistor conectado a la linea de alimentacion negativa (5V)

![Agrega Resistores Pulsadores](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img03.jpeg)

Para agregar la conexión tierra a cada Pulsador conectamos un cable verde en cada uno a la pata derecha y a el carril positivo (GND)

![Agrega Tierra Pulsadores](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img04.jpeg)

Para la lectura de los pulsadores agregamos en cada pata izquierda un cable azul 

![Agrega Cables lectura](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img05.jpeg)

Los otros extremos de los cables azules de lectura los conectamos en los pines digitales 6,7,8 y con esto terminamos con los pulsadores.

![Conecta pines6_7_8](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img06.jpeg)

Ahora fijamos los 2 potenciometros en el carril izquierdo de la Protoboard

![Agrega Potenciometros](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img08.jpeg)

para conectar los potenciometros los conectamos de la siguiente manera mirandolo desde atras, Cable naranjo para alimentación (5V), cable blanco para lectura Analogica y Cable cafe para tierra (GND).
![Conecta Potenciometros](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img09.jpeg)

Conectamos el cable naranjo a la alimentación negativa (5v) del carril central y el cable café a el carril positivo Tierra (GND). Repetimos el paso anterior y este con el otro potenciometro
![Alimentacion Potenciometros](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img10.jpeg)

Para la lectura analogica de los potenciometros conectamos los extremos de los cables blancos a los pines A0 y A5 del Arduino Uno

![Lectura analogicaPotenciometros](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/img11.jpeg)

Finalmente nuestro circuito se verá asi

![Circuito Final](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/imag3.jpeg)

Aqui en otros Angulos
![Vista lateral](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/imag4.jpeg)
![Vista Aerea](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/imag2.jpeg)

Imagenes del Proceso
![Proceso 1](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/imag1.jpeg)

## Código para microcontrolador Arduino

El código está hecho para Arduino Uno, y está incluido en este repositorio aquí: [codigo_arduino/codigo_arduino_enviadatos.ino](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/codigo_arduino/codigo_arduino_enviadatos.ino).

Este código está basado en los ejemplos de Arduino hechos por el instructor [montoyamoraga](https://github.com/montoyamoraga) y en los ejemplos de esta clase 8 en los enlaces [ej_01_arduino_envia_pulsador_potenciometro](https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-08/ej_01_arduino_envia_pulsador_potenciometro) y [clase-08-ejemplo-p5js-texto](https://github.com/aud5i022-2022-1/clase-08-ejemplo-p5js-texto/blob/main/sketch.js).

Primero creamos las variables *cons int pinpulsador1, cons int pinpulsador2, cons int pinpulsador3* para que arduino sepa donde leer los pulsadores indicando los pines de lectura digital que en este caso designamos 6,7,8. Por otro lado creamos *cons int pinpotenciometro1 y cons int pinpotenciometro2* para designar los pines de lectura analogica en nuestro Arduino Uno que en este caso son A0 y A5.

Siguiente para almacenar valores, creamos variables tipo enteras de nombres *int valorpulsador1, int valorpulsador2, int valorpulsador3* estas variables son digitales y tiene valores posibles 0 y 1. Y en el caso de los Potenciometros creamos *int valorpotenciometro1 y int valorpotenciometro2* estas variables son analogicas y se mueven en un rango de 0 a 1023.

Comenzando en setup() iniciamos la comunicación serial con 9600 y definimos los pines Pulsadores 1,2,3 como entradas digitales.

Luego en loop() leemos las entradas digitales y analogas, y finalizamos imprimiendo los valores en el orden de: </br>
valorpulsador1, valorpulsador2, valorpulsador3/ valorPotenciometro1 , valorPotenciometro2

Posterior a esta prueba logrando conectar el circuito con el codigo utilizamos p5.serialcontrol para conectar la lectura de datos a el navegador a través del codigo [sketch.js](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/codigo_arduino/sketch.js) el cual solo se modifico el nombre de puerto a "COM3" puerto donde estaba nuestro Arduino Uno.

En esta prueba fallamos y el Profesor nos explico que para hacer la conexión se agrega el archivo [Index.html](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/codigo_arduino/index.html) que es el elemento que permite a arduino y p5 ejecutar el código en la web, ademas de agregar las [librerias](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/tree/main/codigo_arduino/Librerias) de p5js a la carpeta en github. 

Recien ahí logramos hacer la lectura de datos.

Aqui esta el [video](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/Test1/Prueba_1.mp4) de nuestro primer test disponible para su descarga, tambien compartimos una foto pantalla de la lectura de datos en el navegador.

![Lectura de Datos](https://github.com/Pabecy/clase-09-proyecto-mitad-semestre/blob/main/imagenes/imag_data.png)

## Conclusiones

En esta etapa: **I Arduino** de proyecto tuvimos los siguientes aprendizajes: 

* Crear un repositorio en github para añadir el proceso como bitacora y los integrantes del grupo.
* Construir un circuito con los componentes señalados en la lista de materiales.
* Realizar una comunicación serial entre arduino y p5.serialcontrol.


##### Dificultades

Lo más difícil de la primera etapa del proyecto fue poder coordinar la comunicación entre arduino y p5 para proyectar los datos, además de añadir los recursos html y librerias, al momento de cargar la pagina para proyectar los datos cometimos el error de no tener en el repositorio las librerias y el archivo index.html para visualizar los datos en la pestaña.

Los avances de hoy nos permitirán enviar datos desde arduino hacia p5 para utilizarlos como parametros gráficos y poder dibujar en el navegador, de esta forma seguir desarrollando la siguiente etapa en nuestro proyecto.
