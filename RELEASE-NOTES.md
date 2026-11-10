# BlitBun 1.15.3 — IZ2S Platform 0.22

- Requires [IZ2S Platform 0.22](https://github.com/byizmysh/IZ2S-Platform/releases/tag/v0.22.0) and a connected console session.
- Self-contained ABI-1 GPU application with module-owned shaders, font and menu; RAM and SD installation use the same host runtime.
- Adaptive bounded audio buffering accounts for actual refill latency and reports missed deadlines.
- Video acknowledgements carry input and route telemetry, removing redundant steady-stream polling and timer-driven display resets.
- Double R3 returns to the launcher; double Minus opens the module menu. Performance overlay is off by default.
- Source installation package and portable IZM are included.

# BlitBun 1.14.4

- Remove the Doom launch action from the PC panel.
- Replace the large monitor with a fixed 320×180 preview at up to 5 FPS, separate from full-resolution encoding.
- Add bounded native-window thumbnails without altering captured frames.
- Arrange source controls and status beside a wider settings grid, with responsive small-screen layouts.
- Keep the console receiver, video codecs, audio and transport unchanged.

# BlitBun 1.14.3

First public BlitBun release, based on the committed 1.14.3 implementation.
Uncommitted lab changes are excluded.

Original module-owned capture, BC1 encoding, block/dictionary compression,
persistent transport, live render profiles and optional controller forwarding
are retained. No renderer code was changed for this packaging operation.

Requires IZ2S Platform/IZlauncher. VacooTube is not required. No game,
experimental GPU-test app or private user profile is bundled.

See SUPPORT.md, VALIDATION.md, LICENSE and THIRD_PARTY.json.

- License independently authored IZMYSH code under GPL-2.0-or-later; retain explicit component terms and prior grants.
