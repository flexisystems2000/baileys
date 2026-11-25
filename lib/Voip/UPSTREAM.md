# Vendored VoIP engine

This directory vendors the VoIP implementation from [HirooSy/baileys-lite](https://github.com/HirooSy/baileys-lite), version **0.4.1**.

Upstream source commit: `7814614c80a5511a63f8947beed3c99151659fde`.

The upstream MIT license is reproduced in `THIRD_PARTY_LICENSE`. The source is kept under `lib/Voip` and resolves the parent Baileys package through `lib/index.js`.

This is a source import only. Runtime compatibility with this fork's socket internals and live WhatsApp calling still requires automated checks and a staging call before replacing JARVIS's current adapter.
