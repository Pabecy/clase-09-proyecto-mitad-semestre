# clase-09-proyecto-mitad-semestre

## intsrucciones

* hacer login en GitHub.com
* entrar a este repositorio disponible en [https://github.com/aud5i022-2022-1/clase-09-proyecto-mitad-semestre](https://github.com/aud5i022-2022-1/clase-09-proyecto-mitad-semestre)
* hacer click en el botón "Fork" de este repositorio para copiarlo a tu cuenta personal.
* enviar el enlace de tu repositorio y la lista de integrantes a través de u-cursos al instructor.
* ahora puedes editar este archivo siguiendo este enlace [README.md](README.md) y haciendo click en el ícono de lápiz para editar.
* recomendación: grabar tus avances seguido, para que no pierdas tu avance, para esto, baja al final de la sección de edición, elige la opción " Commit directly to the main branch." luego haz click en el botón verde "Commit changes". repite esto cada vez que quieras grabar cambios.
* para subir imágenes, haz click en este enlace a la carpeta [imagenes/](imagenes/), luego haz click en el botón "Add files" y selecciona "Upload files". arrastra tus imágenes o añadelas con el enlace "choose your files". luego elige la opción "Commit directly to the main branch" y haz click en el botón verde "Commit changes"

## contenidos de este repositorio

* carpeta [codigo_arduino/](codigo_arduino/): carpeta para tener el codigo de tu proyecto
  * archivo [odigo_arduino/codigo_arduino.ino](codigo_arduino/codigo_arduino.ino) : debe incluir encabezado y comentarios describiendo tu proyecto
* carpeta [imagenes/](imagenes/): sube aquí las imágenes para tu proyecto.
  * archivo [/imagenes/00-ejemplo.jpg](/imagenes/00-ejemplo.jpg) como ejemplo.
* archivo [README.md](README.md)]: este mismo archivo, aquí escribe tus apuntes durante el proyecto.
* archivo [README.pdf](README.pdf): este archivo pero convertido a PDF, puedes borrarlo.

## ejemplos útiles

cada párrafo es una línea continua de texto. los puntos "." son para punto seguido.
esta línea está escrita en la siguiente línea en el archivo, pero se ve seguida a la anterior.

para hacer un nuevo párrafo, hay que dejar una línea en blanco entremedio.

* las
* listas
* son
* así
  * las sub-listas
  * son así
  * con dos espacios de indentación

los enlaces se hacen con corchetes y después paréntesis. el texto dentro de corchetes es lo que se ve en el enlace, y el texto dentro de paréntesis es dónde va ese enlace. les pido que sea el mismo texto. aquí ejemplos de enlaces a web y a otros archivos dentro de este repositorio.

* [https://www.wikipedia.org/](https://www.wikipedia.org/)
* [https://www.arduino.cc/](https://www.arduino.cc/)
* [imagenes/00-ejemplo.jpg](imagenes/00-ejemplo.jpg)
* [codigo_arduino/codigo_arduino.ino](codigo_arduino/codigo_arduino.ino)

para incluir imágenes que sean visibles en este documento, es igual que un enlace a una imagen, pero con un signo de exclamación antes de los corchetes "!", así:

![texto descripción de la foto](imagenes/00-ejemplo.jpg)

## borrador de muestra

a continuación les dejo un breve borrador con ejemplos, que si completan, tendrán todos los puntos de la pauta, suerte!


# Acerca del Proyecto
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

Tipeo y modificación del codigo ejemplo hecho por [montoyamoraga](https://github.com/montoyamoraga) [ej_01_arduino_envia_pulsador_potenciometro](https://github.com/montoyamoraga/aud5i022-2022-1/blob/main/clases/clase-08/ej_01_arduino_envia_pulsador_potenciometro/ej_01_arduino_envia_pulsador_potenciometro.ino) </br>
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

el código está hecho para Arduino Uno, y está incluido en este repositorio aquí: [codigo_arduino/codigo_arduino.ino](codigo_arduino/codigo_arduino.ino).

este código está basado en los ejemplos de Arduino blabla y en los ejemplos de esta clase en los enlaces [bla](blabla) y [bla](blabla).

primero creamos las variables blabla para almacenar valores para blabla. la variabla bla es análoga en el rango blabla y la variable blabla es digital y tiene valores posibles 0 y 1.

primero en setup() hacemos que los pines X e Y sean entradas digitales, el pin Z sea salida digital, y abrimos la comunicación serial.

luego en loop() leemos las entradas y usamos la salida Z para lograr prender una luz LED.

## Conclusiones

En este proyecto tuvimos los siguientes aprendizajes: 

* crear un repositorio y añadir ediciones de los integrantes del grupo
* realizar una comunicacion serial entre arduino y p5
* construir un circuito con los componentes señalados en la lista de materiales

lo más difícil de este proyecto fue poder coordinar la comunicación entre arduino y p5 para proyectar los datos, además de añadir los recursos html y librerias.

al momento de cargar la pagina para proyectar los datos cometimos el error de no tener en el repositorio las librerias y el archivo html para visualizar los datos en la pestaña.

los avances de hoy nos permitirán enviar datos desde arduino hacia p5 para utilizarlos como parametros gráficos y poder dibujar en el navegador asi seguir desarrollando nuestro proyecto.
