# Badger Studios releases

Downloads for the [EarthAI](https://earthai.cloud) Minecraft server's own plugins and apps.
The source code for these lives in private repositories; this repository only carries the built releases.
The table below is the source of truth for the newest version of each project (the "Latest" badge on the
releases page just marks whichever project was published most recently).

| Project | What it is | Newest | Download | Needs |
|---|---|---|---|---|
| **EarthAIJarvis** | Loopback bridge + CLI to watch and act inside a Paper server | 1.0.0 | [EarthAIJarvis-1.0.0.jar](https://github.com/BadgerStudios/releases/releases/download/earthai-jarvis-v1.0.0/EarthAIJarvis-1.0.0.jar)<br>[jarvis-cli.sh](https://github.com/BadgerStudios/releases/releases/download/earthai-jarvis-v1.0.0/jarvis-cli.sh) | Paper 1.21 |
| **EarthAICommandLog** | Audit log of every command the server dispatches, with attribution | 1.2.1 | [EarthAICommandLog-1.2.1.jar](https://github.com/BadgerStudios/releases/releases/download/earthai-cmdlog-v1.2.1/EarthAICommandLog-1.2.1.jar) | Paper 1.21 |
| **EarthAIPortal** | Bridge and magic links for the player web portal | 1.0.0 | [EarthAIPortal-1.0.0.jar](https://github.com/BadgerStudios/releases/releases/download/earthai-portal-v1.0.0/EarthAIPortal-1.0.0.jar) | Paper 1.21 · Vault, AuctionHouse, Essentials, LuckPerms (optional) |
| **EarthAIPets** | Companion pets for Java and Bedrock players | 1.1.0 | [EarthAIPets-1.1.0.jar](https://github.com/BadgerStudios/releases/releases/download/earthai-pets-v1.1.0/EarthAIPets-1.1.0.jar)<br>[EarthAIPets-1.1.0-itemsadder-pack.zip](https://github.com/BadgerStudios/releases/releases/download/earthai-pets-v1.1.0/EarthAIPets-1.1.0-itemsadder-pack.zip) | Paper 1.21 · ItemsAdder, floodgate, LuckPerms (optional) |
| **EarthAIMining** | Metered 3x3 mining that respects claims and regions | 1.0.0 | [EarthAIMining-1.0.0.jar](https://github.com/BadgerStudios/releases/releases/download/earthai-mining-v1.0.0/EarthAIMining-1.0.0.jar) | Paper 1.21 · GriefPrevention, WorldGuard (optional) |
| **EarthAI for Android** | The earthai.cloud site as a native Android app | 1.0.0 | [EarthAI-1.0.0.apk](https://github.com/BadgerStudios/releases/releases/download/earthai-android-v1.0.0/EarthAI-1.0.0.apk) | Android 8.0+ |

## Installing

**Plugins** are built against Paper 1.21 (`api-version: 1.21`). Drop the jar into `plugins/` and restart the
server; each plugin writes its config on first start. They were written for EarthAI and talk to its staff
dashboard where noted, so expect to point the config at your own endpoints.

**Android apps** are signed release builds. Allow installs from your browser or file manager when Android asks,
then open the APK. The player app is also served at <https://earthai.cloud/app/EarthAI.apk>.

Every release page lists the SHA-256 of its files; `latest.json` here carries the same download links for scripts.
