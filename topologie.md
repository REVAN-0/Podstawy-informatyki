# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to....
  - Wady: Awaria kabla powoduje przerwanie całej sieci, trudność w diagnozowaniu problemów.
  - Zalety: Łatwa w rozbudowie, niskie koszty.
  - Gdzie stosowane: W małych sieciach lokalnych (LAN), starsze systemy komputerowe.
- **Topologia pierścienia** (Ring): jest to....
  - Wady: Awaria jednego urządzenia przerywa cały obieg danych, skomplikowana w rozbudowie.
  - Zalety: Efektywne przesyłanie danych w obu kierunkach, dobra dla małych i średnich sieci.
  - Gdzie stosowane: W sieciach o dużym natężeniu danych, np. w sieciach token ring.
- **Topologia gwiazdy** (Star): jest to....
  - Wady:  Awaria centralnego punktu powoduje utratę komunikacji wszystkich urządzeń.
  - Zalety: Łatwa w rozbudowie i zarządzaniu, łatwa do wykrywania awarii.
  - Gdzie stosowane: W nowoczesnych sieciach lokalnych (LAN), np. w biurach i szkołach.



## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to....
  - Wady: Ograniczona skalowalność, wymaga dedykowanego połączenia.
  - Zalety: Prosta konfiguracja, stabilne połączenie.
  - Zastosowanie: Połączenia między routerami, łącza szeregowe.
- **Przekazywanie żetonu** (Token Passing): jest to....
 - Wady: Możliwość opóźnień w sieci, zależność od żetonu.
 - Zalety: Eliminacja kolizji danych, zorganizowane przesyłanie informacji.
 - Zastosowanie: W starszych sieciach Token Ring, sieci o dużym natężeniu danych.
- **Wielodostępowa** (Multiple Access): jest to....
 - Wady: Możliwość kolizji danych, wymaga mechanizmów rozwiązywania konfliktów.
 - Zalety: Umożliwia efektywne współdzielenie medium, elastyczność w użyciu.
 - Zastosowanie: Sieci Ethernet, Wi-Fi.