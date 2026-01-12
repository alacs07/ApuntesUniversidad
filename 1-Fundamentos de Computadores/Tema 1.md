## Introducción
* **Bit**: Unidad mínima de información => 0 o 1.
* **Byte**: Unidad de información formada por 8 bits ($2^8 = 256 \text{ posibles combinaciones}$).

## Historia y evolución
* El primer dispositivo mecánico considerado un computador lo diseñó Charles Babagge en el año 1816, llamado la "Máquina analítica".
	* Basándose en esta máquina **Lady Ada Lovelace** (Hija de *Lord Byron*) desarrolló los principios de la programación moderna.

* El primer dispositivo mecánico considerado una calculadora (*Pascalina*) fue diseñado por Blaise Pascal en el siglo XVII. => Era capaz de realizar sumas y restas con el concepto de *acarreo*.

* **Hernan Hollerit** desarrolló la máquina para el censo de Estados Unidos, dando lugar a la empresa IBM.
* **Torres Quevedo** formuló lo que sería una nueva rama de la ingeniería. La automática. Concepto de aritmética en *coma flotante*.

* La historia del computador moderno durate el siglo XX gira alrededor de la introducción y la posterior evolución del interruptor electrónico.

### Generaciones
- **Primera generación** (1940 - 1956):
	- **Válvulas de vacío**.
	- Alto consumo y disipación de calor.
	- Baja fiabilidad.
- **Segunda generación** (1956 - 1963):
	- **Transistor**.
	- Grandes mejores en consumo, disipación y fiabilidad.
	- Reduce costes e inicia el camino de la miniaturización.
- **Tercera generación** (1964 - 1971):
	- Circuitos integrados (**chips**) con múltiples transistores.
	- Minicomputadores.
- **Cuarta generación** (1971 - Actualidad):
	- **Microprocesador**.
	- Alta escala de integración.
	- Computador personal.
- ¿*Quinta generación*? (1981 - 1991):
	- El gobierno japonés, junto a 6 empresas privadas trataron de crear un ordenador capaz de tener inteligencia humana, con respuesta al lenguaje natural y con una capacidad de aprendizaje y organización autónoma. => **Fracaso** total => Se concluye que son necesarias mejoras tecnológicas.

* Se dejan de clasificar los computadores por medio de generaciones. La tecnología avanza en diferentes líneas:
	1. Nuevas tecnologías (óptica, cuántica, etc.)
	2. Procesadores multinúcleo.
	3. Grandes sistemas multicomputadores.
	4. Procesamiento distribuido y paralelo.
	5. Computación y comunicaciones ubicuas.
	6. Aplicaciones de Inteligencia Artificial.


## Arquitectura de un computador
Define su comportamiento funcional y se puede caracterizar por el número de unidades funcionales y como se interconectan entre sí: 
* **Arquitectura Von Neumann** (Memoria combinada)
* **Arquitectura Harvard** (Memoria segregada)
### Arquitectura Von Neumann
(IMAGEN)
* Es la base de la inmensa mayoría de computadores actuales:
	* La memoria almacena instrucciones y datos.
	* La unidad central de procesamiento (CPU) ejecuta instrucciones.
	* Las instrucciones pueden leer y escribir datos en memoria y acceder al sistema de  entrada/salida.

### Arquitectura Harvard 
* La memoria de datos e instrucciones está separada
	* En un mismo ciclo se puede acceder a la instrucción y a los datos.
	* Esta arquitectura funciona mejor cuando la frecuencia de instrucciones y datos es aproximadamente la misma. Normalmente se suele utilizar en DSP (Digital Signal Processor).

## Unidades funcionales del computador
* **Unidad Central de Proceso** (CPU):
	* Es el componente que interpreta las instrucciones y procesa los datos contenidos en los programas.
* **Memoria**
	* Dispositivo de almacenamiento que permite lectura y escritura.
	* En general, el procesador accede a la memoria como si esta fuera un vector indexado por *direcciones*.
(IMÁGENES)

* **Sistema de E/S** (Entrada/Salida):
	* Permite la comunicación entre CPU y periféricos externos (Ratón, teclado, impresora, etc.)
IMAGEN


## Sistemas de representación básicos
* **Sistema de numeración**
	* Conjunto de signos, reglas y convenciones que permiten expresar cantidades verbal y gráficamente.
	* Ejemplo: Decimal y binario.
* **Base de un sistema de numeración**
	* Número de símbolos distintos que se emplean. Cada uno de estos símbolos se denomina **dígito**.
	* Ejemplo: Decimal => 10 signos y Binario => 2 signos.
* **Sistema de numeración posicional**: 
	* Un número viene definido por una cadena de dígitos, donde cada uno de ellos está afectado por un factor de escala.

### Sistema binario
* Base = 2; Dígitos = 0 y 1 (bits).
* Una cantidad *N* se representa mediante una secuencia de bits 
	* Ejemplo: 
	* 