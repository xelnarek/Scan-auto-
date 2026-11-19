# AUTO SCAN PRO 2.0

Polskojezyczna aplikacja PWA do edukacyjnej diagnostyki OBD-II.

## Uruchomienie

Projekt jest przygotowany do wdrozenia na Vercel. Wymaga HTTPS dla instalacji PWA i Web Bluetooth.

## Funkcje
- PWA z trybem offline i instalacja na Androidzie oraz komputerze.
- Profile pojazdow, historia i import/eksport JSON.
- Baza kodow DTC i edukacyjny asystent diagnostyczny.
- Odczyt podstawowych PID przez kompatybilny adapter BLE ELM327.
- Dekoder VIN oraz informacje o akcjach serwisowych i zgloszeniach z bazy NHTSA.

## Ograniczenia
Web Bluetooth wymaga kompatybilnej przegladarki i adaptera BLE UART. Adaptery Bluetooth Classic/SPP nie sa obslugiwane przez PWA. Zakres PID zalezy od pojazdu. Dane NHTSA sa glownie amerykanskie. Asystent lokalny opiera sie na regulach i nie zastepuje profesjonalnej diagnostyki.

## Testy
`npm test`
