Arduino IDE version - 1.8.3
Board Management - Espressif Version 1.0.6
(If version 2.0.1, then compling fail)

Board: ESP32 Wrover Module
Partition scheme - Huge App (3MB)
Preference - https://dl.espressif.com/dl/package_esp32_index.json

------------Modification------------
#define CAMERA_MODEL_AI_THINKER // Has PSRAM
const char* ssid = "ABC";
const char* password = "11021102";
Serial.begin(115200);
