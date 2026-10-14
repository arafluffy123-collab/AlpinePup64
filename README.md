# AlpinePup64

An ultra-lean, lightweight custom Linux container distribution based on the Alpine Linux core userland and designed as a minimalist Puppy Linux sandbox variant.

## Features
- **Core Engine:** Built using custom BusyBox binary compilation links.
- **Package Management:** Operates using the lightweight Alpine `apk` tool architecture.
- **Footprint:** Super small footprint under 10 megabytes!

## How to Boot (Chroot Entry)
To enter the AlpinePup64 container environment from a host terminal, use the change-root mapping command:
```bash
sudo chroot "./my container" /bin/sh
```
