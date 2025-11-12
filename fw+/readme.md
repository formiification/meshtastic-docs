# Meshtastic Firmware+
## Disclaimer wersji
### firmware
- fw - vanilia (wersje w formacie X.Y.Z)
- fw+ - musznik (wersje w formacie vXXX)
### platformy
- rak4631...
### modyfikacje
- EU868 - domyślny region
- CLIENT - domyślna rola
- nopinger - wyłączona odpowiedź na Pinger
- TXqueueFIX - [poprawiona obsługa tx queue](https://github.com/m1nl/meshtastic-firmware/commit/2a3ebd99c34c1c8ec240366757e3b2ff0fddc5ba?fbclid=IwY2xjawOBkdtleHRuA2FlbQIxMABicmlkETB6YktyNzdjenoyYXZXenZEc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHo3NBdpWf2IFXCmTJOBhTRYHI0HohIz1zHrIMhQe-dZFxSSMiwt-t6EkYyM2_aem_USFNVVOSXKDnecivg8JPyA)
- 7hops - domyślne nadawanie na 7 hops (sugeruję zmniejszyć po uruchomieniu, nie mniej dobrze żeby węzeł w terenie wstawał z 7 po factory reset)
- +4hopsReply - domyślnie węzły odpowiadają na ramki z ilością hopów wiadomości przychodzącej +2, więc w przypadku gdy droga powrotna jest znacznie dłuższa niż droga do węzła odpowiedź nie dociera do pytającego, zmieniono na +4
- OKtoMQTT - domyślne OKtoMQTT
- 30TXpower - domyślne 30dBm (firmware i tak zmniejszy żeby dopasować do możliwości modułu)
