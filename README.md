# cruise_ship_analytics

1. API Implementierung und Datenbank-Design
  a. Implementiere die PS01-API von Marine Traffic und rufe die stündlichen Positionsdaten (simple) von zwei zusammenhängende Tagen aus diesem Jahr für die Schiffe mit der MMSI ‚269057489‘ und ‚269057500' ab.
  b. Lese die beigefügten CSV-Daten ein.
  c. ErstelleeineDatenbankmitangemessenerStrukturinderDudieDatensätzeaus(a.)und(b.) ablegst.
- Ermögliche einem Nutzer anhand einer MMSI und eines Zeitfensters zusätzliche Datensätze direkt in die Datenbank zu spielen.
- Hinweis: Bei Erstellen eines kostenlosen Accounts bei marinetraffic.com erhältst Du 100 Credits, die du zum Testen und Abrufen der benötigten Daten nutzen kannst. API documentation: https://www.marinetraffic.com/en/ais-api-services/documentation/api- service:ps01

2. Webcrawling
  a. Lese die technischen Spezifikationen für alle Motoren unter
     https://www.finning.com/en_CA/products/new/power-systems/electric-power-generation.html
     ein und erweitere die bestehende Datenbank sinnvoll um diese Daten. Benötigte Daten sind Min. Rating, Max. Rating, Voltage, Frequency, Speed.

3. Aggregation
  Beantworte folgende Fragen mittels SQL-Abfragen (jeweils ohne die in (1 a.) abgerufenen Daten):
    - Wie hoch ist die Durchschnittsgeschwindigkeit je Schiff und Tag über alle Schiffe?
    - Wie viele nautische Meilen wurden je Eigner durchschnittlich in der Mittagszeit von 12-14 Uhr zurückgelegt?
    - Zeige die Rangfolge der Motortypen (engine_name) bezogen auf die gezeigte Maximalgeschwindigkeit. Korrespondiert diese Rangfolge mit der maximalen Leistungsabgabe aus den technischen Spezifikationen?
    - Hinweis: Der Zeitstempel zeigt nur die Eintragung in der Datenbank an. Der Speed-Wert ist jeweils das Mittel der vollen vorherige Stunde.
    
