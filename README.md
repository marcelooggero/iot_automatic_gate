# iot_automatic_gate


 * Title: WiFiManager and Blynk Token to control automatic sliding gate
 * File: WM_Blynk_token_1parameter_GPIO4_OUTPUT_PUSHBUTTON.ino
 * Author: Marcelo Oggero
 * Date: 20/10/2021
 *
 * This program controls a ESP8266 Mini board with a output relay (220VAC 10A). The module is controlled from the
 * internet via the Blynk cloud app and can change a relay status. Alco can receive status change throught Blynk app.
 * Download Blynk APP, create a new project from witch you can get the token, then ADD a button with output pin V0 type PUSHBUTTON.
 * The ESP8266 output relay is connected to D2 (GPIO4). 
 
 * 
 * 
 * Notes:
 *  (1) Requires the following arduino libraries:
 *      ESP8266 2.7.4
 *      Blynk 1.0.1
 *      WiFiManager 2.0.4 Beta 
 *      ArduinoJson 5.13.5
 *  (2) Compiled with arduino ide 1.8.12
 *  (3) Uses three Blynk app widgets:
 *       V0: Momentary pushbutton.
 *       V1: --
 *       V2: --
