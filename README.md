# GreenGuard Farm Scout

GreenGuard is an open-source rover design and software prototype for crop scouting along dry paths between maize, wheat, and paddy rows. Its aim is to help farmers record crop observations and review possible issues; it does not diagnose disease or recommend treatment.

## Versioned source

The **R2.0.0-rc.2 source package** is available from the [GitHub release page](https://github.com/Brubeee/GreenGuard-Farm-Scout/releases/tag/v2.0.0-rc.2). The archive contains editable R2 CAD and print files, firmware and phone-app source, generic row-vision software, protocols, parts and dependency records, licenses, documentation, tests, and a SHA-256 manifest.

R2.0.0-rc.2 is a preliminary design and software release. GreenGuard is **not OSHWA-certified** and is not a ready-to-operate or field-qualified rover. The CAD deliverable is complete for its stated reference assumptions; physical fit, strength, and terrain performance are not established. ESP32 motion remains disabled by default. Row-vision deployment is not UNO Q verified, live rover-triggered phone capture is disabled, and no validated maize/wheat/paddy disease model is included. The optional best.pt checkpoint is excluded while its training lineage, crop coverage, and redistribution terms remain unresolved.

The phone app supports an offline farmer notebook with user-started camera capture and local records. Its rover capture walkthrough uses synthetic host data; it is not a live operating link to the rover. Do not interpret software tests or digital CAD checks as proof of physical operation or field performance.

## Licenses

GreenGuard hardware design files use CERN-OHL-P-2.0, GreenGuard software uses MIT, and selected GreenGuard documentation uses CC BY 4.0. Third-party components and dependencies retain their own terms; the source archive contains the applicable notices and scope notes.
