# R2.0.0-rc.3: Source package and reproducibility

**Version:** `2.0.0-rc.3` (documented design/software prototype)  
**OSHWA registration:** [IN000105](https://certification.oshwa.org/in000105.html)  
**Release:** [v2.0.0-rc.3](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.3)

## Getting the source

The versioned hardware and software files are provided in the [release archive](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/download/v2.0.0-rc.3/GreenGuard-Farm-Scout-R2.0.0-rc.3-documented-prototype-corrected.zip), rather than as individual files in the repository's `main` branch.

The release notes describe **296 payload files plus `MANIFEST.json`**, including:

- Editable FreeCAD R2 CAD files and parameters, 56 part designs, STEP/STL exports, assemblies and a provisional BOM.
- Logical electrical schematic and power/net references.
- ESP32 firmware source and host tests.
- Offline phone field-notebook PWA and generic saved-video row-vision prototype.
- Protocols, setup/build notes, software dependencies, third-party notices, license records and focused tests.

The archive is labeled a *documented prototype*. The release does not claim a field-qualified or integrated operational rover.

## File integrity

The SHA-256 value published with the release asset is:

```text
0a6ceda404e124b98df93b4e047fef6840f5b371a5c3972e4ca93ef6570dd470
```

To compare the downloaded file against that published digest:

**Windows PowerShell**

```powershell
Get-FileHash .\GreenGuard-Farm-Scout-R2.0.0-rc.3-documented-prototype-corrected.zip -Algorithm SHA256
```

**macOS / Linux**

```bash
sha256sum GreenGuard-Farm-Scout-R2.0.0-rc.3-documented-prototype-corrected.zip
```

This is the release's published checksum, not a claim of independent reproduction or validation.

## Current engineering boundaries

| Area | What is available | What is not established |
| --- | --- | --- |
| Hardware design | Editable CAD, part exports, assembly and digital geometry reports | Physical fit, strength, terrain performance or field qualification |
| Electronics/firmware | Schematics, ESP32 source and host tests | Integrated rover actuation; motion outputs are disabled by default |
| Farmer phone app | Offline field notebook and user-started capture | Live rover-triggered capture or field usability |
| Row vision | Generic saved-video prototype | Verified UNO Q deployment, validated crop-disease model or diagnostic accuracy |

The optional `best.pt` classifier is excluded from this release. Host software tests and digital CAD checks should not be represented as real-world robot performance.

## Version and certification scope

The OSHWA certification mark and UID [IN000105](https://certification.oshwa.org/in000105.html) identify the registered project version. A materially different future release may need its own OSHWA registration under the program's versioning rules.

Licenses documented in the release: **CERN-OHL-P-2.0** for GreenGuard hardware designs, **MIT** for GreenGuard software, and **CC BY 4.0** for selected GreenGuard documentation. Third-party material keeps its respective licenses and notices.
