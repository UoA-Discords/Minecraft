# UoA Discords / Minecraft Server <!-- omit in toc -->

Information and other metadata about the UoA Discords Minecraft server!

For information about the previous server, see [archive.md](./ARCHIVE.md).

## Table of Contents <!-- omit in toc -->

- [Datapacks](#datapacks)
- [Mods](#mods)
- [Gamerules](#gamerules)
- [Scoreboard Objectives](#scoreboard-objectives)
- [Permissions](#permissions)
- [Timeline](#timeline)
- [Roadmap](#roadmap)
- [Links](#links)

### Datapacks

> [!IMPORTANT]
> None of these Vanilla Tweaks datapacks are active yet, as they haven't been released for 1.12.

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Version</th>
            <th>Description</th>
            <th>Added</th>
            <th>Updated</th>
            <th>Notes</th>
        </tr>
        <tr>
    </thead>
    <tbody>
        <tr>
            <td>[<a href="https://vanillatweaks.net/picker/datapacks/">Vanilla Tweaks</a>] Bat Membranes</td>
            <td>1.0.5</td>
            <td>Disable phantoms and get membranes from bats instead.</td>
            <td>19/6/23</td>
            <td>19/6/23</td>
            <td></td>
        </tr>
        <tr>
            <td>[<a href="https://vanillatweaks.net/picker/datapacks/">Vanilla Tweaks</a>] Dragon Drops</td>
            <td>1.3.4</td>
            <td>Makes the Ender Dragon drop a dragon egg and elytra on death.</td>
            <td>19/6/23</td>
            <td>19/6/23</td>
            <td></td>
        </tr>
        <tr>
            <td>[<a href="https://vanillatweaks.net/picker/datapacks/">Vanilla Tweaks</a>] Double Shulker Shells</td>
            <td>1.3.4</td>
            <td>Makes all shulkers drop 2 shells.</td>
            <td>19/6/23</td>
            <td>19/6/23</td>
            <td></td>
        </tr>
        <tr>
            <td>[<a href="https://vanillatweaks.net/picker/datapacks/">Vanilla Tweaks</a>] Cauldron Concrete</td>
            <td>2.0.7</td>
            <td>Drop concrete powder into a cauldron filled with water to instantly harden all of it.</td>
            <td>19/6/23</td>
            <td>19/6/23</td>
            <td></td>
        </tr>
        <tr>
            <td>[<a href="https://vanillatweaks.net/picker/datapacks/">Vanilla Tweaks</a>] Spectator Night Vision</td>
            <td>1.1.4</td>
            <td>Easily toggle night vision when in spectator.</td>
            <td>19/6/23</td>
            <td>19/6/23</td>
            <td>To be removed.</td>
        </tr>
    </tbody>
</table>

### Mods

> [!NOTE]
> Full documentation of all mods is a WIP, this list is incomplete.

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Version</th>
            <th>Description</th>
            <th>Added</th>
            <th>Updated</th>
            <th>Links</th>
            <th>Notes</th>
        </tr>
        <tr>
    </thead>
    <tbody>
        <tr>
            <td>AdvancedBackups</td>
            <td>3.6</td>
            <td>Routine world backups.</td>
            <td>22/6/23</td>
            <td>22/6/23</td>
            <td><a href="https://modrinth.com/plugin/advanced-backups">Modrinth</a></td>
            <td>Untestes</td>
        </tr>
    </tbody>
</table>

### Gamerules

> [!NOTE]
> Many of these gamerules are transferred over from the previous server.

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Value</th>
            <th>Set At</th>
            <th>Reason</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>keepInventory</td>
            <td>true</td>
            <td>19/6/23</td>
            <td>Popular vote <sup>[<a href="https://discord.com/channels/814384895530106933/814385237122613248/1119440604942835822">1</a>]</sup></td>
        <tr>
        <tr>
            <td>doInsomnia</td>
            <td>false</td>
            <td>19/6/23</td>
            <td>Disabled by "Bat Membranes" datapack.</td>
        <tr>
        <tr>
            <td>commandBlockOutput</td>
            <td>false</td>
            <td>19/6/23</td>
            <td>Developer purposes.</td>
        <tr>
        <tr>
            <td>spawnRadius</td>
            <td>0</td>
            <td>19/6/23</td>
            <td>Communal spawn purposes.</td>
        <tr>
        <tr>
            <td>disableElytraMovementCheck</td>
            <td>true</td>
            <td>19/6/23</td>
            <td>Performance reasons.</td>
        <tr>
        <tr>
            <td>playersSleepingPercentage</td>
            <td>50</td>
            <td>19/6/23</td>
            <td>Just seems like a fair value.</td>
        <tr>
    </tbody>
</table>

### Scoreboard Objectives

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Criteria</th>
            <th>Display Type</th>
            <th>Display Name</th>
            <th>Comment</th>
        </tr>
        <tr>
    </thead>
    <tbody>
        <tr>
            <td>health</td>
            <td>health</td>
            <td>belowName</td>
            <td><code>{"text":"Health","color":"red"}</code></td>
            <td></td>
        </tr>
        <tr>
            <td>totalDeaths</td>
            <td>deathCount</td>
            <td>list</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>playerDeaths</td>
            <td>minecraft.killed_by:minecraft.player</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>playerKills</td>
            <td>playerKillCount</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>


### Permissions

_Managed by LuckPerms, all permissions pertain to the "default" group._

<table>
    <thead>
        <tr>
            <th>Permission</th>
            <th>Value</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>tabtps.defaultdisplay</td>
            <td>true</td>
        </tr>
    </tbody>
</table>


### Timeline

<details open>

<summary>Previous Server Timeline</summary>

- 19/6/23 Created server (Paper).

- 25/6/23 Temporarily disabled treasure maps due to an ongoing bug with them ([MC-218156](https://bugs.mojang.com/browse/MC-218156), read more [here](https://paper-chan.moe/paper-optimization/)).

- 3/7/23 Restarted to update [paper-world-defaults.yml](config/paper-world-defaults.yml), setting `entities.armor-stands.tick` to `true` following [the suggestion poll](https://discord.com/channels/814384895530106933/814404402365857792/1124239644104605717).

- 9/7/23 Restarted to update [paper-global.yml](config/paper-global.yml), setting `allow-permanent-block-break-exploits` to `true` following [the suggestion poll](https://discord.com/channels/814384895530106933/814404402365857792/1126758311463751721).

- 14/7/23 Restarted to update [paper-world-defaults.yml](config/paper-world-defaults.yml), setting `fixes.disable-unloaded-chunk-enderpearl-exploit` to `false` following [the suggestion poll](https://discord.com/channels/814384895530106933/814404402365857792/1128504991984918528).

- 26/10/23 Restarted to update server to Minecraft 1.20.2

</details>

- 21/06/24 Created server (1.20.1, Fabric)

- 22/6/24 Finished setup of all mods.

### Roadmap

- Automated whitelist application submitting via Discord bot.
- Update website.
- Faculty-based teams, joinable at worldspawn.
- Spawn area(s).

### Links

- [Website](https://nachotoast.com/mc) (outdated)
- [Discord](https://discord.gg/Ds4bfVac6J)
