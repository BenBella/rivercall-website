---
layout: minimal
title: Open-Source Licences
---

# Open-Source Licences

RiverCall uses open-source software maintained by third-party authors and communities. We are grateful for their work.

This document is a template for RiverCall's third-party software notices. **Before publishing it, verify the libraries, versions, licence types, copyright notices, and required notice text against the actual Android and iOS release builds.** Include transitive dependencies and any bundled native libraries where their licences require attribution.

## Third-Party Components

Replace the example entries below with the components actually included in RiverCall.

| Component | Version | Licence | Project |
|---|---|---|---|
| Kotlin | `<version>` | Apache License 2.0 | <https://kotlinlang.org/> |
| Compose Multiplatform | `<version>` | Apache License 2.0 | <https://www.jetbrains.com/compose-multiplatform/> |
| Ktor | `<version>` | Apache License 2.0 | <https://ktor.io/> |
| MapLibre Native | `<version>` | BSD 2-Clause License | <https://maplibre.org/> |

> The table above is illustrative, not a confirmed inventory of RiverCall dependencies. Remove components that are not shipped and add all required dependencies.

## Licence Texts and Notices

For each component, provide the licence text and any copyright or attribution notices required by its licence. Where appropriate, include the component's `LICENSE` and `NOTICE` files verbatim.

### Apache License 2.0

For components distributed under Apache License 2.0, include the applicable copyright notices and licence text, and preserve any required `NOTICE` content.

Licence text: <https://www.apache.org/licenses/LICENSE-2.0>

### BSD 2-Clause License

For components distributed under the BSD 2-Clause License, include the applicable copyright notice, licence conditions, and disclaimer.

For MapLibre Native, verify the exact licence and copyright text for the version included in the app.

Project: <https://maplibre.org/>

## Map Data Attribution

Map-rendering software licences are separate from map-data attribution requirements. If RiverCall displays OpenStreetMap data, provide suitable attribution in the app and link to the OpenStreetMap copyright and licence page. Also identify the actual map-tile provider used by the app and comply with that provider's attribution and usage terms.

OpenStreetMap copyright and licence: <https://www.openstreetmap.org/copyright>

## How to Keep This File Accurate

Before each release:

1. Generate a dependency inventory for the Android release variant.
2. Review iOS dependencies, including Swift Package Manager and CocoaPods dependencies if used.
3. Include transitive dependencies and bundled native components where required.
4. Confirm each component's exact version, licence, copyright notice, and any `NOTICE` obligations.
5. Preserve the required licence text and notices; do not rely only on a link to the licence.
6. Update this file whenever shipped dependencies change.

## Contact

For questions about these notices, contact: **`<your support email>`**.


