# world-currencies
This repository contains information of different currencies that are still appearing on currency exchange board today. It provides all the information in JSON format and it contains:

* ISO-4217 currency codes
* Currency symbols
* Currency names
* Associated countries for each currency
* ISO 3166-2 country codes with associated continent

## Example
```json
[
  {
    "code": "MYR",
    "symbol": "RM",
    "name": "Malaysian Ringgit",
    "country": [
      {
        "name": "Malaysia",
        "code": "MY",
        "continent": "Asia",
        "continent_code": "CAS"
      }
    ]
  }
]
```

## Sources

* [Currencylayer Supported Currencies](https://currencylayer.com/currencies)
* [XE World Currency Symbols](http://www.xe.com/symbols.php#section1)
* [List of Currencies of The World](https://www.countries-ofthe-world.com/world-currencies.html)
* [World Regions](http://www.internetworldstats.com/list1.htm#geo)
* [List of all countries with their 2 digit codes (ISO 3166-2)](http://data.okfn.org/data/core/country-list/r/data.json)
* Wikipedia
