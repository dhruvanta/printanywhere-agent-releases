# PrintAnywhere Agent — Releases

Official **signed** Windows installers for the PrintAnywhere Agent by **Dhruvanta Systems Private Limited**. This repository hosts release binaries only; the source code is maintained privately.

## Download
- Latest installer (stable URL): **[PrintAnywhereSetup.exe](https://github.com/Jayashanker-Padishala/printanywhere-agent-releases/releases/latest/download/PrintAnywhereSetup.exe)**
- All versions: see [Releases](https://github.com/Jayashanker-Padishala/printanywhere-agent-releases/releases)
- More info: https://www.dhruvantasystems.com/download

## Verify your download
1. **Publisher signature (automatic):** right-click the file → Properties → Digital Signatures → signer should be `Dhruvanta Systems Private Limited` (Authenticode, RFC3161-timestamped). Windows SmartScreen also shows this publisher at install time.
2. **Checksum (optional):** download `SHA256SUMS.txt` from the same release, then in PowerShell:
   `Get-FileHash .\PrintAnywhereSetup.exe -Algorithm SHA256` — the hash must match the line in `SHA256SUMS.txt`.

Every release is built by CI that hard-fails unless the binaries are signed, and is scanned with VirusTotal before publishing.
