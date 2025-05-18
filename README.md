# Netwerken_HTTP_client

TCP server luistert op poort 22

TCP server accepteert meerdere verbindingen

TCP server achterhaalt IP adres van client

TCP server logt IP adres in logs

TCP server start een HTTP client per nieuwe verbinding

HTTP client maakt een TCP verbinding met IP Geolocation API

HTTP client stuurt een correcte HTTP GET request

HTTP client ontvangt de reactie van de HTTP server

HTTP client extraheert zuiver de volledige json reactie

HTTP client logt de geolocatie in logs

HTTP client sluit de verbinding zuiver af

TCP server accepteert gegevens van client en logt ze in logs

TCP server stuurt zoveel mogelijk gegevens naar de openstaande verbinding

TCP server houdt een teller bij hoeveel gegevens succesvol zijn afgeleverd en logt deze bij het sluiten van de verbinding in logs

TCP server sluit de verbinding nadat de client de verbinding sluit

TCP server kan meerdere verbindingen simultaan verwerken

Het geheel werk volledig zonder crashen en er wordt efficiënt met de resources (i.e. memory en sockets) van de computer gebruik gemaakt

Code staat professioneel op GitHub (i.e. meerdere nuttige commits en uitleg)