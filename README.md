# MISMOTur: QR-code “museum passport” for a network of ethnographic museums

*“Passaporto” a codici QR per una rete di musei etnografici*

**MIT App Inventor (Android)** · 2020 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

MISMOTur turns a visit to a network of five small ethnographic museums in a border mountain area into a game. Each museum has its own screen with a description; at each museum the visitor scans the QR code on site and the app stamps the visit. When all museums have been visited the app congratulates the visitor and prepares an e-mail to claim a prize. Interface in Slovene, Italian and English.

I designed and programmed this application in 2020. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Main screen with the list of museums and the visit status (`Screen1`).
- One screen per museum with description, call, e-mail and website buttons (`MATAJUR`, `REZIJA`, `SMO`, `TIPANA`, `BARDO`).
- QR-code scanning; each correct code marks the museum as visited and stores it on the device (TinyDB).
- Final screen when all museums are visited, with vibration and an e-mail to claim the prize (`Archivio`).

## Data

Visit status stored locally on the device; museum contact details have been removed from this publication.

## Technology

MIT App Inventor 2: BarcodeScanner, TinyDB, ActivityStarter, PhoneCall, Player, Clock, Notifier, CheckBox; permissions CAMERA, VIBRATE.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## Related repositories

- [museum-qr-guide-prototype-appinventor](https://github.com/massimosbarbaro/museum-qr-guide-prototype-appinventor)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *MISMOTur: QR-code “museum passport” for a network of ethnographic museums (MIT App Inventor (Android), 2020)*. Software, version 1.0. GitHub: https://github.com/massimosbarbaro/museum-network-qr-passport-appinventor

## License

Released under the [MIT License](LICENSE). © 2020 Massimo Sbarbaro.
