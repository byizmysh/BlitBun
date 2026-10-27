# Local preparation checks

Prepared as a separate BlitBun repository with module ID `blitbun`. This record covers local software checks, not a new physical-console qualification.

- Source syntax and declared module/console assets checked against IZ2S API 1.
- Installed into an isolated clean IZ2S release copy; module/package checks passed.
- Accidental replacement without --replace refused. Intentional update retained private preferences and pinned snapshots; the previous module was backed up.
- Generated IZM inventory checked for exclusion of runtime binaries, npm dependency trees and private profiles.
- Branded console and application icons exported with real alpha. Existing codec, receiver ABI and controller gesture IDs are retained.
- No physical-console FPS or network-throughput claim is made by the packaging checks. Encoding algorithms and stream ABI were not redesigned for this branding/extraction change.

A new Switch session is required to validate the new loaded module version and icon in the real launcher. Linux ARM64 and Windows/macOS streaming are not implied by the local Linux x64 checks.

## Named, independent module release — 1.14.3

- Physical module directory and API identity migrated with the real installer; private data/runtime preserved and previous installation backed up.
- The module installs on its own, in either installation order with the other media module, with no dependency on that other module.
- Shared console-shell contributions compile independently and together.
- Targeted platform/module and exclusive-stream ownership checks passed (30 cases).
- The private isolated Linux fixture masked the other media module: BlitBun captured valid HD and Full HD frames across a live resolution change.
- A new physical Switch/gameplay/FPS validation was not performed as part of this packaging change.
