# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic
Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.0] - 2023-12-07
### Improved
- Add full.json and test.mjs to npmignore

## [0.4.0] - 2023-12-07
### Added
- aliases field: Array of aliases for the zone

### Breaking
- Move data format to be organized with name meaning the zone identifier

### Removed
- zone field (in favor of name being zone and combining with an alias array)

## [0.3.0] - 2023-12-07
### Added
- Added the zone identifier for each entry
- Added the following missing timezones
-- Africa/Accra
-- America/Atikokan
-- America/Blanc-Sablon
-- America/Creston
-- America/Curacao
-- America/Godthab
-- America/Nassau
-- America/Nipigon
-- America/Pangnirtung
-- America/Port_of_Spain
-- America/Rainy_River
-- America/Thunder_Bay
-- America/Yellowknife
-- Antarctica/DumontDUrville
-- Antarctica/Syowa
-- Antarctica/Vostok
-- Asia/Brunei
-- Asia/Kuala_Lumpur
-- Atlantic/Reykjavik
-- Australia/Currie
-- Europe/Amsterdam
-- Europe/Copenhagen
-- Europe/Kiev (both Europe/Kyiv and Europe/Kiev are valid timezones because of their aliases: https://nodatime.org/TimeZones)
-- Europe/Luxembourg
-- Europe/Monaco
-- Europe/Oslo
-- Europe/Stockholm
-- Europe/Uzhgorod
-- Europe/Zaporozhye
-- Indian/Christmas
-- Indian/Cocos
-- Indian/Kerguelen
-- Indian/Mahe
-- Indian/Reunion
-- Pacific/Chuuk
-- Pacific/Enderbury
-- Pacific/Funafuti
-- Pacific/Majuro
-- Pacific/Pohnpei
-- Pacific/Wake
-- Pacific/Wallis

## [0.2.0] - 2023-12-07
### Improved
- Update readme with installation details
- Update readme with other data pack documentation
- Update readme with npm badges

## [0.1.0] - 2023-12-07
### Added
- raw.json: Baseline list of timezones (only name)
