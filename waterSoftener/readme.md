Water Softener builds
  **_WEMOS_**

  - PIN wyjściowy D2 -> GPIO2 -> D4 -> poprzez rezystor 300 Ohm do diody LED i masy
  - PIN D1 i D2 odpowiednio jako SCL , SDA podpięte do tak opisanych pinów czujnika odległości
  - PIN D6 jako wejście od guzika CONFIG do masy

  **_Czujnik zbliżeniowy VL53L0X podłączenia:_**

  - VCC - 5V 
  - GND -> do masa
  - SCL -> D1 mikroprocesora
  - SDA -> D2 mikroprocesora
  

**Instalacja urządzenia w SUPLA**

- Urządzenie na potrzeby auto instalacji w SUPLA wystawia sieć o SID: SUPLA-AAFF
- W aplikacji SUPLA należy włączyć wyszukiwanie urządzenia i jeśli pojawi się pytanie o sieć urządzenia wskazać SUPLA-AAFF

- Szczegółowa instalacja: https://docs.google.com/document/d/16kpUtxsnjw5PnmqxU1OxcAFQ2O78mgNJ2Iljd1y7DOY/edit?pli=1#heading=h.t42ha2cg7wg
