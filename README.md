# Verity JE Extra

Issue tracker for **Verity JE Extra**, an addon for [Verity JE](https://modrinth.com/mod/verity-je-official) on Forge 1.20.1.

This repository exists for bug reports and feature requests. The mod source is not published here yet; it will be added once the mod leaves beta.

## What the mod does

Adds a "Verity JE Extra" tab to Verity's own config screen, with three overrides:

- **Chat** points Verity's chat at any OpenAI-compatible endpoint you choose, with your own endpoint URL, API key and model name. Verity's own AI Provider setting is a fixed dropdown, and for most of those choices the real endpoint is hardcoded internally.
- **Cloud Voice** sends Verity's cloud speech to a TTS endpoint of your own, either OpenAI-compatible or fish.audio, with its own API key separate from the chat one.
- **Offline Voice** swaps the voice behind Verity's built-in CPU speech engine for a Piper model of your own. Fully offline, no server and no key.

## Download

The mod is distributed on Modrinth. This repository is not a download location.

## Requirements

- Minecraft 1.20.1 with Forge
- Verity JE 6.0 or newer (required, the mod will not load without it)
- YACL 3.6 or newer (already required by Verity JE itself)

## Reporting an issue

Open a [new issue](../../issues/new/choose) and pick the bug report or feature request template.

**Before you paste logs or config files, remove your API keys.** This mod stores keys in `config/verityjeextra.json`, and endpoint URLs can carry identifying information. Replace anything sensitive with `REDACTED`.

Please check the existing issues first in case your problem is already reported.

## Not the right place

Bugs in Verity JE itself belong to that mod's author, not here. If the problem still happens with Verity JE Extra removed, it is not an issue with this addon.
