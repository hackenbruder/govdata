# GovData

# Fakta
Stručné důvody proč používat naše API:

* Státní správa nemá platný SSL certifikát
* Státní správa nemá funkční DNS servery
* Státní správa nemá highly-available škálovatelné služby
* Výstupy jsou XML v době masivní adopce JSONu
* API mají nízké limity a dlouhé odezvy
* API nemají žádná SDK
* Podmínky použití a dokumentace API jsou plné nesmyslů, chyb a výhružek

# API
Máme povolené CORS pro všechny zdrojové domény.

##Dotaz
Spuštěním následující dotazu získáte aktuální informace o subjektu MFČR.

`curl -H 'X-Api-Key: ZX1Ap4RUDY2VisBOu2P0e4sEvh2LhWh4Cx8lqoO6' 'https://api.govdata.cz/demo/ico/00006947'` nebo [ve vašem prohlížeči](http://www.govdata.cz/demo/ico/00006947)

##Odpověď
[Ukázka API odpovědi pro subjekt MFČR](https://gist.github.com/hackenbruder/7e6590122e4bbe7f77a8)
