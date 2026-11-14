# pAIDE™ Official Binary Releases

Website: [https://paide.dev](https://paide.dev)

## Overview

Official pre-built runtime binary distributions for the **pAIDE™** compiler and **pAIPL™** (`pAIPL-BIN™`) execution runtime, published for automated benchmarking (including `PrimePAIPL™` / `PlummersSoftwareLLC/Primes`) and authorized evaluation.

## Release v1.2.0 Verification

| Field | Value |
| --- | --- |
| **Artifact** | `paide-linux-amd64` (`4,460,704` bytes, static `CGO_ENABLED=0`) |
| **SHA-256** | `6d7ed402a7c906a37104d1a5e0cf99470f670506361f15e7ea54cfcc39c8ba5f` |
| **Download URL** | [https://github.com/Codrey/pAIDE_Releases/releases/download/v1.2.0/paide-linux-amd64](https://github.com/Codrey/pAIDE_Releases/releases/download/v1.2.0/paide-linux-amd64) |

Verify the downloaded binary checksum on Linux:

```bash
echo "6d7ed402a7c906a37104d1a5e0cf99470f670506361f15e7ea54cfcc39c8ba5f  paide-linux-amd64" | sha256sum -c -
```

## Proprietary Notice

All binary distributions in this repository are governed by the **pAIQos Ecosystem Proprietary License v1.0** in [`LICENSE.md`](LICENSE.md) (**Copyright (c) 2026 Corey Lloyd Winter. All Rights Reserved.**) and the **pAIQos Ecosystem Trademark Policy** in [`TRADEMARK.md`](TRADEMARK.md).

The underlying compiler and runtime source code is strictly closed-source and proprietary. Reverse engineering, decompilation, disassembly, unauthorized commercial use, redistribution of modified binaries, or copying/distribution of underlying source code is prohibited under [`LICENSE.md`](LICENSE.md).
