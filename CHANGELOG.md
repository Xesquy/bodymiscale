# Changelog

All notable changes to this project will be documented in this file.

<!--next-version-placeholder-->

## v3.0.5

- moved the get_age function to utils (thank you @Gerto)
- added ATTR_AGE to state_attributes (thank you @Gerto)

## v3.0.4

- allow input type "input_number" in addition to "sensor" (thank you @erannave)

## v3.0.3

- added Russian language support (thank you @glebsterx)

## v3.0.2

- added Romania language support (thank you @18rrs)

## v3.0.1

- #104 fix Subscribe to correct handler
- #100 added Italian language support (thank you @mansellrace)
- #103 added Polish language support (thank you @LukaszP2)

## v3.0.0

- #75 Create a sensor for each attribute @edenhaus
- #75 Update pt-BR translation @dckiller51
- #75 Update FR translation @dckiller51
- #97 Bump pylint from 2.13.9 to 2.14.3 @dependabot
- #96 Bump actions/setup-python from 3 to 4 @dependabot
- #95 Bump mypy from 0.960 to 0.961 @dependabot
- #80 remove yaml support + fix config flow options @edenhaus
- #87 Bump pre-commit from 2.18.1 to 2.19.0 @dependabot
- #84 Bump github/codeql-action from 1 to 2 @dependabot

## v2.1.1

- fix for error for iOS users where the birthday selection was not displayed
- fix for error in selecting a date lower than 1970
- update of the translation FR

## v2.1.0

- add config flow (thank you @edenhaus)
  Goodbye yaml file. Easily add your users. Click on the button above or go to your HA Configuration (Settings) -> Devices & Services -> Add -> Bodymiscale.

## v2.0.0

Big update offered by @edenhaus. It offers us a better quality code and especially to be able to work in devcontainer.

- add code quality tools, which run with pre-commit
- removed unused code (e.g. holtek)
- use @cached_property to run certain calculation only once
- adjust names and code to python coding styles
- update ci actions
- add devcontainer for easier development

Thanks to you for the work done.

## v1.1.5

- convert weight from lbs to kgs if your scale is set to this unit (thank you @rale)
- added Portuguese Brazilian language support (thank you @hudsonbrendon)

## v1.1.4

- update getage function to correctly calculate age from DOB (thank you @borpin)
- use assignment expressions

## v1.1.3

- update readme: default integration in Hacs is available
- update iot_class (thank you @edenhaus)

## v1.1.2

- update for default integration in Hacs

## v1.1.1

- update to fix startup errors (thank you @stefangries )

## v1.1.0

- adding body score (thank you @alinelena )

## v1.0.0

- update for the "181B" model: display the minimum score if the impedance sensor is unavailable.

## v0.0.8

- spelling update: Lack-exerscise => Lack-exercise

## v0.0.7

- update decimal by @typxxi (Thanks)
- update readme by @typxxi (Thanks)

## v0.0.6

- use snake_case format for attribute names (thanks to Pavel Popov <https://github.com/dckiller51/bodymiscale/pull/13>)

## v0.0.5

- rename HomeAssistantType —> HomeAssistant for integrations n*- p* #49559

## v0.0.4

- fixed a startup error.
- update readme by @Ernst79 (Thanks)

## v0.0.3

- delete the units for the future custom card.

## v0.0.2

- implantation of calculations. Thanks to lolouk44. I took the liberty of taking back these files.

## v0.0.1

First version. Thanks to the designer of the component plant of homeassistant.
