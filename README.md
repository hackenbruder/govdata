# GovData

Jsou vysoce dostupnou službou poskytující vybraná open data k přímému použití ve webových a mobilních aplikacích.

Důvody vzniku služby shrnujeme v článku [Proč vznikají GovData?](https://medium.com/@hackenbruder/pro%C4%8D-vznikaj%C3%AD-govdata-ec08288fee0c)

[![Chatujte https://gitter.im/hackenbruder/govdata](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/hackenbruder/govdata?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

^^^^^^^^^^^^^^^^^^^ Napište nám!

# Fakta

Stručné důvody proč používat naše API:

* Máme a budujeme SDK
* Je vysoce dostupné a škálovatelné
* Máme vysoké limity a krátké odezvy
* SSL zabezpečení s platnými certifikáty je náš standard

Státní online služby mají tyto nedostatky:

* Nejsou vysoce dostupné a škálovatelné
* API mají nízké limity a velmi dlouhé odezvy
* API nemají SDK
* Mají neplatné SSL certifikáty
* Mají nespolehlivé DNS servery a velmi dlouhé odezvy požadavků
* Výstupy API pouze v XML v době masivní adopce JSONu
* Podmínky použití a dokumentace API jsou plné nesmyslů, chyb a výhružek

## Dostupná data

Postupně zpřístupňujeme data:

* Obchodního rejstříku
* Plátců DPH

Konkrétní příklad najdete v článku [Proč vznikají GovData?](https://medium.com/@hackenbruder/pro%C4%8D-vznikaj%C3%AD-govdata-ec08288fee0c)

# SDK

* [GovData Javascript SDK pro Node.js a prohlížeče](https://github.com/hackenbruder/govdata-js)

Pracujeme na dalších SDK pro nejpopulárnější programovací jazyky.

## RESTful API

Máme povolené CORS pro všechny zdrojové domény.

###Dotaz

Spuštěním následující dotazu získáte aktuální informace o subjektu MFČR.

`curl -H 'X-Api-Key: ZX1Ap4RUDY2VisBOu2P0e4sEvh2LhWh4Cx8lqoO6' 'https://api.govdata.cz/v1/demo/entity/00006947'`

###Odpověď

[Ukázka API odpovědi pro subjekt MFČR](https://gist.github.com/hackenbruder/7e6590122e4bbe7f77a8)
