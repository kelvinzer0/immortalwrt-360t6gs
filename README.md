# ImmortalWrt Firmware Builder for 360 T6GS (MT7621)

Automated GitHub Actions CI build for **360 T6GS** router (MediaTek MT7621 + MT7915E Wi-Fi 6) based on ImmortalWrt `openwrt-18.06` kernel with built-in **WireGuard** support.

## Hardware Specifications
- **Model**: 360 T6GS
- **SoC**: MediaTek MT7621AT
- **Wireless**: MediaTek MT7915E (Wi-Fi 6 AX1800)
- **Flash Size**: 16 MB SPI Flash (`IMAGE_SIZE := 15872k`)
- **RAM**: 256 MB DDR3

## Built-in Features
- Full Wi-Fi 6 MT7915 driver & firmware
- Kernel WireGuard support (`kmod-wireguard`, `wireguard-tools`, `luci-proto-wireguard`)
- LuCI Web Interface
- Optimized firmware image size (~8-10MB) to prevent flash bloat

## How to Build
1. Go to the **Actions** tab in this repository.
2. Select **Build ImmortalWrt 360T6GS with WireGuard**.
3. Click **Run workflow**.
4. Once completed, download the `.bin` firmware from the **Artifacts** section.
