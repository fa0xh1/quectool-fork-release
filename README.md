# quectool-fork-release

Public release binaries for **QuecTool** (Quectel RM520N-GL / RM520N-EU / RM520N / RG520N / RG501Q web UI + RPC daemon).

Source code stays private in a separate repository. This repo only hosts release tarballs and checksums.

## Install

Download the latest tarball from [Releases](https://github.com/fa0xh1/quectool-fork-release/releases), push it to the modem and run the on-device installer, or use the deploy script from the source repo:

```sh
./deploy.sh              # latest
./deploy.sh v2.1.22      # specific version
```

Assets: `quectool-vX.Y.Z-N-g<sha>-armv7.tar.gz` + `.sha256`.
