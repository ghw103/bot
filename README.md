# bot
Lab project

# Abstrakt
Projekt zespołu balansujących robotów mobilnych. Zadaniem grupy robotów będzie poruszanie się w zamkniętej przestrzeni i współpraca przy przesuwaniu obiektów. 

## Funkcjonalność 
* Lokalizacja w przestrzni zamkniętej ograniczinej nadajnikami
* Przesyłanie obrazu i danych z czujników do komputera sterującego
* Mapowanie przestrzeni
* Sterowanie za pomocą aplikacji mobilnej
* Programowanie "On air" poszczególnych robotów 

## Elementy
### Napęd
* Silnki krokowe typu NEMA 17
* Sterowniki DRV8825

### Elektronika
* STM32 nucleo board
* ARM v7< board
* Transceiver DMW1000 (lokalizacja)
* Moduł WiFi (komunikacja z siecią)
* Diody WS2812B (sygnalizacja aktualnego stanu robota)

### Sensoryka
* Czujniki odległości SHARP (cyfrowe)
* IMU MPU6050
* Gniazda do podłączenia innych czujników (w zależonści od wykorzystania)

## Wykonanie
Projekt zakłada stworzenie uniwersalnej płyty głównej robota scalającej wszyskie moduły, umożliwiającej proste podłączenie wszystkich elementów i ramy wydrukowanej na drukarce 3D. Dodatkowo w skład zestawu wchodziły bedą moduły lokalizacji (do umieszczenia wewnątrz pomieszczenia jako punkty odniesienia przy lokalizacji). Do organizacji pracy zespołu robotów zostanie opracowane oprogramowanie w języku C++ zaimplementowane na komputerze pełniącym jednocześnie rolę routera WiFi z którym będą połączone wszystkie roboty. 

### Zadania
* Projekt CAD elementów mechanicznych 
* Schemat oraz projekt PCB płyty głównej robota
* Schemat oraz PCB modułu lokalizacji
* Program z obsługą sieci na komputer sterujący
* Program na mikrokontroler sterujący robotem 
* Program na mikrokontroler w module lokalizacji
* Dokumentacja projektu 
* Matematyczno-Fizyczny opis algorytmów (lokalizacja i sterowanie)
* Aplikacja android (Pilot do zdalnego sterowania robotem) 
* Testowanie software
* Testowanie fizyczne
* Lutowanie i montaż elektroniki
* Wykonanie elementów mechanicznych i druk 3D
* Tworzenie "Landing page" projektu 
* PR i znajdowanie zastosowań (pomysł gier na bazie projektu)


