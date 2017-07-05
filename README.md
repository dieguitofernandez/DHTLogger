# DHTLogger

Un simple logger de temperatura y humedad

### Hard
Esp8266 (Actualmente un nodeMCU, con ganas de migrar a un esp-01) y un modulo DHT11

### Soft
Firmware combinando algunos ejemplos tipicos
Servicio mqtt de adafruit para la persistencia y visualizacion de los datos.

### Usos
Hasta el momento se utilizo para determinar cantidad de encendidos de un termotanque residencial y poder medir efectividad de futuras mejoras en el aprovechamiento del calor.

### Backlog
* Implementar libreria wifi manager para ganar portabilidad.
* Mejorar el consumo de bateria durmiendo el dispositivo en periodos de inactividad.
* Cambiar sensor por algo mas exacto, el DHT11 tiene un error muy grande para algunas mediciones que deseo realizar.
* Incorporar un segundo sensor para contar con una temperatura de referencia.
