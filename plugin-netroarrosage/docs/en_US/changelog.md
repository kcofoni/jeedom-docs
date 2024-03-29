# Changelog plugin Netro Arrosage

>**IMPORTANT**
>
>If there is no information for a given update, it means that it concerns only the update of documentation, translation or text.

# 7/6/2023
- Added an Info command giving the number of tokens remaining to be consumed by the end of the day on the Netro API for the ground sensors (was previously implemented for the controllers only).
- Small bugs fixed and enriched log.

# 6/5/2023
- Adding controller battery level, useful for standalone models (e.g. Pixie).
- Generate alternate names when creating equipment whose Netro names are already taken in Jeedom.
- Pixie model integration.
- Ability to manage several controllers.
- Name and versions of the sensors now displayed in the "Equipment" tab.

>**IMPORTANT**: It is recommended to redo a synchronization after a version upgrade to update the information on the equipment (non-destructive operation therefore without risk).

# 23/2/2023
bug fix related to next watering scheduling date.

# 15/1/2023
The configuration screen now allows to extend the period within which the history and watering forecast is got (please refer to documentation).

# 10/12/2022
Added an Info command (*so what*) giving a complete textual status of the zone.

# 3/12/2022
Added an Info command giving the number of tokens remaining to be consumed by the end of the day on the Netro API.

# 11/11/2022
Finalization of the English translation. The translation of the command names is performed when synchronizing. It is therefore necessary to redo a synchronization after having changed the language if you want the commands in the target language. All properties of existing commands are preserved so that the name change has no impact otherwise.
