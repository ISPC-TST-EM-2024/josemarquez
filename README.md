![alt text](/josemarquez/rcs/Visual/Banner-ispc.png)

# MATERIA: ELECTRONICA MICROCONTROLADA
## Profesor: Gonzalo Vera
___
### Alumno: Jose Marquez
___

### **Trabajo practico N°1: Simulacion eléctrica.**


#### ***Objetivos***  


• Comprender los fundamentos eléctricos básicos en circuitos.
• Aprender a diseñar y simular circuitos eléctricos.
• Familiarizarse con los componentes eléctricos y electrónicos, y su función en
los circuitos.
• Analizar y comprender los resultados de las simulaciones.
Fundamentos eléctricos – Semana 1
1. Diseñar y simular un circuito eléctrico básico con una fuente de tensión,
resistencia y un LED.
2. Diseñar y simular un circuito eléctrico básico con conexión serie, paralelo y
mixta. Analizar corrientes y tensiones.
3. Diseñar y simular un circuito eléctrico con un capacitor y analizar el
comportamiento de la corriente y la tensión en el capacitor.
4. Diseñar y simular un circuito eléctrico con un inductor y analizar el
comportamiento de la corriente y la tensión en el inductor.
5. Diseñar y simular un circuito eléctrico con un transformador y analizar el
comportamiento de la corriente y la tensión en el transformador.
6. Diseñar y simular un circuito eléctrico complejo que involucre fuentes de
tensión y corriente, resistencias, capacitores e inductores, y analizar su
comportamiento.  

### Trabajo Práctico N°2: Simulación Electrónica  

#### Objetivos  

  
• Comprender los fundamentos eléctricos y electrónicos básicos en circuitos.
• Aprender a diseñar y simular circuitos eléctricos y electrónicos.
• Familiarizarse con los componentes eléctricos y electrónicos, y su función en los circuitos.
• Analizar y comprender los resultados de las simulaciones.
Fundamentos electrónicos – Semana2
1. Diseñar y simular un circuito con un diodo rectificador y analizar su comportamiento.
2. Diseñar y simular un circuito con un transistor bipolar como amplificador y analizar su comportamiento.
3. Diseñar y simular un circuito con un transistor bipolar como interruptor y analizar su comportamiento.
4. Diseñar y simular un circuito con un amplificador operacional como sumador inversor y analizar su comportamiento.
5. Diseñar y simular un circuito con un amplificador operacional como comparador y analizar su comportamiento.

### Trabajo Práctico N°3: Circuito Lógicos Combinacionales:
"Introducción al diseño de circuitos lógicos combinacionales y al álgebra de Boole"  
  
#### Objetivos:  

1. Comprender los fundamentos de la lógica combinacional y su aplicación en el diseño de circuitos lógicos.
2. Aprender a utilizar el álgebra de Boole para la simplificación de expresiones lógicas y la implementación de circuitos combinacionales.
3. Desarrollar habilidades para la identificación y análisis de problemas en circuitos lógicos combinacionales, y para la aplicación de soluciones efectivas utilizando las herramientas y técnicas adecuadas.
Desarrollo del Trabajo Práctico:
1. Implementación de una función lógica: Diseñar un circuito combinacional que implemente la función lógica F(A, B, C) = A'B + AC.
2. Simplificación de una expresión lógica: Simplificar la expresión lógica F(A, B, C, D) = ABC + AB'D + ACD' utilizando álgebra de Boole y mapas de Karnaugh.
3. Multiplexor: Diseñar un circuito combinacional que implemente un multiplexor 4:1 utilizando compuertas lógicas.
4. Comparador de números de 2 bits: Diseñar un circuito combinacional que compare dos números de 2 bits A y B, y produzca una salida de 1 si A > B, 0 si A = B, y -1 si A < B.
5. Codificador: Diseñar un circuito combinacional que implemente un codificador 4:2 utilizando compuertas lógicas.  

### Trabajo Práctico N°4: Afianzar fundamentos y herramientas de desarrollo.

#### Objetivos  

• Afianzar fundamentos de programación en C/C++.  

• Afianzar fundamentos de herramientas de desarrollo ( simuladores, ide).  

• Afianzar fundamentos de sensores y actuadores básicos.  

***Desarrollo***  

***Ejercicio 1:*** Manejo de Entradas Digitales y Control de Relés  

Objetivos:
1. Configurar y leer entradas digitales en Arduino.  

2. Enviar y recibir datos a través del monitor serie.  

3. Controlar relés como salidas digitales basados en la entrada de datos del monitor serie.  

4. Implementar un sistema de control básico en Proteus utilizando botones y relés.  

***Desarrollo:***  

• Configura el Arduino para leer los estados de dos botones conectados a dos pines digitales.  

• Establece una comunicación serial para recibir comandos que controlen un grupo de relés.  

• Los relés deberán estar conectados a otros pines digitales y controlarán luces LED simuladas en Proteus.  

• Programa el Arduino para que, al recibir ciertos comandos a través del monitor serie, active o desactive los relés correspondientes.  

***Ejercicio 2:*** Lectura de Sensores Resistivos  

Objetivos:  

1. Aprender a leer valores analógicos de un potenciómetro.  

2. Convertir valores analógicos en datos digitales comprensibles.  

3. Visualizar y monitorear cambios en el valor del potenciómetro a través del monitor serie.  

4. Simular la conexión y lectura de un sensor resistivo en Proteus.  

***Desarrollo:***  

• Conecta un potenciómetro a un pin analógico del Arduino.  

• Utiliza la función analogRead() para leer los valores del potenciómetro.  

• Envía los valores leídos al monitor serie para visualizarlos.  

• Implementa un sistema de visualización en Proteus para representar los valores leídos del potenciómetro.  

Ejercicio 3: Interacción con un Sensor Digital (DHT11)  

***Objetivos:***  

1. Integrar y configurar el sensor de temperatura y humedad DHT11 con Arduino.  

2. Leer datos digitales de un sensor ambiental.  

3. Interpretar y procesar datos de temperatura y humedad.  

4. Mostrar los datos procesados en el monitor serie y simular esta configuración en Proteus.  

***Desarrollo:***  

• Conecta el sensor DHT11 a un pin digital en el Arduino.  

• Utiliza una biblioteca adecuada para leer los datos de temperatura y humedad del sensor.  

• Programa el Arduino para enviar estos datos al monitor serie, mostrando la temperatura y la humedad ambiental.  

• Configura el simulador Proteus para modelar esta interacción, utilizando representaciones visuales de los datos recibidos del DHT11.  



***Presentación***

Cada actividad deberá estar documentada y alojada en un monorepositorio, con un
informe que incluya el diseño del circuito, la simulación en Proteus, los cálculos
teóricos correspondientes, la comparación entre los valores teóricos y los resultados
de la simulación, y las conclusiones obtenidas.
El plazo de entrega es el correspondiente a la finalización de la semana.***
