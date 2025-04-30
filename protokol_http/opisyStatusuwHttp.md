# Grupy statusów HTTP

Poniżej znajduje się opis podstawowych grup kodów statusu HTTP:

## 1XX – Informacyjne
Oznaczają, że żądanie zostało odebrane i proces trwa.  
**Przykład:** `100 Continue`

## 2XX – Sukces
Informują, że żądanie zakończyło się powodzeniem.  
**Przykłady:** `200 OK`, `201 Created`

## 3XX – Przekierowania
Wskazują, że klient powinien podjąć dodatkowe kroki, by zakończyć żądanie.  
**Przykłady:** `301 Moved Permanently`, `302 Found`

## 4XX – Błędy klienta
Oznaczają, że problem leży po stronie klienta.  
**Przykłady:** `404 Not Found`, `403 Forbidden`

## 5XX – Błędy serwera
Informują, że serwer napotkał błąd i nie mógł wykonać żądania.  
**Przykłady:** `500 Internal Server Error`, `503 Service Unavailable`