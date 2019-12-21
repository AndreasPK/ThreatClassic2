# ClassicThreatMeter [!["Open Issues"](https://img.shields.io/github/issues-raw/dfherr/ClassicThreatMeter2.svg)](https://github.com/dfherr/ClassicThreatMeter2/issues)
ClassicThreatMeter2 is the successor of [EsreverWow/ClassicThreatMeter](https://github.com/EsreverWoW/ClassicThreatMeter). It is a threat meter for WoW Classic that attempts to provide reasonably accurate estimates of your group's relative threat values against enemy NPCs by recording pertinent data from the combat log and making calculations from that data.

## Bugs and feature requests
**Bugs:**
 - Please check for bugs and feature requests in the [issue tracker](https://github.com/dfherr/ClassicThreatMeter2/issues) and report them, if you don't find them mentioned there already.

## Download
 - [CurseForge](https://www.curseforge.com/wow/addons/classicthreatmeter2)

## FAQ
**Q: Why am I not seeing other players in ClassicThreatMeter?**
 
A: Other players must have ClassicThreatMeter or a compatible AddOn enabled in order to track their threat similar to how KLH Threat Meter/Omen required compatible AddOns communicating threat to one another in Vanilla/TBC.

**Q: Why isn't ClassicThreatMeter using the built-in threat API?**

A: To answer simply, it can't! Blizzard added in a threat API in patch 3.0.2 for WotLK and has been in the game since, but it has been purposely removed for WoW Classic, which means we must rely on combat log parsing.

**Q: How does ClassicThreatMeter handle multiple targets?**

A: The combat log in WoW Classic is fortunately much more detailed than that which was available in the game originally before patch 2.4. This allows us to track NPCs by GUID (global unique identifier), and there should be no issues with mobs having the same name and threat becoming muddled between them. It is also designed in such a way that effects that are meant to add divided threat between active targets, such as heals and buffs, are able to do so.

**Q: Why aren't there more options to customize the threat window?**

A: ClassicThreatMeter is still a very young AddOn. More features and customization options will come over time.

## Sreenshots
<img src="https://i.imgur.com/7ipFacm.png">
<img src="https://i.imgur.com/FUg8kLg.png">
<img src="https://i.imgur.com/bDxNw6X.png">

**Sources:**
 - https://github.com/magey/classic-warrior/wiki/Threat-Mechanics
 - https://classicwow.live/guides/19/threat-guide-and-reference-table
 - https://classic.wowhead.com/guides/threat-overview-classic-wow#threat-modifier-abilities-and-values-warrior

 - https://web.archive.org/web/20061115070619/http://www.evilempireguild.org/guides/kenco2.php
 - https://web.archive.org/web/20091213135841/forums.wow-europe.com/thread.html?topicId=116562109&pageNo=1&sid=1

 - https://wow.gamepedia.com/Aggro
 - https://wow.gamepedia.com/Talk:Aggro
 - https://wow.gamepedia.com/Talk:Aggro/Archive1
 - https://wow.gamepedia.com/Talk:Aggro/Archive2
 - https://wow.gamepedia.com/index.php?title=Aggro&oldid=352753 (Vanilla)
 - https://wow.gamepedia.com/index.php?title=Aggro&oldid=1599827 (TBC)
 - https://wow.gamepedia.com/index.php?title=Aggro&oldid=2380563 (WotLK)

 - https://wow.gamepedia.com/Threat
 - https://wow.gamepedia.com/Talk:Threat
 - https://wow.gamepedia.com/index.php?title=Threat&oldid=175341 (Vanilla)

 - https://wow.gamepedia.com/Threat_list
 - https://wow.gamepedia.com/index.php?title=Threat_list&oldid=193144 (Vanilla)

## License

[MIT](license/ClassicThreatMeter2)

Copyright (c) 2019 Dennis-Florian Herr
