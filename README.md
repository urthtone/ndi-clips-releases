# NDI Clips releases

Signed Windows builds of **NDI Clips** by [PHNTM](https://phntm.com). This repository holds release builds only. There is no source code here.

Each release has:

- `ndi-clips-<version>-windows-x64.exe`, signed with Azure Artifact Signing (publisher "james dancer")
- `SHA256SUMS.txt`, the SHA-256 of the exe

NDI Clips checks the latest release here to update itself. It only installs a build that is signed, matches its checksum, and is newer than the one running.

NDI Clips needs the NDI Runtime, which comes with NDI Tools: http://ndi.link/NDIRedistV6

© PHNTM. All rights reserved.
