# Minecraft-Protocol-Map
Map Minecraft versions and protocol numbers for Minecraft 1.7+

# What is inside ?
An array of JSON object containing 3 parameters :

| Field         | Description                                   | Examples             |
|---------------|-----------------------------------------------|----------------------|
| name          | The name of the version                       | `1.18.2`, `21w08a`   |
| protocol      | The protocol name or integer                  | `Snapshot 47`, `755` |
| real_protocol | The real protocol value as int (used in code) | `1073741871`, `755`  |

> **/!\ Warning**: Some version have **the same** `protocol` and/or `real_protocol` value. **They are not unique for a specific version.**  
> For instance, `1.10`, `1.10.1` and `1.10.2` have the same `protocol` and `real_protocol` (`210`).

# How to use ?
Download file or access directly to the [readable version](https://raw.githubusercontent.com/Vinetos/Minecraft-Protocol-Map/master/map.json) or the [minified version](https://raw.githubusercontent.com/Vinetos/Minecraft-Protocol-Map/master/map.min.json) to retreive all versions and protocol.
