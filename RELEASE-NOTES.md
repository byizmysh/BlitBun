# BlitBun 1.15.8

This release pairs the PC module with a ready-to-install Switch 2 client.

- Smaller overlay controls and a dedicated EXIT action.
- The Switch executable is included in the PC package as an .iza file.
- The PC module and the Switch executable can also be installed separately.

## Install on the PC

Extract the source installer archive. Open a terminal in the extracted folder and run:

```sh
./install.sh --platform "/path/to/iz2s-platform"
```

Replace the path with your IZ2S Platform installation folder. Keep IZ2S Platform running on the PC while using BlitBun on Switch.

## Install on Switch 2

1. **Through IZ2S:** Connect your Switch 2 to IZ2S Platform on the PC. Open **App library → Add app** and select `blitbun-1.15.8.iza`. Open **Add App** in IZ2S on the Switch to receive and install the file.
2. **Copy to the SD card:** Open the card on your PC. Create `iz2s/modules/blitbun/` at the root if needed. Copy `blitbun-1.15.8.iza` there and rename it to `launcher.iza`. The final path is `SD:/iz2s/modules/blitbun/launcher.iza`. Reinsert the card and open BlitBun from the IZ2S menu.
