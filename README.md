# GreenGuard Farm Scout

[![Official OSHWA open-source hardware certification mark, IN000105](assets/oshwa-certified-IN000105-wide.svg)](https://certification.oshwa.org/in000105.html)

**OSHWA-certified open-source hardware project · IN000105 · Registered version: 2.0.0-rc.3**

[Official OSHWA certification](https://certification.oshwa.org/in000105.html) · [R2.0.0-rc.3 release](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.3) · [Download versioned source](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/download/v2.0.0-rc.3/GreenGuard-Farm-Scout-R2.0.0-rc.3-documented-prototype-corrected.zip) · [Source access and verification](SOURCE_ACCESS.md)

GreenGuard Farm Scout is an **open-source rover design and software prototype** intended for crop scouting along dry paths between maize, wheat and paddy rows. The concept aims to help farmers record observations and review possible issues. It **does not diagnose plant diseases or recommend treatments**.

The project began during the **Lodha Genius Programme** and has developed into a documented hardware/software release intended for study, modification and further engineering work.

## Certification and current release

GreenGuard Farm Scout is listed in the **Open Source Hardware Association (OSHWA)** registry under **[IN000105](https://certification.oshwa.org/in000105.html)**. The certification mark above uses OSHWA's official artwork with the project's assigned UID.

The currently published certified source package is **[v2.0.0-rc.3](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.3)**, a *documented design and software prototype*, **not a complete, integrated or field-qualified robot**. OSHWA certification concerns open-source hardware compliance; it is not independent validation of technical performance.

## What is included

The versioned release archive contains:

- **Mechanical design:** editable FreeCAD R2 files and parameters, 56 part designs with STEP/STL exports, assemblies, a provisional bill of materials and digital geometry reports.
- **Electronics and firmware:** logical electrical schematics, power/net references, ESP32 firmware and host tests.
- **Farmer application:** offline field-notebook PWA with farmer-entered records and user-started camera capture.
- **Computer vision:** generic saved-video row-vision prototype, not a validated crop-disease detector.
- **Reproducibility materials:** protocols, setup notes, dependency and license records, third-party notices, tests and a SHA-256 manifest.

**Where is the source?** The complete versioned package is attached as a ZIP to the [rc.3 GitHub release](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.3). The `main` branch currently contains this public overview and certification assets; it is **not** a browsable copy of the 296-file release archive. See [SOURCE_ACCESS.md](SOURCE_ACCESS.md) for the download, checksum and scope.

## What is and is not verified

| Area | Documented in the release | Not yet demonstrated |
| --- | --- | --- |
| Rover CAD | Editable designs, exports and digital checks | Physical fit, strength, terrain performance |
| ESP32 firmware | Source and host-side tests | Integrated operation; motion outputs disabled by default |
| Offline phone notebook | Local records and user-started camera capture | Live rover-triggered capture; farmer usability |
| Row-vision software | Generic saved-video processing | UNO Q deployment or validated crop-disease detection |
| Full system | Design and software components | Integrated, operating, field-tested agricultural rover |

The optional `best.pt` checkpoint is **not included** in rc.3. Tests conducted on hosts and digital CAD checks do not establish physical or agricultural field performance.

## Licensing

The release records the following licensing scope:

- **Hardware design files:** CERN-OHL-P-2.0
- **GreenGuard software:** MIT
- **Selected GreenGuard documentation:** CC BY 4.0

Third-party dependencies and materials retain their own licenses and notices; refer to the versioned source package for details.

## Links

- **Certification:** https://certification.oshwa.org/in000105.html
- **Source release:** https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.3
- **Download and verification instructions:** [SOURCE_ACCESS.md](SOURCE_ACCESS.md)
- **Official certification mark (stacked):** [SVG](assets/oshwa-certified-IN000105-stack.svg)
- **Official certification mark (wide):** [SVG](assets/oshwa-certified-IN000105-wide.svg)
