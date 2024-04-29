# ESP32-RS485-Bridge
A Modbus bridge with an ESP32 and a RS485 adapter

## part list

I built this solution with

- [TTL to RS485 Converter 3.3V/5.0V Hardware Automatic Control Converter Module AVR9](https://www.aliexpress.com/item/32849051202.html)
- [D1 MINI ESP32 WiFi+Bluetooth ESP-32](https://www.aliexpress.com/item/1005006400668971.html)

Wiring information can be found at [here](https://github.com/zivillian/esp32-modbus-gateway?tab=readme-ov-file#hardware).

## information

This solution is based on [esp32-modbus-gateway](https://github.com/zivillian/esp32-modbus-gateway). I've added a reconnect logic for Wifi and disabled the brownout detector.