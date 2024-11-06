# ◼ Description
MythicFusion is a spigot plugin designed to extend the functionality of MythicMobs by introducing custom `conditions` and `mechanics` that allows integration with other plugins.

MythicFusion enables the `execution of skills` with the player as the caster on `specific events`, this works for plugin and vanilla events. 

Also the new [Trinket System](https://github.com/KellerThompson/MythicFusionWiki/wiki/Trinkets)  allows players to trigger specific skills by having designated MythicMobs items in their inventory. Each item is linked to a predefined skill that activates automatically when the item is present. This mechanic can be configured to work with various plugins like  Aurelium Skills, enabling the integration of custom effects, buffs, or conditions, offering a flexible and dynamic gameplay experience.

* This is my first plugin so if you find an error/bug please create an issue [here](https://github.com/KellerThompson/MythicFusionWiki/issues). 
* All comments and suggestions are wellcome

# ◼ Installation 
1. Use `spigot/paper 1.20 - 1.21` and `java 21`
2. Download the last version of MythicFusion [here](https://modrinth.com/plugin/mythicfusion).
3. Make sure you have the following plugins installed in your server:


| Plugin       | Version      | Mandatory ?   | New Mechanics and Conditions |
|--------------|--------------|--------------|--------------|
| [MythicMobs](https://www.spigotmc.org/resources/%E2%9A%94-mythicmobs-free-version-%E2%96%BAthe-1-custom-mob-creator%E2%97%84.5702/)| 5.7.1 | Yes | [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/Vanilla-Fusion) |
| [AuraSkills](https://www.spigotmc.org/resources/auraskills.81069/)| 2.2.3 | No  | [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/AuraSkills-Fusion)|
| [Essentialsx](https://essentialsx.net/downloads.html)| 2.20.1 | No | [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/Essentialsx-Fusion)|
| [AlonsoTags](https://www.spigotmc.org/resources/%E2%9C%85-alonsotags-1-8-%E2%80%A2-unlimited-tags-textures-custom-model-data.83664/)| 2.2.1 | No |  [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/AlonsoTags-Fusion)|
| [Gsit](https://www.spigotmc.org/resources/gsit-modern-sit-seat-and-chair-lay-and-crawl-plugin-1-16-1-21-1.62325/)| 1.10.0 | No   | [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/Gsit-Fusion)|
| [LibDisguise](https://www.spigotmc.org/resources/libs-disguises-free.81/)| 10.0.44 | No   | [See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/LibDisguise-Fusion)|
|[VotingPlugin](https://www.spigotmc.org/resources/votingplugin.15358/)|6.17.1|No|[See here](https://github.com/KellerThompson/MythicFusionWiki/wiki/VotingPlugin-Fusion)|

4. Restart the server.
5. Enjoy the new mechanics and conditions.
6. If you find an error/bug report the issue [here](https://github.com/KellerThompson/MythicFusionWiki/issues)

# ◼ Commands
| Command| Aliases| Description|Permission|
|--------------|--------------|--------------|-------------|
| mythicfusion| mfusion, mf | Base command for the plugin| ```mythicfusion.basecommand```|

## ◻ Subcommands
| SubCommand   |Description | Permission |
|--------------|--------------|--------------|
| reload | Reload the plugin| ```mythicfusion.reload```|
| skill | Execute a skill with the player as the caster. The player needs to have permission for the subcommand and for the specific skill. | For subcomand: ```mythicfusion.skill```, for each skill: ```mythicfusion.skill.<skillName>```|

# ◼ License
* All rights reserved.
