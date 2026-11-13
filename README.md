# Panel ESP32 · DHT22 + MQ-135

Panel web que lee por USB (Web Serial, 115200 baudios) los datos de un ESP32 con sensores DHT22 (temperatura y humedad) y MQ-135 (calidad del aire) y los muestra con tarjetas y gráficas en tiempo real.

## Uso

1. Cierra cualquier otro programa que use el puerto serie (p. ej. el Monitor Serie de Arduino).
2. Abre `panel-esp32.html` en Google Chrome o Microsoft Edge.
3. Pulsa **Conectar placa** y elige el puerto del ESP32 (p. ej. `USB-SERIAL CH340`).

El botón **Modo demo** muestra datos simulados para ver el panel sin la placa.
