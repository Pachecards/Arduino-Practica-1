Por Iago Sieiro Junto a: Miguel Gomez y Efrén Alonso

# Práctica 2

Ejercicio 2: 3 Leds consecutivas

En el siguiente ejercicio seguimos con nuestras pruebas con LED, en esta ocasión, procedemos a incluir 2 luces LED más y a coordinarlas
entre si.

El código resultó no ser mucho más complejo que el del primer ejercicio, así que volvimos a usar Tinkerkad para diseñar el nuevo sistema con una configuración muy básica, pero funcional.

Una vez con el diseño en nuestras manos, lo aplicamos a nivel físico, usando 3 Leds, 3 cables Macho-Hembra, 1 Arudino-UNO y 1 cable de electricidad.

La instalación estaba hecha, pero nos faltaba parte del código para que funcionara, buscando en internet nos encontramos una página que nos permitió que funcionaran en la secuencia deseada, se puede encontrar como ArduinoUnoEx2Faster.ino.

Una vez que acabamos la primera parte del código, lo modificamos un poco para que las Leds se encendieran parpadeando en intervalos temporales pequeños, no nos costó mucho más de unos minutos.

Por último, conseguimos que los Leds parpadearn de forma irregular, haciendo que se encendiera uno solo al principio y después los otros dos que faltaban. El código usado es el siguiente.

# Práctica 3

Ejercicio 3: Aplicando el Buzzer

En esta próxima práctica, nos tocó aplicar sonido a nuestro sistema usando un Buzzer y un par de cables nuevos que aplicamos a nuestro ya creado sistema. Básicamente, el objetivo ahora era encender el Buzzer en el momento exacto en el que la última Led se encendiera.

Nada del otro mundo, esta vez usamos Codebender para realizar la prueba de código, aunque con algunas dificultades, ya que no entendiamos muy bien el objetivo del ejercicio al principio, y para cuando lo dedugimos, nos llevo un rato más el llevarlo a cabo, pero siguiendo la pista del ejercicio pudimos con ello.

Llevar el sistema con éxito una vez con el código no nos llevó nada, y todo salió a pedir de boca.

# Práctica 4

Ejercicio 4: Moviendo un Servo

Ahora nos tocaba mover un Servo consistente de una pequeña helice usando Arduino, esto se consiguió usando 3 cables Macho-Macho, el propio Servo y su cable de conexiones y la placa Arduino UNO que ya poseíamos.

Debido a nuestro poco conocimiento del funcionamiento de los servos, las conexiones de este ejercicio se nos escaparon bastante al principio, pero una vez entendimos como funcionaban los cables del servo con sus respectivos colores, pasamos a la acción.

En lo que al código se refiere, tuvimos un lío bastante importante con respecto a los ángulos y las velocidades del servo, no entendiendo como conseguir que fuera a la velocidad que desearamos y que se parase en un punto concreto, pero tras unos cuantos esfuerzos colaborativos por parte del grupo, pasamos la dificultad. Volvimos a usar Tinkerkad para el prototipo.

Una vez conseguido, pasarlo a la versión física conlleva a cambiar de servo, ya que el que tenemos es bastante peculiar, pero la base es la misma así que conseguimos llevarlo a cabo.

# Práctica 5

Ejercicio 5: Servo e Interruptor

Añadimos en esta práctica un pequeño interruptor que nos sirve para controlar cuando se activa el mecanismo para rotar al servo.

En esta ocasión nos enredamos durante mucho tiempo intentando hacer por nuestra cuenta un código y un prototipo de la página Tinkerkad. No sabíamos muy bien como funcionaban las conexiones del interruptor así que todos nuestros esfuerzos fueron en vano, por suerte nuestro cerebro tuvo la brillante idea de acudir a los ejemplos ofrecidos en la página que usamos para informarnos y acabamos así de conseguir un prototipo adecuado.

El prototipo fue pasado a versión física y tras un par de errores y correcciones acabamos la práctica.

# Práctica 6

Ejercicio 6: Sensor de Proximidad

Para esta última prueba sobre Arduino cogemos un sensor de proximidad y una Led que nos indique cuando hay un objeto cerca.

Trabajar sobre un sensor de proximidad puede intimidar un poco, pero realmente el código usado se asemeja bastante a los anteriores, encontramos ciertas dificultades al establecer el rango al que nuestro dispositivo detectará objetos y confundimos un poco los valores necesarios para hacer que trabaje, pero fugazmente descubrimos nuestras equivocaciones a base de prueba y error y obtuvimos el código que nos valía para la práctica.

Volvimos a usar Tinkerkad para nuestro proyecto y ,al pasarlo a físico, funciona sin mayor problema.
