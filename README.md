# SparkFun_HyperDisplay

Standardized library for control of displays. This is an abstract display library that makes it easy to get new displays up and running quickly with a full set of drawing and printing functions with multi-window support. This library is relatively flexible allowing for the user to use a completely custom color definition and override default implementations for printing. All that is needed to make a display work is to provide the interface to draw one pixel to the display, and instruct the library how to handle your custom color type. Increased efficiency can be obtained by overriding additional drawing functions. Original author: SparkFun Electronics <techsupport@sparkfun.com>. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 2.0.1. Upstream: <https://github.com/sparkfun/SparkFun_HyperDisplay>.

**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SparkFun HyperDisplay` | C++ / Arduino | library | Standardized library for control of displays |
| `Example1_simpleBareNecessities` | C++ / Arduino | example sketch | `examples/Example1_simpleBareNecessities/Example1_simpleBareNecessities.ino` |
| `Example2_DisplayTestTemplate` | C++ / Arduino | example sketch | `examples/Example2_DisplayTestTemplate/Example2_DisplayTestTemplate.ino` |
| `Example3_FontHandling` | C++ / Arduino | example sketch | `examples/Example3_FontHandling/Example3_FontHandling.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/SparkFun_HyperDisplay`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** SparkFun Electronics <techsupport@sparkfun.com>
- **library.properties name:** SparkFun HyperDisplay
- **Version:** 2.0.1
- **Upstream URL:** <https://github.com/sparkfun/SparkFun_HyperDisplay>
- **Category:** Device Control
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
