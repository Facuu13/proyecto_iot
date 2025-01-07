# Proyecto IoT: Monitoreo y Control en el Hogar

## Descripción General
Este proyecto tiene como objetivo implementar un sistema IoT para monitoreo y control en el hogar utilizando un ESP32, sensores DHT11 y BME280, y tecnologías IoT clave como MQTT y ThingsBoard. El sistema permitirá:

1. **Monitorear**: Capturar datos de temperatura, humedad y presión del ambiente.
2. **Controlar**: Encender o apagar dispositivos como luces o ventiladores desde un dashboard.
3. **Practicar IoT**: Integrar tecnologías clave como MicroPython, MQTT y un servidor IoT para el almacenamiento y visualización de datos.

---

## Funcionalidades Principales

### **1. Monitoreo**
- **Sensores**: Utilizaremos los sensores DHT11 y BME280 para medir las variables ambientales.
  - DHT11: Temperatura y humedad.
  - BME280: Temperatura, humedad y presión atmosférica.
- Los datos capturados se enviarán a un servidor IoT en tiempo real.

### **2. Control**
- Agregaremos funcionalidades para encender y apagar dispositivos como ventiladores o luces.
- Control remoto desde un dashboard interactivo.

### **3. Almacenamiento y Visualización**
- Los datos serán almacenados y visualizados en el servidor IoT **ThingsBoard**:
  - Tableros interactivos para graficar y analizar los datos.
  - Alertas configurables basadas en valores umbral.

---

## Tecnologías y Herramientas

### **1. Microcontrolador**
- **ESP32**: Se usará como el núcleo del sistema para capturar datos de sensores y comunicarse con el servidor.

### **2. Firmware**
- **MicroPython**: Lenguaje de programación ligero y eficiente para el ESP32.

### **3. Protocolo de Comunicación**
- **MQTT**: Protocolo de comunicación liviano para enviar los datos al servidor IoT.

### **4. Conectividad**
- **Wi-Fi**: El ESP32 se conectará a internet mediante una red Wi-Fi doméstica.

### **5. Servidor IoT**
- **ThingsBoard**: Plataforma IoT que permitirá:
  - Almacenamiento de datos.
  - Configuración de alertas.
  - Creación de dashboards interactivos.

---

## Pasos del Proyecto

1. **Configuración Inicial**
   - Preparar el ESP32 con MicroPython.
   - Instalar y probar los sensores DHT11 y BME280.

2. **Lectura de Sensores**
   - Implementar un script para capturar datos de los sensores y verificar su correcto funcionamiento.

3. **Comunicación MQTT**
   - Configurar el ESP32 para conectarse al broker MQTT.
   - Publicar datos de los sensores en temas específicos.

4. **Conexión con ThingsBoard**
   - Configurar un dispositivo en ThingsBoard.
   - Enviar datos del ESP32 a ThingsBoard a través de MQTT.

5. **Desarrollo del Dashboard**
   - Crear dashboards en ThingsBoard para visualizar los datos en tiempo real.
   - Configurar alertas basadas en valores umbral.

6. **Control de Dispositivos**
   - Agregar control remoto de dispositivos (ej., encendido/apagado de luces o ventiladores).
   - Implementar botones interactivos en el dashboard.

7. **Pruebas y Optimización**
   - Validar la funcionalidad del sistema.
   - Realizar ajustes para mejorar el rendimiento y la experiencia de usuario.

---

## Objetivo del Proyecto
Este proyecto busca desarrollar habilidades prácticas en IoT mediante la implementación de un sistema funcional y útil para el hogar, integrando tecnologías modernas para el monitoreo, control y visualización de datos en tiempo real.
