# python - informacion y ejemplos sobre machine learning

[![arduino-library-badge](https://www.ardu-badge.com/badge/SinricPro.svg?)](https://www.ardu-badge.com/SinricPro) [![](https://img.shields.io/badge/PlatformIO_Libraries-SinricPro-brightgreen.svg)](https://platformio.org/lib/show/6519/SinricPro)

[![Platform ESP8266](https://img.shields.io/badge/Platform-Espressif8266-orange)](#) [![Platform ESP32](https://img.shields.io/badge/Platform-Espressif32-orange)](#)

[![Framework](https://img.shields.io/badge/Framework-Arduino-blue)](https://www.arduino.cc/)

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/sinricpro/esp8266-esp32-sdk)](https://github.com/sinricpro/esp8266-esp32-sdk/releases)

#

### VS Code & PlatformIO:
1. Install [VS Code](https://code.visualstudio.com/)  
2. Install [PlatformIO](https://platformio.org/platformio-ide)  
3. Install **SinricPro** library by using [Library Manager](https://docs.platformio.org/en/latest/librarymanager/)  
4. Use included [platformio.ini](examples/platformio/platformio.ini) file from examples to ensure that all dependent libraries will installed automaticly.


<!--If you like **Tasmota**, give it a star, or fork it and contribute!

Estadisticas

[![GitHub stars](https://img.shields.io/github/stars/arendst/Tasmota.svg?style=social&label=Star)](https://github.com/arendst/Tasmota/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/arendst/Tasmota.svg?style=social&label=Fork)](https://github.com/arendst/Tasmota/network)
[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://paypal.me/tasmota)

-->


One Paragraph of project description goes here

Getting Started - These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. Prerequisites
What things you need to install the software and how to install them
Installing - A step by step series of examples that tell you how to get a development env running
Say what the step will be

#

### machine learning information:
```

https://naps.com.mx/blog/introduccion-al-machine-learning-en-python/

```
 
 ### environments information:
```
   
   https://code.visualstudio.com/docs/python/environments
   
```


para crear el entorno: 
```

    python -m venv .venv

```

para habilitar o desabilitar el entorno: 
```    

    nombre_de_env\Scripts\activate.bat
    
    nombre_de_env\Scripts\deactivate.bat
    
```
### librerias...

### Pandas
La primera librería de Python para Machine learning a considerar sería Pandas, una de las más utilizadas para el tratamiento de datos en Python. Una de las principales virtudes que tiene la librería es la carga de datos, la cual permite realizar la carga desde distintos orígenes. Entre los orígenes que acepta encontramos archivos de texto plano como CSV, ficheros en el extendido formato Excel y cargas directas desde bases de datos SQL, entre otros orígenes de datos. Todas estas fuentes de datos contienen la información en formato tabular y pandas permite representar este tipo de datos a la perfección mediante el uso de su estructura principal, el DataFrame.

### Numpy
Numpy es una librería de Python para Machine Learning caracterizada por ser la librería de procesamiento de arrays por excelencia. Contiene una gran colección de funciones que permiten realizar cálculos matemáticos complejos sobre arrays multidimensionales. La funcionalidad que implementa permite realizar operaciones lógicas, redimensiones, búsquedas y aplicar estadísticos entre otras muchas. El núcleo de la librería se basa en los objetos ndarray, los cuales permiten encapsular arrays de n dimensiones sobre los que se pueden realizar las operaciones antes descritas de una forma muy eficiente.

### SciPy
La librería Scipy está formada por una serie de módulos que proporcionan funcionalidad para resolver el cómputo de tareas científicas y analíticas. Entre estos módulos podemos encontrar soluciones de álgebra lineal, integración, optimización, interpolación, procesamiento de señales, procesamiento de imagen, etc. La estructura de datos utilizada por SciPy se trata de los arrays multidimensionales proporcionados por el módulo de Numpy, es decir, para la ejecución de sus operaciones SciPy depende de Numpy. 

### Scikit-learn
Una de las librerías Python más importantes enfocadas al Machine Learning es Scikit-Learn. Esta librería está formada por una gran cantidad de algoritmos de ML (clasificación, regresión, clustering, etc.) y proporciona funcionalidades básicas que facilitan el trabajo diario de los ingenieros dedicados a este tipo de tareas. Entre sus funcionalidades podemos destacar las herramientas para preprocesar datos, las funciones para evaluar modelos y los mecanismos para ajustar los parámetros de cada modelo.

### Matplotlib
Hasta este punto únicamente hemos introducido librerías que nos permiten manipular los datos y realizar algoritmos. Sin embargo, existe un procedimiento igual de importante en los flujos de trabajo y ese es el de visualización. La librería de Python para Machine Learning empleada en tareas de visualización por excelencia es Matplotlib y entre sus cualidades destacan que es open source y trabaja a bajo nivel. Es tal su importancia que otras librerías, como Plotly, se basan en ella.

### TensorFlow
Tensorflow es una de las librerías open source más importantes de Deep Learning y ha sido creada por Google. Está formada por un ecosistema flexible de herramientas, librerías y recursos de la comunidad y ayuda a los investigadores a innovar aplicando técnicas de Machine Learning. Además, permite a los desarrolladores incorporar este tipo de tecnologías en sus aplicaciones.

![Librerias necesarias](assets/ml_lib.png)
    

