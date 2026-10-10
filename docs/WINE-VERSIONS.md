# Wine Versions

The installer supports two Wine versions, both built from [Affinity-Wine-Builder](https://github.com/ryzendew/Affinity-Wine-Builder/releases/tag/11.18) and patched for Affinity compatibility:

| Version | Best For | Description |
|---------|----------|-------------|
| **11.19** (Recommended) | Most users | Latest build with the full Affinity patch set (through 0085): Direct2D throughput and brush-latency fixes, wined3d Vulkan presentation fixes, OpenCL event dispatcher, plus color, printing and login fixes |
| **11.18** | Fallback | Previous build with the Affinity login fix and performance patches (D2D geometry cache, OpenCL cache, SDR white-level and printer mapping). Use if 11.19 has issues |

## Features

**Both versions include:**
- OpenCL support patches
- AMD GPU compatibility fixes
- Affinity-specific optimizations (WinRT/WinMetadata, window management, Direct2D)
- Canva sign-in (login metadata) support

The installer defaults to Wine 11.19. You can switch between versions anytime using the GUI installer.

## Download Links

Both builds are published under the [11.18 release tag](https://github.com/ryzendew/Affinity-Wine-Builder/releases/tag/11.18):

- 11.19: `ElementalWarrior-wine-11.19.tar.xz`
- 11.18: `ElementalWarrior-wine-11.18.tar.xz`

## Important Notes

### Wine 10.17 Warning

Wine 10.17 has major bugs and issues. This installer does not use it.
