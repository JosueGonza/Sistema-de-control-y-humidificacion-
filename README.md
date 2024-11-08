# Sistema-de-control-y-humidificacion-
Sistema de Control y Humidificación
Descripción

Este proyecto es un sistema de control y monitoreo de humedad y temperatura para una planta de hilatura. Su objetivo es mantener la humedad y la temperatura en niveles óptimos para la producción de hilos, mejorando la calidad y reduciendo problemas como roturas, electricidad estática y defectos en el hilo.
Instalación
1. Clona el Repositorio

Clona el proyecto en tu máquina local:

bash

git clone https://github.com/JosueGonza/Sistema-de-control-y-humidificacion-.git
cd Sistema-de-control-y-humidificacion-

2. Instala las Dependencias

Asegúrate de tener pip instalado y ejecuta:

bash

pip install -r requirements.txt

Esto instalará las bibliotecas necesarias, como Tkinter para la interfaz gráfica y cualquier otra dependencia especificada en requirements.txt.
Configuración de Arduino

    Carga el Código de Arduino:
        Abre el archivo Codigo_Arduino.ino en el IDE de Arduino.
        Selecciona el puerto COM correcto y carga el código en el Arduino Uno.

    Conectar el Sensor de Humedad y Temperatura:
        Conecta el sensor (por ejemplo, un DHT22) al Arduino en el pin digital especificado en el código, usualmente D2.
        Revisa que los pines estén correctamente configurados para la toma de datos.

    Verifica los Pines en el Código: Asegúrate de que los pines configurados en el archivo de Arduino coincidan con la configuración de tu circuito físico.

Uso

    Ejecutar el Archivo Principal: Para iniciar el sistema, ejecuta el archivo main.py desde la terminal:

    bash

    python main.py

    Funcionalidades de la Interfaz:
        Visualización en Tiempo Real: Observa los niveles actuales de humedad y temperatura.
        Control Automático: Configura el sistema para ajustar automáticamente la humedad en función de los valores predeterminados.
        Registro de Datos: Consulta el historial de humedad y temperatura almacenado en la base de datos SQLite.

Requerimientos de Hardware

    Microcontrolador: Arduino Uno R3.
    Sensor de Humedad y Temperatura: Sensor DHT22 (u otro compatible).
    Pantalla LCD 16x2: Para mostrar los niveles de humedad y temperatura.
    Relés: Control de dispositivos de humidificación.
    Componentes Adicionales: Resistencias, potenciómetros y LEDs para indicación de estado y ajustes de valores.

Conexiones Básicas de Hardware

    Sensor de Humedad y Temperatura: Conecta el pin de datos al pin digital D2 del Arduino.
