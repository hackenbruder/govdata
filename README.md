# GovData

Jsou vysoce dostupnou službou poskytující vybraná open data k přímému použití ve webových a mobilních aplikacích.

Důvody vzniku služby shrnujeme v článku [Proč vznikají GovData?](https://medium.com/@hackenbruder/pro%C4%8D-vznikaj%C3%AD-govdata-ec08288fee0c)

# Fakta

Stručné důvody, proč používat GovData:

* Máme a budujeme SDK
* API je vysoce dostupné
* Máme vysoké limity a krátké odezvy na požadavky
* SSL zabezpečení s platnými certifikáty je standardem

Státní online služby mají tyto nedostatky:

* Nejsou vysoce dostupné a škálovatelné
* API mají nízké limity a velmi dlouhé odezvy
* API nemají SDK
* Mají neplatné SSL certifikáty
* Mají nespolehlivé DNS servery a velmi dlouhé odezvy požadavků
* Výstupy API pouze v XML v době masivní adopce JSONu
* Mají nedostatečnou dokumentaci
* Mají nevhodné podmínky použití

## Dostupná data

Postupně zpřístupňujeme data:

* Obchodního a živnostenského rejstříku
* Plátců DPH včetně informací o jejich spolehlivosti a bankovních účtech

Konkrétní příklad najdete v článku [Proč vznikají GovData?](https://medium.com/@hackenbruder/pro%C4%8D-vznikaj%C3%AD-govdata-ec08288fee0c)

# SDK

* [GovData Javascript SDK pro Node.js a prohlížeče](https://github.com/hackenbruder/govdata-js)
* [GovData iOS SDK](https://github.com/hackenbruder/govdata-ios)

Odkazy na uvedené repozitáře obsahují příklady použití SDK.

### RESTful API

K API doporučujeme přistupovat prostřednictvím SDK.

####Dotaz

Spuštěním následující dotazu získáte aktuální informace o subjektu MFČR.

`curl -H 'X-Api-Key: ZX1Ap4RUDY2VisBOu2P0e4sEvh2LhWh4Cx8lqoO6' 'https://api.govdata.cz/v1/demo/entity/00006947'`

####Odpověď

[Ukázka API odpovědi pro subjekt MFČR](https://gist.github.com/hackenbruder/7e6590122e4bbe7f77a8)
