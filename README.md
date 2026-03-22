# desktopbuddy
DeskBuddy is a small interactive robot that displays real-time weather information, date and time, and expresses funny animated facial reactions to engage users.

# Weather api kye 
Go to the website and create your API key to use this project.(https://home.openweathermap.org/users/sign_in)

# Component
1.oled 0.96 disply 
2.lithium battery
3.TP4056 chargen modul
4.ESP32-C3
5.TTP223 touch sensor module
6.on/of switch

# The connection diagram has been provided for easy wiring and setup.

# Add your API key and WiFi credentials in the code before uploading:

const char* wifiSsid    = "your_wifi_name";
const char* wifiPass    = "your_wifi_password";
const char* apiKey      = "your_api_key";
const char* city        = "Pune";
const char* countryCode = "IN";
const char* tzString    = "IST-5:30";

Alternatively, you can use the configuration portal: //192.168.4.1//
Connect to the WiFi network "DeskBuddy"
using the password "123456789",
Then open http://192.168.4.1 in your browser to configure WiFi credentials and API key.


