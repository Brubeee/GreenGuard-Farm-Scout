# GreenGuard Farm Scout

GreenGuard is a planned crop-inspection rover and offline phone notebook for maize, wheat, and paddy. Its purpose is to help a farmer record crop observations and review possible issues; it is not a diagnosis or treatment system.

## Current status

This is a development-stage repository. The R2 CAD candidate and software prototypes are being prepared as a versioned source package. The rover is not yet an integrated operational system and is not OSHWA-certified. Motor-driver limits, exact motor/encoder selection, and the complete power/wiring design remain unresolved.

## Planned system

- ESP32 as the sole motion authority.
- Arduino UNO Q for planned camera and crop-row perception.
- An offline phone app for user-directed photo capture and field notes.
- Farmer review of observations; no autonomous treatment recommendations.

## Release and licensing

A versioned source package with editable CAD, firmware, app source, documentation, licenses, and reproducible checks is being prepared. The intended project terms are CERN-OHL-P-2.0 for hardware design, MIT for GreenGuard software, and CC BY 4.0 for selected documentation. Third-party components and dependencies retain their own terms.

Until a versioned package is available, this repository is not a build guide.
