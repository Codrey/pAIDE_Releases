# pAIDE™ Official Binary Releases

Website: [https://paide.dev](https://paide.dev)

## Overview

Official pre-built runtime binary distributions for the **pAIDE™** compiler and **pAIPL™** (`pAIPL-BIN™`) execution runtime, published for automated benchmarking (including `PrimePAIPL™` / `PlummersSoftwareLLC/Primes`) and authorized evaluation.

## Release v1.2.0 Verification

| Field | Value |
| --- | --- |
| **Artifact** | `paide-linux-amd64` (`4,444,320` bytes, static `CGO_ENABLED=0`) |
| **SHA-256** | `ded306e87006b7f99735d35b7e058d94ccd230cd5702ce4bd1c9ad6d0adf3c4e` |
| **Download URL** | [https://github.com/Codrey/pAIDE_Releases/releases/download/v1.2.0/paide-linux-amd64](https://github.com/Codrey/pAIDE_Releases/releases/download/v1.2.0/paide-linux-amd64) |

Verify the downloaded binary checksum on Linux:

```bash
echo "ded306e87006b7f99735d35b7e058d94ccd230cd5702ce4bd1c9ad6d0adf3c4e  paide-linux-amd64" | sha256sum -c -
```

## Proprietary Notice

All binary distributions in this repository are governed by the **pAIQos Ecosystem Proprietary License v1.0** in [`LICENSE.md`](LICENSE.md) (**Copyright (c) 2026 Corey Lloyd Winter. All Rights Reserved.**) and the **pAIQos Ecosystem Trademark Policy** in [`TRADEMARK.md`](TRADEMARK.md).

The underlying compiler and runtime source code is strictly closed-source and proprietary. Reverse engineering, decompilation, disassembly, unauthorized commercial use, redistribution of modified binaries, or copying/distribution of underlying source code is prohibited under [`LICENSE.md`](LICENSE.md).
