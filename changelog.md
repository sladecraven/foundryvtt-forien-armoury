# Changelog

## v0.X.X
### v0.2.X

#### v0.2.3
* prepared groundwork for translation using Babele to any language
* added automation for applying Bleed Conditions upon hit with Slashing weapon
* started translating Forien's Armoury compendium to Polish (all names and most descriptions done)

#### v0.2.2
* under DasSauerkraut's permission, integrated Gerwin Waffenhalter’s Magnificent Weapons Gallery weapons and slashing quality 
* prepared module for translation to Polish
* translated basic strings for now, Compendium still English only
* added check for ammunition to avoid errors on tests not using ammunition
* removed unnecessary logging

#### v0.2.1
* fixed links to changelog and readme in module.json

#### v0.2.0
* Extended Arrow Recovery system with more rules
* Added new qualities and flaws to use with projectiles:
  * Unbreakable (used extisting quality) – projectiles is always recovered, bypassing rules, as long as it is recoverable (settings/quailities)
  * Recoverable – projectile can be recovered, even if settings won't allow it
  * Unrecoverable – projectile always perishes, will never be recovered
  * Sturdy – projectile is sturdy and easier to recover
  * Frail – projectile breaks easily and is harder to recover
  * Hard To Find – projectile is hard to find, if it would be recovered, roll again with -10 modifier
* Added new qualities and flaws to some items in compendium
* Added variants for lead and stone bullets that use projectile qualities and flaws
* Created changelog

### v0.1.X

#### v0.1.7
* Fixed Arrow Recovery to use sockets, so it works for everyone, not only GM

#### v0.1.6 - Arrow Recovery
* Added arrow recovery feature with several rules
