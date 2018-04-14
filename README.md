# AirAuto
AirAuto to niewielka aplikacja, przekazująca do [Android Auto](https://www.android.com/auto/ "Strona Android Auto") informacje o stanie powietrze pobrane z czujników [Airly](https://airly.eu/pl/ "Strona Airly").

# Instalacja 
Pobierz plik [apk](https://github.com/maciejbudzyn/AirAuto/raw/master/AirAuto.apk "AirAuto") na urządzenie mobilne i uruchom. 
Zezwól na dostęp aplikacji do informacji o lokalizacji twojego urzadzenia.

# Używanie
Aplikacja automatycznie, po podłączeniu urządzenia do konsoli w samochodzie, będzie przekazywać do Android Auto informacje o stanie powietrza. 
Aby nie rozpraszać kierowcy, aplikacja wysyła informacje o stanie powietrza tylko jeżeli: uległ zmianie poziom zanieczyszczeń, zmienił się sensor od którego pobierano dane, mineło min. 15 od czasu ostatniego komunikatu.

Stan powietrza przekazywany jest: w postaci koloru ikony w powiadomieniu (wg CAQI, 5 poziomów zanieczyszczenia, zielony czysto, ..., czerwony bardzo zanieczyszczone), w postaci komunikatu głosowego zawierającego informacje o poziomie zanieczyszczeń, normach PM2.5 i PM10 oraz adresie czujnika.

Obsługiwane języki: polski, angielski.

EN version:

# AirAuto
AirAuto is a tiny application, forwarding to Android Auto the information about air quality, received from Airly sensors.

# Installation
Download [apk](https://github.com/maciejbudzyn/AirAuto/raw/master/AirAuto.apk "AirAuto") file on your mobile device, install it and run.
Allow the application to gather information about localization of your device.

# Usage
The application, after mobile is connected to car head unit device, notifies Android Auto about air quality.
To avoid driver distraction, application sends the notification only if: pollution level has changed, data source sensor has changed, 15 minutes have elapsed from the last notification.

The air quality is presented in Android Auto notification in two ways: graphically  - icon color (according CAQI, 5 quality levels from green (good quality) to black, as audio message, with quality details and location of a sensor.

Supported languages: polish, english.
