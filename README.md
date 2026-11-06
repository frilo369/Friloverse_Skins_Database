# Divinity Skins Database

Converted `.fantome` copies for Divinity, generated from the local FrYiLoCo Riot skin database with converter revision 6 on 2026-11-06.

The repository contains 9,068 archives. Files keep the numeric folder layout: `<championId>/<skinId>/<skinId>.fantome`. `riot-skins-manifest.json` lists each archive's relative path, size, content hash, and catalogue name.

Divinity reads the converted database from `%LOCALAPPDATA%\divinity\Database\RiotSkins`; the offline converter mirrors it here so application updates can restore the local folder. The original input archives remain in `%LOCALAPPDATA%\FrYiLoCo\Riot Skins`.

The converter transforms local mod packages; LTK and the game remain responsible for checking whether any particular archive loads. Skin assets remain subject to their respective owners' rights.