# WorldEdit Schematic Fetcher

**Project Creative Enchancer Workshop **#2

  **English** | [简体中文(Simplified Chinese)](https://github.com/ra1ny-yuki/weschem/blob/main/README_zh.md)

  A MCDR plugin to fetch WorldEdit Schematics in the other sub-server on the same server.

## Requirement
- [MCDReforged](https://github.com/Fallen-Breath/MCDReforged/) 1.x

## Configuration Tips
- Don't forget to confirgurate the config file `config/WESchem.json` in your MCDR working directory after generating config file when plugin is loaded for the first time.

- You can have your config file and command prefixes changed in the plugin file if needed.

## Command help
`!!wes` or `!!weschem` are the command prefixes, they can also be used to call the help message out.

In the rest of this guide, `<Prefix>` refer to the two command prefixes.

1. `<Prefix> list` 
List all the sub-servers that this plugin can access.

2. `<Prefix> list <sub-server>`
List all the schematics in the sub-server you input.

3. `<Prefix> fetch <sub-server> <schematic>`
Copy the schematic you want in one another sub-server to the sub-server you are currently in.
